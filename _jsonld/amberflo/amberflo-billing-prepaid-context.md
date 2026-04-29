---
class_count: 3
classes:
- PrepaidOrderRequest
- PrepaidOrder
- createTime
context_file: json-ld/amberflo-billing-prepaid-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amberflo/refs/heads/main/json-ld/amberflo-billing-prepaid-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amberflo Billing Prepaid from Amberflo.
layout: jsonld
name: Amberflo Billing Prepaid Context
namespaces:
- prefix: amberflo
  uri: https://amberflo.io/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: customerId
  type: string
- container: ''
  name: amount
  type: decimal
- container: ''
  name: currency
  type: string
- container: ''
  name: expirationTime
  type: integer
- container: ''
  name: orderId
  type: string
property_count: 5
provider_name: Amberflo
provider_slug: amberflo
slug: amberflo-billing-prepaid-context
source_filename: amberflo-billing-prepaid-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amberflo\": \"https://amberflo.io/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PrepaidOrderRequest\": \"amberflo:PrepaidOrderRequest\",\n    \"customerId\": {\n      \"@id\": \"amberflo:customerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"amberflo:amount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"currency\": {\n      \"@id\": \"amberflo:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expirationTime\": {\n      \"@id\": \"amberflo:expirationTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"PrepaidOrder\": \"amberflo:PrepaidOrder\",\n    \"orderId\": {\n      \"@id\": \"amberflo:orderId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createTime\": \"schema:dateCreated\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amberflo/refs/heads/main/json-ld/amberflo-billing-prepaid-context.jsonld
tags:
- Usage-Based Billing
- Metering
- FinOps
- AI Cost Management
- Billing
- Monetization
- JSON-LD
- Linked Data
- Semantic Web
---
