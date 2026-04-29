---
api_specs:
- filename: bjs-wholesale-club-openapi.yaml
  format: yaml
  label: BJ's Wholesale Club API
  slug: bjs-wholesale-club
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bjs-wholesale-club/refs/heads/main/openapi/bjs-wholesale-club-openapi.yaml
class_count: 5
classes:
- productId
- membershipNumber
- tier
- clubId
- fulfillmentMethod
context_file: json-ld/bjs-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/bjs-wholesale-club/refs/heads/main/json-ld/bjs-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Bjs from BJ's Wholesale Club.
layout: jsonld
name: Bjs Context
namespaces:
- prefix: bjs
  uri: https://www.bjs.com/ontology/
- prefix: inStock
  uri: https://schema.org/availability
- prefix: price
  uri: https://schema.org/price
- prefix: regularPrice
  uri: https://schema.org/highPrice
- prefix: brand
  uri: https://schema.org/brand
- prefix: category
  uri: https://schema.org/category
- prefix: orderId
  uri: https://schema.org/orderNumber
- prefix: status
  uri: https://schema.org/orderStatus
- prefix: estimatedDelivery
  uri: https://schema.org/expectedArrivalUntil
properties: []
property_count: 0
provider_name: BJ's Wholesale Club
provider_slug: bjs-wholesale-club
slug: bjs-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"bjs\": \"https://www.bjs.com/ontology/\",\n    \"productId\": \"identifier\",\n    \"membershipNumber\": \"bjs:membershipNumber\",\n    \"tier\": \"bjs:membershipTier\",\n    \"inStock\": \"https://schema.org/availability\",\n    \"price\": \"https://schema.org/price\",\n    \"regularPrice\": \"https://schema.org/highPrice\",\n    \"brand\": \"https://schema.org/brand\",\n    \"category\": \"https://schema.org/category\",\n    \"orderId\": \"https://schema.org/orderNumber\",\n    \"status\": \"https://schema.org/orderStatus\",\n    \"estimatedDelivery\": \"https://schema.org/expectedArrivalUntil\",\n    \"clubId\": \"bjs:clubId\",\n    \"fulfillmentMethod\": \"bjs:fulfillmentMethod\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/bjs-wholesale-club/refs/heads/main/json-ld/bjs-context.jsonld
tags:
- Ecommerce
- Membership
- Retail
- Wholesale
- JSON-LD
- Linked Data
- Semantic Web
---
