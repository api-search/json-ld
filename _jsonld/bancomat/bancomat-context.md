---
class_count: 0
classes: []
context_file: json-ld/bancomat-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/bancomat/refs/heads/main/json-ld/bancomat-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Bancomat from Bancomat.
layout: jsonld
name: Bancomat Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: bancomat
  uri: https://bancomat.it/vocab/
properties:
- container: ''
  name: Payment
  type: reference
- container: ''
  name: paymentId
  type: string
- container: ''
  name: amount
  type: decimal
- container: ''
  name: currency
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: Merchant
  type: reference
- container: ''
  name: merchantId
  type: string
- container: ''
  name: merchantName
  type: string
- container: ''
  name: QRCode
  type: reference
- container: ''
  name: qrContent
  type: string
- container: ''
  name: expiresAt
  type: dateTime
- container: ''
  name: BankAccount
  type: reference
- container: ''
  name: iban
  type: string
- container: ''
  name: phoneNumber
  type: string
property_count: 15
provider_name: Bancomat
provider_slug: bancomat
slug: bancomat-context
source_filename: bancomat-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"bancomat\": \"https://bancomat.it/vocab/\",\n\n    \"Payment\": {\n      \"@id\": \"bancomat:Payment\",\n      \"@type\": \"@id\"\n    },\n    \"paymentId\": {\n      \"@id\": \"bancomat:paymentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"bancomat:amount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"currency\": {\n      \"@id\": \"bancomat:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"bancomat:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"bancomat:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"Merchant\": {\n      \"@id\": \"bancomat:Merchant\",\n      \"@type\": \"@id\"\n    },\n    \"merchantId\": {\n      \"@id\": \"bancomat:merchantId\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"merchantName\": {\n      \"@id\": \"bancomat:merchantName\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"QRCode\": {\n      \"@id\": \"bancomat:QRCode\",\n      \"@type\": \"@id\"\n    },\n    \"qrContent\": {\n      \"@id\": \"bancomat:qrContent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiresAt\": {\n      \"@id\": \"bancomat:expiresAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"BankAccount\": {\n      \"@id\": \"bancomat:BankAccount\",\n      \"@type\": \"@id\"\n    },\n    \"iban\": {\n      \"@id\": \"bancomat:iban\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phoneNumber\": {\n      \"@id\": \"bancomat:phoneNumber\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/bancomat/refs/heads/main/json-ld/bancomat-context.jsonld
tags:
- ATM
- Banking
- Financial Services
- Italy
- Mobile Payments
- Payments
- Debit Cards
- JSON-LD
- Linked Data
- Semantic Web
---
