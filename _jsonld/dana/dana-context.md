---
api_specs:
- filename: dana-aftermarket-api-openapi.yml
  format: yaml
  label: Dana Aftermarket API
  slug: aftermarket-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dana/refs/heads/main/openapi/dana-aftermarket-api-openapi.yml
class_count: 2
classes:
- Part
- Order
context_file: json-ld/dana-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dana/refs/heads/main/json-ld/dana-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dana from Dana.
layout: jsonld
name: Dana Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: dana
  uri: https://schema.danaaftermarket.com/
properties:
- container: ''
  name: partNumber
  type: schema:Text
- container: ''
  name: description
  type: schema:Text
- container: ''
  name: brand
  type: schema:Brand
- container: ''
  name: category
  type: schema:Text
- container: ''
  name: make
  type: schema:Text
- container: ''
  name: model
  type: schema:Text
- container: ''
  name: year
  type: schema:Text
- container: ''
  name: orderId
  type: schema:Text
- container: ''
  name: status
  type: schema:Text
- container: ''
  name: items
  type: ''
- container: ''
  name: trackingNumber
  type: schema:Text
- container: ''
  name: quantity
  type: schema:Integer
- container: ''
  name: shippingAddress
  type: ''
property_count: 13
provider_name: Dana
provider_slug: dana
slug: dana-context
source_filename: dana-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.danaaftermarket.com/\",\n    \"schema\": \"https://schema.org/\",\n    \"dana\": \"https://schema.danaaftermarket.com/\",\n    \"Part\": \"schema:Product\",\n    \"Order\": \"schema:Order\",\n    \"partNumber\": {\"@id\": \"schema:productID\", \"@type\": \"schema:Text\"},\n    \"description\": {\"@id\": \"schema:description\", \"@type\": \"schema:Text\"},\n    \"brand\": {\"@id\": \"schema:brand\", \"@type\": \"schema:Brand\"},\n    \"category\": {\"@id\": \"schema:category\", \"@type\": \"schema:Text\"},\n    \"make\": {\"@id\": \"dana:make\", \"@type\": \"schema:Text\"},\n    \"model\": {\"@id\": \"dana:model\", \"@type\": \"schema:Text\"},\n    \"year\": {\"@id\": \"dana:vehicleYear\", \"@type\": \"schema:Text\"},\n    \"orderId\": {\"@id\": \"schema:orderNumber\", \"@type\": \"schema:Text\"},\n    \"status\": {\"@id\": \"schema:orderStatus\", \"@type\": \"schema:Text\"},\n    \"items\": {\"@id\"\
  : \"schema:orderedItem\"},\n    \"trackingNumber\": {\"@id\": \"schema:trackingNumber\", \"@type\": \"schema:Text\"},\n    \"quantity\": {\"@id\": \"schema:orderQuantity\", \"@type\": \"schema:Integer\"},\n    \"shippingAddress\": {\"@id\": \"schema:shippingDestination\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dana/refs/heads/main/json-ld/dana-context.jsonld
tags:
- Aftermarket
- Auto Parts
- Drivetrain
- eCommerce
- Supply Chain
- JSON-LD
- Linked Data
- Semantic Web
---
