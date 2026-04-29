---
api_specs:
- filename: apidog-apidog-openapi.yml
  format: yaml
  label: Apidog
  slug: apidog
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apidog/refs/heads/main/openapi/apidog-apidog-openapi.yml
class_count: 2
classes:
- name
- description
context_file: json-ld/apidog-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apidog/refs/heads/main/json-ld/apidog-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apidog from Apidog.
layout: jsonld
name: Apidog Context
namespaces:
- prefix: apidog
  uri: https://api.apidog.com/v1/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: projectId
  type: integer
- container: ''
  name: endpointCount
  type: integer
- container: ''
  name: schemaCount
  type: integer
- container: ''
  name: environmentCount
  type: integer
- container: ''
  name: apiVersion
  type: string
- container: ''
  name: success
  type: boolean
- container: ''
  name: errorCode
  type: string
- container: ''
  name: errorMessage
  type: string
- container: ''
  name: exportData
  type: string
property_count: 9
provider_name: Apidog
provider_slug: apidog
slug: apidog-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"apidog\": \"https://api.apidog.com/v1/\",\n    \"projectId\": {\n      \"@id\": \"apidog:projectId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"endpointCount\": {\n      \"@id\": \"apidog:endpointCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"schemaCount\": {\n      \"@id\": \"apidog:schemaCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"environmentCount\": {\n      \"@id\": \"apidog:environmentCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"apiVersion\": {\n      \"@id\": \"apidog:apiVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"success\": {\n      \"@id\": \"apidog:success\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"errorCode\": {\n      \"@id\": \"apidog:errorCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorMessage\": {\n      \"@id\": \"apidog:errorMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exportData\": {\n      \"\
  @id\": \"apidog:exportData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apidog/refs/heads/main/json-ld/apidog-context.jsonld
tags:
- API Design
- API Lifecycle
- API Testing
- Collaboration
- Design-First
- Documentation
- Mocking
- Platform
- JSON-LD
- Linked Data
- Semantic Web
---
