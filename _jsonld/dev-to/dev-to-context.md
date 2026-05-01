---
api_specs:
- filename: dev-to-forem-api-openapi.yml
  format: yaml
  label: Dev.to Forem API
  slug: forem-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dev-to/refs/heads/main/openapi/dev-to-forem-api-openapi.yml
- filename: dev-to-webhooks-asyncapi.yml
  format: yaml
  label: Dev.to Webhooks API
  slug: webhooks-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/dev-to/refs/heads/main/asyncapi/dev-to-webhooks-asyncapi.yml
class_count: 0
classes: []
context_file: json-ld/dev-to-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dev-to/refs/heads/main/json-ld/dev-to-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dev To from dev-to.
layout: jsonld
name: Dev To Context
namespaces:
- prefix: forem
  uri: https://dev.to/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Article
  type: ''
- container: ''
  name: Comment
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Organization
  type: ''
- container: ''
  name: Tag
  type: ''
- container: ''
  name: PodcastEpisode
  type: ''
- container: ''
  name: Webhook
  type: ''
property_count: 7
provider_name: dev-to
provider_slug: dev-to
slug: dev-to-context
source_filename: dev-to-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"forem\": \"https://dev.to/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Article\": {\n      \"@id\": \"schema:BlogPosting\",\n      \"@context\": {\n        \"title\": \"schema:headline\",\n        \"description\": \"schema:description\",\n        \"body_html\": \"schema:articleBody\",\n        \"body_markdown\": {\n          \"@id\": \"forem:bodyMarkdown\",\n          \"@type\": \"xsd:string\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"canonical_url\": {\n          \"@id\": \"schema:mainEntityOfPage\",\n          \"@type\": \"@id\"\n        },\n        \"cover_image\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"social_image\": {\n          \"@id\": \"schema:thumbnailUrl\",\n         \
  \ \"@type\": \"@id\"\n        },\n        \"slug\": \"forem:slug\",\n        \"path\": \"forem:path\",\n        \"tag_list\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"reading_time_minutes\": {\n          \"@id\": \"schema:timeRequired\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"comments_count\": {\n          \"@id\": \"schema:commentCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"public_reactions_count\": {\n          \"@id\": \"schema:interactionCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"positive_reactions_count\": {\n          \"@id\": \"forem:positiveReactionsCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"published_at\": {\n          \"@id\": \"schema:datePublished\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n       \
  \ },\n        \"edited_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"published_timestamp\": {\n          \"@id\": \"schema:datePublished\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"collection_id\": {\n          \"@id\": \"schema:isPartOf\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"user\": {\n          \"@id\": \"schema:author\",\n          \"@type\": \"@id\"\n        },\n        \"organization\": {\n          \"@id\": \"schema:publisher\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Comment\": {\n      \"@id\": \"schema:Comment\",\n      \"@context\": {\n        \"body_html\": \"schema:text\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"user\": {\n          \"@id\": \"schema:author\",\n          \"@type\": \"@id\"\n        },\n        \"children\": {\n          \"@id\": \"\
  schema:comment\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"username\": \"schema:alternateName\",\n        \"profile_image\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"website_url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"location\": \"schema:homeLocation\",\n        \"summary\": \"schema:description\",\n        \"twitter_username\": {\n          \"@id\": \"forem:twitterUsername\",\n          \"@type\": \"xsd:string\"\n        },\n        \"github_username\": {\n          \"@id\": \"forem:githubUsername\",\n          \"@type\": \"xsd:string\"\n        },\n        \"joined_at\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Organization\": {\n      \"@id\": \"schema:Organization\"\
  ,\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"username\": \"schema:alternateName\",\n        \"slug\": \"forem:slug\",\n        \"profile_image\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Tag\": {\n      \"@id\": \"schema:DefinedTerm\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"bg_color_hex\": {\n          \"@id\": \"forem:bgColorHex\",\n          \"@type\": \"xsd:string\"\n        },\n        \"text_color_hex\": {\n          \"@id\": \"forem:textColorHex\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"PodcastEpisode\": {\n      \"@id\": \"schema:PodcastEpisode\",\n      \"@context\": {\n        \"title\": \"schema:name\",\n        \"path\": \"forem:path\",\n        \"image_url\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"podcast\": {\n          \"@id\": \"schema:partOfSeries\",\n        \
  \  \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Webhook\": {\n      \"@id\": \"forem:WebhookEndpoint\",\n      \"@context\": {\n        \"target_url\": {\n          \"@id\": \"forem:targetUrl\",\n          \"@type\": \"@id\"\n        },\n        \"source\": \"forem:source\",\n        \"events\": {\n          \"@id\": \"forem:subscribedEvents\",\n          \"@container\": \"@set\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dev-to/refs/heads/main/json-ld/dev-to-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
