---
api_specs:
- filename: tillo-gift-card-openapi.yml
  format: yaml
  label: Tillo Gift Card API
  slug: tillo-gift-card-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tillo/refs/heads/main/openapi/tillo-gift-card-openapi.yml
- filename: tillo-gift-card-openapi.yml
  format: yaml
  label: Tillo Float Management API
  slug: tillo-float-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tillo/refs/heads/main/openapi/tillo-gift-card-openapi.yml
class_count: 15
classes:
- identifier
- brand_identifier
- face_value
- currency
- redemption_url
- expiry_date
- client_request_id
- tillo_order_id
- float_balance
- async_only
- transaction_types
- TilloBrand
- TilloGiftCard
- TilloOrder
- TilloFloat
context_file: json-ld/tillo-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tillo/refs/heads/main/json-ld/tillo-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tillo from Tillo.
layout: jsonld
name: Tillo Context
namespaces:
- prefix: tillo
  uri: https://www.tillo.io/vocab/
properties: []
property_count: 0
provider_name: Tillo
provider_slug: tillo
slug: tillo-context
source_filename: tillo-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"tillo\": \"https://www.tillo.io/vocab/\",\n    \"identifier\": \"identifier\",\n    \"brand_identifier\": \"tillo:brandIdentifier\",\n    \"face_value\": \"price\",\n    \"currency\": \"priceCurrency\",\n    \"redemption_url\": \"url\",\n    \"expiry_date\": \"expires\",\n    \"client_request_id\": \"tillo:clientRequestId\",\n    \"tillo_order_id\": \"tillo:tilloOrderId\",\n    \"float_balance\": \"tillo:floatBalance\",\n    \"async_only\": \"tillo:asyncOnly\",\n    \"transaction_types\": \"tillo:transactionTypes\",\n    \"TilloBrand\": \"Brand\",\n    \"TilloGiftCard\": \"tillo:GiftCard\",\n    \"TilloOrder\": \"Order\",\n    \"TilloFloat\": \"tillo:FloatAccount\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tillo/refs/heads/main/json-ld/tillo-context.jsonld
tags:
- Finance
- Gift Cards
- Payments
- Rewards
- Incentives
- JSON-LD
- Linked Data
- Semantic Web
---
