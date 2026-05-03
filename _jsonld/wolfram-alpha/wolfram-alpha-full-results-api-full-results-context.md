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
- FullResultsResponse
context_file: json-ld/wolfram-alpha-full-results-api-full-results-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/wolfram-alpha/refs/heads/main/json-ld/wolfram-alpha-full-results-api-full-results-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Wolfram Alpha Full Results Api Full Results from Wolfram|Alpha.
layout: jsonld
name: Wolfram Alpha Full Results Api Full Results Context
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
  name: queryresult
  type: reference
- container: ''
  name: success
  type: boolean
- container: ''
  name: error
  type: boolean
- container: ''
  name: numpods
  type: integer
- container: ''
  name: datatypes
  type: string
- container: ''
  name: timing
  type: decimal
- container: set
  name: pods
  type: string
property_count: 7
provider_name: Wolfram|Alpha
provider_slug: wolfram-alpha
slug: wolfram-alpha-full-results-api-full-results-context
source_filename: wolfram-alpha-full-results-api-full-results-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"wa\": \"https://wolfram-alpha.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"FullResultsResponse\": \"wa:FullResultsResponse\",\n    \"queryresult\": {\n      \"@id\": \"wa:queryresult\",\n      \"@type\": \"@id\"\n    },\n    \"success\": {\n      \"@id\": \"wa:success\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"error\": {\n      \"@id\": \"wa:error\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"numpods\": {\n      \"@id\": \"wa:numpods\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"datatypes\": {\n      \"@id\": \"wa:datatypes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timing\": {\n      \"@id\": \"wa:timing\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"pods\": {\n      \"@id\": \"wa:pods\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/wolfram-alpha/refs/heads/main/json-ld/wolfram-alpha-full-results-api-full-results-context.jsonld
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
