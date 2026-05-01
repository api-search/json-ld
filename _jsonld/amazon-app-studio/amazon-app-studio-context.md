---
api_specs:
- filename: amazon-app-studio-openapi.yaml
  format: yaml
  label: Amazon App Studio API
  slug: app-studio-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-app-studio/refs/heads/main/openapi/amazon-app-studio-openapi.yaml
class_count: 0
classes: []
context_file: json-ld/amazon-app-studio-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-app-studio/refs/heads/main/json-ld/amazon-app-studio-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon App Studio from Amazon App Studio.
layout: jsonld
name: Amazon App Studio Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: appId
  type: ''
- container: ''
  name: name
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: status
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
property_count: 6
provider_name: Amazon App Studio
provider_slug: amazon-app-studio
slug: amazon-app-studio-context
source_filename: amazon-app-studio-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"appId\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"status\": {\n      \"@id\": \"schema:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-app-studio/refs/heads/main/json-ld/amazon-app-studio-context.jsonld
tags:
- Generative AI
- Internal Tools
- Low-Code
- No-Code
- JSON-LD
- Linked Data
- Semantic Web
---
