---
api_specs:
- filename: apinizer-api.yaml
  format: yaml
  label: Apinizer API
  slug: apinizer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apinizer/refs/heads/main/openapi/apinizer-api.yaml
class_count: 10
classes:
- id
- type
- name
- description
- status
- configuration
- policies
- endpoints
- totalRequests
- averageLatency
context_file: json-ld/apinizer-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apinizer/refs/heads/main/json-ld/apinizer-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apinizer from Apinizer.
layout: jsonld
name: Apinizer Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: apinizer
  uri: https://apinizer.com/vocab/
properties:
- container: ''
  name: baseUrl
  type: reference
- container: ''
  name: createdAt
  type: dateTime
property_count: 2
provider_name: Apinizer
provider_slug: apinizer
slug: apinizer-context
source_filename: apinizer-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"apinizer\": \"https://apinizer.com/vocab/\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"baseUrl\": { \"@id\": \"schema:url\", \"@type\": \"@id\" },\n    \"status\": \"apinizer:status\",\n    \"createdAt\": { \"@id\": \"dcterms:created\", \"@type\": \"xsd:dateTime\" },\n    \"configuration\": \"apinizer:configuration\",\n    \"policies\": \"apinizer:policies\",\n    \"endpoints\": \"apinizer:endpoints\",\n    \"totalRequests\": \"apinizer:totalRequests\",\n    \"averageLatency\": \"apinizer:averageLatency\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apinizer/refs/heads/main/json-ld/apinizer-context.jsonld
tags:
- API Gateway
- API Management
- API Monitoring
- API Security
- Policies
- JSON-LD
- Linked Data
- Semantic Web
---
