---
api_specs:
- filename: cometapi-unified-api-openapi.yml
  format: yaml
  label: CometAPI Unified API
  slug: cometapi-unified-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cometapi/refs/heads/main/openapi/cometapi-unified-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/cometapi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cometapi/refs/heads/main/json-ld/cometapi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cometapi from CometAPI.
layout: jsonld
name: Cometapi Context
namespaces:
- prefix: cometapi
  uri: https://cometapi.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: ChatCompletion
  type: ''
- container: ''
  name: Message
  type: ''
- container: ''
  name: Usage
  type: ''
- container: ''
  name: Model
  type: ''
property_count: 4
provider_name: CometAPI
provider_slug: cometapi
slug: cometapi-context
source_filename: cometapi-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cometapi\": \"https://cometapi.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"ChatCompletion\": {\n      \"@id\": \"cometapi:ChatCompletion\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"model\": {\n          \"@id\": \"cometapi:model\",\n          \"@type\": \"xsd:string\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"choices\": {\n          \"@id\": \"cometapi:choices\",\n          \"@container\": \"@set\"\n        },\n        \"usage\": {\n          \"@id\": \"cometapi:usage\"\n        }\n      }\n    },\n\n    \"Message\": {\n      \"@id\": \"cometapi:Message\",\n      \"@context\": {\n        \"role\": {\n          \"@id\": \"cometapi:role\",\n          \"@type\": \"xsd:string\"\n        },\n \
  \       \"content\": \"schema:text\"\n      }\n    },\n\n    \"Usage\": {\n      \"@id\": \"cometapi:Usage\",\n      \"@context\": {\n        \"prompt_tokens\": {\n          \"@id\": \"cometapi:promptTokens\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"completion_tokens\": {\n          \"@id\": \"cometapi:completionTokens\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"total_tokens\": {\n          \"@id\": \"cometapi:totalTokens\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Model\": {\n      \"@id\": \"cometapi:Model\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"owned_by\": {\n          \"@id\": \"cometapi:ownedBy\",\n          \"@type\": \"xsd:string\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cometapi/refs/heads/main/json-ld/cometapi-context.jsonld
tags:
- AI
- Aggregator
- Audio
- Chat
- Embeddings
- Generative AI
- Images
- LLM
- Multi-Model
- OpenAI-Compatible
- Video
- JSON-LD
- Linked Data
- Semantic Web
---
