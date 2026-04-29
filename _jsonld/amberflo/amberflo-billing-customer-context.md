---
class_count: 5
classes:
- Customer
- createTime
- updateTime
- description
- CustomerRequest
context_file: json-ld/amberflo-billing-customer-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amberflo/refs/heads/main/json-ld/amberflo-billing-customer-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amberflo Billing Customer from Amberflo.
layout: jsonld
name: Amberflo Billing Customer Context
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
  name: deleteTime
  type: integer
- container: ''
  name: customerId
  type: string
- container: ''
  name: customerName
  type: string
- container: ''
  name: customerEmail
  type: string
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: test
  type: boolean
- container: ''
  name: lifecycleStage
  type: string
- container: ''
  name: deactivateTimeStamp
  type: integer
- container: ''
  name: traits
  type: reference
- container: ''
  name: address
  type: string
property_count: 10
provider_name: Amberflo
provider_slug: amberflo
slug: amberflo-billing-customer-context
source_filename: amberflo-billing-customer-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amberflo\": \"https://amberflo.io/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Customer\": \"amberflo:Customer\",\n    \"createTime\": \"schema:dateCreated\",\n    \"updateTime\": \"schema:dateModified\",\n    \"deleteTime\": {\n      \"@id\": \"amberflo:deleteTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"customerId\": {\n      \"@id\": \"amberflo:customerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customerName\": {\n      \"@id\": \"amberflo:customerName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customerEmail\": {\n      \"@id\": \"amberflo:customerEmail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"enabled\": {\n      \"@id\": \"amberflo:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"test\": {\n      \"@id\": \"amberflo:test\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lifecycleStage\": {\n      \"@id\": \"amberflo:lifecycleStage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deactivateTimeStamp\": {\n      \"@id\": \"amberflo:deactivateTimeStamp\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"traits\": {\n      \"@id\": \"amberflo:traits\",\n      \"@type\": \"@id\"\n    },\n    \"address\": {\n      \"@id\": \"amberflo:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CustomerRequest\": \"amberflo:CustomerRequest\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amberflo/refs/heads/main/json-ld/amberflo-billing-customer-context.jsonld
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
