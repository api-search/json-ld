---
api_specs:
- filename: fullstory-server-api-openapi.yml
  format: yaml
  label: FullStory Server API
  slug: server-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fullstory/refs/heads/main/openapi/fullstory-server-api-openapi.yml
- filename: fullstory-segments-export-api-openapi.yml
  format: yaml
  label: FullStory Segments Export API
  slug: segments-export-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fullstory/refs/heads/main/openapi/fullstory-segments-export-api-openapi.yml
- filename: fullstory-sessions-api-openapi.yml
  format: yaml
  label: FullStory Sessions API
  slug: sessions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fullstory/refs/heads/main/openapi/fullstory-sessions-api-openapi.yml
- filename: fullstory-webhooks-api-openapi.yml
  format: yaml
  label: FullStory Webhooks API
  slug: webhooks-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fullstory/refs/heads/main/openapi/fullstory-webhooks-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/fullstory-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/fullstory/refs/heads/main/json-ld/fullstory-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Fullstory from FullStory.
layout: jsonld
name: Fullstory Context
namespaces:
- prefix: fs
  uri: https://developer.fullstory.com/ns/
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
  name: Event
  type: ''
- container: ''
  name: Session
  type: ''
- container: ''
  name: Segment
  type: ''
- container: ''
  name: WebhookEndpoint
  type: ''
- container: ''
  name: SessionSummary
  type: ''
- container: ''
  name: Operation
  type: ''
property_count: 7
provider_name: FullStory
provider_slug: fullstory
slug: fullstory-context
source_filename: fullstory-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"fs\": \"https://developer.fullstory.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"User\": {\n      \"@id\": \"fs:User\",\n      \"@context\": {\n        \"id\": \"fs:userId\",\n        \"uid\": \"fs:externalUserId\",\n        \"display_name\": \"schema:name\",\n        \"email\": \"schema:email\",\n        \"properties\": \"fs:customProperties\",\n        \"app_url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Event\": {\n      \"@id\": \"fs:Event\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"timestamp\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"properties\": \"fs:customProperties\",\n        \"session\": \"fs:sessionReference\",\n        \"user\": \"fs:userReference\"\
  \n      }\n    },\n\n    \"Session\": {\n      \"@id\": \"fs:Session\",\n      \"@context\": {\n        \"sessionId\": \"fs:sessionId\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Segment\": {\n      \"@id\": \"fs:Segment\",\n      \"@context\": {\n        \"id\": \"fs:segmentId\",\n        \"name\": \"schema:name\",\n        \"creator\": \"dcterms:creator\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"WebhookEndpoint\": {\n      \"@id\": \"fs:WebhookEndpoint\",\n      \"@context\": {\n        \"id\": \"fs:endpointId\",\n        \"url\": {\n          \"@id\": \"fs:destinationUrl\",\n          \"@type\"\
  : \"@id\"\n        },\n        \"events\": {\n          \"@id\": \"fs:configuredEvents\",\n          \"@container\": \"@set\"\n        },\n        \"enabled\": \"fs:isEnabled\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"SessionSummary\": {\n      \"@id\": \"fs:SessionSummary\",\n      \"@context\": {\n        \"sessionId\": \"fs:sessionId\",\n        \"summary\": \"schema:text\",\n        \"configProfileId\": \"fs:configProfileId\"\n      }\n    },\n\n    \"Operation\": {\n      \"@id\": \"fs:Operation\",\n      \"@context\": {\n        \"id\": \"fs:operationId\",\n        \"type\": \"fs:operationType\",\n        \"state\": \"fs:operationState\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"finishedAt\": {\n          \"@id\": \"fs:finishedAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n\
  \    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/fullstory/refs/heads/main/json-ld/fullstory-context.jsonld
tags:
- Analytics
- Digital Experience
- Session Replay
- Webhooks
- Data Export
- JSON-LD
- Linked Data
- Semantic Web
---
