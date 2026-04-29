---
class_count: 2
classes:
- NotifyShopperRequest
- NotifyShopperResult
context_file: json-ld/adyen-recurring-notify-shopper-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-recurring-notify-shopper-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Recurring Notify Shopper from Adyen.
layout: jsonld
name: Adyen Recurring Notify Shopper Context
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
  name: billingDate
  type: string
- container: ''
  name: billingSequenceNumber
  type: string
- container: ''
  name: displayedReference
  type: string
- container: ''
  name: merchantAccount
  type: string
- container: ''
  name: recurringDetailReference
  type: string
- container: ''
  name: reference
  type: string
- container: ''
  name: shopperReference
  type: string
- container: ''
  name: storedPaymentMethodId
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: pspReference
  type: string
- container: ''
  name: resultCode
  type: string
- container: ''
  name: shopperNotificationReference
  type: string
property_count: 13
provider_name: Adyen
provider_slug: adyen
slug: adyen-recurring-notify-shopper-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"NotifyShopperRequest\": \"adyen:NotifyShopperRequest\",\n    \"NotifyShopperResult\": \"adyen:NotifyShopperResult\",\n    \"amount\": {\n      \"@id\": \"adyen:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billingDate\": {\n      \"@id\": \"adyen:billingDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billingSequenceNumber\": {\n      \"@id\": \"adyen:billingSequenceNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayedReference\": {\n      \"@id\": \"adyen:displayedReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantAccount\": {\n      \"@id\": \"adyen:merchantAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recurringDetailReference\": {\n      \"@id\": \"adyen:recurringDetailReference\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"adyen:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperReference\": {\n      \"@id\": \"adyen:shopperReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storedPaymentMethodId\": {\n      \"@id\": \"adyen:storedPaymentMethodId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"adyen:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pspReference\": {\n      \"@id\": \"adyen:pspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resultCode\": {\n      \"@id\": \"adyen:resultCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperNotificationReference\": {\n      \"@id\": \"adyen:shopperNotificationReference\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-recurring-notify-shopper-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
