---
class_count: 0
classes: []
context_file: json-ld/meta-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/meta/refs/heads/main/json-ld/meta-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Meta from Meta.
layout: jsonld
name: Meta Context
namespaces:
- prefix: meta
  uri: https://developers.facebook.com/docs/graph-api/reference/
- prefix: marketing
  uri: https://developers.facebook.com/docs/marketing-api/reference/
- prefix: whatsapp
  uri: https://developers.facebook.com/docs/whatsapp/cloud-api/reference/
properties:
- container: ''
  name: User
  type: ''
- container: ''
  name: Page
  type: ''
- container: ''
  name: Post
  type: ''
- container: ''
  name: AdCampaign
  type: ''
- container: ''
  name: Message
  type: ''
- container: ''
  name: Media
  type: ''
property_count: 6
provider_name: Meta
provider_slug: meta
slug: meta-context
source_filename: meta-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"meta\": \"https://developers.facebook.com/docs/graph-api/reference/\",\n    \"marketing\": \"https://developers.facebook.com/docs/marketing-api/reference/\",\n    \"whatsapp\": \"https://developers.facebook.com/docs/whatsapp/cloud-api/reference/\",\n\n    \"User\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"first_name\": \"schema:givenName\",\n        \"last_name\": \"schema:familyName\",\n        \"middle_name\": \"schema:additionalName\",\n        \"email\": \"schema:email\",\n        \"birthday\": \"schema:birthDate\",\n        \"gender\": \"schema:gender\",\n        \"link\": \"schema:url\",\n        \"picture\": \"schema:image\",\n        \"locale\": \"schema:knowsLanguage\",\n        \"timezone\": \"schema:timeZone\",\n        \"location\": {\n          \"@id\": \"schema:homeLocation\",\n        \
  \  \"@type\": \"schema:Place\"\n        },\n        \"hometown\": {\n          \"@id\": \"schema:birthPlace\",\n          \"@type\": \"schema:Place\"\n        },\n        \"languages\": \"schema:knowsLanguage\",\n        \"friends\": \"schema:knows\",\n        \"significant_other\": \"schema:spouse\",\n        \"quotes\": \"schema:description\"\n      }\n    },\n\n    \"Page\": {\n      \"@id\": \"schema:Organization\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"about\": \"schema:description\",\n        \"bio\": \"schema:description\",\n        \"description\": \"schema:description\",\n        \"category\": \"schema:category\",\n        \"category_list\": \"schema:category\",\n        \"cover\": \"schema:image\",\n        \"picture\": \"schema:logo\",\n        \"link\": \"schema:url\",\n        \"website\": \"schema:sameAs\",\n        \"username\": \"schema:alternateName\",\n        \"emails\": \"schema:email\",\n     \
  \   \"phone\": \"schema:telephone\",\n        \"location\": {\n          \"@id\": \"schema:location\",\n          \"@type\": \"schema:PostalAddress\",\n          \"@context\": {\n            \"city\": \"schema:addressLocality\",\n            \"state\": \"schema:addressRegion\",\n            \"country\": \"schema:addressCountry\",\n            \"street\": \"schema:streetAddress\",\n            \"zip\": \"schema:postalCode\",\n            \"latitude\": \"schema:latitude\",\n            \"longitude\": \"schema:longitude\"\n          }\n        },\n        \"fan_count\": \"schema:interactionCount\",\n        \"followers_count\": \"schema:interactionCount\",\n        \"founded\": \"schema:foundingDate\",\n        \"hours\": \"schema:openingHours\",\n        \"overall_star_rating\": {\n          \"@id\": \"schema:aggregateRating\",\n          \"@type\": \"schema:AggregateRating\"\n        },\n        \"rating_count\": \"schema:reviewCount\",\n        \"is_verified\": \"schema:hasCredential\"\
  ,\n        \"whatsapp_number\": \"schema:telephone\"\n      }\n    },\n\n    \"Post\": {\n      \"@id\": \"schema:SocialMediaPosting\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"message\": \"schema:articleBody\",\n        \"story\": \"schema:headline\",\n        \"created_time\": \"schema:dateCreated\",\n        \"updated_time\": \"schema:dateModified\",\n        \"from\": {\n          \"@id\": \"schema:author\",\n          \"@type\": \"schema:Person\"\n        },\n        \"permalink_url\": \"schema:url\",\n        \"full_picture\": \"schema:image\",\n        \"picture\": \"schema:thumbnailUrl\",\n        \"type\": \"schema:additionalType\",\n        \"is_published\": \"schema:publishedStatus\",\n        \"privacy\": \"schema:accessMode\",\n        \"place\": {\n          \"@id\": \"schema:contentLocation\",\n          \"@type\": \"schema:Place\"\n        },\n        \"shares\": {\n          \"@id\": \"schema:interactionStatistic\",\n          \"@type\"\
  : \"schema:InteractionCounter\",\n          \"@context\": {\n            \"count\": \"schema:userInteractionCount\"\n          }\n        },\n        \"likes\": {\n          \"@id\": \"schema:interactionStatistic\",\n          \"@type\": \"schema:InteractionCounter\"\n        },\n        \"comments\": {\n          \"@id\": \"schema:comment\",\n          \"@type\": \"schema:Comment\"\n        },\n        \"message_tags\": \"schema:mentions\",\n        \"application\": {\n          \"@id\": \"schema:provider\",\n          \"@type\": \"schema:SoftwareApplication\"\n        },\n        \"scheduled_publish_time\": \"schema:datePublished\"\n      }\n    },\n\n    \"AdCampaign\": {\n      \"@id\": \"schema:AdvertiserContentArticle\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"account_id\": \"schema:sponsor\",\n        \"objective\": \"schema:purpose\",\n        \"status\": \"schema:creativeWorkStatus\",\n        \"effective_status\"\
  : \"schema:creativeWorkStatus\",\n        \"buying_type\": \"schema:additionalType\",\n        \"bid_strategy\": \"schema:additionalType\",\n        \"daily_budget\": {\n          \"@id\": \"schema:offers\",\n          \"@type\": \"schema:MonetaryAmount\"\n        },\n        \"lifetime_budget\": {\n          \"@id\": \"schema:offers\",\n          \"@type\": \"schema:MonetaryAmount\"\n        },\n        \"start_time\": \"schema:startDate\",\n        \"stop_time\": \"schema:endDate\",\n        \"created_time\": \"schema:dateCreated\",\n        \"updated_time\": \"schema:dateModified\",\n        \"special_ad_categories\": \"schema:category\",\n        \"promoted_object\": \"schema:about\"\n      }\n    },\n\n    \"Message\": {\n      \"@id\": \"schema:Message\",\n      \"@context\": {\n        \"to\": {\n          \"@id\": \"schema:recipient\",\n          \"@type\": \"schema:Person\"\n        },\n        \"type\": \"schema:additionalType\",\n        \"messaging_product\": \"schema:provider\"\
  ,\n        \"text\": {\n          \"@id\": \"schema:text\",\n          \"@context\": {\n            \"body\": \"schema:text\"\n          }\n        },\n        \"image\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"schema:ImageObject\"\n        },\n        \"video\": {\n          \"@id\": \"schema:video\",\n          \"@type\": \"schema:VideoObject\"\n        },\n        \"audio\": {\n          \"@id\": \"schema:audio\",\n          \"@type\": \"schema:AudioObject\"\n        },\n        \"document\": {\n          \"@id\": \"schema:associatedMedia\",\n          \"@type\": \"schema:MediaObject\"\n        },\n        \"location\": {\n          \"@id\": \"schema:contentLocation\",\n          \"@type\": \"schema:Place\",\n          \"@context\": {\n            \"latitude\": \"schema:latitude\",\n            \"longitude\": \"schema:longitude\",\n            \"name\": \"schema:name\",\n            \"address\": \"schema:address\"\n          }\n        },\n        \"contacts\"\
  : {\n          \"@id\": \"schema:mentions\",\n          \"@type\": \"schema:Person\"\n        },\n        \"context\": {\n          \"@id\": \"schema:isPartOf\",\n          \"@context\": {\n            \"message_id\": \"schema:identifier\"\n          }\n        }\n      }\n    },\n\n    \"Media\": {\n      \"@id\": \"schema:MediaObject\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"media_type\": \"schema:additionalType\",\n        \"media_url\": \"schema:contentUrl\",\n        \"thumbnail_url\": \"schema:thumbnailUrl\",\n        \"permalink\": \"schema:url\",\n        \"caption\": \"schema:caption\",\n        \"timestamp\": \"schema:datePublished\",\n        \"created_time\": \"schema:dateCreated\",\n        \"updated_time\": \"schema:dateModified\",\n        \"username\": \"schema:author\",\n        \"owner\": {\n          \"@id\": \"schema:author\",\n          \"@type\": \"schema:Person\"\n        },\n        \"like_count\": {\n          \"@id\": \"schema:interactionStatistic\"\
  ,\n          \"@type\": \"schema:InteractionCounter\"\n        },\n        \"comments_count\": {\n          \"@id\": \"schema:commentCount\"\n        },\n        \"width\": \"schema:width\",\n        \"height\": \"schema:height\",\n        \"place\": {\n          \"@id\": \"schema:contentLocation\",\n          \"@type\": \"schema:Place\"\n        },\n        \"tags\": \"schema:mentions\",\n        \"children\": \"schema:hasPart\",\n        \"album\": {\n          \"@id\": \"schema:isPartOf\",\n          \"@type\": \"schema:ImageGallery\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/meta/refs/heads/main/json-ld/meta-context.jsonld
tags:
- Advertising
- Analytics
- Artificial Intelligence
- Messaging
- Social
- Social Media
- Virtual Reality
- JSON-LD
- Linked Data
- Semantic Web
---
