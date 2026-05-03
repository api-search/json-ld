---
class_count: 4
classes:
- Organization
- Product
- Order
- Invoice
context_file: json-ld/vwr-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/vwr/refs/heads/main/json-ld/vwr-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Vwr from VWR International (Avantor).
layout: jsonld
name: Vwr Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: vwr
  uri: https://vwr.com/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: LabSupply
  type: schema:Product
- container: ''
  name: Reagent
  type: schema:Product
- container: ''
  name: Laboratory
  type: schema:Place
- container: ''
  name: PurchaseOrder
  type: schema:Order
- container: ''
  name: catalogNumber
  type: string
- container: ''
  name: casNumber
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: sku
  type: string
- container: ''
  name: price
  type: decimal
- container: ''
  name: priceCurrency
  type: string
- container: ''
  name: manufacturer
  type: reference
- container: ''
  name: brand
  type: schema:Brand
- container: ''
  name: orderDate
  type: dateTime
- container: ''
  name: orderStatus
  type: string
property_count: 15
provider_name: VWR International (Avantor)
provider_slug: vwr
slug: vwr-context
source_filename: vwr-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"vwr\": \"https://vwr.com/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Organization\": \"schema:Organization\",\n    \"Product\": \"schema:Product\",\n    \"Order\": \"schema:Order\",\n    \"Invoice\": \"schema:Invoice\",\n\n    \"LabSupply\": {\n      \"@id\": \"vwr:LabSupply\",\n      \"@type\": \"schema:Product\"\n    },\n\n    \"Reagent\": {\n      \"@id\": \"vwr:Reagent\",\n      \"@type\": \"schema:Product\"\n    },\n\n    \"Laboratory\": {\n      \"@id\": \"vwr:Laboratory\",\n      \"@type\": \"schema:Place\"\n    },\n\n    \"PurchaseOrder\": {\n      \"@id\": \"vwr:PurchaseOrder\",\n      \"@type\": \"schema:Order\"\n    },\n\n    \"catalogNumber\": {\n      \"@id\": \"vwr:catalogNumber\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"casNumber\": {\n      \"@id\": \"vwr:casNumber\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"name\": {\n\
  \      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"sku\": {\n      \"@id\": \"schema:sku\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"price\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"priceCurrency\": {\n      \"@id\": \"schema:priceCurrency\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"manufacturer\": {\n      \"@id\": \"schema:manufacturer\",\n      \"@type\": \"@id\"\n    },\n\n    \"brand\": {\n      \"@id\": \"schema:brand\",\n      \"@type\": \"schema:Brand\"\n    },\n\n    \"orderDate\": {\n      \"@id\": \"schema:orderDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"orderStatus\": {\n      \"@id\": \"schema:orderStatus\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/vwr/refs/heads/main/json-ld/vwr-context.jsonld
tags:
- Distribution
- Laboratory
- Life Sciences
- Procurement
- Scientific Supplies
- JSON-LD
- Linked Data
- Semantic Web
---
