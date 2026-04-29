---
class_count: 1
classes:
- VisaCheckoutDetails
context_file: json-ld/adyen-checkout-visa-checkout-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-visa-checkout-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Visa Checkout from Adyen.
layout: jsonld
name: Adyen Checkout Visa Checkout Context
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
  name: checkoutAttemptId
  type: string
- container: ''
  name: fundingSource
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: visaCheckoutCallId
  type: string
property_count: 4
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-visa-checkout-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"VisaCheckoutDetails\": \"adyen:VisaCheckoutDetails\",\n    \"checkoutAttemptId\": {\n      \"@id\": \"adyen:checkoutAttemptId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fundingSource\": {\n      \"@id\": \"adyen:fundingSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"visaCheckoutCallId\": {\n      \"@id\": \"adyen:visaCheckoutCallId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-visa-checkout-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
