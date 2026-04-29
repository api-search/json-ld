---
class_count: 1
classes:
- PayoutResponse
context_file: json-ld/adyen-payouts-payout-response-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payouts-payout-response-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Payouts Payout Response from Adyen.
layout: jsonld
name: Adyen Payouts Payout Response Context
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
  name: additionalData
  type: reference
- container: ''
  name: authCode
  type: string
- container: ''
  name: dccAmount
  type: string
- container: ''
  name: dccSignature
  type: string
- container: ''
  name: fraudResult
  type: string
- container: ''
  name: issuerUrl
  type: string
- container: ''
  name: md
  type: string
- container: ''
  name: paRequest
  type: string
- container: ''
  name: pspReference
  type: string
- container: ''
  name: refusalReason
  type: string
- container: ''
  name: resultCode
  type: string
property_count: 11
provider_name: Adyen
provider_slug: adyen
slug: adyen-payouts-payout-response-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PayoutResponse\": \"adyen:PayoutResponse\",\n    \"additionalData\": {\n      \"@id\": \"adyen:additionalData\",\n      \"@type\": \"@id\"\n    },\n    \"authCode\": {\n      \"@id\": \"adyen:authCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dccAmount\": {\n      \"@id\": \"adyen:dccAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dccSignature\": {\n      \"@id\": \"adyen:dccSignature\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fraudResult\": {\n      \"@id\": \"adyen:fraudResult\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuerUrl\": {\n      \"@id\": \"adyen:issuerUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"md\": {\n      \"@id\": \"adyen:md\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"paRequest\": {\n      \"@id\": \"adyen:paRequest\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pspReference\": {\n      \"@id\": \"adyen:pspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"refusalReason\": {\n      \"@id\": \"adyen:refusalReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resultCode\": {\n      \"@id\": \"adyen:resultCode\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payouts-payout-response-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
