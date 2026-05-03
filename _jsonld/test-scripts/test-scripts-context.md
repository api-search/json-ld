---
api_specs:
- filename: 72a32ca1-f3a2-4a5e-91f2-token
  format: yaml
  label: Postman API
  slug: ''
  spec_type: OpenAPI
  url: https://www.postman.com/postman/postman-public-workspace/api/72a32ca1-f3a2-4a5e-91f2-token
- filename: openapi.yaml
  format: yaml
  label: k6 Performance Testing
  slug: ''
  spec_type: OpenAPI
  url: https://grafana.com/docs/k6/latest/misc/k6-rest-api/
class_count: 22
classes:
- id
- name
- description
- tags
- framework
- language
- environment
- url
- method
- path
- operationId
- platform
- workflow
- trigger
- UnitTest
- IntegrationTest
- EndToEndTest
- ContractTest
- PerformanceTest
- SecurityTest
- SmokeTest
- RegressionTest
context_file: json-ld/test-scripts-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/test-scripts/refs/heads/main/json-ld/test-scripts-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Test Scripts from Test Scripts.
layout: jsonld
name: Test Scripts Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: ts
  uri: https://raw.githubusercontent.com/api-evangelist/test-scripts/main/vocabulary/test-scripts-vocabulary.yml#
properties:
- container: ''
  name: TestScript
  type: reference
- container: ''
  name: Assertion
  type: reference
- container: ''
  name: TestTarget
  type: reference
- container: ''
  name: created
  type: date
- container: ''
  name: modified
  type: date
- container: ''
  name: type
  type: reference
- container: ''
  name: target
  type: reference
- container: set
  name: assertions
  type: ''
- container: ''
  name: ci
  type: reference
property_count: 9
provider_name: Test Scripts
provider_slug: test-scripts
slug: test-scripts-context
source_filename: test-scripts-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ts\": \"https://raw.githubusercontent.com/api-evangelist/test-scripts/main/vocabulary/test-scripts-vocabulary.yml#\",\n\n    \"TestScript\": {\n      \"@id\": \"ts:TestScript\",\n      \"@type\": \"@id\"\n    },\n    \"Assertion\": {\n      \"@id\": \"ts:Assertion\",\n      \"@type\": \"@id\"\n    },\n    \"TestTarget\": {\n      \"@id\": \"ts:TestTarget\",\n      \"@type\": \"@id\"\n    },\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"created\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:date\"\n    },\n    \"modified\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:date\"\n    },\n    \"tags\": \"schema:keywords\",\n\n    \"type\": {\n      \"@id\": \"ts:testType\",\n      \"@type\": \"@id\"\n    },\n    \"framework\": \"\
  ts:framework\",\n    \"language\": \"schema:programmingLanguage\",\n    \"target\": {\n      \"@id\": \"ts:target\",\n      \"@type\": \"@id\"\n    },\n    \"assertions\": {\n      \"@id\": \"ts:assertions\",\n      \"@container\": \"@set\"\n    },\n    \"environment\": \"ts:environment\",\n    \"ci\": {\n      \"@id\": \"ts:ciIntegration\",\n      \"@type\": \"@id\"\n    },\n\n    \"url\": \"schema:url\",\n    \"method\": \"ts:httpMethod\",\n    \"path\": \"ts:apiPath\",\n    \"operationId\": \"ts:operationId\",\n\n    \"platform\": \"ts:ciPlatform\",\n    \"workflow\": \"ts:ciWorkflow\",\n    \"trigger\": \"ts:ciTrigger\",\n\n    \"UnitTest\": \"ts:UnitTest\",\n    \"IntegrationTest\": \"ts:IntegrationTest\",\n    \"EndToEndTest\": \"ts:EndToEndTest\",\n    \"ContractTest\": \"ts:ContractTest\",\n    \"PerformanceTest\": \"ts:PerformanceTest\",\n    \"SecurityTest\": \"ts:SecurityTest\",\n    \"SmokeTest\": \"ts:SmokeTest\",\n    \"RegressionTest\": \"ts:RegressionTest\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/test-scripts/refs/heads/main/json-ld/test-scripts-context.jsonld
tags:
- Automation
- CI/CD
- Contract Testing
- Quality Assurance
- Software Development
- Testing
- JSON-LD
- Linked Data
- Semantic Web
---
