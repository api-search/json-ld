---
class_count: 5
classes:
- Product
- Order
- Account
- name
- description
context_file: json-ld/airgas-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/airgas/refs/heads/main/json-ld/airgas-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Airgas from Airgas.
layout: jsonld
name: Airgas Context
namespaces:
- prefix: airgas
  uri: https://airgas.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: productNumber
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: gasType
  type: string
- container: ''
  name: grade
  type: string
- container: ''
  name: price
  type: decimal
- container: ''
  name: orderNumber
  type: string
- container: ''
  name: accountNumber
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: orderDate
  type: dateTime
- container: ''
  name: deliveryDate
  type: date
- container: ''
  name: totalAmount
  type: decimal
- container: ''
  name: companyName
  type: string
- container: ''
  name: accountType
  type: string
- container: ''
  name: creditLimit
  type: decimal
- container: ''
  name: paymentTerms
  type: string
- container: ''
  name: isActive
  type: boolean
property_count: 16
provider_name: Airgas
provider_slug: airgas
slug: airgas-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"airgas\": \"https://airgas.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Product\": \"airgas:Product\",\n    \"Order\": \"airgas:Order\",\n    \"Account\": \"airgas:Account\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"productNumber\": {\n      \"@id\": \"airgas:product_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"airgas:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gasType\": {\n      \"@id\": \"airgas:gas_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"grade\": {\n      \"@id\": \"airgas:grade\",\n      \"@type\": \"xsd:string\"\n    },\n    \"price\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"orderNumber\": {\n      \"@id\": \"airgas:order_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountNumber\"\
  : {\n      \"@id\": \"airgas:account_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"airgas:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orderDate\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"deliveryDate\": {\n      \"@id\": \"schema:deliveryLeadTime\",\n      \"@type\": \"xsd:date\"\n    },\n    \"totalAmount\": {\n      \"@id\": \"schema:totalPrice\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"companyName\": {\n      \"@id\": \"schema:legalName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountType\": {\n      \"@id\": \"airgas:account_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creditLimit\": {\n      \"@id\": \"airgas:credit_limit\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"paymentTerms\": {\n      \"@id\": \"airgas:payment_terms\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isActive\": {\n      \"@id\": \"airgas:is_active\",\n      \"@type\"\
  : \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/airgas/refs/heads/main/json-ld/airgas-context.jsonld
tags:
- Industrial Gases
- Welding
- Safety
- B2B
- Supply Chain
- Manufacturing
- Healthcare
- JSON-LD
- Linked Data
- Semantic Web
---
