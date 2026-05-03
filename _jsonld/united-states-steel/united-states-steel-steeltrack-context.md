---
api_specs:
- filename: united-states-steel-steeltrack-openapi.yml
  format: yaml
  label: U.S. Steel SteelTrack API
  slug: steeltrack-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-states-steel/refs/heads/main/openapi/united-states-steel-steeltrack-openapi.yml
class_count: 8
classes:
- InventoryItem
- InventoryList
- OrderList
- Order
- ShipmentList
- Shipment
- TestReportList
- TestReport
context_file: json-ld/united-states-steel-steeltrack-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/united-states-steel/refs/heads/main/json-ld/united-states-steel-steeltrack-context.jsonld
description: JSON-LD context defining the semantic vocabulary for United States Steel Steeltrack from United States Steel.
layout: jsonld
name: United States Steel Steeltrack Context
namespaces:
- prefix: uss
  uri: https://ussteel.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: itemId
  type: string
- container: ''
  name: customerId
  type: string
- container: ''
  name: orderId
  type: string
- container: ''
  name: product
  type: string
- container: ''
  name: grade
  type: string
- container: ''
  name: coilId
  type: string
- container: ''
  name: weight
  type: decimal
- container: ''
  name: weightUnit
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: total
  type: integer
- container: set
  name: items
  type: string
- container: set
  name: orders
  type: string
- container: ''
  name: purchaseOrder
  type: string
- container: ''
  name: facility
  type: string
- container: ''
  name: quantity
  type: decimal
- container: ''
  name: quantityUnit
  type: string
- container: ''
  name: orderDate
  type: date
- container: ''
  name: requiredDate
  type: date
- container: ''
  name: estimatedDeliveryDate
  type: date
- container: set
  name: shipments
  type: string
- container: ''
  name: shipmentId
  type: string
- container: ''
  name: shipDate
  type: date
- container: ''
  name: carrier
  type: string
- container: ''
  name: destination
  type: string
- container: set
  name: reports
  type: string
- container: ''
  name: reportId
  type: string
- container: ''
  name: reportType
  type: string
- container: ''
  name: certified
  type: boolean
- container: ''
  name: reportDate
  type: date
- container: ''
  name: yieldStrength
  type: decimal
- container: ''
  name: tensileStrength
  type: decimal
- container: ''
  name: elongation
  type: decimal
property_count: 33
provider_name: United States Steel
provider_slug: united-states-steel
slug: united-states-steel-steeltrack-context
source_filename: united-states-steel-steeltrack-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"uss\": \"https://ussteel.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"InventoryItem\": \"uss:InventoryItem\",\n    \"InventoryList\": \"uss:InventoryList\",\n    \"OrderList\": \"uss:OrderList\",\n    \"Order\": \"uss:Order\",\n    \"ShipmentList\": \"uss:ShipmentList\",\n    \"Shipment\": \"uss:Shipment\",\n    \"TestReportList\": \"uss:TestReportList\",\n    \"TestReport\": \"uss:TestReport\",\n    \"itemId\": {\n      \"@id\": \"uss:itemId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customerId\": {\n      \"@id\": \"uss:customerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orderId\": {\n      \"@id\": \"uss:orderId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"product\": {\n      \"@id\": \"uss:product\",\n      \"@type\": \"xsd:string\"\n    },\n    \"grade\": {\n      \"@id\": \"\
  uss:grade\",\n      \"@type\": \"xsd:string\"\n    },\n    \"coilId\": {\n      \"@id\": \"uss:coilId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"weight\": {\n      \"@id\": \"uss:weight\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"weightUnit\": {\n      \"@id\": \"uss:weightUnit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"uss:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"uss:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"total\": {\n      \"@id\": \"uss:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"items\": {\n      \"@id\": \"uss:items\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orders\": {\n      \"@id\": \"uss:orders\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"purchaseOrder\": {\n      \"@id\": \"uss:purchaseOrder\",\n      \"@type\": \"xsd:string\"\n    },\n    \"facility\": {\n     \
  \ \"@id\": \"uss:facility\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quantity\": {\n      \"@id\": \"uss:quantity\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"quantityUnit\": {\n      \"@id\": \"uss:quantityUnit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orderDate\": {\n      \"@id\": \"uss:orderDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"requiredDate\": {\n      \"@id\": \"uss:requiredDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"estimatedDeliveryDate\": {\n      \"@id\": \"uss:estimatedDeliveryDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"shipments\": {\n      \"@id\": \"uss:shipments\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shipmentId\": {\n      \"@id\": \"uss:shipmentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shipDate\": {\n      \"@id\": \"uss:shipDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"carrier\": {\n      \"@id\": \"uss:carrier\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"destination\": {\n      \"@id\": \"uss:destination\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reports\": {\n      \"@id\": \"uss:reports\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reportId\": {\n      \"@id\": \"uss:reportId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reportType\": {\n      \"@id\": \"uss:reportType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certified\": {\n      \"@id\": \"uss:certified\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"reportDate\": {\n      \"@id\": \"uss:reportDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"yieldStrength\": {\n      \"@id\": \"uss:yieldStrength\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"tensileStrength\": {\n      \"@id\": \"uss:tensileStrength\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"elongation\": {\n      \"@id\": \"uss:elongation\",\n      \"@type\": \"xsd:decimal\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/united-states-steel/refs/heads/main/json-ld/united-states-steel-steeltrack-context.jsonld
tags:
- Steel
- Manufacturing
- Automotive
- Construction
- Energy
- Supply Chain
- JSON-LD
- Linked Data
- Semantic Web
---
