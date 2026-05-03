---
class_count: 4
classes:
- name
- description
- url
- identifier
context_file: json-ld/sheetz-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sheetz/refs/heads/main/json-ld/sheetz-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sheetz from Sheetz.
layout: jsonld
name: Sheetz Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: sheetz
  uri: https://api-evangelist.github.io/sheetz/vocab#
properties:
- container: ''
  name: Store
  type: reference
- container: ''
  name: storeId
  type: schema:Text
- container: ''
  name: address
  type: schema:PostalAddress
- container: ''
  name: fuelPrice
  type: schema:PriceSpecification
- container: ''
  name: fuelGrade
  type: schema:Text
- container: ''
  name: LoyaltyAccount
  type: reference
- container: ''
  name: loyaltyPoints
  type: schema:Number
- container: ''
  name: rewardBalance
  type: schema:MonetaryAmount
- container: ''
  name: Order
  type: reference
- container: ''
  name: orderId
  type: schema:Text
- container: ''
  name: orderStatus
  type: schema:Text
- container: ''
  name: orderItems
  type: reference
- container: ''
  name: MenuItem
  type: reference
- container: ''
  name: price
  type: schema:Number
- container: ''
  name: currency
  type: schema:Text
- container: ''
  name: SupplierOrder
  type: reference
- container: ''
  name: purchaseOrderNumber
  type: schema:Text
- container: ''
  name: supplier
  type: schema:Organization
- container: ''
  name: invoiceNumber
  type: schema:Text
- container: ''
  name: shipmentDate
  type: schema:Date
property_count: 20
provider_name: Sheetz
provider_slug: sheetz
slug: sheetz-context
source_filename: sheetz-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"sheetz\": \"https://api-evangelist.github.io/sheetz/vocab#\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"identifier\": \"schema:identifier\",\n    \"Store\": {\n      \"@id\": \"schema:LocalBusiness\",\n      \"@type\": \"@id\"\n    },\n    \"storeId\": {\n      \"@id\": \"sheetz:storeId\",\n      \"@type\": \"schema:Text\"\n    },\n    \"address\": {\n      \"@id\": \"schema:address\",\n      \"@type\": \"schema:PostalAddress\"\n    },\n    \"fuelPrice\": {\n      \"@id\": \"sheetz:fuelPrice\",\n      \"@type\": \"schema:PriceSpecification\"\n    },\n    \"fuelGrade\": {\n      \"@id\": \"sheetz:fuelGrade\",\n      \"@type\": \"schema:Text\"\n    },\n    \"LoyaltyAccount\": {\n      \"@id\": \"schema:LoyaltyProgram\",\n      \"@type\": \"@id\"\n    },\n    \"loyaltyPoints\": {\n      \"@id\": \"sheetz:loyaltyPoints\"\
  ,\n      \"@type\": \"schema:Number\"\n    },\n    \"rewardBalance\": {\n      \"@id\": \"sheetz:rewardBalance\",\n      \"@type\": \"schema:MonetaryAmount\"\n    },\n    \"Order\": {\n      \"@id\": \"schema:Order\",\n      \"@type\": \"@id\"\n    },\n    \"orderId\": {\n      \"@id\": \"schema:orderNumber\",\n      \"@type\": \"schema:Text\"\n    },\n    \"orderStatus\": {\n      \"@id\": \"schema:orderStatus\",\n      \"@type\": \"schema:Text\"\n    },\n    \"orderItems\": {\n      \"@id\": \"schema:orderedItem\",\n      \"@type\": \"@id\"\n    },\n    \"MenuItem\": {\n      \"@id\": \"schema:MenuItem\",\n      \"@type\": \"@id\"\n    },\n    \"price\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"schema:Number\"\n    },\n    \"currency\": {\n      \"@id\": \"schema:priceCurrency\",\n      \"@type\": \"schema:Text\"\n    },\n    \"SupplierOrder\": {\n      \"@id\": \"schema:Order\",\n      \"@type\": \"@id\"\n    },\n    \"purchaseOrderNumber\": {\n      \"@id\": \"sheetz:purchaseOrderNumber\"\
  ,\n      \"@type\": \"schema:Text\"\n    },\n    \"supplier\": {\n      \"@id\": \"schema:seller\",\n      \"@type\": \"schema:Organization\"\n    },\n    \"invoiceNumber\": {\n      \"@id\": \"sheetz:invoiceNumber\",\n      \"@type\": \"schema:Text\"\n    },\n    \"shipmentDate\": {\n      \"@id\": \"schema:orderDate\",\n      \"@type\": \"schema:Date\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sheetz/refs/heads/main/json-ld/sheetz-context.jsonld
tags:
- Convenience Store
- Energy
- Food Service
- Fortune 500
- Fuel
- Retail
- JSON-LD
- Linked Data
- Semantic Web
---
