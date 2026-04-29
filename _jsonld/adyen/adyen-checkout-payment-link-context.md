---
class_count: 4
classes:
- PaymentLinkRequest
- PaymentLinkResponse
- description
- url
context_file: json-ld/adyen-checkout-payment-link-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-payment-link-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Payment Link from Adyen.
layout: jsonld
name: Adyen Checkout Payment Link Context
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
- container: set
  name: allowedPaymentMethods
  type: string
- container: ''
  name: amount
  type: string
- container: ''
  name: applicationInfo
  type: string
- container: ''
  name: billingAddress
  type: string
- container: set
  name: blockedPaymentMethods
  type: string
- container: ''
  name: captureDelayHours
  type: integer
- container: ''
  name: countryCode
  type: string
- container: ''
  name: dateOfBirth
  type: date
- container: ''
  name: deliverAt
  type: dateTime
- container: ''
  name: deliveryAddress
  type: string
- container: ''
  name: expiresAt
  type: dateTime
- container: ''
  name: installmentOptions
  type: reference
- container: set
  name: lineItems
  type: string
- container: ''
  name: manualCapture
  type: boolean
- container: ''
  name: mcc
  type: string
- container: ''
  name: merchantAccount
  type: string
- container: ''
  name: merchantOrderReference
  type: string
- container: ''
  name: metadata
  type: reference
- container: ''
  name: recurringProcessingModel
  type: string
- container: ''
  name: reference
  type: string
- container: set
  name: requiredShopperFields
  type: string
- container: ''
  name: returnUrl
  type: string
- container: ''
  name: reusable
  type: boolean
- container: ''
  name: riskData
  type: string
- container: ''
  name: shopperEmail
  type: string
- container: ''
  name: shopperLocale
  type: string
- container: ''
  name: shopperName
  type: string
- container: ''
  name: shopperReference
  type: string
- container: ''
  name: shopperStatement
  type: string
- container: ''
  name: showRemovePaymentMethodButton
  type: boolean
- container: ''
  name: socialSecurityNumber
  type: string
- container: ''
  name: splitCardFundingSources
  type: boolean
- container: set
  name: splits
  type: string
- container: ''
  name: store
  type: string
- container: ''
  name: storePaymentMethodMode
  type: string
- container: ''
  name: telephoneNumber
  type: string
- container: ''
  name: themeId
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: updatedAt
  type: dateTime
property_count: 40
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-payment-link-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PaymentLinkRequest\": \"adyen:PaymentLinkRequest\",\n    \"PaymentLinkResponse\": \"adyen:PaymentLinkResponse\",\n    \"allowedPaymentMethods\": {\n      \"@id\": \"adyen:allowedPaymentMethods\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"adyen:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applicationInfo\": {\n      \"@id\": \"adyen:applicationInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billingAddress\": {\n      \"@id\": \"adyen:billingAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"blockedPaymentMethods\": {\n      \"@id\": \"adyen:blockedPaymentMethods\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n   \
  \ },\n    \"captureDelayHours\": {\n      \"@id\": \"adyen:captureDelayHours\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"countryCode\": {\n      \"@id\": \"adyen:countryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateOfBirth\": {\n      \"@id\": \"adyen:dateOfBirth\",\n      \"@type\": \"xsd:date\"\n    },\n    \"deliverAt\": {\n      \"@id\": \"adyen:deliverAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"deliveryAddress\": {\n      \"@id\": \"adyen:deliveryAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"expiresAt\": {\n      \"@id\": \"adyen:expiresAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"installmentOptions\": {\n      \"@id\": \"adyen:installmentOptions\",\n      \"@type\": \"@id\"\n    },\n    \"lineItems\": {\n      \"@id\": \"adyen:lineItems\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manualCapture\": {\n      \"@id\": \"adyen:manualCapture\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"mcc\": {\n      \"@id\": \"adyen:mcc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantAccount\": {\n      \"@id\": \"adyen:merchantAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantOrderReference\": {\n      \"@id\": \"adyen:merchantOrderReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"adyen:metadata\",\n      \"@type\": \"@id\"\n    },\n    \"recurringProcessingModel\": {\n      \"@id\": \"adyen:recurringProcessingModel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"adyen:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requiredShopperFields\": {\n      \"@id\": \"adyen:requiredShopperFields\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"returnUrl\": {\n      \"@id\": \"adyen:returnUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reusable\": {\n      \"@id\": \"adyen:reusable\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"riskData\": {\n      \"@id\": \"adyen:riskData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperEmail\": {\n      \"@id\": \"adyen:shopperEmail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperLocale\": {\n      \"@id\": \"adyen:shopperLocale\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperName\": {\n      \"@id\": \"adyen:shopperName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperReference\": {\n      \"@id\": \"adyen:shopperReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperStatement\": {\n      \"@id\": \"adyen:shopperStatement\",\n      \"@type\": \"xsd:string\"\n    },\n    \"showRemovePaymentMethodButton\": {\n      \"@id\": \"adyen:showRemovePaymentMethodButton\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"socialSecurityNumber\": {\n      \"@id\": \"adyen:socialSecurityNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"splitCardFundingSources\": {\n      \"@id\"\
  : \"adyen:splitCardFundingSources\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"splits\": {\n      \"@id\": \"adyen:splits\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"store\": {\n      \"@id\": \"adyen:store\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storePaymentMethodMode\": {\n      \"@id\": \"adyen:storePaymentMethodMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"telephoneNumber\": {\n      \"@id\": \"adyen:telephoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"themeId\": {\n      \"@id\": \"adyen:themeId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"adyen:updatedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"url\": \"schema:url\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-payment-link-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
