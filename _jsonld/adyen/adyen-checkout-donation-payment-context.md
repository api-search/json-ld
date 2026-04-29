---
class_count: 2
classes:
- DonationPaymentRequest
- DonationPaymentResponse
context_file: json-ld/adyen-checkout-donation-payment-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-donation-payment-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Donation Payment from Adyen.
layout: jsonld
name: Adyen Checkout Donation Payment Context
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
  name: additionalData
  type: reference
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
- container: ''
  name: browserInfo
  type: string
- container: ''
  name: channel
  type: string
- container: ''
  name: checkoutAttemptId
  type: string
- container: ''
  name: conversionId
  type: string
- container: ''
  name: countryCode
  type: string
- container: ''
  name: dateOfBirth
  type: dateTime
- container: ''
  name: deliverAt
  type: dateTime
- container: ''
  name: deliveryAddress
  type: string
- container: ''
  name: deviceFingerprint
  type: string
- container: ''
  name: donationAccount
  type: string
- container: ''
  name: donationOriginalPspReference
  type: string
- container: ''
  name: donationToken
  type: string
- container: set
  name: lineItems
  type: string
- container: ''
  name: merchantAccount
  type: string
- container: ''
  name: merchantRiskIndicator
  type: string
- container: ''
  name: metadata
  type: reference
- container: ''
  name: mpiData
  type: string
- container: ''
  name: origin
  type: string
- container: ''
  name: paymentMethod
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
  name: socialSecurityNumber
  type: string
- container: ''
  name: telephoneNumber
  type: string
- container: ''
  name: threeDS2RequestData
  type: string
- container: ''
  name: threeDSAuthenticationOnly
  type: boolean
- container: ''
  name: id
  type: string
- container: ''
  name: payment
  type: string
- container: ''
  name: status
  type: string
property_count: 44
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-donation-payment-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DonationPaymentRequest\": \"adyen:DonationPaymentRequest\",\n    \"DonationPaymentResponse\": \"adyen:DonationPaymentResponse\",\n    \"accountInfo\": {\n      \"@id\": \"adyen:accountInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"additionalData\": {\n      \"@id\": \"adyen:additionalData\",\n      \"@type\": \"@id\"\n    },\n    \"amount\": {\n      \"@id\": \"adyen:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applicationInfo\": {\n      \"@id\": \"adyen:applicationInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authenticationData\": {\n      \"@id\": \"adyen:authenticationData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billingAddress\": {\n      \"@id\": \"adyen:billingAddress\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"browserInfo\": {\n      \"@id\": \"adyen:browserInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"channel\": {\n      \"@id\": \"adyen:channel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checkoutAttemptId\": {\n      \"@id\": \"adyen:checkoutAttemptId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"conversionId\": {\n      \"@id\": \"adyen:conversionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryCode\": {\n      \"@id\": \"adyen:countryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateOfBirth\": {\n      \"@id\": \"adyen:dateOfBirth\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"deliverAt\": {\n      \"@id\": \"adyen:deliverAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"deliveryAddress\": {\n      \"@id\": \"adyen:deliveryAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceFingerprint\": {\n      \"@id\": \"adyen:deviceFingerprint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"donationAccount\"\
  : {\n      \"@id\": \"adyen:donationAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"donationOriginalPspReference\": {\n      \"@id\": \"adyen:donationOriginalPspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"donationToken\": {\n      \"@id\": \"adyen:donationToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lineItems\": {\n      \"@id\": \"adyen:lineItems\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantAccount\": {\n      \"@id\": \"adyen:merchantAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantRiskIndicator\": {\n      \"@id\": \"adyen:merchantRiskIndicator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"adyen:metadata\",\n      \"@type\": \"@id\"\n    },\n    \"mpiData\": {\n      \"@id\": \"adyen:mpiData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"origin\": {\n      \"@id\": \"adyen:origin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentMethod\"\
  : {\n      \"@id\": \"adyen:paymentMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recurringProcessingModel\": {\n      \"@id\": \"adyen:recurringProcessingModel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"redirectFromIssuerMethod\": {\n      \"@id\": \"adyen:redirectFromIssuerMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"redirectToIssuerMethod\": {\n      \"@id\": \"adyen:redirectToIssuerMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"adyen:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"returnUrl\": {\n      \"@id\": \"adyen:returnUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionValidity\": {\n      \"@id\": \"adyen:sessionValidity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperEmail\": {\n      \"@id\": \"adyen:shopperEmail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperIP\": {\n      \"@id\": \"adyen:shopperIP\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperInteraction\"\
  : {\n      \"@id\": \"adyen:shopperInteraction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperLocale\": {\n      \"@id\": \"adyen:shopperLocale\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperName\": {\n      \"@id\": \"adyen:shopperName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperReference\": {\n      \"@id\": \"adyen:shopperReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"socialSecurityNumber\": {\n      \"@id\": \"adyen:socialSecurityNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"telephoneNumber\": {\n      \"@id\": \"adyen:telephoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDS2RequestData\": {\n      \"@id\": \"adyen:threeDS2RequestData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDSAuthenticationOnly\": {\n      \"@id\": \"adyen:threeDSAuthenticationOnly\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payment\"\
  : {\n      \"@id\": \"adyen:payment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-donation-payment-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
