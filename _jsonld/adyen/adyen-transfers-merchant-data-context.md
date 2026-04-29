---
class_count: 1
classes:
- MerchantData
context_file: json-ld/adyen-transfers-merchant-data-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-transfers-merchant-data-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Transfers Merchant Data from Adyen.
layout: jsonld
name: Adyen Transfers Merchant Data Context
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
  name: acquirerId
  type: string
- container: ''
  name: mcc
  type: string
- container: ''
  name: merchantId
  type: string
- container: ''
  name: nameLocation
  type: string
- container: ''
  name: postalCode
  type: string
property_count: 5
provider_name: Adyen
provider_slug: adyen
slug: adyen-transfers-merchant-data-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"MerchantData\": \"adyen:MerchantData\",\n    \"acquirerId\": {\n      \"@id\": \"adyen:acquirerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mcc\": {\n      \"@id\": \"adyen:mcc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantId\": {\n      \"@id\": \"adyen:merchantId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nameLocation\": {\n      \"@id\": \"adyen:nameLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postalCode\": {\n      \"@id\": \"adyen:postalCode\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-transfers-merchant-data-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
