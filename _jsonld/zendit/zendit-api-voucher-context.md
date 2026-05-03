---
api_specs:
- filename: zendit-api.yml
  format: yaml
  label: Zendit API
  slug: zendit-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/openapi/zendit-api.yml
class_count: 2
classes:
- VoucherPurchaseRequest
- email
context_file: json-ld/zendit-api-voucher-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/json-ld/zendit-api-voucher-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Zendit Api Voucher from Zendit.
layout: jsonld
name: Zendit Api Voucher Context
namespaces:
- prefix: zendit
  uri: https://zendit.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: transactionId
  type: string
- container: ''
  name: offerId
  type: string
- container: ''
  name: sendValue
  type: string
- container: ''
  name: recipient
  type: reference
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
property_count: 6
provider_name: Zendit
provider_slug: zendit
slug: zendit-api-voucher-context
source_filename: zendit-api-voucher-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"zendit\": \"https://zendit.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"VoucherPurchaseRequest\": \"zendit:VoucherPurchaseRequest\",\n    \"transactionId\": {\n      \"@id\": \"zendit:transactionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"offerId\": {\n      \"@id\": \"zendit:offerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sendValue\": {\n      \"@id\": \"zendit:sendValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recipient\": {\n      \"@id\": \"zendit:recipient\",\n      \"@type\": \"@id\"\n    },\n    \"email\": \"schema:email\",\n    \"firstName\": {\n      \"@id\": \"zendit:firstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"zendit:lastName\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/json-ld/zendit-api-voucher-context.jsonld
tags:
- eSIM
- Gift Cards
- Mobile Top-Up
- Payments
- Prepaid
- JSON-LD
- Linked Data
- Semantic Web
---
