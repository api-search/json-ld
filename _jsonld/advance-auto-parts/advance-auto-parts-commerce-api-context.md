---
api_specs:
- filename: advance-auto-parts-catalog-api-openapi.yml
  format: yaml
  label: Advance Auto Parts Catalog API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/advance-auto-parts/refs/heads/main/openapi/advance-auto-parts-catalog-api-openapi.yml
- filename: advance-auto-parts-commerce-api-openapi.yml
  format: yaml
  label: Advance Auto Parts Commerce API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/advance-auto-parts/refs/heads/main/openapi/advance-auto-parts-commerce-api-openapi.yml
class_count: 30
classes:
- CartItem
- productId
- quantity
- CartItemInput
- Cart
- id
- items
- OrderInput
- cartId
- storeId
- fulfillmentType
- paymentMethodId
- Order
- status
- OrderList
- orders
- LoyaltyAccount
- accountId
- memberId
- pointsBalance
- tier
- LoyaltyTransaction
- type
- points
- description
- LoyaltyTransactionList
- transactions
- ErrorResponse
- code
- message
context_file: json-ld/advance-auto-parts-commerce-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/advance-auto-parts/refs/heads/main/json-ld/advance-auto-parts-commerce-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Advance Auto Parts Commerce Api from Advance Auto Parts.
layout: jsonld
name: Advance Auto Parts Commerce Api Context
namespaces:
- prefix: aap
  uri: https://api.advanceautoparts.com/commerce/v1/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: unitPrice
  type: decimal
- container: ''
  name: subtotal
  type: decimal
- container: ''
  name: total
  type: decimal
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: rewardValue
  type: decimal
- container: ''
  name: date
  type: dateTime
property_count: 6
provider_name: Advance Auto Parts
provider_slug: advance-auto-parts
slug: advance-auto-parts-commerce-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aap\": \"https://api.advanceautoparts.com/commerce/v1/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CartItem\": \"schema:OrderItem\",\n    \"productId\": \"aap:productId\",\n    \"quantity\": \"schema:orderQuantity\",\n    \"unitPrice\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"CartItemInput\": \"aap:CartItemInput\",\n    \"Cart\": \"schema:Order\",\n    \"id\": \"@id\",\n    \"items\": \"schema:orderedItem\",\n    \"subtotal\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"OrderInput\": \"aap:OrderInput\",\n    \"cartId\": \"aap:cartId\",\n    \"storeId\": \"aap:storeId\",\n    \"fulfillmentType\": \"aap:fulfillmentType\",\n    \"paymentMethodId\": \"aap:paymentMethodId\",\n    \"Order\": \"schema:Order\",\n    \"status\": \"schema:orderStatus\",\n    \"total\": {\n      \"@id\"\
  : \"schema:totalPrice\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:orderDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"OrderList\": \"aap:OrderList\",\n    \"orders\": \"aap:orders\",\n    \"LoyaltyAccount\": \"schema:LoyaltyProgram\",\n    \"accountId\": \"aap:accountId\",\n    \"memberId\": \"aap:memberId\",\n    \"pointsBalance\": \"aap:pointsBalance\",\n    \"tier\": \"aap:tier\",\n    \"rewardValue\": {\n      \"@id\": \"aap:rewardValue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"LoyaltyTransaction\": \"aap:LoyaltyTransaction\",\n    \"type\": \"@type\",\n    \"points\": \"aap:points\",\n    \"description\": \"schema:description\",\n    \"date\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"LoyaltyTransactionList\": \"aap:LoyaltyTransactionList\",\n    \"transactions\": \"aap:transactions\",\n    \"ErrorResponse\": \"aap:ErrorResponse\",\n    \"code\": \"aap:errorCode\"\
  ,\n    \"message\": \"schema:description\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/advance-auto-parts/refs/heads/main/json-ld/advance-auto-parts-commerce-api-context.jsonld
tags:
- Automotive
- E-Commerce
- Parts Catalog
- Retail
- Supply Chain
- JSON-LD
- Linked Data
- Semantic Web
---
