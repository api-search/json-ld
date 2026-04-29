---
api_specs:
- filename: apipark-api.yaml
  format: yaml
  label: APIPark API
  slug: apipark-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apipark/refs/heads/main/openapi/apipark-api.yaml
class_count: 13
classes:
- id
- type
- name
- description
- teamId
- status
- tags
- provider
- modelName
- priority
- memberCount
- serviceId
- apiKey
context_file: json-ld/apipark-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apipark/refs/heads/main/json-ld/apipark-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apipark from APIPark.
layout: jsonld
name: Apipark Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: apipark
  uri: https://apipark.com/vocab/
properties:
- container: ''
  name: createdAt
  type: dateTime
property_count: 1
provider_name: APIPark
provider_slug: apipark
slug: apipark-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"apipark\": \"https://apipark.com/vocab/\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"teamId\": \"apipark:teamId\",\n    \"status\": \"apipark:status\",\n    \"tags\": \"schema:keywords\",\n    \"createdAt\": { \"@id\": \"dcterms:created\", \"@type\": \"xsd:dateTime\" },\n    \"provider\": \"schema:provider\",\n    \"modelName\": \"apipark:modelName\",\n    \"priority\": \"apipark:priority\",\n    \"memberCount\": \"apipark:memberCount\",\n    \"serviceId\": \"apipark:serviceId\",\n    \"apiKey\": \"apipark:apiKey\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apipark/refs/heads/main/json-ld/apipark-context.jsonld
tags:
- AI Gateway
- API Gateway
- API Management
- Developer Portal
- LLM
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
