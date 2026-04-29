---
class_count: 3
classes:
- BalanceTransferRequest
- BalanceTransferResponse
- description
context_file: json-ld/adyen-balance-control-balance-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-balance-control-balance-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Balance Control Balance from Adyen.
layout: jsonld
name: Adyen Balance Control Balance Context
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
  name: fromMerchant
  type: string
- container: ''
  name: reference
  type: string
- container: ''
  name: toMerchant
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: pspReference
  type: string
- container: ''
  name: status
  type: string
property_count: 8
provider_name: Adyen
provider_slug: adyen
slug: adyen-balance-control-balance-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"BalanceTransferRequest\": \"adyen:BalanceTransferRequest\",\n    \"BalanceTransferResponse\": \"adyen:BalanceTransferResponse\",\n    \"amount\": {\n      \"@id\": \"adyen:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"fromMerchant\": {\n      \"@id\": \"adyen:fromMerchant\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"adyen:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"toMerchant\": {\n      \"@id\": \"adyen:toMerchant\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"adyen:createdAt\",\n      \"@type\"\
  : \"xsd:dateTime\"\n    },\n    \"pspReference\": {\n      \"@id\": \"adyen:pspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-balance-control-balance-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
