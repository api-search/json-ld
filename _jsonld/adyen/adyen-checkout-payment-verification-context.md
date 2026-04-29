---
class_count: 2
classes:
- PaymentVerificationRequest
- PaymentVerificationResponse
context_file: json-ld/adyen-checkout-payment-verification-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-payment-verification-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Payment Verification from Adyen.
layout: jsonld
name: Adyen Checkout Payment Verification Context
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
  name: payload
  type: string
- container: ''
  name: additionalData
  type: reference
- container: ''
  name: fraudResult
  type: string
- container: ''
  name: merchantReference
  type: string
- container: ''
  name: order
  type: string
- container: ''
  name: pspReference
  type: string
- container: ''
  name: refusalReason
  type: string
- container: ''
  name: refusalReasonCode
  type: string
- container: ''
  name: resultCode
  type: string
- container: ''
  name: serviceError
  type: string
- container: ''
  name: shopperLocale
  type: string
property_count: 11
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-payment-verification-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PaymentVerificationRequest\": \"adyen:PaymentVerificationRequest\",\n    \"PaymentVerificationResponse\": \"adyen:PaymentVerificationResponse\",\n    \"payload\": {\n      \"@id\": \"adyen:payload\",\n      \"@type\": \"xsd:string\"\n    },\n    \"additionalData\": {\n      \"@id\": \"adyen:additionalData\",\n      \"@type\": \"@id\"\n    },\n    \"fraudResult\": {\n      \"@id\": \"adyen:fraudResult\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantReference\": {\n      \"@id\": \"adyen:merchantReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"order\": {\n      \"@id\": \"adyen:order\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pspReference\": {\n      \"@id\": \"adyen:pspReference\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"refusalReason\": {\n      \"@id\": \"adyen:refusalReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"refusalReasonCode\": {\n      \"@id\": \"adyen:refusalReasonCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resultCode\": {\n      \"@id\": \"adyen:resultCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceError\": {\n      \"@id\": \"adyen:serviceError\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperLocale\": {\n      \"@id\": \"adyen:shopperLocale\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-payment-verification-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
