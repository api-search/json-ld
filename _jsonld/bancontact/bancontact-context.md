---
class_count: 0
classes: []
context_file: json-ld/bancontact-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/bancontact/refs/heads/main/json-ld/bancontact-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Bancontact from Bancontact.
layout: jsonld
name: Bancontact Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: bancontact
  uri: https://www.bancontact.com/vocab/
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
  name: description
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: expiresAt
  type: dateTime
- container: ''
  name: QRCode
  type: reference
- container: ''
  name: qrContent
  type: string
- container: ''
  name: deeplink
  type: anyURI
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
  name: Refund
  type: reference
- container: ''
  name: refundId
  type: string
- container: ''
  name: refundAmount
  type: decimal
- container: ''
  name: originalPaymentId
  type: string
property_count: 18
provider_name: Bancontact
provider_slug: bancontact
slug: bancontact-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"bancontact\": \"https://www.bancontact.com/vocab/\",\n\n    \"Payment\": {\n      \"@id\": \"bancontact:Payment\",\n      \"@type\": \"@id\"\n    },\n    \"paymentId\": {\n      \"@id\": \"bancontact:paymentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"bancontact:amount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"currency\": {\n      \"@id\": \"bancontact:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"bancontact:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"bancontact:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"bancontact:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"expiresAt\": {\n      \"@id\": \"bancontact:expiresAt\",\n   \
  \   \"@type\": \"xsd:dateTime\"\n    },\n\n    \"QRCode\": {\n      \"@id\": \"bancontact:QRCode\",\n      \"@type\": \"@id\"\n    },\n    \"qrContent\": {\n      \"@id\": \"bancontact:qrContent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deeplink\": {\n      \"@id\": \"bancontact:deeplink\",\n      \"@type\": \"xsd:anyURI\"\n    },\n\n    \"Merchant\": {\n      \"@id\": \"bancontact:Merchant\",\n      \"@type\": \"@id\"\n    },\n    \"merchantId\": {\n      \"@id\": \"bancontact:merchantId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantName\": {\n      \"@id\": \"bancontact:merchantName\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"Refund\": {\n      \"@id\": \"bancontact:Refund\",\n      \"@type\": \"@id\"\n    },\n    \"refundId\": {\n      \"@id\": \"bancontact:refundId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"refundAmount\": {\n      \"@id\": \"bancontact:refundAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"originalPaymentId\": {\n \
  \     \"@id\": \"bancontact:originalPaymentId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/bancontact/refs/heads/main/json-ld/bancontact-context.jsonld
tags:
- Banking
- Belgium
- Debit Cards
- E-Commerce
- Fintech
- Payments
- JSON-LD
- Linked Data
- Semantic Web
---
