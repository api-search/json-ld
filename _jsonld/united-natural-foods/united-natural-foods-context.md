---
api_specs:
- filename: unfi-supplier-openapi.yml
  format: yaml
  label: UNFI Harmony Core API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-natural-foods/main/openapi/unfi-supplier-openapi.yml
class_count: 0
classes: []
context_file: json-ld/united-natural-foods-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/united-natural-foods/refs/heads/main/json-ld/united-natural-foods-context.jsonld
description: JSON-LD context defining the semantic vocabulary for United Natural Foods from United Natural Foods (UNFI).
layout: jsonld
name: United Natural Foods Context
namespaces:
- prefix: unfi
  uri: https://schema.unfi.com/
- prefix: schema
  uri: https://schema.org/
- prefix: gs1
  uri: https://www.gs1.org/voc/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Product
  type: reference
- container: ''
  name: FoodProduct
  type: reference
- container: ''
  name: productId
  type: string
- container: ''
  name: upc
  type: string
- container: ''
  name: gtin
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: brand
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: category
  type: string
- container: set
  name: certifications
  type: string
- container: ''
  name: unitSize
  type: string
- container: ''
  name: unitsPerCase
  type: integer
- container: ''
  name: retailPrice
  type: decimal
- container: ''
  name: status
  type: string
- container: ''
  name: PurchaseOrder
  type: reference
- container: ''
  name: orderId
  type: string
- container: ''
  name: purchaseOrderNumber
  type: string
- container: ''
  name: orderDate
  type: date
- container: ''
  name: requiredDeliveryDate
  type: date
- container: ''
  name: supplierId
  type: string
- container: ''
  name: warehouseId
  type: string
- container: ''
  name: totalAmount
  type: decimal
- container: ''
  name: Supplier
  type: reference
- container: list
  name: lineItems
  type: reference
- container: ''
  name: SalesInsight
  type: reference
- container: ''
  name: totalSales
  type: decimal
- container: ''
  name: unitsSold
  type: integer
- container: ''
  name: fillRate
  type: decimal
property_count: 28
provider_name: United Natural Foods (UNFI)
provider_slug: united-natural-foods
slug: united-natural-foods-context
source_filename: united-natural-foods-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"unfi\": \"https://schema.unfi.com/\",\n    \"schema\": \"https://schema.org/\",\n    \"gs1\": \"https://www.gs1.org/voc/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Product\": {\n      \"@id\": \"schema:Product\",\n      \"@type\": \"@id\"\n    },\n    \"FoodProduct\": {\n      \"@id\": \"unfi:FoodProduct\",\n      \"@type\": \"@id\",\n      \"subClassOf\": \"schema:Product\"\n    },\n    \"productId\": { \"@id\": \"unfi:productId\", \"@type\": \"xsd:string\" },\n    \"upc\": { \"@id\": \"gs1:gtin12\", \"@type\": \"xsd:string\" },\n    \"gtin\": { \"@id\": \"gs1:gtin14\", \"@type\": \"xsd:string\" },\n    \"name\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"brand\": { \"@id\": \"schema:brand\", \"@type\": \"xsd:string\" },\n    \"description\": { \"@id\": \"schema:description\", \"@type\": \"xsd:string\" },\n    \"category\": { \"@id\": \"schema:category\", \"@type\": \"xsd:string\"\
  \ },\n    \"certifications\": { \"@id\": \"unfi:hasCertification\", \"@type\": \"xsd:string\", \"@container\": \"@set\" },\n    \"unitSize\": { \"@id\": \"gs1:netContent\", \"@type\": \"xsd:string\" },\n    \"unitsPerCase\": { \"@id\": \"gs1:quantityOfLayers\", \"@type\": \"xsd:integer\" },\n    \"retailPrice\": { \"@id\": \"schema:price\", \"@type\": \"xsd:decimal\" },\n    \"status\": { \"@id\": \"schema:itemCondition\", \"@type\": \"xsd:string\" },\n\n    \"PurchaseOrder\": {\n      \"@id\": \"unfi:PurchaseOrder\",\n      \"@type\": \"@id\",\n      \"subClassOf\": \"schema:Order\"\n    },\n    \"orderId\": { \"@id\": \"schema:orderNumber\", \"@type\": \"xsd:string\" },\n    \"purchaseOrderNumber\": { \"@id\": \"unfi:purchaseOrderNumber\", \"@type\": \"xsd:string\" },\n    \"orderDate\": { \"@id\": \"schema:orderDate\", \"@type\": \"xsd:date\" },\n    \"requiredDeliveryDate\": { \"@id\": \"unfi:requiredDeliveryDate\", \"@type\": \"xsd:date\" },\n    \"supplierId\": { \"@id\": \"unfi:supplierId\"\
  , \"@type\": \"xsd:string\" },\n    \"warehouseId\": { \"@id\": \"unfi:warehouseId\", \"@type\": \"xsd:string\" },\n    \"totalAmount\": { \"@id\": \"schema:totalPrice\", \"@type\": \"xsd:decimal\" },\n\n    \"Supplier\": {\n      \"@id\": \"unfi:Supplier\",\n      \"@type\": \"@id\",\n      \"subClassOf\": \"schema:Organization\"\n    },\n    \"lineItems\": { \"@id\": \"unfi:hasLineItem\", \"@type\": \"@id\", \"@container\": \"@list\" },\n\n    \"SalesInsight\": {\n      \"@id\": \"unfi:SalesInsight\",\n      \"@type\": \"@id\"\n    },\n    \"totalSales\": { \"@id\": \"unfi:totalSales\", \"@type\": \"xsd:decimal\" },\n    \"unitsSold\": { \"@id\": \"unfi:unitsSold\", \"@type\": \"xsd:integer\" },\n    \"fillRate\": { \"@id\": \"unfi:fillRate\", \"@type\": \"xsd:decimal\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/united-natural-foods/refs/heads/main/json-ld/united-natural-foods-context.jsonld
tags:
- Food Distribution
- Wholesale
- Natural Foods
- Supply Chain
- Fortune 500
- JSON-LD
- Linked Data
- Semantic Web
---
