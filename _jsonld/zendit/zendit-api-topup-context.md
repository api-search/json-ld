---
api_specs:
- filename: zendit-api.yml
  format: yaml
  label: Zendit API
  slug: zendit-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/openapi/zendit-api.yml
class_count: 1
classes:
- TopupPurchaseRequest
context_file: json-ld/zendit-api-topup-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/json-ld/zendit-api-topup-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Zendit Api Topup from Zendit.
layout: jsonld
name: Zendit Api Topup Context
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
  name: subscriberNumber
  type: string
- container: ''
  name: sendValue
  type: string
property_count: 4
provider_name: Zendit
provider_slug: zendit
slug: zendit-api-topup-context
source_filename: zendit-api-topup-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"zendit\": \"https://zendit.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"TopupPurchaseRequest\": \"zendit:TopupPurchaseRequest\",\n    \"transactionId\": {\n      \"@id\": \"zendit:transactionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"offerId\": {\n      \"@id\": \"zendit:offerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subscriberNumber\": {\n      \"@id\": \"zendit:subscriberNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sendValue\": {\n      \"@id\": \"zendit:sendValue\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/json-ld/zendit-api-topup-context.jsonld
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
