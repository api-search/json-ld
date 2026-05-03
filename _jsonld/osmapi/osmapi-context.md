---
api_specs:
- filename: osmapi-chat-completions-openapi.yml
  format: yaml
  label: osmAPI Chat Completions API
  slug: osmapi-chat-completions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/osmapi/refs/heads/main/openapi/osmapi-chat-completions-openapi.yml
- filename: osmapi-anthropic-messages-openapi.yml
  format: yaml
  label: osmAPI Anthropic Messages API
  slug: osmapi-anthropic-messages-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/osmapi/refs/heads/main/openapi/osmapi-anthropic-messages-openapi.yml
- filename: osmapi-models-openapi.yml
  format: yaml
  label: osmAPI Models API
  slug: osmapi-models-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/osmapi/refs/heads/main/openapi/osmapi-models-openapi.yml
- filename: osmapi-health-openapi.yml
  format: yaml
  label: osmAPI Health API
  slug: osmapi-health-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/osmapi/refs/heads/main/openapi/osmapi-health-openapi.yml
class_count: 4
classes:
- name
- description
- url
- provider
context_file: json-ld/osmapi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/osmapi/refs/heads/main/json-ld/osmapi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Osmapi from osmAPI.
layout: jsonld
name: Osmapi Context
namespaces:
- prefix: osmapi
  uri: https://api.osmapi.com/v1/
properties:
- container: ''
  name: model
  type: reference
- container: ''
  name: chatCompletion
  type: reference
- container: ''
  name: message
  type: reference
- container: ''
  name: usage
  type: reference
- container: ''
  name: pricing
  type: reference
- container: ''
  name: metadata
  type: reference
property_count: 6
provider_name: osmAPI
provider_slug: osmapi
slug: osmapi-context
source_filename: osmapi-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"osmapi\": \"https://api.osmapi.com/v1/\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"provider\": \"schema:provider\",\n    \"model\": {\n      \"@id\": \"osmapi:Model\",\n      \"@type\": \"@id\"\n    },\n    \"chatCompletion\": {\n      \"@id\": \"osmapi:ChatCompletion\",\n      \"@type\": \"@id\"\n    },\n    \"message\": {\n      \"@id\": \"osmapi:Message\",\n      \"@type\": \"@id\"\n    },\n    \"usage\": {\n      \"@id\": \"osmapi:Usage\",\n      \"@type\": \"@id\"\n    },\n    \"pricing\": {\n      \"@id\": \"osmapi:Pricing\",\n      \"@type\": \"@id\"\n    },\n    \"metadata\": {\n      \"@id\": \"osmapi:Metadata\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/osmapi/refs/heads/main/json-ld/osmapi-context.jsonld
tags:
- AI
- Anthropic
- Gateway
- LLM
- OpenAI
- Routing
- JSON-LD
- Linked Data
- Semantic Web
---
