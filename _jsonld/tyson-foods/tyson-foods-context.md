---
api_specs:
- filename: tyson-foods-edi-integration-api-openapi.yml
  format: yaml
  label: Tyson Foods EDI Integration API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tyson-foods/refs/heads/main/openapi/tyson-foods-edi-integration-api-openapi.yml
class_count: 9
classes:
- Order
- PurchaseOrder
- Shipment
- AdvanceShipNotice
- TradingPartner
- Product
- OrderItem
- FoodProduct
- Corporation
context_file: json-ld/tyson-foods-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tyson-foods/refs/heads/main/json-ld/tyson-foods-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tyson Foods from Tyson Foods.
layout: jsonld
name: Tyson Foods Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: gs1
  uri: https://www.gs1.org/voc/
- prefix: tf
  uri: https://www.tysonfoods.com/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: orderId
  type: string
- container: ''
  name: partnerId
  type: string
- container: ''
  name: orderStatus
  type: '@vocab'
- container: ''
  name: orderDate
  type: dateTime
- container: ''
  name: trackingNumber
  type: string
- container: ''
  name: carrier
  type: reference
- container: ''
  name: productId
  type: string
- container: ''
  name: quantity
  type: integer
- container: ''
  name: shipDate
  type: date
- container: ''
  name: deliveryDate
  type: date
- container: ''
  name: shipToAddress
  type: schema:PostalAddress
property_count: 11
provider_name: Tyson Foods
provider_slug: tyson-foods
slug: tyson-foods-context
source_filename: tyson-foods-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"gs1\": \"https://www.gs1.org/voc/\",\n    \"tf\": \"https://www.tysonfoods.com/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Order\": \"schema:Order\",\n    \"PurchaseOrder\": \"tf:PurchaseOrder\",\n    \"Shipment\": \"tf:Shipment\",\n    \"AdvanceShipNotice\": \"tf:AdvanceShipNotice\",\n    \"TradingPartner\": \"schema:Organization\",\n    \"Product\": \"schema:Product\",\n    \"OrderItem\": \"schema:OrderItem\",\n    \"FoodProduct\": \"schema:FoodProduct\",\n    \"Corporation\": \"schema:Corporation\",\n\n    \"orderId\": {\n      \"@id\": \"schema:orderNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partnerId\": {\n      \"@id\": \"tf:tradingPartnerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orderStatus\": {\n      \"@id\": \"schema:orderStatus\",\n      \"@type\": \"@vocab\"\n    },\n    \"orderDate\": {\n      \"@id\": \"schema:orderDate\"\
  ,\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"trackingNumber\": {\n      \"@id\": \"gs1:trackingID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carrier\": {\n      \"@id\": \"schema:provider\",\n      \"@type\": \"@id\"\n    },\n    \"productId\": {\n      \"@id\": \"gs1:gtin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quantity\": {\n      \"@id\": \"schema:orderQuantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"shipDate\": {\n      \"@id\": \"tf:shipDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"deliveryDate\": {\n      \"@id\": \"schema:expectedArrivalFrom\",\n      \"@type\": \"xsd:date\"\n    },\n    \"shipToAddress\": {\n      \"@id\": \"schema:deliveryAddress\",\n      \"@type\": \"schema:PostalAddress\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tyson-foods/refs/heads/main/json-ld/tyson-foods-context.jsonld
tags:
- B2B Integration
- EDI
- Food
- Fortune 100
- Supply Chain
- JSON-LD
- Linked Data
- Semantic Web
---
