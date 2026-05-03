---
api_specs:
- filename: sysco-food-distribution-api-openapi.yml
  format: yaml
  label: Sysco Food Distribution API
  slug: food-distribution-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sysco/refs/heads/main/openapi/sysco-food-distribution-api-openapi.yml
class_count: 24
classes:
- Product
- Order
- Delivery
- Account
- ProductPrice
- productId
- gtin
- brand
- category
- packCount
- size
- unitOfMeasure
- storageType
- inStock
- orderId
- deliveryId
- trackingNumber
- contractPrice
- listPrice
- currency
- accountId
- name
- email
- description
context_file: json-ld/sysco-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sysco/refs/heads/main/json-ld/sysco-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sysco from Sysco.
layout: jsonld
name: Sysco Context
namespaces:
- prefix: sysco
  uri: https://api.sysco.com/vocab/
properties:
- container: ''
  name: nextReceiveDate
  type: schema:Date
- container: ''
  name: deliveryDate
  type: schema:Date
- container: ''
  name: estimatedArrival
  type: schema:DateTime
- container: ''
  name: createdAt
  type: schema:DateTime
property_count: 4
provider_name: Sysco
provider_slug: sysco
slug: sysco-context
source_filename: sysco-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"sysco\": \"https://api.sysco.com/vocab/\",\n    \"Product\": \"schema:Product\",\n    \"Order\": \"schema:Order\",\n    \"Delivery\": \"sysco:Delivery\",\n    \"Account\": \"schema:Organization\",\n    \"ProductPrice\": \"schema:Offer\",\n    \"productId\": \"sysco:supc\",\n    \"gtin\": \"schema:gtin\",\n    \"brand\": \"schema:brand\",\n    \"category\": \"schema:category\",\n    \"packCount\": \"sysco:packCount\",\n    \"size\": \"schema:size\",\n    \"unitOfMeasure\": \"sysco:unitOfMeasure\",\n    \"storageType\": \"sysco:storageType\",\n    \"inStock\": \"schema:availability\",\n    \"nextReceiveDate\": {\n      \"@id\": \"sysco:nextReceiveDate\",\n      \"@type\": \"schema:Date\"\n    },\n    \"orderId\": \"schema:orderNumber\",\n    \"deliveryDate\": {\n      \"@id\": \"sysco:deliveryDate\",\n      \"@type\": \"schema:Date\"\n    },\n    \"deliveryId\": \"sysco:deliveryId\",\n    \"trackingNumber\"\
  : \"sysco:trackingNumber\",\n    \"estimatedArrival\": {\n      \"@id\": \"sysco:estimatedArrival\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"contractPrice\": \"schema:price\",\n    \"listPrice\": \"schema:highPrice\",\n    \"currency\": \"schema:priceCurrency\",\n    \"accountId\": \"sysco:accountId\",\n    \"name\": \"schema:name\",\n    \"email\": \"schema:email\",\n    \"description\": \"schema:description\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"schema:DateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sysco/refs/heads/main/json-ld/sysco-context.jsonld
tags:
- Food Distribution
- Food Service
- Supply Chain
- Fortune 100
- Wholesale
- JSON-LD
- Linked Data
- Semantic Web
---
