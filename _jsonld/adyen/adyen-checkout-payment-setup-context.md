---
class_count: 2
classes:
- PaymentSetupRequest
- PaymentSetupResponse
context_file: json-ld/adyen-checkout-payment-setup-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-payment-setup-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Payment Setup from Adyen.
layout: jsonld
name: Adyen Checkout Payment Setup Context
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
  name: additionalAmount
  type: string
- container: ''
  name: additionalData
  type: reference
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
  name: channel
  type: string
- container: ''
  name: checkoutAttemptId
  type: string
- container: ''
  name: company
  type: string
- container: ''
  name: configuration
  type: string
- container: ''
  name: conversionId
  type: string
- container: ''
  name: countryCode
  type: string
- container: ''
  name: dateOfBirth
  type: date
- container: ''
  name: dccQuote
  type: string
- container: ''
  name: deliveryAddress
  type: string
- container: ''
  name: deliveryDate
  type: dateTime
- container: ''
  name: enableOneClick
  type: boolean
- container: ''
  name: enablePayOut
  type: boolean
- container: ''
  name: enableRecurring
  type: boolean
- container: ''
  name: entityType
  type: string
- container: ''
  name: fraudOffset
  type: integer
- container: ''
  name: installments
  type: string
- container: set
  name: lineItems
  type: string
- container: ''
  name: localizedShopperStatement
  type: reference
- container: ''
  name: mandate
  type: string
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
  name: orderReference
  type: string
- container: ''
  name: origin
  type: string
- container: ''
  name: platformChargebackLogic
  type: string
- container: ''
  name: recurringExpiry
  type: string
- container: ''
  name: recurringFrequency
  type: string
- container: ''
  name: reference
  type: string
- container: ''
  name: returnUrl
  type: string
- container: ''
  name: riskData
  type: string
- container: ''
  name: sdkVersion
  type: string
- container: ''
  name: sessionValidity
  type: string
- container: ''
  name: shopperEmail
  type: string
- container: ''
  name: shopperIP
  type: string
- container: ''
  name: shopperInteraction
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
  name: socialSecurityNumber
  type: string
- container: set
  name: splits
  type: string
- container: ''
  name: store
  type: string
- container: ''
  name: storePaymentMethod
  type: boolean
- container: ''
  name: telephoneNumber
  type: string
- container: ''
  name: threeDSAuthenticationOnly
  type: boolean
- container: ''
  name: token
  type: string
- container: ''
  name: trustedShopper
  type: boolean
- container: ''
  name: paymentSession
  type: string
- container: set
  name: recurringDetails
  type: string
property_count: 58
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-payment-setup-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PaymentSetupRequest\": \"adyen:PaymentSetupRequest\",\n    \"PaymentSetupResponse\": \"adyen:PaymentSetupResponse\",\n    \"additionalAmount\": {\n      \"@id\": \"adyen:additionalAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"additionalData\": {\n      \"@id\": \"adyen:additionalData\",\n      \"@type\": \"@id\"\n    },\n    \"allowedPaymentMethods\": {\n      \"@id\": \"adyen:allowedPaymentMethods\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"adyen:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applicationInfo\": {\n      \"@id\": \"adyen:applicationInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billingAddress\": {\n      \"@id\":\
  \ \"adyen:billingAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"blockedPaymentMethods\": {\n      \"@id\": \"adyen:blockedPaymentMethods\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"captureDelayHours\": {\n      \"@id\": \"adyen:captureDelayHours\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"channel\": {\n      \"@id\": \"adyen:channel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checkoutAttemptId\": {\n      \"@id\": \"adyen:checkoutAttemptId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"company\": {\n      \"@id\": \"adyen:company\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configuration\": {\n      \"@id\": \"adyen:configuration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"conversionId\": {\n      \"@id\": \"adyen:conversionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryCode\": {\n      \"@id\": \"adyen:countryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateOfBirth\": {\n     \
  \ \"@id\": \"adyen:dateOfBirth\",\n      \"@type\": \"xsd:date\"\n    },\n    \"dccQuote\": {\n      \"@id\": \"adyen:dccQuote\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deliveryAddress\": {\n      \"@id\": \"adyen:deliveryAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deliveryDate\": {\n      \"@id\": \"adyen:deliveryDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"enableOneClick\": {\n      \"@id\": \"adyen:enableOneClick\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"enablePayOut\": {\n      \"@id\": \"adyen:enablePayOut\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"enableRecurring\": {\n      \"@id\": \"adyen:enableRecurring\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"entityType\": {\n      \"@id\": \"adyen:entityType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fraudOffset\": {\n      \"@id\": \"adyen:fraudOffset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"installments\": {\n      \"@id\": \"adyen:installments\",\n    \
  \  \"@type\": \"xsd:string\"\n    },\n    \"lineItems\": {\n      \"@id\": \"adyen:lineItems\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"localizedShopperStatement\": {\n      \"@id\": \"adyen:localizedShopperStatement\",\n      \"@type\": \"@id\"\n    },\n    \"mandate\": {\n      \"@id\": \"adyen:mandate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mcc\": {\n      \"@id\": \"adyen:mcc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantAccount\": {\n      \"@id\": \"adyen:merchantAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantOrderReference\": {\n      \"@id\": \"adyen:merchantOrderReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"adyen:metadata\",\n      \"@type\": \"@id\"\n    },\n    \"orderReference\": {\n      \"@id\": \"adyen:orderReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"origin\": {\n      \"@id\": \"adyen:origin\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"platformChargebackLogic\": {\n      \"@id\": \"adyen:platformChargebackLogic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recurringExpiry\": {\n      \"@id\": \"adyen:recurringExpiry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recurringFrequency\": {\n      \"@id\": \"adyen:recurringFrequency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"adyen:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"returnUrl\": {\n      \"@id\": \"adyen:returnUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"riskData\": {\n      \"@id\": \"adyen:riskData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sdkVersion\": {\n      \"@id\": \"adyen:sdkVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionValidity\": {\n      \"@id\": \"adyen:sessionValidity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperEmail\": {\n      \"@id\": \"adyen:shopperEmail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperIP\"\
  : {\n      \"@id\": \"adyen:shopperIP\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperInteraction\": {\n      \"@id\": \"adyen:shopperInteraction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperLocale\": {\n      \"@id\": \"adyen:shopperLocale\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperName\": {\n      \"@id\": \"adyen:shopperName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperReference\": {\n      \"@id\": \"adyen:shopperReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperStatement\": {\n      \"@id\": \"adyen:shopperStatement\",\n      \"@type\": \"xsd:string\"\n    },\n    \"socialSecurityNumber\": {\n      \"@id\": \"adyen:socialSecurityNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"splits\": {\n      \"@id\": \"adyen:splits\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"store\": {\n      \"@id\": \"adyen:store\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storePaymentMethod\"\
  : {\n      \"@id\": \"adyen:storePaymentMethod\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"telephoneNumber\": {\n      \"@id\": \"adyen:telephoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDSAuthenticationOnly\": {\n      \"@id\": \"adyen:threeDSAuthenticationOnly\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"token\": {\n      \"@id\": \"adyen:token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trustedShopper\": {\n      \"@id\": \"adyen:trustedShopper\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"paymentSession\": {\n      \"@id\": \"adyen:paymentSession\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recurringDetails\": {\n      \"@id\": \"adyen:recurringDetails\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-payment-setup-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
