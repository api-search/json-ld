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
class_count: 2
classes:
- Pod
- Subpod
context_file: json-ld/wolfram-alpha-full-results-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/wolfram-alpha/refs/heads/main/json-ld/wolfram-alpha-full-results-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Wolfram Alpha Full Results Api from Wolfram|Alpha.
layout: jsonld
name: Wolfram Alpha Full Results Api Context
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
  name: title
  type: string
- container: ''
  name: scanner
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: position
  type: integer
- container: ''
  name: primary
  type: boolean
- container: set
  name: subpods
  type: ''
- container: ''
  name: plaintext
  type: string
- container: ''
  name: img
  type: reference
- container: ''
  name: src
  type: reference
- container: ''
  name: alt
  type: string
- container: ''
  name: width
  type: integer
- container: ''
  name: height
  type: integer
property_count: 12
provider_name: Wolfram|Alpha
provider_slug: wolfram-alpha
slug: wolfram-alpha-full-results-api-context
source_filename: wolfram-alpha-full-results-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"wa\": \"https://wolfram-alpha.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Pod\": \"wa:Pod\",\n    \"title\": {\n      \"@id\": \"wa:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scanner\": {\n      \"@id\": \"wa:scanner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"wa:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"position\": {\n      \"@id\": \"wa:position\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"primary\": {\n      \"@id\": \"wa:primary\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"subpods\": {\n      \"@id\": \"wa:subpods\",\n      \"@container\": \"@set\"\n    },\n    \"Subpod\": \"wa:Subpod\",\n    \"plaintext\": {\n      \"@id\": \"wa:plaintext\",\n      \"@type\": \"xsd:string\"\n    },\n    \"img\": {\n      \"@id\": \"wa:img\",\n\
  \      \"@type\": \"@id\"\n    },\n    \"src\": {\n      \"@id\": \"wa:src\",\n      \"@type\": \"@id\"\n    },\n    \"alt\": {\n      \"@id\": \"wa:alt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"width\": {\n      \"@id\": \"wa:width\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"height\": {\n      \"@id\": \"wa:height\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/wolfram-alpha/refs/heads/main/json-ld/wolfram-alpha-full-results-api-context.jsonld
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
