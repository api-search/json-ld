---
api_specs:
- filename: freshworks-freshdesk-api-openapi.yml
  format: yaml
  label: Freshworks Freshdesk API
  slug: freshdesk-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/freshworks/refs/heads/main/openapi/freshworks-freshdesk-api-openapi.yml
- filename: freshworks-freshservice-api-openapi.yml
  format: yaml
  label: Freshworks Freshservice API
  slug: freshservice-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/freshworks/refs/heads/main/openapi/freshworks-freshservice-api-openapi.yml
- filename: freshworks-freshsales-api-openapi.yml
  format: yaml
  label: Freshworks Freshsales API
  slug: freshsales-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/freshworks/refs/heads/main/openapi/freshworks-freshsales-api-openapi.yml
- filename: freshworks-freshchat-api-openapi.yml
  format: yaml
  label: Freshworks Freshchat API
  slug: freshchat-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/freshworks/refs/heads/main/openapi/freshworks-freshchat-api-openapi.yml
- filename: freshworks-freshcaller-api-openapi.yml
  format: yaml
  label: Freshworks Freshcaller API
  slug: freshcaller-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/freshworks/refs/heads/main/openapi/freshworks-freshcaller-api-openapi.yml
- filename: freshworks-freshteam-api-openapi.yml
  format: yaml
  label: Freshworks Freshteam API
  slug: freshteam-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/freshworks/refs/heads/main/openapi/freshworks-freshteam-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/freshworks-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/freshworks/refs/heads/main/json-ld/freshworks-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Freshworks from freshworks.
layout: jsonld
name: Freshworks Context
namespaces:
- prefix: freshworks
  uri: https://freshworks.com/schemas/
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
  name: Conversation
  type: ''
- container: ''
  name: Deal
  type: ''
- container: ''
  name: Employee
  type: ''
- container: ''
  name: Asset
  type: ''
- container: ''
  name: Call
  type: ''
property_count: 9
provider_name: freshworks
provider_slug: freshworks
slug: freshworks-context
source_filename: freshworks-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"freshworks\": \"https://freshworks.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Ticket\": {\n      \"@id\": \"freshworks:Ticket\",\n      \"@context\": {\n        \"subject\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"status\": \"freshworks:ticketStatus\",\n        \"priority\": \"freshworks:ticketPriority\",\n        \"type\": \"freshworks:ticketType\",\n        \"source\": \"freshworks:ticketSource\",\n        \"requester\": {\n          \"@id\": \"freshworks:requester\",\n          \"@type\": \"@id\"\n        },\n        \"responder\": {\n          \"@id\": \"freshworks:responder\",\n          \"@type\": \"@id\"\n        },\n        \"group\": {\n          \"@id\": \"freshworks:assignedGroup\",\n          \"@type\": \"@id\"\n        },\n        \"tags\": \"schema:keywords\"\
  ,\n        \"dueBy\": {\n          \"@id\": \"freshworks:dueBy\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Contact\": {\n      \"@id\": \"freshworks:Contact\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"email\": \"schema:email\",\n        \"phone\": \"schema:telephone\",\n        \"mobile\": \"freshworks:mobilePhone\",\n        \"address\": \"schema:address\",\n        \"jobTitle\": \"schema:jobTitle\",\n        \"company\": {\n          \"@id\": \"schema:worksFor\",\n          \"@type\": \"@id\"\n        },\n        \"language\": \"schema:knowsLanguage\",\n        \"timeZone\": \"freshworks:timeZone\"\
  ,\n        \"tags\": \"schema:keywords\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Company\": {\n      \"@id\": \"freshworks:Company\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"industry\": \"schema:industry\",\n        \"website\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"phone\": \"schema:telephone\",\n        \"address\": \"schema:address\",\n        \"numberOfEmployees\": \"schema:numberOfEmployees\",\n        \"annualRevenue\": \"freshworks:annualRevenue\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Agent\": {\n      \"@id\": \"freshworks:Agent\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"email\": \"schema:email\",\n        \"phone\": \"schema:telephone\",\n        \"jobTitle\": \"schema:jobTitle\",\n        \"available\": \"freshworks:isAvailable\",\n        \"groups\": {\n          \"@id\": \"schema:memberOf\",\n          \"@container\": \"@set\"\n        },\n        \"roles\": {\n          \"@id\": \"schema:hasOccupation\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Conversation\": {\n      \"@id\": \"freshworks:Conversation\",\n      \"@context\": {\n        \"status\": \"freshworks:conversationStatus\",\n    \
  \    \"assignedAgent\": {\n          \"@id\": \"freshworks:assignedAgent\",\n          \"@type\": \"@id\"\n        },\n        \"assignedGroup\": {\n          \"@id\": \"freshworks:assignedGroup\",\n          \"@type\": \"@id\"\n        },\n        \"channel\": {\n          \"@id\": \"freshworks:channel\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Deal\": {\n      \"@id\": \"freshworks:Deal\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"amount\": \"schema:price\",\n        \"currency\": \"schema:priceCurrency\",\n        \"stage\": \"freshworks:dealStage\",\n        \"probability\": \"freshworks:probability\",\n        \"expectedClose\": {\n          \"@id\": \"freshworks:expectedCloseDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"account\": {\n          \"@id\": \"freshworks:salesAccount\",\n       \
  \   \"@type\": \"@id\"\n        },\n        \"owner\": {\n          \"@id\": \"freshworks:owner\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Employee\": {\n      \"@id\": \"freshworks:Employee\",\n      \"@context\": {\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"email\": \"schema:email\",\n        \"phone\": \"schema:telephone\",\n        \"designation\": \"schema:jobTitle\",\n        \"department\": {\n          \"@id\": \"schema:department\",\n          \"@type\": \"@id\"\n        },\n        \"branch\": {\n          \"@id\": \"freshworks:branch\",\n          \"@type\": \"@id\"\n        },\n        \"reportsTo\": {\n          \"@id\": \"freshworks:reportsTo\",\n      \
  \    \"@type\": \"@id\"\n        },\n        \"joiningDate\": {\n          \"@id\": \"freshworks:joiningDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"dateOfBirth\": {\n          \"@id\": \"schema:birthDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Asset\": {\n      \"@id\": \"freshworks:Asset\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"assetTag\": \"freshworks:assetTag\",\n        \"assetType\": {\n          \"@id\": \"freshworks:assetType\",\n          \"@type\": \"@id\"\n        },\n        \"user\": {\n          \"@id\": \"freshworks:assignedUser\",\n          \"@type\": \"@id\"\n        },\n        \"location\": {\n   \
  \       \"@id\": \"schema:location\",\n          \"@type\": \"@id\"\n        },\n        \"department\": {\n          \"@id\": \"schema:department\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Call\": {\n      \"@id\": \"freshworks:Call\",\n      \"@context\": {\n        \"direction\": \"freshworks:callDirection\",\n        \"status\": \"freshworks:callStatus\",\n        \"callerNumber\": \"schema:telephone\",\n        \"duration\": {\n          \"@id\": \"schema:duration\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"recording\": {\n          \"@id\": \"freshworks:recordingUrl\",\n          \"@type\": \"@id\"\n        },\n        \"agent\": {\n          \"@id\": \"freshworks:agent\",\n          \"@type\": \"@id\"\
  \n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/freshworks/refs/heads/main/json-ld/freshworks-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
