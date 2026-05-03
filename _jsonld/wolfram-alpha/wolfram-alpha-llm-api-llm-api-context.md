---
api_specs:
- filename: wolfram-alpha-llm-api-openapi.yml
  format: yaml
  label: Wolfram|Alpha LLM API
  slug: llm-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wolfram-alpha/refs/heads/main/openapi/wolfram-alpha-llm-api-openapi.yml
- filename: wolfram-alpha-full-results-api-openapi.yml
  format: yaml
  label: Wolfram|Alpha Full Results API
  slug: full-results-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wolfram-alpha/refs/heads/main/openapi/wolfram-alpha-full-results-api-openapi.yml
- filename: wolfram-alpha-short-answers-api-openapi.yml
  format: yaml
  label: Wolfram|Alpha Short Answers API
  slug: short-answers-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wolfram-alpha/refs/heads/main/openapi/wolfram-alpha-short-answers-api-openapi.yml
- filename: wolfram-alpha-simple-api-openapi.yml
  format: yaml
  label: Wolfram|Alpha Simple API
  slug: simple-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wolfram-alpha/refs/heads/main/openapi/wolfram-alpha-simple-api-openapi.yml
- filename: wolfram-alpha-spoken-results-api-openapi.yml
  format: yaml
  label: Wolfram|Alpha Spoken Results API
  slug: spoken-results-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wolfram-alpha/refs/heads/main/openapi/wolfram-alpha-spoken-results-api-openapi.yml
class_count: 1
classes:
- LlmApiResponse
context_file: json-ld/wolfram-alpha-llm-api-llm-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/wolfram-alpha/refs/heads/main/json-ld/wolfram-alpha-llm-api-llm-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Wolfram Alpha Llm Api Llm Api from Wolfram|Alpha.
layout: jsonld
name: Wolfram Alpha Llm Api Llm Api Context
namespaces:
- prefix: wa
  uri: https://wolfram-alpha.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: query
  type: string
- container: ''
  name: inputInterpretation
  type: string
- container: ''
  name: result
  type: string
- container: set
  name: images
  type: ''
- container: ''
  name: link
  type: reference
property_count: 5
provider_name: Wolfram|Alpha
provider_slug: wolfram-alpha
slug: wolfram-alpha-llm-api-llm-api-context
source_filename: wolfram-alpha-llm-api-llm-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"wa\": \"https://wolfram-alpha.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"LlmApiResponse\": \"wa:LlmApiResponse\",\n    \"query\": {\n      \"@id\": \"wa:query\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inputInterpretation\": {\n      \"@id\": \"wa:inputInterpretation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"result\": {\n      \"@id\": \"wa:result\",\n      \"@type\": \"xsd:string\"\n    },\n    \"images\": {\n      \"@id\": \"wa:images\",\n      \"@container\": \"@set\"\n    },\n    \"link\": {\n      \"@id\": \"wa:link\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/wolfram-alpha/refs/heads/main/json-ld/wolfram-alpha-llm-api-llm-api-context.jsonld
tags:
- AI
- Artificial Intelligence
- Computational Knowledge
- Natural Language Processing
- Search
- JSON-LD
- Linked Data
- Semantic Web
---
