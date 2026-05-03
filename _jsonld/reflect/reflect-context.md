---
api_specs:
- filename: reflect-openapi.yml
  format: yaml
  label: Reflect
  slug: reflect
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/reflect/refs/heads/main/openapi/reflect-openapi.yml
class_count: 6
classes:
- name
- description
- url
- SoftwareApplication
- Action
- SoftwareSourceCode
context_file: json-ld/reflect-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/reflect/refs/heads/main/json-ld/reflect-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Reflect from Reflect.
layout: jsonld
name: Reflect Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: reflect
  uri: https://reflect.run/vocabulary#
properties:
- container: ''
  name: Test
  type: ''
- container: ''
  name: testId
  type: integer
- container: ''
  name: Execution
  type: ''
- container: ''
  name: executionId
  type: integer
- container: ''
  name: executionStatus
  type: string
- container: ''
  name: tags
  type: ''
- container: ''
  name: TestOverrides
  type: ''
property_count: 7
provider_name: Reflect
provider_slug: reflect
slug: reflect-context
source_filename: reflect-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"reflect\": \"https://reflect.run/vocabulary#\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"Test\": {\n      \"@id\": \"reflect:Test\",\n      \"description\": \"An automated end-to-end test defined in the Reflect platform.\"\n    },\n    \"testId\": {\n      \"@id\": \"reflect:testId\",\n      \"@type\": \"xsd:integer\",\n      \"description\": \"Unique integer identifier for a Reflect test.\"\n    },\n    \"Execution\": {\n      \"@id\": \"reflect:Execution\",\n      \"description\": \"A single run of one or more Reflect tests.\"\n    },\n    \"executionId\": {\n      \"@id\": \"reflect:executionId\",\n      \"@type\": \"xsd:integer\",\n      \"description\": \"Unique integer identifier for a test\
  \ execution.\"\n    },\n    \"executionStatus\": {\n      \"@id\": \"reflect:executionStatus\",\n      \"@type\": \"xsd:string\",\n      \"description\": \"Status of a test execution: pending, running, passed, failed, or error.\"\n    },\n    \"tags\": {\n      \"@id\": \"schema:keywords\",\n      \"description\": \"List of tags for categorizing tests.\"\n    },\n    \"TestOverrides\": {\n      \"@id\": \"reflect:TestOverrides\",\n      \"description\": \"Runtime overrides applied to a test execution for hostnames, parameters, cookies, and headers.\"\n    },\n    \"Action\": \"schema:Action\",\n    \"SoftwareSourceCode\": \"schema:SoftwareSourceCode\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/reflect/refs/heads/main/json-ld/reflect-context.jsonld
tags:
- AI Testing
- Artificial Intelligence
- Automated Testing
- CI/CD
- End-to-End Testing
- QA
- Testing
- JSON-LD
- Linked Data
- Semantic Web
---
