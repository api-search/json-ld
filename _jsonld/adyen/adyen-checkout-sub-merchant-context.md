---
class_count: 3
classes:
- SubMerchantInfo
- SubMerchant
- name
context_file: json-ld/adyen-checkout-sub-merchant-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-sub-merchant-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Sub Merchant from Adyen.
layout: jsonld
name: Adyen Checkout Sub Merchant Context
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
  name: address
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: mcc
  type: string
- container: ''
  name: taxId
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: country
  type: string
property_count: 6
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-sub-merchant-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"SubMerchantInfo\": \"adyen:SubMerchantInfo\",\n    \"SubMerchant\": \"adyen:SubMerchant\",\n    \"address\": {\n      \"@id\": \"adyen:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mcc\": {\n      \"@id\": \"adyen:mcc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"taxId\": {\n      \"@id\": \"adyen:taxId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"adyen:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"adyen:country\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-sub-merchant-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
