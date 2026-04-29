---
class_count: 2
classes:
- ReturnTransferRequest
- ReturnTransferResponse
context_file: json-ld/adyen-transfers-return-transfer-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-transfers-return-transfer-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Transfers Return Transfer from Adyen.
layout: jsonld
name: Adyen Transfers Return Transfer Context
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
  name: amount
  type: string
- container: ''
  name: reference
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: transferId
  type: string
property_count: 5
provider_name: Adyen
provider_slug: adyen
slug: adyen-transfers-return-transfer-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ReturnTransferRequest\": \"adyen:ReturnTransferRequest\",\n    \"ReturnTransferResponse\": \"adyen:ReturnTransferResponse\",\n    \"amount\": {\n      \"@id\": \"adyen:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"adyen:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transferId\": {\n      \"@id\": \"adyen:transferId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-transfers-return-transfer-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
