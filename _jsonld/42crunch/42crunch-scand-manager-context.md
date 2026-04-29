---
api_specs:
- filename: 42crunch-scand-manager.yaml
  format: yaml
  label: 42Crunch API Conformance Scan Jobs Manager
  slug: 42crunch-scand-manager
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/42crunch/refs/heads/main/openapi/42crunch-scand-manager.yaml
class_count: 5
classes:
- Jobs
- JobSpec
- JobStatus
- Error
- name
context_file: json-ld/42crunch-scand-manager-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/42crunch/refs/heads/main/json-ld/42crunch-scand-manager-context.jsonld
description: JSON-LD context defining the semantic vocabulary for 42Crunch Scand Manager from 42Crunch.
layout: jsonld
name: 42Crunch Scand Manager Context
namespaces:
- prefix: 42c
  uri: https://42crunch.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: jobs
  type: string
- container: ''
  name: token
  type: string
- container: ''
  name: expirationTime
  type: integer
- container: ''
  name: platformService
  type: string
- container: ''
  name: scandImage
  type: string
- container: ''
  name: env
  type: reference
- container: ''
  name: status
  type: string
- container: ''
  name: error
  type: string
property_count: 8
provider_name: 42Crunch
provider_slug: 42crunch
slug: 42crunch-scand-manager-context
source_filename: 42crunch-scand-manager-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"42c\": \"https://42crunch.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Jobs\": \"42c:Jobs\",\n    \"JobSpec\": \"42c:JobSpec\",\n    \"JobStatus\": \"42c:JobStatus\",\n    \"Error\": \"42c:Error\",\n    \"jobs\": {\n      \"@id\": \"42c:jobs\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"token\": {\n      \"@id\": \"42c:token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"expirationTime\": {\n      \"@id\": \"42c:expirationTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"platformService\": {\n      \"@id\": \"42c:platformService\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scandImage\": {\n      \"@id\": \"42c:scandImage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"env\": {\n      \"@id\": \"42c:env\",\n      \"\
  @type\": \"@id\"\n    },\n    \"status\": {\n      \"@id\": \"42c:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"error\": {\n      \"@id\": \"42c:error\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/42crunch/refs/heads/main/json-ld/42crunch-scand-manager-context.jsonld
tags:
- API Security
- Platform
- Scanning
- Security
- OpenAPI
- DevSecOps
- JSON-LD
- Linked Data
- Semantic Web
---
