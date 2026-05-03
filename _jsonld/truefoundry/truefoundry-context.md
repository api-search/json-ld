---
api_specs:
- filename: truefoundry-ai-gateway-openapi.yml
  format: yaml
  label: TrueFoundry AI Gateway API
  slug: truefoundry-ai-gateway-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/truefoundry/refs/heads/main/openapi/truefoundry-ai-gateway-openapi.yml
class_count: 28
classes:
- Model
- ChatCompletion
- Embedding
- Batch
- File
- model
- messages
- role
- content
- temperature
- max_tokens
- stream
- tools
- usage
- prompt_tokens
- completion_tokens
- total_tokens
- finish_reason
- choices
- embedding
- dimensions
- query
- documents
- relevance_score
- flagged
- purpose
- provider
- owned_by
context_file: json-ld/truefoundry-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/truefoundry/refs/heads/main/json-ld/truefoundry-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Truefoundry from TrueFoundry.
layout: jsonld
name: Truefoundry Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: ml
  uri: https://www.w3.org/ns/ml-schema#
properties:
- container: ''
  name: created
  type: integer
property_count: 1
provider_name: TrueFoundry
provider_slug: truefoundry
slug: truefoundry-context
source_filename: truefoundry-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.truefoundry.com/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ml\": \"https://www.w3.org/ns/ml-schema#\",\n\n    \"Model\": \"ml:Model\",\n    \"ChatCompletion\": \"schema:Event\",\n    \"Embedding\": \"schema:ItemList\",\n    \"Batch\": \"schema:DataFeed\",\n    \"File\": \"schema:MediaObject\",\n\n    \"model\": \"schema:identifier\",\n    \"messages\": \"schema:hasPart\",\n    \"role\": \"schema:roleName\",\n    \"content\": \"schema:text\",\n    \"temperature\": \"samplingTemperature\",\n    \"max_tokens\": \"maxOutputTokens\",\n    \"stream\": \"schema:isLiveBroadcast\",\n    \"tools\": \"schema:potentialAction\",\n    \"usage\": \"resourceUsage\",\n    \"prompt_tokens\": \"promptTokens\",\n    \"completion_tokens\": \"completionTokens\",\n    \"total_tokens\": \"totalTokens\",\n    \"created\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"\
  xsd:integer\"\n    },\n    \"finish_reason\": \"completionReason\",\n    \"choices\": \"schema:result\",\n    \"embedding\": \"schema:value\",\n    \"dimensions\": \"vectorDimensions\",\n    \"query\": \"schema:query\",\n    \"documents\": \"schema:itemListElement\",\n    \"relevance_score\": \"schema:ratingValue\",\n    \"flagged\": \"isViolation\",\n    \"purpose\": \"schema:purpose\",\n    \"provider\": \"schema:provider\",\n    \"owned_by\": \"schema:author\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/truefoundry/refs/heads/main/json-ld/truefoundry-context.jsonld
tags:
- AI Platform
- Enterprise AI
- Kubernetes
- LLM Gateway
- MLOps
- JSON-LD
- Linked Data
- Semantic Web
---
