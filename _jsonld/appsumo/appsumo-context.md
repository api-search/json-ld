---
api_specs:
- filename: appsumo-licensing-openapi.yaml
  format: yaml
  label: AppSumo Licensing API
  slug: appsumo-licensing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/appsumo/refs/heads/main/openapi/appsumo-licensing-openapi.yaml
class_count: 10
classes:
- licenseKey
- productSlug
- status
- tier
- activatedAt
- userId
- email
- partnerId
- productName
- webhookUrl
context_file: json-ld/appsumo-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/appsumo/refs/heads/main/json-ld/appsumo-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Appsumo from AppSumo.
layout: jsonld
name: Appsumo Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: appsumo
  uri: https://appsumo.com/vocab#
properties: []
property_count: 0
provider_name: AppSumo
provider_slug: appsumo
slug: appsumo-context
source_filename: appsumo-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"appsumo\": \"https://appsumo.com/vocab#\",\n    \"licenseKey\": \"appsumo:licenseKey\",\n    \"productSlug\": \"appsumo:productSlug\",\n    \"status\": \"appsumo:status\",\n    \"tier\": \"appsumo:tier\",\n    \"activatedAt\": \"schema:dateCreated\",\n    \"userId\": \"schema:identifier\",\n    \"email\": \"schema:email\",\n    \"partnerId\": \"schema:identifier\",\n    \"productName\": \"schema:name\",\n    \"webhookUrl\": \"appsumo:webhookUrl\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/appsumo/refs/heads/main/json-ld/appsumo-context.jsonld
tags:
- Marketplace
- SaaS
- Software Deals
- JSON-LD
- Linked Data
- Semantic Web
---
