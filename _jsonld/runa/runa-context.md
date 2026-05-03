---
api_specs:
- filename: runa-payouts-api-openapi.yml
  format: yaml
  label: Runa Payouts API
  slug: runa-payouts-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/runa/refs/heads/main/openapi/runa-payouts-api-openapi.yml
class_count: 5
classes:
- Order
- Product
- Balance
- OrderItem
- id
context_file: json-ld/runa-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/runa/refs/heads/main/json-ld/runa-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Runa from Runa.
layout: jsonld
name: Runa Context
namespaces:
- prefix: runa
  uri: https://developer.runa.io/vocab/
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: name
  type: schema:Text
- container: ''
  name: description
  type: schema:Text
- container: ''
  name: status
  type: schema:Text
- container: ''
  name: created_at
  type: schema:DateTime
- container: ''
  name: completed_at
  type: schema:DateTime
- container: ''
  name: face_value
  type: schema:Number
- container: ''
  name: currency
  type: schema:Text
- container: ''
  name: balance
  type: schema:Text
- container: list
  name: categories
  type: ''
- container: list
  name: countries
  type: ''
- container: ''
  name: image_url
  type: reference
- container: ''
  name: payout
  type: ''
- container: ''
  name: url
  type: reference
- container: ''
  name: expires_at
  type: schema:DateTime
property_count: 14
provider_name: Runa
provider_slug: runa
slug: runa-context
source_filename: runa-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"runa\": \"https://developer.runa.io/vocab/\",\n    \"schema\": \"https://schema.org/\",\n\n    \"Order\": \"schema:Order\",\n    \"Product\": \"schema:Product\",\n    \"Balance\": \"runa:Balance\",\n    \"OrderItem\": \"schema:OrderItem\",\n\n    \"id\": \"@id\",\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"schema:Text\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"schema:Text\"\n    },\n    \"status\": {\n      \"@id\": \"runa:orderStatus\",\n      \"@type\": \"schema:Text\"\n    },\n    \"created_at\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"completed_at\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"face_value\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"schema:Number\"\n    },\n    \"currency\": {\n      \"@id\": \"schema:priceCurrency\"\
  ,\n      \"@type\": \"schema:Text\"\n    },\n    \"balance\": {\n      \"@id\": \"runa:accountBalance\",\n      \"@type\": \"schema:Text\"\n    },\n    \"categories\": {\n      \"@id\": \"schema:category\",\n      \"@container\": \"@list\"\n    },\n    \"countries\": {\n      \"@id\": \"schema:areaServed\",\n      \"@container\": \"@list\"\n    },\n    \"image_url\": {\n      \"@id\": \"schema:image\",\n      \"@type\": \"@id\"\n    },\n    \"payout\": {\n      \"@id\": \"runa:payout\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"expires_at\": {\n      \"@id\": \"schema:expires\",\n      \"@type\": \"schema:DateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/runa/refs/heads/main/json-ld/runa-context.jsonld
tags:
- Gift Cards
- Rewards
- Payments
- Incentives
- Payouts
- JSON-LD
- Linked Data
- Semantic Web
---
