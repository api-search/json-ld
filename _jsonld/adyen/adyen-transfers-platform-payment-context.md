---
class_count: 1
classes:
- PlatformPayment
context_file: json-ld/adyen-transfers-platform-payment-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-transfers-platform-payment-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Transfers Platform Payment from Adyen.
layout: jsonld
name: Adyen Transfers Platform Payment Context
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
  name: modificationMerchantReference
  type: string
- container: ''
  name: modificationPspReference
  type: string
- container: ''
  name: paymentMerchantReference
  type: string
- container: ''
  name: platformPaymentType
  type: string
- container: ''
  name: pspPaymentReference
  type: string
- container: ''
  name: type
  type: string
property_count: 6
provider_name: Adyen
provider_slug: adyen
slug: adyen-transfers-platform-payment-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PlatformPayment\": \"adyen:PlatformPayment\",\n    \"modificationMerchantReference\": {\n      \"@id\": \"adyen:modificationMerchantReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modificationPspReference\": {\n      \"@id\": \"adyen:modificationPspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentMerchantReference\": {\n      \"@id\": \"adyen:paymentMerchantReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platformPaymentType\": {\n      \"@id\": \"adyen:platformPaymentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pspPaymentReference\": {\n      \"@id\": \"adyen:pspPaymentReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n   \
  \   \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-transfers-platform-payment-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
