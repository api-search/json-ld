---
api_specs:
- filename: resources_list.htm
  format: yaml
  label: Salesforce Service Cloud REST API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_list.htm
- filename: salesforce-streaming-api-asyncapi.yml
  format: yaml
  label: Service Cloud Streaming API
  slug: ''
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-service-cloud/refs/heads/main/asyncapi/salesforce-streaming-api-asyncapi.yml
- filename: salesforce-live-agent-openapi.yml
  format: yaml
  label: Live Agent REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-service-cloud/refs/heads/main/openapi/salesforce-live-agent-openapi.yml
class_count: 0
classes: []
context_file: json-ld/salesforce-service-cloud-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/salesforce-service-cloud/refs/heads/main/json-ld/salesforce-service-cloud-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Salesforce Service Cloud from Salesforce Service Cloud.
layout: jsonld
name: Salesforce Service Cloud Context
namespaces:
- prefix: sfsc
  uri: https://developer.salesforce.com/schemas/service-cloud/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Case
  type: ''
- container: ''
  name: Contact
  type: ''
- container: ''
  name: Account
  type: ''
- container: ''
  name: KnowledgeArticle
  type: ''
- container: ''
  name: ChatSession
  type: ''
- container: ''
  name: Agent
  type: ''
property_count: 6
provider_name: Salesforce Service Cloud
provider_slug: salesforce-service-cloud
slug: salesforce-service-cloud-context
source_filename: salesforce-service-cloud-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"sfsc\": \"https://developer.salesforce.com/schemas/service-cloud/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Case\": {\n      \"@id\": \"sfsc:Case\",\n      \"@context\": {\n        \"caseNumber\": \"sfsc:caseNumber\",\n        \"subject\": \"sfsc:subject\",\n        \"description\": \"schema:description\",\n        \"status\": \"sfsc:status\",\n        \"priority\": \"sfsc:priority\",\n        \"origin\": \"sfsc:origin\",\n        \"type\": \"sfsc:caseType\",\n        \"contact\": {\n          \"@id\": \"sfsc:contact\",\n          \"@type\": \"@id\"\n        },\n        \"account\": {\n          \"@id\": \"sfsc:account\",\n          \"@type\": \"@id\"\n        },\n        \"owner\": {\n          \"@id\": \"sfsc:owner\",\n          \"@type\": \"@id\"\n        },\n        \"isClosed\": {\n          \"@id\": \"sfsc:isClosed\"\
  ,\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isEscalated\": {\n          \"@id\": \"sfsc:isEscalated\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"closedDate\": {\n          \"@id\": \"sfsc:closedDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModifiedDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Contact\": {\n      \"@id\": \"sfsc:Contact\",\n      \"@context\": {\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"email\": \"schema:email\",\n        \"phone\": \"schema:telephone\",\n        \"account\": {\n          \"@id\": \"sfsc:account\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Account\": {\n      \"@id\": \"sfsc:Account\",\n      \"@context\"\
  : {\n        \"name\": \"schema:name\",\n        \"website\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"industry\": \"sfsc:industry\",\n        \"phone\": \"schema:telephone\"\n      }\n    },\n\n    \"KnowledgeArticle\": {\n      \"@id\": \"sfsc:KnowledgeArticle\",\n      \"@context\": {\n        \"title\": \"schema:headline\",\n        \"summary\": \"schema:abstract\",\n        \"articleBody\": \"schema:articleBody\",\n        \"articleNumber\": \"sfsc:articleNumber\",\n        \"publishStatus\": \"sfsc:publishStatus\",\n        \"urlName\": \"sfsc:urlName\",\n        \"language\": \"schema:inLanguage\",\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastPublishedDate\": {\n          \"@id\": \"sfsc:lastPublishedDate\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ChatSession\": {\n      \"@id\": \"sfsc:ChatSession\",\n  \
  \    \"@context\": {\n        \"sessionId\": \"sfsc:sessionId\",\n        \"visitorName\": \"schema:name\",\n        \"status\": \"sfsc:status\",\n        \"startTime\": {\n          \"@id\": \"sfsc:startTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endTime\": {\n          \"@id\": \"sfsc:endTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"agent\": {\n          \"@id\": \"sfsc:agent\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Agent\": {\n      \"@id\": \"sfsc:Agent\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"email\": \"schema:email\",\n        \"isAvailable\": {\n          \"@id\": \"sfsc:isAvailable\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"activeChats\": {\n          \"@id\": \"sfsc:activeChats\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/salesforce-service-cloud/refs/heads/main/json-ld/salesforce-service-cloud-context.jsonld
tags:
- Case Management
- CRM
- Customer Service
- Help Desk
- Support
- Ticketing
- JSON-LD
- Linked Data
- Semantic Web
---
