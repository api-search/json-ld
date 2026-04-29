---
class_count: 1
classes:
- PaymentCompletionDetails
context_file: json-ld/adyen-checkout-payment-completion-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-payment-completion-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Payment Completion from Adyen.
layout: jsonld
name: Adyen Checkout Payment Completion Context
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
  name: MD
  type: string
- container: ''
  name: PaReq
  type: string
- container: ''
  name: PaRes
  type: string
- container: ''
  name: authorizationToken
  type: string
- container: ''
  name: billingToken
  type: string
- container: ''
  name: cupsecureplus.smscode
  type: string
- container: ''
  name: facilitatorAccessToken
  type: string
- container: ''
  name: oneTimePasscode
  type: string
- container: ''
  name: orderID
  type: string
- container: ''
  name: payerID
  type: string
- container: ''
  name: payload
  type: string
- container: ''
  name: paymentID
  type: string
- container: ''
  name: paymentStatus
  type: string
- container: ''
  name: redirectResult
  type: string
- container: ''
  name: resultCode
  type: string
- container: ''
  name: threeDSResult
  type: string
- container: ''
  name: threeds2.challengeResult
  type: string
- container: ''
  name: threeds2.fingerprint
  type: string
property_count: 18
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-payment-completion-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PaymentCompletionDetails\": \"adyen:PaymentCompletionDetails\",\n    \"MD\": {\n      \"@id\": \"adyen:MD\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PaReq\": {\n      \"@id\": \"adyen:PaReq\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PaRes\": {\n      \"@id\": \"adyen:PaRes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authorizationToken\": {\n      \"@id\": \"adyen:authorization_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billingToken\": {\n      \"@id\": \"adyen:billingToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cupsecureplus.smscode\": {\n      \"@id\": \"adyen:cupsecureplus.smscode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"facilitatorAccessToken\": {\n      \"@id\": \"adyen:facilitatorAccessToken\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"oneTimePasscode\": {\n      \"@id\": \"adyen:oneTimePasscode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orderID\": {\n      \"@id\": \"adyen:orderID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payerID\": {\n      \"@id\": \"adyen:payerID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payload\": {\n      \"@id\": \"adyen:payload\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentID\": {\n      \"@id\": \"adyen:paymentID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentStatus\": {\n      \"@id\": \"adyen:paymentStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"redirectResult\": {\n      \"@id\": \"adyen:redirectResult\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resultCode\": {\n      \"@id\": \"adyen:resultCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDSResult\": {\n      \"@id\": \"adyen:threeDSResult\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeds2.challengeResult\"\
  : {\n      \"@id\": \"adyen:threeds2.challengeResult\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeds2.fingerprint\": {\n      \"@id\": \"adyen:threeds2.fingerprint\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-payment-completion-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
