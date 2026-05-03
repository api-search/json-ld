---
api_specs:
- filename: dsco-platform-openapi.yml
  format: yaml
  label: Dsco Platform API
  slug: dsco-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rithum/refs/heads/main/openapi/dsco-platform-openapi.yml
class_count: 35
classes:
- Order
- orderId
- orderType
- status
- createdAt
- updatedAt
- retailerId
- supplierId
- items
- sku
- quantity
- cost
- price
- shippingAddress
- name
- street1
- city
- state
- postalCode
- country
- CatalogItem
- title
- description
- Stream
- streamId
- objectType
- Shipment
- trackingNumber
- carrier
- Invoice
- invoiceNumber
- amount
- invoiceDate
- Return
- returnReason
context_file: json-ld/rithum-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/rithum/refs/heads/main/json-ld/rithum-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Rithum from Rithum.
layout: jsonld
name: Rithum Context
namespaces:
- prefix: rithum
  uri: https://api-evangelist.github.io/rithum/vocab#
- prefix: dsco
  uri: https://api.dsco.io/schema#
properties: []
property_count: 0
provider_name: Rithum
provider_slug: rithum
slug: rithum-context
source_filename: rithum-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"rithum\": \"https://api-evangelist.github.io/rithum/vocab#\",\n    \"dsco\": \"https://api.dsco.io/schema#\",\n    \"Order\": \"schema:Order\",\n    \"orderId\": \"schema:orderNumber\",\n    \"orderType\": \"rithum:orderType\",\n    \"status\": \"schema:orderStatus\",\n    \"createdAt\": \"schema:orderDate\",\n    \"updatedAt\": \"schema:modifiedTime\",\n    \"retailerId\": \"rithum:retailerId\",\n    \"supplierId\": \"rithum:supplierId\",\n    \"items\": \"schema:orderedItem\",\n    \"sku\": \"schema:sku\",\n    \"quantity\": \"schema:orderQuantity\",\n    \"cost\": \"schema:price\",\n    \"price\": \"schema:highPrice\",\n    \"shippingAddress\": \"schema:deliveryAddress\",\n    \"name\": \"schema:name\",\n    \"street1\": \"schema:streetAddress\",\n    \"city\": \"schema:addressLocality\",\n    \"state\": \"schema:addressRegion\",\n    \"postalCode\": \"schema:postalCode\",\n    \"country\": \"schema:addressCountry\"\
  ,\n    \"CatalogItem\": \"schema:Product\",\n    \"title\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"Stream\": \"rithum:Stream\",\n    \"streamId\": \"rithum:streamId\",\n    \"objectType\": \"rithum:objectType\",\n    \"Shipment\": \"schema:ParcelDelivery\",\n    \"trackingNumber\": \"schema:trackingNumber\",\n    \"carrier\": \"schema:deliveryMethod\",\n    \"Invoice\": \"schema:Invoice\",\n    \"invoiceNumber\": \"schema:invoiceNumber\",\n    \"amount\": \"schema:price\",\n    \"invoiceDate\": \"schema:dateIssued\",\n    \"Return\": \"rithum:Return\",\n    \"returnReason\": \"rithum:returnReason\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/rithum/refs/heads/main/json-ld/rithum-context.jsonld
tags:
- Commerce
- Dropship
- Marketplace
- Ecommerce
- Supply Chain
- Retail
- JSON-LD
- Linked Data
- Semantic Web
---
