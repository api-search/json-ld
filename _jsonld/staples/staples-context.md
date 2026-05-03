---
api_specs:
- filename: staples-advantage-eprocurement-api-openapi.yml
  format: yaml
  label: Staples Advantage eProcurement API
  slug: staples-advantage-eprocurement-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/staples/refs/heads/main/openapi/staples-advantage-eprocurement-api-openapi.yml
class_count: 47
classes:
- Product
- Order
- Invoice
- CostCenter
- DeliveryTracking
- id
- sku
- name
- brand
- category
- description
- price
- contractPrice
- inStock
- imageUrl
- specifications
- unitOfMeasure
- packSize
- weight
- dimensions
- relatedSkus
- status
- purchaseOrderNumber
- items
- deliveryAddress
- subtotal
- total
- orderedAt
- estimatedDelivery
- trackingNumbers
- contractNumber
- contractExpiry
- creditLimit
- availableCredit
- paymentTerms
- code
- budget
- spent
- carrier
- invoiceNumber
- dueDate
- issuedAt
- lineItems
- unitPrice
- amount
- costCenter
- paymentDate
context_file: json-ld/staples-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/staples/refs/heads/main/json-ld/staples-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Staples from Staples.
layout: jsonld
name: Staples Context
namespaces:
- prefix: staples
  uri: https://api.staplesadvantage.com/vocab#
properties: []
property_count: 0
provider_name: Staples
provider_slug: staples
slug: staples-context
source_filename: staples-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"staples\": \"https://api.staplesadvantage.com/vocab#\",\n    \"Product\": \"Product\",\n    \"Order\": \"Order\",\n    \"Invoice\": \"Invoice\",\n    \"CostCenter\": \"staples:CostCenter\",\n    \"DeliveryTracking\": \"ParcelDelivery\",\n    \"id\": \"@id\",\n    \"sku\": \"sku\",\n    \"name\": \"name\",\n    \"brand\": \"brand\",\n    \"category\": \"category\",\n    \"description\": \"description\",\n    \"price\": \"price\",\n    \"contractPrice\": \"staples:contractPrice\",\n    \"inStock\": \"availability\",\n    \"imageUrl\": \"image\",\n    \"specifications\": \"additionalProperty\",\n    \"unitOfMeasure\": \"unitCode\",\n    \"packSize\": \"staples:packSize\",\n    \"weight\": \"weight\",\n    \"dimensions\": \"size\",\n    \"relatedSkus\": \"isRelatedTo\",\n    \"status\": \"orderStatus\",\n    \"purchaseOrderNumber\": \"orderNumber\",\n    \"items\": \"orderedItem\",\n    \"deliveryAddress\": \"\
  deliveryAddress\",\n    \"subtotal\": \"price\",\n    \"total\": \"totalPrice\",\n    \"orderedAt\": \"orderDate\",\n    \"estimatedDelivery\": \"expectedArrivalFrom\",\n    \"trackingNumbers\": \"trackingNumber\",\n    \"contractNumber\": \"staples:contractNumber\",\n    \"contractExpiry\": \"validThrough\",\n    \"creditLimit\": \"staples:creditLimit\",\n    \"availableCredit\": \"staples:availableCredit\",\n    \"paymentTerms\": \"paymentMethod\",\n    \"code\": \"identifier\",\n    \"budget\": \"staples:budget\",\n    \"spent\": \"staples:amountSpent\",\n    \"carrier\": \"provider\",\n    \"invoiceNumber\": \"staples:invoiceNumber\",\n    \"dueDate\": \"paymentDueDate\",\n    \"issuedAt\": \"dateCreated\",\n    \"lineItems\": \"itemListElement\",\n    \"unitPrice\": \"price\",\n    \"amount\": \"totalPrice\",\n    \"costCenter\": \"staples:costCenter\",\n    \"paymentDate\": \"paymentDate\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/staples/refs/heads/main/json-ld/staples-context.jsonld
tags:
- Office Supplies
- Retail
- Procurement
- B2B
- eProcurement
- JSON-LD
- Linked Data
- Semantic Web
---
