---
api_specs:
- filename: openapi.yml
  format: yaml
  label: APIs.io Search API
  slug: apis-io-search-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/demo-openapi/refs/heads/main/openapi/openapi.yml
class_count: 2
classes:
- API
- Search
context_file: json-ld/demo-openapi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/demo-openapi/refs/heads/main/json-ld/demo-openapi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Demo Openapi from Manage OpenAPI via GitHub Demo.
layout: jsonld
name: Demo Openapi Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: apisio
  uri: https://apis.io/vocab/
properties:
- container: ''
  name: id
  type: ''
- container: ''
  name: name
  type: schema:Text
- container: ''
  name: description
  type: schema:Text
- container: ''
  name: url
  type: schema:URL
- container: ''
  name: humanURL
  type: schema:URL
- container: ''
  name: baseURL
  type: schema:URL
- container: ''
  name: tags
  type: schema:Text
property_count: 7
provider_name: Manage OpenAPI via GitHub Demo
provider_slug: demo-openapi
slug: demo-openapi-context
source_filename: demo-openapi-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://apis.io/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"apisio\": \"https://apis.io/vocab/\",\n    \"API\": \"schema:WebAPI\",\n    \"Search\": \"schema:SearchAction\",\n    \"id\": {\"@id\": \"schema:identifier\"},\n    \"name\": {\"@id\": \"schema:name\", \"@type\": \"schema:Text\"},\n    \"description\": {\"@id\": \"schema:description\", \"@type\": \"schema:Text\"},\n    \"url\": {\"@id\": \"schema:url\", \"@type\": \"schema:URL\"},\n    \"humanURL\": {\"@id\": \"apisio:humanURL\", \"@type\": \"schema:URL\"},\n    \"baseURL\": {\"@id\": \"apisio:baseURL\", \"@type\": \"schema:URL\"},\n    \"tags\": {\"@id\": \"schema:keywords\", \"@type\": \"schema:Text\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/demo-openapi/refs/heads/main/json-ld/demo-openapi-context.jsonld
tags:
- APIs.json
- Demo
- GitHub
- OpenAPI
- Reference
- Search
- JSON-LD
- Linked Data
- Semantic Web
---
