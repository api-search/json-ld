---
class_count: 1
classes:
- BacsDirectDebitDetails
context_file: json-ld/adyen-checkout-bacs-direct-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-bacs-direct-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Bacs Direct from Adyen.
layout: jsonld
name: Adyen Checkout Bacs Direct Context
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
  name: bankAccountNumber
  type: string
- container: ''
  name: bankLocationId
  type: string
- container: ''
  name: checkoutAttemptId
  type: string
- container: ''
  name: holderName
  type: string
- container: ''
  name: recurringDetailReference
  type: string
- container: ''
  name: storedPaymentMethodId
  type: string
- container: ''
  name: type
  type: string
property_count: 7
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-bacs-direct-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"BacsDirectDebitDetails\": \"adyen:BacsDirectDebitDetails\",\n    \"bankAccountNumber\": {\n      \"@id\": \"adyen:bankAccountNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankLocationId\": {\n      \"@id\": \"adyen:bankLocationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checkoutAttemptId\": {\n      \"@id\": \"adyen:checkoutAttemptId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"holderName\": {\n      \"@id\": \"adyen:holderName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recurringDetailReference\": {\n      \"@id\": \"adyen:recurringDetailReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storedPaymentMethodId\": {\n      \"@id\": \"adyen:storedPaymentMethodId\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-bacs-direct-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
