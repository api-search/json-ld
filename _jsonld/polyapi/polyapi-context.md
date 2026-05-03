---
api_specs:
- filename: polyapi-platform-openapi.yml
  format: yaml
  label: PolyAPI Platform API
  slug: polyapi
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/polyapi/refs/heads/main/openapi/polyapi-platform-openapi.yml
class_count: 0
classes: []
context_file: json-ld/polyapi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/polyapi/refs/heads/main/json-ld/polyapi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Polyapi from PolyAPI.
layout: jsonld
name: Polyapi Context
namespaces:
- prefix: poly
  uri: https://docs.polyapi.io/
properties:
- container: ''
  name: ApiFunction
  type: ''
- container: ''
  name: ServerFunction
  type: ''
- container: ''
  name: ClientFunction
  type: ''
- container: ''
  name: Webhook
  type: ''
- container: ''
  name: Variable
  type: ''
- container: ''
  name: Trigger
  type: ''
- container: ''
  name: Job
  type: ''
- container: ''
  name: Schema
  type: ''
- container: ''
  name: Environment
  type: ''
- container: ''
  name: Conversation
  type: ''
property_count: 10
provider_name: PolyAPI
provider_slug: polyapi
slug: polyapi-context
source_filename: polyapi-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"poly\": \"https://docs.polyapi.io/\",\n    \"ApiFunction\": {\n      \"@id\": \"poly:api_functions\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"context\": \"https://schema.org/category\",\n        \"method\": \"https://schema.org/httpMethod\",\n        \"url\": \"https://schema.org/url\",\n        \"headers\": \"https://schema.org/additionalProperty\",\n        \"requestBody\": \"https://schema.org/object\",\n        \"responseSchema\": \"https://schema.org/object\",\n        \"state\": \"https://schema.org/status\",\n        \"owner\": \"https://schema.org/author\",\n        \"visibility\": \"https://schema.org/accessMode\"\n      }\n    },\n    \"ServerFunction\": {\n      \"@id\": \"poly:server_functions\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"description\"\
  : \"https://schema.org/description\",\n        \"context\": \"https://schema.org/category\",\n        \"language\": \"https://schema.org/programmingLanguage\",\n        \"code\": \"https://schema.org/text\",\n        \"deploymentId\": \"https://schema.org/identifier\",\n        \"state\": \"https://schema.org/status\",\n        \"owner\": \"https://schema.org/author\",\n        \"visibility\": \"https://schema.org/accessMode\"\n      }\n    },\n    \"ClientFunction\": {\n      \"@id\": \"poly:client_functions\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"context\": \"https://schema.org/category\",\n        \"language\": \"https://schema.org/programmingLanguage\",\n        \"code\": \"https://schema.org/text\",\n        \"state\": \"https://schema.org/status\",\n        \"owner\": \"https://schema.org/author\",\n        \"visibility\": \"https://schema.org/accessMode\"\n      }\n    },\n\
  \    \"Webhook\": {\n      \"@id\": \"poly:webhooks\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"context\": \"https://schema.org/category\",\n        \"url\": \"https://schema.org/url\",\n        \"authentication\": \"https://schema.org/authenticator\",\n        \"state\": \"https://schema.org/status\"\n      }\n    },\n    \"Variable\": {\n      \"@id\": \"poly:variables\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"pathIdentifier\": \"https://schema.org/identifier\",\n        \"value\": \"https://schema.org/value\",\n        \"secret\": \"https://schema.org/accessMode\",\n        \"visibility\": \"https://schema.org/accessMode\"\n      }\n    },\n    \"Trigger\": {\n      \"@id\": \"poly:triggers\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"description\"\
  : \"https://schema.org/description\",\n        \"sourceType\": \"https://schema.org/category\",\n        \"sourceId\": {\n          \"@id\": \"poly:webhooks\",\n          \"@type\": \"@id\"\n        },\n        \"targetFunctionId\": {\n          \"@id\": \"poly:server_functions\",\n          \"@type\": \"@id\"\n        },\n        \"targetFunctionType\": \"https://schema.org/category\",\n        \"state\": \"https://schema.org/status\"\n      }\n    },\n    \"Job\": {\n      \"@id\": \"poly:jobs\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"functionId\": {\n          \"@id\": \"poly:server_functions\",\n          \"@type\": \"@id\"\n        },\n        \"functionType\": \"https://schema.org/category\",\n        \"schedule\": \"https://schema.org/repeatFrequency\",\n        \"state\": \"https://schema.org/status\",\n        \"lastRunAt\": \"https://schema.org/dateModified\",\n        \"\
  nextRunAt\": \"https://schema.org/scheduledTime\"\n      }\n    },\n    \"Schema\": {\n      \"@id\": \"poly:schemas\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"context\": \"https://schema.org/category\",\n        \"definition\": \"https://schema.org/object\",\n        \"visibility\": \"https://schema.org/accessMode\"\n      }\n    },\n    \"Environment\": {\n      \"@id\": \"poly:environments\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"contextName\": \"https://schema.org/identifier\"\n      }\n    },\n    \"Conversation\": {\n      \"@id\": \"poly:assistants\",\n      \"@context\": {\n        \"slug\": \"https://schema.org/identifier\",\n        \"messages\": \"https://schema.org/comment\",\n        \"role\": \"https://schema.org/roleName\",\n        \"content\": \"https://schema.org/text\"\
  \n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/polyapi/refs/heads/main/json-ld/polyapi-context.jsonld
tags:
- Integrations
- Microservices
- Middleware
- Orchestrations
- Pro-Code API Composition
- JSON-LD
- Linked Data
- Semantic Web
---
