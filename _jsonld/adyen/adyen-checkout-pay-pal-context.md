---
class_count: 1
classes:
- PayPalDetails
context_file: json-ld/adyen-checkout-pay-pal-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-pay-pal-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Pay Pal from Adyen.
layout: jsonld
name: Adyen Checkout Pay Pal Context
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
  name: orderID
  type: string
- container: ''
  name: payeePreferred
  type: string
- container: ''
  name: payerID
  type: string
- container: ''
  name: payerSelected
  type: string
- container: ''
  name: recurringDetailReference
  type: string
- container: ''
  name: storedPaymentMethodId
  type: string
- container: ''
  name: subtype
  type: string
- container: ''
  name: type
  type: string
property_count: 9
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-pay-pal-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PayPalDetails\": \"adyen:PayPalDetails\",\n    \"checkoutAttemptId\": {\n      \"@id\": \"adyen:checkoutAttemptId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orderID\": {\n      \"@id\": \"adyen:orderID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payeePreferred\": {\n      \"@id\": \"adyen:payeePreferred\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payerID\": {\n      \"@id\": \"adyen:payerID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payerSelected\": {\n      \"@id\": \"adyen:payerSelected\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recurringDetailReference\": {\n      \"@id\": \"adyen:recurringDetailReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storedPaymentMethodId\": {\n      \"\
  @id\": \"adyen:storedPaymentMethodId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subtype\": {\n      \"@id\": \"adyen:subtype\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-pay-pal-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
