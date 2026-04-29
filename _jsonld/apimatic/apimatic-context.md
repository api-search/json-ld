---
api_specs:
- filename: apimatic-platform-api.yaml
  format: yaml
  label: APIMatic Platform API
  slug: apimatic-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apimatic/refs/heads/main/openapi/apimatic-platform-api.yaml
class_count: 9
classes:
- id
- type
- name
- description
- version
- platform
- errors
- warnings
- valid
context_file: json-ld/apimatic-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apimatic/refs/heads/main/json-ld/apimatic-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apimatic from APIMatic.
layout: jsonld
name: Apimatic Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: apimatic
  uri: https://www.apimatic.io/vocab/
properties:
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: downloadUrl
  type: reference
- container: ''
  name: expiresAt
  type: dateTime
property_count: 4
provider_name: APIMatic
provider_slug: apimatic
slug: apimatic-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"apimatic\": \"https://www.apimatic.io/vocab/\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"version\": \"schema:version\",\n    \"createdAt\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"dcterms:modified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"platform\": \"apimatic:platform\",\n    \"downloadUrl\": {\n      \"@id\": \"schema:downloadUrl\",\n      \"@type\": \"@id\"\n    },\n    \"expiresAt\": {\n      \"@id\": \"schema:expires\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"errors\": \"apimatic:errors\",\n    \"warnings\": \"apimatic:warnings\",\n    \"valid\": \"apimatic:valid\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apimatic/refs/heads/main/json-ld/apimatic-context.jsonld
tags:
- API Transformation
- Code Generation
- Developer Experience
- Documentation
- SDK Generation
- JSON-LD
- Linked Data
- Semantic Web
---
