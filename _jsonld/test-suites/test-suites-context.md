---
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Postman Collections API
  slug: ''
  spec_type: OpenAPI
  url: https://www.postman.com/postman/postman-public-workspace/
class_count: 14
classes:
- id
- name
- description
- tags
- framework
- language
- suiteType
- executionTime
- status
- duration
- lines
- branches
- functions
- statements
context_file: json-ld/test-suites-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/test-suites/refs/heads/main/json-ld/test-suites-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Test Suites from Test Suites.
layout: jsonld
name: Test Suites Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: ts
  uri: https://raw.githubusercontent.com/api-evangelist/test-suites/main/vocabulary/test-suites-vocabulary.yml#
properties:
- container: ''
  name: TestSuite
  type: reference
- container: ''
  name: TestCase
  type: reference
- container: ''
  name: CoverageReport
  type: reference
- container: ''
  name: created
  type: date
- container: ''
  name: modified
  type: date
- container: set
  name: testCases
  type: ''
- container: set
  name: subSuites
  type: ''
- container: ''
  name: coverage
  type: reference
property_count: 8
provider_name: Test Suites
provider_slug: test-suites
slug: test-suites-context
source_filename: test-suites-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ts\": \"https://raw.githubusercontent.com/api-evangelist/test-suites/main/vocabulary/test-suites-vocabulary.yml#\",\n\n    \"TestSuite\": { \"@id\": \"ts:TestSuite\", \"@type\": \"@id\" },\n    \"TestCase\": { \"@id\": \"ts:TestCase\", \"@type\": \"@id\" },\n    \"CoverageReport\": { \"@id\": \"ts:CoverageReport\", \"@type\": \"@id\" },\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"created\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:date\" },\n    \"modified\": { \"@id\": \"schema:dateModified\", \"@type\": \"xsd:date\" },\n    \"tags\": \"schema:keywords\",\n\n    \"framework\": \"ts:framework\",\n    \"language\": \"schema:programmingLanguage\",\n    \"suiteType\": \"ts:suiteType\",\n    \"testCases\": { \"@id\": \"ts:testCases\", \"@container\": \"@set\"\
  \ },\n    \"subSuites\": { \"@id\": \"ts:subSuites\", \"@container\": \"@set\" },\n    \"coverage\": { \"@id\": \"ts:coverage\", \"@type\": \"@id\" },\n    \"executionTime\": \"ts:executionTime\",\n\n    \"status\": \"ts:executionStatus\",\n    \"duration\": \"ts:executionDuration\",\n\n    \"lines\": \"ts:lineCoverage\",\n    \"branches\": \"ts:branchCoverage\",\n    \"functions\": \"ts:functionCoverage\",\n    \"statements\": \"ts:statementCoverage\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/test-suites/refs/heads/main/json-ld/test-suites-context.jsonld
tags:
- API Testing
- Collections
- Quality Assurance
- Software Development
- Test Management
- Testing
- JSON-LD
- Linked Data
- Semantic Web
---
