---
api_specs:
- filename: mailchimp-marketing-api-openapi.yml
  format: yaml
  label: Mailchimp Marketing API
  slug: mailchimp-marketing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mailchimp/refs/heads/main/openapi/mailchimp-marketing-api-openapi.yml
- filename: mailchimp-transactional-api-openapi.yml
  format: yaml
  label: Mailchimp Transactional API
  slug: mailchimp-transactional-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mailchimp/refs/heads/main/openapi/mailchimp-transactional-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/mailchimp/refs/heads/main/json-ld/context.jsonld
description: JSON-LD context defining the semantic vocabulary for context from Mailchimp.
layout: jsonld
name: context Context
namespaces:
- prefix: mailchimp
  uri: https://mailchimp.com/developer/marketing/api/
- prefix: mc
  uri: https://mailchimp.com/ontology/
properties:
- container: ''
  name: Campaign
  type: ''
- container: ''
  name: Audience
  type: schema:Audience
- container: ''
  name: Member
  type: schema:Person
- container: ''
  name: Template
  type: schema:CreativeWork
- container: ''
  name: TransactionalMessage
  type: schema:EmailMessage
property_count: 5
provider_name: Mailchimp
provider_slug: mailchimp
slug: context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"mailchimp\": \"https://mailchimp.com/developer/marketing/api/\",\n    \"mc\": \"https://mailchimp.com/ontology/\",\n\n    \"Campaign\": {\n      \"@id\": \"mc:Campaign\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"type\": \"schema:additionalType\",\n        \"status\": \"schema:creativeWorkStatus\",\n        \"create_time\": \"schema:dateCreated\",\n        \"send_time\": \"schema:datePublished\",\n        \"archive_url\": \"schema:url\",\n        \"subject_line\": \"schema:headline\",\n        \"preview_text\": \"schema:abstract\",\n        \"from_name\": \"schema:author\",\n        \"reply_to\": \"schema:replyToUrl\",\n        \"emails_sent\": \"schema:commentCount\",\n        \"recipients\": {\n          \"@id\": \"schema:audience\",\n          \"@context\": {\n            \"list_id\": \"schema:identifier\",\n            \"list_name\":\
  \ \"schema:name\",\n            \"recipient_count\": \"schema:audienceSize\"\n          }\n        },\n        \"settings\": {\n          \"@id\": \"mc:campaignSettings\",\n          \"@context\": {\n            \"subject_line\": \"schema:headline\",\n            \"preview_text\": \"schema:abstract\",\n            \"title\": \"schema:name\",\n            \"from_name\": \"schema:author\",\n            \"reply_to\": \"schema:replyToUrl\",\n            \"template_id\": \"schema:isBasedOn\"\n          }\n        },\n        \"tracking\": {\n          \"@id\": \"mc:campaignTracking\",\n          \"@context\": {\n            \"opens\": \"schema:interactionStatistic\",\n            \"html_clicks\": \"schema:interactionStatistic\",\n            \"google_analytics\": \"schema:identifier\"\n          }\n        },\n        \"report_summary\": {\n          \"@id\": \"mc:campaignReport\",\n          \"@context\": {\n            \"opens\": \"schema:interactionStatistic\",\n            \"unique_opens\"\
  : \"schema:interactionStatistic\",\n            \"open_rate\": \"schema:interactionStatistic\",\n            \"clicks\": \"schema:interactionStatistic\",\n            \"click_rate\": \"schema:interactionStatistic\"\n          }\n        }\n      }\n    },\n\n    \"Audience\": {\n      \"@id\": \"mc:Audience\",\n      \"@type\": \"schema:Audience\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"date_created\": \"schema:dateCreated\",\n        \"permission_reminder\": \"schema:description\",\n        \"subscribe_url_short\": \"schema:url\",\n        \"subscribe_url_long\": \"schema:url\",\n        \"visibility\": \"schema:accessMode\",\n        \"double_optin\": \"mc:doubleOptin\",\n        \"email_type_option\": \"mc:emailTypeOption\",\n        \"contact\": {\n          \"@id\": \"schema:contactPoint\",\n          \"@type\": \"schema:PostalAddress\",\n          \"@context\": {\n            \"company\": \"schema:name\",\n  \
  \          \"address1\": \"schema:streetAddress\",\n            \"address2\": \"schema:streetAddress\",\n            \"city\": \"schema:addressLocality\",\n            \"state\": \"schema:addressRegion\",\n            \"zip\": \"schema:postalCode\",\n            \"country\": \"schema:addressCountry\",\n            \"phone\": \"schema:telephone\"\n          }\n        },\n        \"campaign_defaults\": {\n          \"@id\": \"mc:campaignDefaults\",\n          \"@context\": {\n            \"from_name\": \"schema:author\",\n            \"from_email\": \"schema:email\",\n            \"subject\": \"schema:headline\",\n            \"language\": \"schema:inLanguage\"\n          }\n        },\n        \"stats\": {\n          \"@id\": \"mc:audienceStats\",\n          \"@context\": {\n            \"member_count\": \"schema:audienceSize\",\n            \"total_contacts\": \"schema:audienceSize\",\n            \"campaign_count\": \"schema:numberOfItems\",\n            \"open_rate\": \"schema:interactionStatistic\"\
  ,\n            \"click_rate\": \"schema:interactionStatistic\"\n          }\n        }\n      }\n    },\n\n    \"Member\": {\n      \"@id\": \"mc:Member\",\n      \"@type\": \"schema:Person\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"email_address\": \"schema:email\",\n        \"full_name\": \"schema:name\",\n        \"status\": \"mc:subscriptionStatus\",\n        \"language\": \"schema:knowsLanguage\",\n        \"vip\": \"mc:vipStatus\",\n        \"timestamp_signup\": \"schema:dateCreated\",\n        \"timestamp_opt\": \"schema:dateModified\",\n        \"last_changed\": \"schema:dateModified\",\n        \"ip_signup\": \"mc:signupIpAddress\",\n        \"member_rating\": \"schema:ratingValue\",\n        \"email_client\": \"mc:emailClient\",\n        \"source\": \"schema:isBasedOn\",\n        \"location\": {\n          \"@id\": \"schema:homeLocation\",\n          \"@type\": \"schema:GeoCoordinates\",\n          \"@context\": {\n            \"latitude\": \"\
  schema:latitude\",\n            \"longitude\": \"schema:longitude\",\n            \"country_code\": \"schema:addressCountry\",\n            \"timezone\": \"schema:timezone\",\n            \"region\": \"schema:addressRegion\"\n          }\n        },\n        \"merge_fields\": \"mc:mergeFields\",\n        \"interests\": \"schema:interestCount\",\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@context\": {\n            \"id\": \"schema:identifier\",\n            \"name\": \"schema:name\"\n          }\n        },\n        \"stats\": {\n          \"@id\": \"mc:memberStats\",\n          \"@context\": {\n            \"avg_open_rate\": \"schema:interactionStatistic\",\n            \"avg_click_rate\": \"schema:interactionStatistic\",\n            \"ecommerce_data\": {\n              \"@id\": \"mc:ecommerceData\",\n              \"@context\": {\n                \"total_revenue\": \"schema:totalPrice\",\n                \"number_of_orders\": \"schema:orderQuantity\",\n\
  \                \"currency_code\": \"schema:priceCurrency\"\n              }\n            }\n          }\n        },\n        \"marketing_permissions\": \"mc:marketingPermissions\",\n        \"sms_phone_number\": \"schema:telephone\",\n        \"sms_subscription_status\": \"mc:smsSubscriptionStatus\"\n      }\n    },\n\n    \"Template\": {\n      \"@id\": \"mc:Template\",\n      \"@type\": \"schema:CreativeWork\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"type\": \"schema:additionalType\",\n        \"category\": \"schema:genre\",\n        \"date_created\": \"schema:dateCreated\",\n        \"date_edited\": \"schema:dateModified\",\n        \"created_by\": \"schema:creator\",\n        \"edited_by\": \"schema:editor\",\n        \"active\": \"mc:isActive\",\n        \"folder_id\": \"schema:isPartOf\",\n        \"thumbnail\": \"schema:thumbnailUrl\",\n        \"share_url\": \"schema:url\",\n        \"content_type\": \"schema:encodingFormat\"\
  ,\n        \"responsive\": \"mc:isResponsive\",\n        \"drag_and_drop\": \"mc:isDragAndDrop\",\n        \"html\": \"schema:text\",\n        \"sections\": \"schema:hasPart\"\n      }\n    },\n\n    \"TransactionalMessage\": {\n      \"@id\": \"mc:TransactionalMessage\",\n      \"@type\": \"schema:EmailMessage\",\n      \"@context\": {\n        \"_id\": \"schema:identifier\",\n        \"subject\": \"schema:headline\",\n        \"from_email\": \"schema:sender\",\n        \"from_name\": \"schema:author\",\n        \"html\": \"schema:text\",\n        \"text\": \"schema:text\",\n        \"to\": {\n          \"@id\": \"schema:recipient\",\n          \"@context\": {\n            \"email\": \"schema:email\",\n            \"name\": \"schema:name\",\n            \"type\": \"schema:additionalType\"\n          }\n        },\n        \"tags\": \"schema:keywords\",\n        \"metadata\": \"schema:additionalProperty\",\n        \"attachments\": {\n          \"@id\": \"schema:associatedMedia\",\n  \
  \        \"@context\": {\n            \"type\": \"schema:encodingFormat\",\n            \"name\": \"schema:name\",\n            \"content\": \"schema:contentUrl\"\n          }\n        },\n        \"track_opens\": \"mc:trackOpens\",\n        \"track_clicks\": \"mc:trackClicks\",\n        \"send_at\": \"schema:datePublished\",\n        \"subaccount\": \"mc:subaccount\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/mailchimp/refs/heads/main/json-ld/context.jsonld
tags:
- Campaigns
- Email Marketing
- Marketing Automation
- Newsletters
- Transactional Email
- JSON-LD
- Linked Data
- Semantic Web
---
