---
class_count: 3
classes:
- CreateCheckoutSessionRequest
- CreateCheckoutSessionResponse
- url
context_file: json-ld/adyen-checkout-create-checkout-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-create-checkout-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Create Checkout from Adyen.
layout: jsonld
name: Adyen Checkout Create Checkout Context
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
  name: accountInfo
  type: string
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
  name: authenticationData
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
  name: company
  type: string
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
  name: enableOneClick
  type: boolean
- container: ''
  name: enablePayOut
  type: boolean
- container: ''
  name: enableRecurring
  type: boolean
- container: ''
  name: expiresAt
  type: dateTime
- container: ''
  name: fundOrigin
  type: string
- container: ''
  name: fundRecipient
  type: string
- container: ''
  name: installmentOptions
  type: reference
- container: set
  name: lineItems
  type: string
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
  name: mode
  type: string
- container: ''
  name: mpiData
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
  name: recurringProcessingModel
  type: string
- container: ''
  name: redirectFromIssuerMethod
  type: string
- container: ''
  name: redirectToIssuerMethod
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
  name: showInstallmentAmount
  type: boolean
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
  name: storePaymentMethod
  type: boolean
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
  name: threeDSAuthenticationOnly
  type: boolean
- container: ''
  name: trustedShopper
  type: boolean
- container: ''
  name: id
  type: string
- container: ''
  name: sessionData
  type: string
property_count: 61
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-create-checkout-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CreateCheckoutSessionRequest\": \"adyen:CreateCheckoutSessionRequest\",\n    \"CreateCheckoutSessionResponse\": \"adyen:CreateCheckoutSessionResponse\",\n    \"accountInfo\": {\n      \"@id\": \"adyen:accountInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"additionalAmount\": {\n      \"@id\": \"adyen:additionalAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"additionalData\": {\n      \"@id\": \"adyen:additionalData\",\n      \"@type\": \"@id\"\n    },\n    \"allowedPaymentMethods\": {\n      \"@id\": \"adyen:allowedPaymentMethods\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"adyen:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applicationInfo\"\
  : {\n      \"@id\": \"adyen:applicationInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authenticationData\": {\n      \"@id\": \"adyen:authenticationData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billingAddress\": {\n      \"@id\": \"adyen:billingAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"blockedPaymentMethods\": {\n      \"@id\": \"adyen:blockedPaymentMethods\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"captureDelayHours\": {\n      \"@id\": \"adyen:captureDelayHours\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"channel\": {\n      \"@id\": \"adyen:channel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"company\": {\n      \"@id\": \"adyen:company\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryCode\": {\n      \"@id\": \"adyen:countryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateOfBirth\": {\n      \"@id\": \"adyen:dateOfBirth\",\n      \"@type\": \"xsd:date\"\n    },\n    \"deliverAt\"\
  : {\n      \"@id\": \"adyen:deliverAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"deliveryAddress\": {\n      \"@id\": \"adyen:deliveryAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enableOneClick\": {\n      \"@id\": \"adyen:enableOneClick\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"enablePayOut\": {\n      \"@id\": \"adyen:enablePayOut\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"enableRecurring\": {\n      \"@id\": \"adyen:enableRecurring\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"expiresAt\": {\n      \"@id\": \"adyen:expiresAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"fundOrigin\": {\n      \"@id\": \"adyen:fundOrigin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fundRecipient\": {\n      \"@id\": \"adyen:fundRecipient\",\n      \"@type\": \"xsd:string\"\n    },\n    \"installmentOptions\": {\n      \"@id\": \"adyen:installmentOptions\",\n      \"@type\": \"@id\"\n    },\n    \"lineItems\": {\n      \"@id\": \"adyen:lineItems\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mandate\": {\n      \"@id\": \"adyen:mandate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mcc\": {\n      \"@id\": \"adyen:mcc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantAccount\": {\n      \"@id\": \"adyen:merchantAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantOrderReference\": {\n      \"@id\": \"adyen:merchantOrderReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"adyen:metadata\",\n      \"@type\": \"@id\"\n    },\n    \"mode\": {\n      \"@id\": \"adyen:mode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mpiData\": {\n      \"@id\": \"adyen:mpiData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platformChargebackLogic\": {\n      \"@id\": \"adyen:platformChargebackLogic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recurringExpiry\": {\n      \"@id\": \"adyen:recurringExpiry\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"recurringFrequency\": {\n      \"@id\": \"adyen:recurringFrequency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recurringProcessingModel\": {\n      \"@id\": \"adyen:recurringProcessingModel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"redirectFromIssuerMethod\": {\n      \"@id\": \"adyen:redirectFromIssuerMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"redirectToIssuerMethod\": {\n      \"@id\": \"adyen:redirectToIssuerMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"adyen:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"returnUrl\": {\n      \"@id\": \"adyen:returnUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"riskData\": {\n      \"@id\": \"adyen:riskData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperEmail\": {\n      \"@id\": \"adyen:shopperEmail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperIP\": {\n      \"@id\": \"adyen:shopperIP\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"shopperInteraction\": {\n      \"@id\": \"adyen:shopperInteraction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperLocale\": {\n      \"@id\": \"adyen:shopperLocale\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperName\": {\n      \"@id\": \"adyen:shopperName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperReference\": {\n      \"@id\": \"adyen:shopperReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperStatement\": {\n      \"@id\": \"adyen:shopperStatement\",\n      \"@type\": \"xsd:string\"\n    },\n    \"showInstallmentAmount\": {\n      \"@id\": \"adyen:showInstallmentAmount\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"showRemovePaymentMethodButton\": {\n      \"@id\": \"adyen:showRemovePaymentMethodButton\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"socialSecurityNumber\": {\n      \"@id\": \"adyen:socialSecurityNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"splitCardFundingSources\": {\n      \"\
  @id\": \"adyen:splitCardFundingSources\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"splits\": {\n      \"@id\": \"adyen:splits\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"store\": {\n      \"@id\": \"adyen:store\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storePaymentMethod\": {\n      \"@id\": \"adyen:storePaymentMethod\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"storePaymentMethodMode\": {\n      \"@id\": \"adyen:storePaymentMethodMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"telephoneNumber\": {\n      \"@id\": \"adyen:telephoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"themeId\": {\n      \"@id\": \"adyen:themeId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDSAuthenticationOnly\": {\n      \"@id\": \"adyen:threeDSAuthenticationOnly\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"trustedShopper\": {\n      \"@id\": \"adyen:trustedShopper\",\n      \"@type\": \"xsd:boolean\"\n    },\n\
  \    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionData\": {\n      \"@id\": \"adyen:sessionData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": \"schema:url\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-create-checkout-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
