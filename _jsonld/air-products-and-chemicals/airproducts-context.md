---
class_count: 3
classes:
- IndustrialGasProduct
- GasOrder
- TankTelemetry
context_file: json-ld/airproducts-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/air-products-and-chemicals/refs/heads/main/json-ld/airproducts-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Airproducts from Air Products and Chemicals.
layout: jsonld
name: Airproducts Context
namespaces:
- prefix: airproducts
  uri: https://airproducts.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: productId
  type: string
- container: ''
  name: chemicalFormula
  type: string
- container: ''
  name: purityGrade
  type: string
- container: ''
  name: purityPercent
  type: decimal
- container: ''
  name: orderId
  type: string
- container: ''
  name: quantity
  type: decimal
- container: ''
  name: deliveryDate
  type: date
- container: ''
  name: tankId
  type: string
- container: ''
  name: levelPercent
  type: decimal
- container: ''
  name: timestamp
  type: dateTime
property_count: 12
provider_name: Air Products and Chemicals
provider_slug: air-products-and-chemicals
slug: airproducts-context
source_filename: airproducts-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"airproducts\": \"https://airproducts.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"IndustrialGasProduct\": \"airproducts:IndustrialGasProduct\",\n    \"GasOrder\": \"airproducts:GasOrder\",\n    \"TankTelemetry\": \"airproducts:TankTelemetry\",\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productId\": {\n      \"@id\": \"airproducts:product_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"chemicalFormula\": {\n      \"@id\": \"airproducts:chemical_formula\",\n      \"@type\": \"xsd:string\"\n    },\n    \"purityGrade\": {\n      \"@id\": \"airproducts:purity_grade\",\n      \"@type\": \"xsd:string\"\n    },\n    \"purityPercent\": {\n      \"@id\": \"airproducts:purity_percent\",\n      \"@type\"\
  : \"xsd:decimal\"\n    },\n    \"orderId\": {\n      \"@id\": \"airproducts:order_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quantity\": {\n      \"@id\": \"airproducts:quantity\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"deliveryDate\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:date\"\n    },\n    \"tankId\": {\n      \"@id\": \"airproducts:tank_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"levelPercent\": {\n      \"@id\": \"airproducts:level_percent\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"timestamp\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/air-products-and-chemicals/refs/heads/main/json-ld/airproducts-context.jsonld
tags:
- Industrial Gases
- Chemicals
- Energy
- Manufacturing
- Hydrogen
- Enterprise
- JSON-LD
- Linked Data
- Semantic Web
---
