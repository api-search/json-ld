---
api_specs:
- filename: aimlapi-openapi.yml
  format: yaml
  label: AIMLAPI
  slug: aimlapi
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aimlapi/refs/heads/main/openapi/aimlapi-openapi.yml
class_count: 5
classes:
- ChatCompletionRequest
- ChatCompletionResponse
- ImageGenerationRequest
- EmbeddingRequest
- ModelInfo
context_file: json-ld/aimlapi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aimlapi/refs/heads/main/json-ld/aimlapi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aimlapi from AIMLAPI.
layout: jsonld
name: Aimlapi Context
namespaces:
- prefix: aimlapi
  uri: https://aimlapi.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: model
  type: string
- container: set
  name: messages
  type: reference
- container: ''
  name: temperature
  type: decimal
- container: ''
  name: maxTokens
  type: integer
- container: ''
  name: stream
  type: boolean
- container: ''
  name: prompt
  type: string
- container: ''
  name: role
  type: string
- container: ''
  name: content
  type: string
- container: ''
  name: ownedBy
  type: string
- container: ''
  name: createdAt
  type: dateTime
property_count: 10
provider_name: AIMLAPI
provider_slug: aimlapi
slug: aimlapi-context
source_filename: aimlapi-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aimlapi\": \"https://aimlapi.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ChatCompletionRequest\": \"aimlapi:ChatCompletionRequest\",\n    \"ChatCompletionResponse\": \"aimlapi:ChatCompletionResponse\",\n    \"ImageGenerationRequest\": \"aimlapi:ImageGenerationRequest\",\n    \"EmbeddingRequest\": \"aimlapi:EmbeddingRequest\",\n    \"ModelInfo\": \"aimlapi:ModelInfo\",\n    \"model\": {\n      \"@id\": \"aimlapi:model\",\n      \"@type\": \"xsd:string\"\n    },\n    \"messages\": {\n      \"@id\": \"aimlapi:messages\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"temperature\": {\n      \"@id\": \"aimlapi:temperature\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"maxTokens\": {\n      \"@id\": \"aimlapi:max_tokens\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"stream\": {\n      \"@id\": \"aimlapi:stream\",\n    \
  \  \"@type\": \"xsd:boolean\"\n    },\n    \"prompt\": {\n      \"@id\": \"aimlapi:prompt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"role\": {\n      \"@id\": \"aimlapi:role\",\n      \"@type\": \"xsd:string\"\n    },\n    \"content\": {\n      \"@id\": \"aimlapi:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ownedBy\": {\n      \"@id\": \"aimlapi:owned_by\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aimlapi/refs/heads/main/json-ld/aimlapi-context.jsonld
tags:
- Artificial Intelligence
- Machine Learning
- AI Models
- LLM
- Image Generation
- Video Generation
- Speech
- Embeddings
- API Gateway
- Developer Tools
- JSON-LD
- Linked Data
- Semantic Web
---
