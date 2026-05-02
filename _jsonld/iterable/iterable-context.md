---
api_specs:
- filename: iterable-rest-api-openapi.yml
  format: yaml
  label: Iterable REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/iterable/refs/heads/main/openapi/iterable-rest-api-openapi.yml
- filename: iterable-export-api-openapi.yml
  format: yaml
  label: Iterable Export API
  slug: export-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/iterable/refs/heads/main/openapi/iterable-export-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/iterable-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/iterable/refs/heads/main/json-ld/iterable-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Iterable from Iterable.
layout: jsonld
name: Iterable Context
namespaces:
- prefix: iterable
  uri: https://api.iterable.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: User
  type: ''
- container: ''
  name: Campaign
  type: ''
- container: ''
  name: Event
  type: ''
- container: ''
  name: CommerceItem
  type: ''
- container: ''
  name: List
  type: ''
- container: ''
  name: Channel
  type: ''
- container: ''
  name: EmailTemplate
  type: ''
- container: ''
  name: Catalog
  type: ''
property_count: 8
provider_name: Iterable
provider_slug: iterable
slug: iterable-context
source_filename: iterable-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"iterable\": \"https://api.iterable.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"User\": {\n      \"@id\": \"iterable:User\",\n      \"@context\": {\n        \"email\": \"schema:email\",\n        \"userId\": \"iterable:userId\",\n        \"phoneNumber\": \"schema:telephone\",\n        \"signupDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"profileUpdatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"dataFields\": \"iterable:dataFields\",\n        \"emailListIds\": {\n          \"@id\": \"iterable:emailListIds\",\n          \"@container\": \"@set\"\n        },\n        \"devices\": {\n          \"@id\": \"iterable:devices\",\n          \"@container\": \"@set\"\n        },\n      \
  \  \"unsubscribedChannelIds\": {\n          \"@id\": \"iterable:unsubscribedChannelIds\",\n          \"@container\": \"@set\"\n        },\n        \"unsubscribedMessageTypeIds\": {\n          \"@id\": \"iterable:unsubscribedMessageTypeIds\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Campaign\": {\n      \"@id\": \"iterable:Campaign\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"campaignType\": \"iterable:campaignType\",\n        \"messageMedium\": \"iterable:messageMedium\",\n        \"campaignState\": \"iterable:campaignState\",\n        \"templateId\": \"iterable:templateId\",\n        \"workflowId\": \"iterable:workflowId\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"startAt\": {\n          \"@id\": \"iterable:startAt\",\n  \
  \        \"@type\": \"xsd:dateTime\"\n        },\n        \"endedAt\": {\n          \"@id\": \"iterable:endedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"listIds\": {\n          \"@id\": \"iterable:listIds\",\n          \"@container\": \"@set\"\n        },\n        \"labels\": {\n          \"@id\": \"iterable:labels\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Event\": {\n      \"@id\": \"iterable:Event\",\n      \"@context\": {\n        \"eventName\": \"schema:name\",\n        \"email\": \"schema:email\",\n        \"userId\": \"iterable:userId\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"campaignId\": \"iterable:campaignId\",\n        \"templateId\": \"iterable:templateId\",\n        \"dataFields\": \"iterable:dataFields\"\n      }\n    },\n\n    \"CommerceItem\": {\n      \"@id\": \"iterable:CommerceItem\",\n      \"@context\": {\n        \"name\"\
  : \"schema:name\",\n        \"sku\": \"schema:sku\",\n        \"description\": \"schema:description\",\n        \"price\": \"schema:price\",\n        \"quantity\": \"iterable:quantity\",\n        \"imageUrl\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"categories\": {\n          \"@id\": \"schema:category\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"List\": {\n      \"@id\": \"iterable:List\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"listType\": \"iterable:listType\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Channel\": {\n      \"@id\": \"iterable:Channel\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"channelType\"\
  : \"iterable:channelType\",\n        \"messageMedium\": \"iterable:messageMedium\"\n      }\n    },\n\n    \"EmailTemplate\": {\n      \"@id\": \"iterable:EmailTemplate\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"subject\": \"iterable:subject\",\n        \"fromName\": \"iterable:fromName\",\n        \"fromEmail\": \"iterable:fromEmail\",\n        \"html\": \"iterable:html\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Catalog\": {\n      \"@id\": \"iterable:Catalog\",\n      \"@context\": {\n        \"catalogName\": \"schema:name\",\n        \"fieldMappings\": \"iterable:fieldMappings\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/iterable/refs/heads/main/json-ld/iterable-context.jsonld
tags:
- Cross-Channel Messaging
- Customer Engagement
- Email
- Marketing Automation
- Push Notifications
- SMS
- JSON-LD
- Linked Data
- Semantic Web
---
