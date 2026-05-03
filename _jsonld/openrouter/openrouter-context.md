---
api_specs:
- filename: openapi.json
  format: json
  label: OpenRouter
  slug: openrouter
  spec_type: OpenAPI
  url: https://openrouter.ai/openapi.json
- filename: openapi.json
  format: json
  label: OpenRouter Chat Completions API
  slug: chat-completions-api
  spec_type: OpenAPI
  url: https://openrouter.ai/openapi.json
- filename: openapi.json
  format: json
  label: OpenRouter Models API
  slug: models-api
  spec_type: OpenAPI
  url: https://openrouter.ai/openapi.json
- filename: openapi.json
  format: json
  label: OpenRouter Generation API
  slug: generation-api
  spec_type: OpenAPI
  url: https://openrouter.ai/openapi.json
- filename: openapi.json
  format: json
  label: OpenRouter Keys Management API
  slug: keys-api
  spec_type: OpenAPI
  url: https://openrouter.ai/openapi.json
class_count: 21
classes:
- Model
- Provider
- ChatCompletion
- Generation
- id
- name
- description
- pricing
- prompt
- completion
- top_provider
- architecture
- messages
- role
- content
- model
- usage
- prompt_tokens
- completion_tokens
- total_tokens
- finish_reason
context_file: json-ld/openrouter-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/openrouter/refs/heads/main/json-ld/openrouter-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Openrouter from OpenRouter.
layout: jsonld
name: Openrouter Context
namespaces:
- prefix: openrouter
  uri: https://openrouter.ai/ns#
properties:
- container: ''
  name: context_length
  type: integer
property_count: 1
provider_name: OpenRouter
provider_slug: openrouter
slug: openrouter-context
source_filename: openrouter-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"openrouter\": \"https://openrouter.ai/ns#\",\n    \"Model\": \"openrouter:Model\",\n    \"Provider\": \"openrouter:Provider\",\n    \"ChatCompletion\": \"openrouter:ChatCompletion\",\n    \"Generation\": \"openrouter:Generation\",\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"context_length\": {\n      \"@id\": \"openrouter:contextLength\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pricing\": \"openrouter:pricing\",\n    \"prompt\": \"openrouter:promptPrice\",\n    \"completion\": \"openrouter:completionPrice\",\n    \"top_provider\": \"openrouter:topProvider\",\n    \"architecture\": \"openrouter:architecture\",\n    \"messages\": \"openrouter:messages\",\n    \"role\": \"openrouter:role\",\n    \"content\": \"schema:text\",\n    \"model\": \"openrouter:model\",\n    \"usage\": \"openrouter:usage\",\n    \"prompt_tokens\": \"openrouter:promptTokens\"\
  ,\n    \"completion_tokens\": \"openrouter:completionTokens\",\n    \"total_tokens\": \"openrouter:totalTokens\",\n    \"finish_reason\": \"openrouter:finishReason\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/openrouter/refs/heads/main/json-ld/openrouter-context.jsonld
tags:
- Artificial Intelligence
- Gateway
- Large Language Models
- Router
- JSON-LD
- Linked Data
- Semantic Web
---
