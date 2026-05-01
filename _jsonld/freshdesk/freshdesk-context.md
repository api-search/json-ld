---
api_specs:
- filename: freshdesk-rest-api-openapi.yml
  format: yaml
  label: Freshdesk REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/freshdesk/refs/heads/main/openapi/freshdesk-rest-api-openapi.yml
- filename: freshdesk-webhook-api-asyncapi.yml
  format: yaml
  label: Freshdesk Webhook API
  slug: webhook-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/freshdesk/refs/heads/main/asyncapi/freshdesk-webhook-api-asyncapi.yml
class_count: 0
classes: []
context_file: json-ld/freshdesk-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/freshdesk/refs/heads/main/json-ld/freshdesk-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Freshdesk from freshdesk.
layout: jsonld
name: Freshdesk Context
namespaces:
- prefix: freshdesk
  uri: https://developers.freshdesk.com/api/ns#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Ticket
  type: ''
- container: ''
  name: Contact
  type: ''
- container: ''
  name: Company
  type: ''
- container: ''
  name: Agent
  type: ''
- container: ''
  name: Group
  type: ''
- container: ''
  name: Conversation
  type: ''
- container: ''
  name: SolutionArticle
  type: ''
- container: ''
  name: Product
  type: ''
property_count: 8
provider_name: freshdesk
provider_slug: freshdesk
slug: freshdesk-context
source_filename: freshdesk-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"freshdesk\": \"https://developers.freshdesk.com/api/ns#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Ticket\": {\n      \"@id\": \"freshdesk:Ticket\",\n      \"@context\": {\n        \"subject\": \"freshdesk:subject\",\n        \"description\": \"schema:description\",\n        \"status\": \"freshdesk:status\",\n        \"priority\": \"freshdesk:priority\",\n        \"source\": \"freshdesk:source\",\n        \"type\": \"freshdesk:ticketType\",\n        \"requester\": {\n          \"@id\": \"freshdesk:requester\",\n          \"@type\": \"@id\"\n        },\n        \"responder\": {\n          \"@id\": \"freshdesk:responder\",\n          \"@type\": \"@id\"\n        },\n        \"group\": {\n          \"@id\": \"freshdesk:group\",\n          \"@type\": \"@id\"\n        },\n        \"product\": {\n          \"@id\": \"\
  freshdesk:product\",\n          \"@type\": \"@id\"\n        },\n        \"company\": {\n          \"@id\": \"freshdesk:company\",\n          \"@type\": \"@id\"\n        },\n        \"tags\": \"schema:keywords\",\n        \"dueBy\": {\n          \"@id\": \"freshdesk:dueBy\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"firstResponseDueBy\": {\n          \"@id\": \"freshdesk:firstResponseDueBy\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"ticketUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Contact\": {\n      \"@id\": \"freshdesk:Contact\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"email\": \"schema:email\",\n        \"phone\"\
  : \"schema:telephone\",\n        \"mobile\": \"freshdesk:mobile\",\n        \"address\": \"schema:address\",\n        \"jobTitle\": \"schema:jobTitle\",\n        \"language\": \"schema:knowsLanguage\",\n        \"timeZone\": \"freshdesk:timeZone\",\n        \"company\": {\n          \"@id\": \"schema:worksFor\",\n          \"@type\": \"@id\"\n        },\n        \"twitterId\": \"freshdesk:twitterId\",\n        \"active\": \"freshdesk:active\",\n        \"tags\": \"schema:keywords\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Company\": {\n      \"@id\": \"freshdesk:Company\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"domains\": \"freshdesk:domains\",\n        \"industry\": \"schema:industry\",\n\
  \        \"healthScore\": \"freshdesk:healthScore\",\n        \"accountTier\": \"freshdesk:accountTier\",\n        \"renewalDate\": {\n          \"@id\": \"freshdesk:renewalDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Agent\": {\n      \"@id\": \"freshdesk:Agent\",\n      \"@context\": {\n        \"contact\": {\n          \"@id\": \"freshdesk:agentContact\",\n          \"@type\": \"@id\"\n        },\n        \"available\": \"freshdesk:available\",\n        \"occasional\": \"freshdesk:occasional\",\n        \"ticketScope\": \"freshdesk:ticketScope\",\n        \"groups\": {\n          \"@id\": \"freshdesk:groups\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"roles\": {\n\
  \          \"@id\": \"freshdesk:roles\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"signature\": \"freshdesk:signature\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Group\": {\n      \"@id\": \"freshdesk:Group\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"agents\": {\n          \"@id\": \"freshdesk:agents\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"businessHours\": {\n          \"@id\": \"freshdesk:businessHours\",\n          \"@type\": \"@id\"\n        },\n        \"autoTicketAssign\": \"freshdesk:autoTicketAssign\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\"\
  : \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Conversation\": {\n      \"@id\": \"freshdesk:Conversation\",\n      \"@context\": {\n        \"body\": \"freshdesk:body\",\n        \"incoming\": \"freshdesk:incoming\",\n        \"private\": \"freshdesk:private\",\n        \"user\": {\n          \"@id\": \"freshdesk:user\",\n          \"@type\": \"@id\"\n        },\n        \"ticket\": {\n          \"@id\": \"freshdesk:ticket\",\n          \"@type\": \"@id\"\n        },\n        \"attachments\": {\n          \"@id\": \"freshdesk:attachments\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"SolutionArticle\"\
  : {\n      \"@id\": \"freshdesk:SolutionArticle\",\n      \"@context\": {\n        \"title\": \"schema:headline\",\n        \"description\": \"schema:articleBody\",\n        \"folder\": {\n          \"@id\": \"freshdesk:folder\",\n          \"@type\": \"@id\"\n        },\n        \"category\": {\n          \"@id\": \"freshdesk:category\",\n          \"@type\": \"@id\"\n        },\n        \"status\": \"freshdesk:publicationStatus\",\n        \"tags\": \"schema:keywords\",\n        \"hits\": \"schema:interactionCount\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Product\": {\n      \"@id\": \"freshdesk:Product\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/freshdesk/refs/heads/main/json-ld/freshdesk-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
