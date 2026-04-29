---
class_count: 4
classes:
- ApplePayDetails
- ApplePayDonations
- ApplePaySessionRequest
- ApplePaySessionResponse
context_file: json-ld/adyen-checkout-apple-pay-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-apple-pay-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Apple Pay from Adyen.
layout: jsonld
name: Adyen Checkout Apple Pay Context
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
  name: applePayToken
  type: string
- container: ''
  name: checkoutAttemptId
  type: string
- container: ''
  name: fundingSource
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
- container: ''
  name: displayName
  type: string
- container: ''
  name: domainName
  type: string
- container: ''
  name: merchantIdentifier
  type: string
- container: ''
  name: data
  type: string
property_count: 10
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-apple-pay-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ApplePayDetails\": \"adyen:ApplePayDetails\",\n    \"ApplePayDonations\": \"adyen:ApplePayDonations\",\n    \"ApplePaySessionRequest\": \"adyen:ApplePaySessionRequest\",\n    \"ApplePaySessionResponse\": \"adyen:ApplePaySessionResponse\",\n    \"applePayToken\": {\n      \"@id\": \"adyen:applePayToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checkoutAttemptId\": {\n      \"@id\": \"adyen:checkoutAttemptId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fundingSource\": {\n      \"@id\": \"adyen:fundingSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recurringDetailReference\": {\n      \"@id\": \"adyen:recurringDetailReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storedPaymentMethodId\": {\n   \
  \   \"@id\": \"adyen:storedPaymentMethodId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": {\n      \"@id\": \"adyen:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domainName\": {\n      \"@id\": \"adyen:domainName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantIdentifier\": {\n      \"@id\": \"adyen:merchantIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"adyen:data\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-apple-pay-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
