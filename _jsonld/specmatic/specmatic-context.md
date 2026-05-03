---
class_count: 9
classes:
- name
- description
- url
- version
- dateCreated
- dateModified
- provider
- SoftwareApplication
- APIReference
context_file: json-ld/specmatic-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/specmatic/refs/heads/main/json-ld/specmatic-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Specmatic from Specmatic.
layout: jsonld
name: Specmatic Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: specmatic
  uri: https://specmatic.io/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Contract
  type: reference
- container: ''
  name: ContractTest
  type: reference
- container: ''
  name: Stub
  type: reference
- container: ''
  name: ApiCoverage
  type: reference
- container: ''
  name: specificationFormat
  type: '@vocab'
- container: ''
  name: protocol
  type: '@vocab'
- container: ''
  name: breakingChange
  type: boolean
- container: ''
  name: backwardCompatible
  type: boolean
- container: ''
  name: coveragePercent
  type: decimal
property_count: 9
provider_name: Specmatic
provider_slug: specmatic
slug: specmatic-context
source_filename: specmatic-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"specmatic\": \"https://specmatic.io/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Contract\": {\n      \"@id\": \"specmatic:Contract\",\n      \"@type\": \"@id\",\n      \"schema:description\": \"An API specification used as an executable agreement between API producer and consumer.\"\n    },\n    \"ContractTest\": {\n      \"@id\": \"specmatic:ContractTest\",\n      \"@type\": \"@id\",\n      \"schema:description\": \"A test that verifies a service implementation against its API contract.\"\n    },\n    \"Stub\": {\n      \"@id\": \"specmatic:Stub\",\n      \"@type\": \"@id\",\n      \"schema:description\": \"A simulated API endpoint returning specification-compliant responses.\"\n    },\n    \"ApiCoverage\": {\n      \"@id\": \"specmatic:ApiCoverage\",\n      \"@type\": \"@id\",\n      \"schema:description\": \"A metric measuring how much of an API specification\
  \ is exercised by tests.\"\n    },\n\n    \"specificationFormat\": {\n      \"@id\": \"specmatic:specificationFormat\",\n      \"@type\": \"@vocab\"\n    },\n    \"protocol\": {\n      \"@id\": \"specmatic:protocol\",\n      \"@type\": \"@vocab\"\n    },\n    \"breakingChange\": {\n      \"@id\": \"specmatic:breakingChange\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"backwardCompatible\": {\n      \"@id\": \"specmatic:backwardCompatible\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"coveragePercent\": {\n      \"@id\": \"specmatic:coveragePercent\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"version\": \"schema:version\",\n    \"dateCreated\": \"schema:dateCreated\",\n    \"dateModified\": \"schema:dateModified\",\n    \"provider\": \"schema:provider\",\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"APIReference\": \"schema:APIReference\"\
  \n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/specmatic/refs/heads/main/json-ld/specmatic-context.jsonld
tags:
- API Contract Testing
- API Governance
- API Mocking
- Backward Compatibility
- Contract-Driven Development
- Service Virtualization
- JSON-LD
- Linked Data
- Semantic Web
---
