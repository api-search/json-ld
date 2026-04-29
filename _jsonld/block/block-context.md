---
class_count: 35
classes:
- id
- type
- Payment
- Order
- Customer
- CatalogObject
- Location
- Money
- status
- source_type
- amount_money
- total_money
- amount
- currency
- location_id
- created_at
- updated_at
- state
- version
- line_items
- given_name
- family_name
- email_address
- phone_number
- name
- description
- address
- timezone
- item_data
- variations
- price_money
- idempotency_key
- source_id
- cursor
- limit
context_file: json-ld/block-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/block/refs/heads/main/json-ld/block-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Block from Block.
layout: jsonld
name: Block Context
namespaces:
- prefix: block
  uri: https://developer.squareup.com/docs/
- prefix: schema
  uri: https://schema.org/
properties: []
property_count: 0
provider_name: Block
provider_slug: block
slug: block-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"block\": \"https://developer.squareup.com/docs/\",\n    \"schema\": \"https://schema.org/\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"Payment\": \"block:Payment\",\n    \"Order\": \"block:Order\",\n    \"Customer\": \"block:Customer\",\n    \"CatalogObject\": \"block:CatalogObject\",\n    \"Location\": \"block:Location\",\n    \"Money\": \"block:Money\",\n    \"status\": \"block:status\",\n    \"source_type\": \"block:sourceType\",\n    \"amount_money\": \"block:amountMoney\",\n    \"total_money\": \"block:totalMoney\",\n    \"amount\": \"block:amount\",\n    \"currency\": \"schema:currency\",\n    \"location_id\": \"block:locationId\",\n    \"created_at\": \"schema:dateCreated\",\n    \"updated_at\": \"schema:dateModified\",\n    \"state\": \"block:state\",\n    \"version\": \"block:version\",\n    \"line_items\": \"block:lineItems\",\n    \"given_name\": \"schema:givenName\",\n    \"family_name\": \"schema:familyName\"\
  ,\n    \"email_address\": \"schema:email\",\n    \"phone_number\": \"schema:telephone\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"address\": \"schema:address\",\n    \"timezone\": \"schema:eventSchedule\",\n    \"item_data\": \"block:itemData\",\n    \"variations\": \"block:variations\",\n    \"price_money\": \"block:priceMoney\",\n    \"idempotency_key\": \"block:idempotencyKey\",\n    \"source_id\": \"block:sourceId\",\n    \"cursor\": \"block:cursor\",\n    \"limit\": \"block:limit\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/block/refs/heads/main/json-ld/block-context.jsonld
tags:
- Commerce
- Cryptocurrency
- eCommerce
- Fintech
- Payments
- Point Of Sale
- Square
- JSON-LD
- Linked Data
- Semantic Web
---
