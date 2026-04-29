---
class_count: 3
classes:
- PaymentDetailsRequest
- PaymentDetailsResponse
- PaymentDetails
context_file: json-ld/adyen-checkout-payment-details-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-payment-details-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Payment Details from Adyen.
layout: jsonld
name: Adyen Checkout Payment Details Context
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
  name: authenticationData
  type: string
- container: ''
  name: details
  type: string
- container: ''
  name: paymentData
  type: string
- container: ''
  name: threeDSAuthenticationOnly
  type: boolean
- container: ''
  name: additionalData
  type: reference
- container: ''
  name: amount
  type: string
- container: ''
  name: donationToken
  type: string
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
  name: paymentMethod
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
  name: shopperLocale
  type: string
- container: ''
  name: threeDS2ResponseData
  type: string
- container: ''
  name: threeDS2Result
  type: string
- container: ''
  name: threeDSPaymentData
  type: string
- container: ''
  name: checkoutAttemptId
  type: string
- container: ''
  name: type
  type: string
property_count: 21
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-payment-details-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PaymentDetailsRequest\": \"adyen:PaymentDetailsRequest\",\n    \"PaymentDetailsResponse\": \"adyen:PaymentDetailsResponse\",\n    \"PaymentDetails\": \"adyen:PaymentDetails\",\n    \"authenticationData\": {\n      \"@id\": \"adyen:authenticationData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"details\": {\n      \"@id\": \"adyen:details\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentData\": {\n      \"@id\": \"adyen:paymentData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDSAuthenticationOnly\": {\n      \"@id\": \"adyen:threeDSAuthenticationOnly\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"additionalData\": {\n      \"@id\": \"adyen:additionalData\",\n      \"@type\": \"@id\"\n    },\n    \"amount\"\
  : {\n      \"@id\": \"adyen:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"donationToken\": {\n      \"@id\": \"adyen:donationToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fraudResult\": {\n      \"@id\": \"adyen:fraudResult\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantReference\": {\n      \"@id\": \"adyen:merchantReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"order\": {\n      \"@id\": \"adyen:order\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentMethod\": {\n      \"@id\": \"adyen:paymentMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pspReference\": {\n      \"@id\": \"adyen:pspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"refusalReason\": {\n      \"@id\": \"adyen:refusalReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"refusalReasonCode\": {\n      \"@id\": \"adyen:refusalReasonCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resultCode\": {\n      \"@id\": \"adyen:resultCode\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"shopperLocale\": {\n      \"@id\": \"adyen:shopperLocale\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDS2ResponseData\": {\n      \"@id\": \"adyen:threeDS2ResponseData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDS2Result\": {\n      \"@id\": \"adyen:threeDS2Result\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDSPaymentData\": {\n      \"@id\": \"adyen:threeDSPaymentData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checkoutAttemptId\": {\n      \"@id\": \"adyen:checkoutAttemptId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-payment-details-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
