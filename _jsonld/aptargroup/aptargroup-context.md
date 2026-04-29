---
api_specs:
- filename: aptargroup-openapi.yaml
  format: yaml
  label: AptarGroup API
  slug: aptargroup-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aptargroup/refs/heads/main/openapi/aptargroup-openapi.yaml
class_count: 10
classes:
- productId
- name
- category
- market
- description
- material
- sustainable
- sku
- orderId
- status
context_file: json-ld/aptargroup-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aptargroup/refs/heads/main/json-ld/aptargroup-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aptargroup from AptarGroup.
layout: jsonld
name: Aptargroup Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: aptar
  uri: https://www.aptargroup.com/vocab#
properties: []
property_count: 0
provider_name: AptarGroup
provider_slug: aptargroup
slug: aptargroup-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"aptar\": \"https://www.aptargroup.com/vocab#\",\n    \"productId\": \"schema:identifier\",\n    \"name\": \"schema:name\",\n    \"category\": \"schema:category\",\n    \"market\": \"schema:audience\",\n    \"description\": \"schema:description\",\n    \"material\": \"schema:material\",\n    \"sustainable\": \"aptar:sustainable\",\n    \"sku\": \"schema:sku\",\n    \"orderId\": \"schema:identifier\",\n    \"status\": \"aptar:status\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aptargroup/refs/heads/main/json-ld/aptargroup-context.jsonld
tags:
- Packaging
- Dispensing
- Manufacturing
- Sustainability
- Consumer Goods
- JSON-LD
- Linked Data
- Semantic Web
---
