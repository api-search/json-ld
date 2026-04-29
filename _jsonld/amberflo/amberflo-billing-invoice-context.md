---
class_count: 1
classes:
- Invoice
context_file: json-ld/amberflo-billing-invoice-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amberflo/refs/heads/main/json-ld/amberflo-billing-invoice-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amberflo Billing Invoice from Amberflo.
layout: jsonld
name: Amberflo Billing Invoice Context
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
  name: invoiceId
  type: string
- container: ''
  name: customerId
  type: string
- container: ''
  name: startTime
  type: integer
- container: ''
  name: endTime
  type: integer
- container: ''
  name: totalAmount
  type: decimal
- container: ''
  name: currency
  type: string
- container: ''
  name: status
  type: string
property_count: 7
provider_name: Amberflo
provider_slug: amberflo
slug: amberflo-billing-invoice-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amberflo\": \"https://amberflo.io/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Invoice\": \"amberflo:Invoice\",\n    \"invoiceId\": {\n      \"@id\": \"amberflo:invoiceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customerId\": {\n      \"@id\": \"amberflo:customerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"amberflo:startTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"endTime\": {\n      \"@id\": \"amberflo:endTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalAmount\": {\n      \"@id\": \"amberflo:totalAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"currency\": {\n      \"@id\": \"amberflo:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"amberflo:status\",\n      \"@type\": \"xsd:string\"\
  \n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amberflo/refs/heads/main/json-ld/amberflo-billing-invoice-context.jsonld
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
