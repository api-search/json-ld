---
class_count: 2
classes:
- PaymentCaptureRequest
- PaymentCaptureResponse
context_file: json-ld/adyen-checkout-payment-capture-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-payment-capture-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Payment Capture from Adyen.
layout: jsonld
name: Adyen Checkout Payment Capture Context
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
  name: applicationInfo
  type: string
- container: set
  name: lineItems
  type: string
- container: ''
  name: merchantAccount
  type: string
- container: ''
  name: platformChargebackLogic
  type: string
- container: ''
  name: reference
  type: string
- container: set
  name: splits
  type: string
- container: set
  name: subMerchants
  type: string
- container: ''
  name: paymentPspReference
  type: string
- container: ''
  name: pspReference
  type: string
- container: ''
  name: status
  type: string
property_count: 11
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-payment-capture-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PaymentCaptureRequest\": \"adyen:PaymentCaptureRequest\",\n    \"PaymentCaptureResponse\": \"adyen:PaymentCaptureResponse\",\n    \"amount\": {\n      \"@id\": \"adyen:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applicationInfo\": {\n      \"@id\": \"adyen:applicationInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lineItems\": {\n      \"@id\": \"adyen:lineItems\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantAccount\": {\n      \"@id\": \"adyen:merchantAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platformChargebackLogic\": {\n      \"@id\": \"adyen:platformChargebackLogic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\"\
  : \"adyen:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"splits\": {\n      \"@id\": \"adyen:splits\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subMerchants\": {\n      \"@id\": \"adyen:subMerchants\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentPspReference\": {\n      \"@id\": \"adyen:paymentPspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pspReference\": {\n      \"@id\": \"adyen:pspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-payment-capture-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
