---
class_count: 1
classes:
- PaymentRequest
context_file: json-ld/adyen-terminal-payment-request-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-payment-request-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Payment Request from Adyen.
layout: jsonld
name: Adyen Terminal Payment Request Context
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
  name: SaleData
  type: string
- container: ''
  name: PaymentTransaction
  type: string
- container: ''
  name: PaymentData
  type: string
- container: set
  name: LoyaltyData
  type: string
property_count: 4
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-payment-request-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PaymentRequest\": \"adyen:PaymentRequest\",\n    \"SaleData\": {\n      \"@id\": \"adyen:SaleData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PaymentTransaction\": {\n      \"@id\": \"adyen:PaymentTransaction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PaymentData\": {\n      \"@id\": \"adyen:PaymentData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LoyaltyData\": {\n      \"@id\": \"adyen:LoyaltyData\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-payment-request-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
