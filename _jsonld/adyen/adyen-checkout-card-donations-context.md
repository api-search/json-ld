---
class_count: 1
classes:
- CardDonations
context_file: json-ld/adyen-checkout-card-donations-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-card-donations-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Card Donations from Adyen.
layout: jsonld
name: Adyen Checkout Card Donations Context
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
  name: brand
  type: string
- container: ''
  name: checkoutAttemptId
  type: string
- container: ''
  name: cupsecureplus.smscode
  type: string
- container: ''
  name: cvc
  type: string
- container: ''
  name: encryptedCardNumber
  type: string
- container: ''
  name: encryptedExpiryMonth
  type: string
- container: ''
  name: encryptedExpiryYear
  type: string
- container: ''
  name: encryptedSecurityCode
  type: string
- container: ''
  name: expiryMonth
  type: string
- container: ''
  name: expiryYear
  type: string
- container: ''
  name: fundingSource
  type: string
- container: ''
  name: holderName
  type: string
- container: ''
  name: networkPaymentReference
  type: string
- container: ''
  name: number
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
  name: threeDS2SdkVersion
  type: string
- container: ''
  name: type
  type: string
property_count: 19
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-card-donations-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CardDonations\": \"adyen:CardDonations\",\n    \"brand\": {\n      \"@id\": \"adyen:brand\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checkoutAttemptId\": {\n      \"@id\": \"adyen:checkoutAttemptId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cupsecureplus.smscode\": {\n      \"@id\": \"adyen:cupsecureplus.smscode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cvc\": {\n      \"@id\": \"adyen:cvc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encryptedCardNumber\": {\n      \"@id\": \"adyen:encryptedCardNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encryptedExpiryMonth\": {\n      \"@id\": \"adyen:encryptedExpiryMonth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encryptedExpiryYear\": {\n  \
  \    \"@id\": \"adyen:encryptedExpiryYear\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encryptedSecurityCode\": {\n      \"@id\": \"adyen:encryptedSecurityCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiryMonth\": {\n      \"@id\": \"adyen:expiryMonth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiryYear\": {\n      \"@id\": \"adyen:expiryYear\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fundingSource\": {\n      \"@id\": \"adyen:fundingSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"holderName\": {\n      \"@id\": \"adyen:holderName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"networkPaymentReference\": {\n      \"@id\": \"adyen:networkPaymentReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"number\": {\n      \"@id\": \"adyen:number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recurringDetailReference\": {\n      \"@id\": \"adyen:recurringDetailReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperNotificationReference\"\
  : {\n      \"@id\": \"adyen:shopperNotificationReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storedPaymentMethodId\": {\n      \"@id\": \"adyen:storedPaymentMethodId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDS2SdkVersion\": {\n      \"@id\": \"adyen:threeDS2SdkVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-card-donations-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
