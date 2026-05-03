---
class_count: 13
classes:
- id
- name
- description
- version
- tags
- format
- given
- expected
- priority
- specificationUrl
- statusCode
- method
- path
context_file: json-ld/test-specifications-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/test-specifications/refs/heads/main/json-ld/test-specifications-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Test Specifications from Test Specifications.
layout: jsonld
name: Test Specifications Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: ts
  uri: https://raw.githubusercontent.com/api-evangelist/test-specifications/main/vocabulary/test-specifications-vocabulary.yml#
properties:
- container: ''
  name: TestSpecification
  type: reference
- container: ''
  name: TestCase
  type: reference
- container: ''
  name: ConformanceLevel
  type: reference
- container: ''
  name: created
  type: date
- container: ''
  name: modified
  type: date
- container: ''
  name: scope
  type: reference
- container: set
  name: testCases
  type: ''
- container: set
  name: conformanceLevels
  type: ''
property_count: 8
provider_name: Test Specifications
provider_slug: test-specifications
slug: test-specifications-context
source_filename: test-specifications-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ts\": \"https://raw.githubusercontent.com/api-evangelist/test-specifications/main/vocabulary/test-specifications-vocabulary.yml#\",\n\n    \"TestSpecification\": {\n      \"@id\": \"ts:TestSpecification\",\n      \"@type\": \"@id\"\n    },\n    \"TestCase\": {\n      \"@id\": \"ts:TestCase\",\n      \"@type\": \"@id\"\n    },\n    \"ConformanceLevel\": {\n      \"@id\": \"ts:ConformanceLevel\",\n      \"@type\": \"@id\"\n    },\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"version\": \"schema:version\",\n    \"created\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:date\" },\n    \"modified\": { \"@id\": \"schema:dateModified\", \"@type\": \"xsd:date\" },\n    \"tags\": \"schema:keywords\",\n\n    \"scope\": { \"@id\": \"ts:scope\", \"@type\": \"@id\" },\n    \"\
  format\": \"ts:specificationFormat\",\n    \"testCases\": { \"@id\": \"ts:testCases\", \"@container\": \"@set\" },\n    \"conformanceLevels\": { \"@id\": \"ts:conformanceLevels\", \"@container\": \"@set\" },\n\n    \"given\": \"ts:given\",\n    \"expected\": \"ts:expected\",\n    \"priority\": \"ts:priority\",\n\n    \"specificationUrl\": \"schema:url\",\n    \"statusCode\": \"ts:httpStatusCode\",\n    \"method\": \"ts:httpMethod\",\n    \"path\": \"ts:apiPath\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/test-specifications/refs/heads/main/json-ld/test-specifications-context.jsonld
tags:
- Acceptance Testing
- Contract Testing
- Documentation
- OpenAPI
- Quality Assurance
- Testing
- JSON-LD
- Linked Data
- Semantic Web
---
