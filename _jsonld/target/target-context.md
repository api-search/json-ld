---
api_specs:
- filename: target-target-api-openapi.yml
  format: yaml
  label: Target API
  slug: target-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/target/refs/heads/main/openapi/target-target-api-openapi.yml
class_count: 32
classes:
- tcin
- dpci
- storeId
- fulfillment
- driveUp
- inStorePickup
- shipToHome
- sameDayDelivery
- Product
- name
- description
- brand
- image
- offers
- price
- priceCurrency
- availability
- Store
- address
- telephone
- openingHours
- geo
- latitude
- longitude
- Order
- orderId
- orderStatus
- orderDate
- orderedItem
- Rating
- ratingValue
- reviewCount
context_file: json-ld/target-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/target/refs/heads/main/json-ld/target-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Target from target.
layout: jsonld
name: Target Context
namespaces:
- prefix: target
  uri: https://developer.target.com/vocab/
properties: []
property_count: 0
provider_name: target
provider_slug: target
slug: target-context
source_filename: target-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"target\": \"https://developer.target.com/vocab/\",\n    \"tcin\": \"target:tcin\",\n    \"dpci\": \"target:dpci\",\n    \"storeId\": \"target:storeId\",\n    \"fulfillment\": \"target:fulfillment\",\n    \"driveUp\": \"target:driveUp\",\n    \"inStorePickup\": \"target:inStorePickup\",\n    \"shipToHome\": \"target:shipToHome\",\n    \"sameDayDelivery\": \"target:sameDayDelivery\",\n    \"Product\": \"schema:Product\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"brand\": \"schema:brand\",\n    \"image\": \"schema:image\",\n    \"offers\": \"schema:offers\",\n    \"price\": \"schema:price\",\n    \"priceCurrency\": \"schema:priceCurrency\",\n    \"availability\": \"schema:availability\",\n    \"Store\": \"schema:Store\",\n    \"address\": \"schema:address\",\n    \"telephone\": \"schema:telephone\",\n    \"openingHours\": \"schema:openingHours\",\n    \"geo\": \"schema:geo\"\
  ,\n    \"latitude\": \"schema:latitude\",\n    \"longitude\": \"schema:longitude\",\n    \"Order\": \"schema:Order\",\n    \"orderId\": \"schema:orderNumber\",\n    \"orderStatus\": \"schema:orderStatus\",\n    \"orderDate\": \"schema:orderDate\",\n    \"orderedItem\": \"schema:orderedItem\",\n    \"Rating\": \"schema:AggregateRating\",\n    \"ratingValue\": \"schema:ratingValue\",\n    \"reviewCount\": \"schema:reviewCount\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/target/refs/heads/main/json-ld/target-context.jsonld
tags:
- E-Commerce
- Retail
- Products
- Inventory
- Fortune 100
- Stores
- Orders
- JSON-LD
- Linked Data
- Semantic Web
---
