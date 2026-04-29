---
class_count: 2
classes:
- CheckoutVoucherAction
- url
context_file: json-ld/adyen-checkout-checkout-voucher-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-checkout-voucher-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Checkout Voucher from Adyen.
layout: jsonld
name: Adyen Checkout Checkout Voucher Context
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
  name: alternativeReference
  type: string
- container: ''
  name: collectionInstitutionNumber
  type: string
- container: ''
  name: downloadUrl
  type: string
- container: ''
  name: entity
  type: string
- container: ''
  name: expiresAt
  type: string
- container: ''
  name: initialAmount
  type: string
- container: ''
  name: instructionsUrl
  type: string
- container: ''
  name: issuer
  type: string
- container: ''
  name: maskedTelephoneNumber
  type: string
- container: ''
  name: merchantName
  type: string
- container: ''
  name: merchantReference
  type: string
- container: ''
  name: passCreationToken
  type: string
- container: ''
  name: paymentData
  type: string
- container: ''
  name: paymentMethodType
  type: string
- container: ''
  name: reference
  type: string
- container: ''
  name: shopperEmail
  type: string
- container: ''
  name: shopperName
  type: string
- container: ''
  name: surcharge
  type: string
- container: ''
  name: totalAmount
  type: string
- container: ''
  name: type
  type: string
property_count: 20
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-checkout-voucher-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CheckoutVoucherAction\": \"adyen:CheckoutVoucherAction\",\n    \"alternativeReference\": {\n      \"@id\": \"adyen:alternativeReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"collectionInstitutionNumber\": {\n      \"@id\": \"adyen:collectionInstitutionNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"downloadUrl\": {\n      \"@id\": \"adyen:downloadUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entity\": {\n      \"@id\": \"adyen:entity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiresAt\": {\n      \"@id\": \"adyen:expiresAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"initialAmount\": {\n      \"@id\": \"adyen:initialAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instructionsUrl\"\
  : {\n      \"@id\": \"adyen:instructionsUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuer\": {\n      \"@id\": \"adyen:issuer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maskedTelephoneNumber\": {\n      \"@id\": \"adyen:maskedTelephoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantName\": {\n      \"@id\": \"adyen:merchantName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantReference\": {\n      \"@id\": \"adyen:merchantReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"passCreationToken\": {\n      \"@id\": \"adyen:passCreationToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentData\": {\n      \"@id\": \"adyen:paymentData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentMethodType\": {\n      \"@id\": \"adyen:paymentMethodType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"adyen:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperEmail\": {\n      \"@id\"\
  : \"adyen:shopperEmail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperName\": {\n      \"@id\": \"adyen:shopperName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"surcharge\": {\n      \"@id\": \"adyen:surcharge\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalAmount\": {\n      \"@id\": \"adyen:totalAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": \"schema:url\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-checkout-voucher-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
