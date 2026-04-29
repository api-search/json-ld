---
class_count: 1
classes:
- UpiIntentDetails
context_file: json-ld/adyen-checkout-upi-intent-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-upi-intent-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Upi Intent from Adyen.
layout: jsonld
name: Adyen Checkout Upi Intent Context
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
  name: recurringDetailReference
  type: string
- container: ''
  name: shopperNotificationReference
  type: string
- container: ''
  name: storedPaymentMethodId
  type: string
- container: ''
  name: type
  type: string
property_count: 5
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-upi-intent-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"UpiIntentDetails\": \"adyen:UpiIntentDetails\",\n    \"checkoutAttemptId\": {\n      \"@id\": \"adyen:checkoutAttemptId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recurringDetailReference\": {\n      \"@id\": \"adyen:recurringDetailReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperNotificationReference\": {\n      \"@id\": \"adyen:shopperNotificationReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storedPaymentMethodId\": {\n      \"@id\": \"adyen:storedPaymentMethodId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-upi-intent-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
