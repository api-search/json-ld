---
class_count: 13
classes:
- productId
- partNumber
- name
- description
- category
- manufacturer
- price
- inStock
- leadTimeDays
- orderId
- status
- totalAmount
- createdAt
context_file: json-ld/applied-industrial-technologies-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/applied-industrial-technologies/refs/heads/main/json-ld/applied-industrial-technologies-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Applied Industrial Technologies from Applied Industrial Technologies.
layout: jsonld
name: Applied Industrial Technologies Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: ait
  uri: https://www.applied-industrial-technologies.com/vocab#
properties: []
property_count: 0
provider_name: Applied Industrial Technologies
provider_slug: applied-industrial-technologies
slug: applied-industrial-technologies-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"ait\": \"https://www.applied-industrial-technologies.com/vocab#\",\n    \"productId\": \"schema:identifier\",\n    \"partNumber\": \"schema:gtin\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"category\": \"schema:category\",\n    \"manufacturer\": \"schema:manufacturer\",\n    \"price\": \"schema:price\",\n    \"inStock\": \"schema:availability\",\n    \"leadTimeDays\": \"ait:leadTimeDays\",\n    \"orderId\": \"schema:identifier\",\n    \"status\": \"schema:orderStatus\",\n    \"totalAmount\": \"schema:totalPrice\",\n    \"createdAt\": \"schema:orderDate\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/applied-industrial-technologies/refs/heads/main/json-ld/applied-industrial-technologies-context.jsonld
tags:
- Industrial Distribution
- Bearings
- Power Transmission
- Fluid Power
- Supply Chain
- JSON-LD
- Linked Data
- Semantic Web
---
