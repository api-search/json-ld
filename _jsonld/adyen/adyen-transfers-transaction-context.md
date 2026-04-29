---
class_count: 1
classes:
- Transaction
context_file: json-ld/adyen-transfers-transaction-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-transfers-transaction-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Transfers Transaction from Adyen.
layout: jsonld
name: Adyen Transfers Transaction Context
namespaces:
- prefix: adyen
  uri: https://docs.adyen.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: accountHolder
  type: string
- container: ''
  name: amount
  type: string
- container: ''
  name: balanceAccount
  type: string
- container: ''
  name: balancePlatform
  type: string
- container: ''
  name: bookingDate
  type: dateTime
- container: ''
  name: creationDate
  type: dateTime
- container: ''
  name: id
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: transfer
  type: string
- container: ''
  name: valueDate
  type: dateTime
property_count: 10
provider_name: Adyen
provider_slug: adyen
slug: adyen-transfers-transaction-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Transaction\": \"adyen:Transaction\",\n    \"accountHolder\": {\n      \"@id\": \"adyen:accountHolder\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"adyen:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"balanceAccount\": {\n      \"@id\": \"adyen:balanceAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"balancePlatform\": {\n      \"@id\": \"adyen:balancePlatform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bookingDate\": {\n      \"@id\": \"adyen:bookingDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"creationDate\": {\n      \"@id\": \"adyen:creationDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transfer\": {\n      \"@id\": \"adyen:transfer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"valueDate\": {\n      \"@id\": \"adyen:valueDate\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-transfers-transaction-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
