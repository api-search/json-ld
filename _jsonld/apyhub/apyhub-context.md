---
class_count: 12
classes:
- requestId
- type
- inputUrl
- outputFormat
- status
- outputUrl
- createdAt
- amount
- source
- target
- convertedAmount
- rate
context_file: json-ld/apyhub-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apyhub/refs/heads/main/json-ld/apyhub-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apyhub from ApyHub.
layout: jsonld
name: Apyhub Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: apyhub
  uri: https://apyhub.com/vocab#
properties: []
property_count: 0
provider_name: ApyHub
provider_slug: apyhub
slug: apyhub-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"apyhub\": \"https://apyhub.com/vocab#\",\n    \"requestId\": \"schema:identifier\",\n    \"type\": \"schema:category\",\n    \"inputUrl\": \"schema:url\",\n    \"outputFormat\": \"schema:encodingFormat\",\n    \"status\": \"apyhub:status\",\n    \"outputUrl\": \"schema:url\",\n    \"createdAt\": \"schema:dateCreated\",\n    \"amount\": \"schema:price\",\n    \"source\": \"schema:currency\",\n    \"target\": \"schema:currency\",\n    \"convertedAmount\": \"apyhub:convertedAmount\",\n    \"rate\": \"apyhub:exchangeRate\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apyhub/refs/heads/main/json-ld/apyhub-context.jsonld
tags:
- API Platform
- Data Processing
- Document Conversion
- Utility APIs
- JSON-LD
- Linked Data
- Semantic Web
---
