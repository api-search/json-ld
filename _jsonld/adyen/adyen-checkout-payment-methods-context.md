---
class_count: 2
classes:
- PaymentMethodsRequest
- PaymentMethodsResponse
context_file: json-ld/adyen-checkout-payment-methods-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-payment-methods-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Payment Methods from Adyen.
layout: jsonld
name: Adyen Checkout Payment Methods Context
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
- container: set
  name: allowedPaymentMethods
  type: string
- container: ''
  name: amount
  type: string
- container: set
  name: blockedPaymentMethods
  type: string
- container: ''
  name: channel
  type: string
- container: ''
  name: countryCode
  type: string
- container: ''
  name: merchantAccount
  type: string
- container: ''
  name: order
  type: string
- container: ''
  name: shopperLocale
  type: string
- container: ''
  name: shopperReference
  type: string
- container: ''
  name: splitCardFundingSources
  type: boolean
- container: ''
  name: store
  type: string
- container: set
  name: paymentMethods
  type: string
- container: set
  name: storedPaymentMethods
  type: string
property_count: 14
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-payment-methods-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PaymentMethodsRequest\": \"adyen:PaymentMethodsRequest\",\n    \"PaymentMethodsResponse\": \"adyen:PaymentMethodsResponse\",\n    \"additionalData\": {\n      \"@id\": \"adyen:additionalData\",\n      \"@type\": \"@id\"\n    },\n    \"allowedPaymentMethods\": {\n      \"@id\": \"adyen:allowedPaymentMethods\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"adyen:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"blockedPaymentMethods\": {\n      \"@id\": \"adyen:blockedPaymentMethods\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"channel\": {\n      \"@id\": \"adyen:channel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  countryCode\": {\n      \"@id\": \"adyen:countryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantAccount\": {\n      \"@id\": \"adyen:merchantAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"order\": {\n      \"@id\": \"adyen:order\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperLocale\": {\n      \"@id\": \"adyen:shopperLocale\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperReference\": {\n      \"@id\": \"adyen:shopperReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"splitCardFundingSources\": {\n      \"@id\": \"adyen:splitCardFundingSources\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"store\": {\n      \"@id\": \"adyen:store\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentMethods\": {\n      \"@id\": \"adyen:paymentMethods\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storedPaymentMethods\": {\n      \"@id\": \"adyen:storedPaymentMethods\",\n      \"@container\": \"@set\"\
  ,\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-payment-methods-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
