---
class_count: 1
classes:
- PaymentRequest
context_file: json-ld/adyen-payments-payment-request-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payments-payment-request-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Payments Payment Request from Adyen.
layout: jsonld
name: Adyen Payments Payment Request Context
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
- container: ''
  name: amount
  type: string
- container: ''
  name: applicationInfo
  type: string
- container: ''
  name: bankAccount
  type: string
- container: ''
  name: billingAddress
  type: string
- container: ''
  name: browserInfo
  type: string
- container: ''
  name: captureDelayHours
  type: integer
- container: ''
  name: card
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
  name: deviceFingerprint
  type: string
- container: ''
  name: entityType
  type: string
- container: ''
  name: fraudOffset
  type: integer
- container: ''
  name: fundDestination
  type: string
- container: ''
  name: fundSource
  type: string
- container: ''
  name: fundingSource
  type: string
- container: ''
  name: installments
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
  name: merchantRiskIndicator
  type: string
- container: ''
  name: metadata
  type: reference
- container: ''
  name: mpiData
  type: string
- container: ''
  name: nationality
  type: string
- container: ''
  name: orderReference
  type: string
- container: ''
  name: platformChargebackLogic
  type: string
- container: ''
  name: recurring
  type: string
- container: ''
  name: recurringProcessingModel
  type: string
- container: ''
  name: reference
  type: string
- container: ''
  name: selectedBrand
  type: string
- container: ''
  name: selectedRecurringDetailReference
  type: string
- container: ''
  name: sessionId
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
  name: telephoneNumber
  type: string
- container: ''
  name: threeDS2RequestData
  type: string
- container: ''
  name: threeDSAuthenticationOnly
  type: boolean
- container: ''
  name: totalsGroup
  type: string
- container: ''
  name: trustedShopper
  type: boolean
property_count: 53
provider_name: Adyen
provider_slug: adyen
slug: adyen-payments-payment-request-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PaymentRequest\": \"adyen:PaymentRequest\",\n    \"accountInfo\": {\n      \"@id\": \"adyen:accountInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"additionalAmount\": {\n      \"@id\": \"adyen:additionalAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"additionalData\": {\n      \"@id\": \"adyen:additionalData\",\n      \"@type\": \"@id\"\n    },\n    \"amount\": {\n      \"@id\": \"adyen:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applicationInfo\": {\n      \"@id\": \"adyen:applicationInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankAccount\": {\n      \"@id\": \"adyen:bankAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billingAddress\": {\n      \"@id\": \"adyen:billingAddress\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"browserInfo\": {\n      \"@id\": \"adyen:browserInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"captureDelayHours\": {\n      \"@id\": \"adyen:captureDelayHours\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"card\": {\n      \"@id\": \"adyen:card\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateOfBirth\": {\n      \"@id\": \"adyen:dateOfBirth\",\n      \"@type\": \"xsd:date\"\n    },\n    \"dccQuote\": {\n      \"@id\": \"adyen:dccQuote\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deliveryAddress\": {\n      \"@id\": \"adyen:deliveryAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deliveryDate\": {\n      \"@id\": \"adyen:deliveryDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"deviceFingerprint\": {\n      \"@id\": \"adyen:deviceFingerprint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entityType\": {\n      \"@id\": \"adyen:entityType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  fraudOffset\": {\n      \"@id\": \"adyen:fraudOffset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"fundDestination\": {\n      \"@id\": \"adyen:fundDestination\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fundSource\": {\n      \"@id\": \"adyen:fundSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fundingSource\": {\n      \"@id\": \"adyen:fundingSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"installments\": {\n      \"@id\": \"adyen:installments\",\n      \"@type\": \"xsd:string\"\n    },\n    \"localizedShopperStatement\": {\n      \"@id\": \"adyen:localizedShopperStatement\",\n      \"@type\": \"@id\"\n    },\n    \"mandate\": {\n      \"@id\": \"adyen:mandate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mcc\": {\n      \"@id\": \"adyen:mcc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantAccount\": {\n      \"@id\": \"adyen:merchantAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantOrderReference\": {\n      \"@id\": \"\
  adyen:merchantOrderReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantRiskIndicator\": {\n      \"@id\": \"adyen:merchantRiskIndicator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"adyen:metadata\",\n      \"@type\": \"@id\"\n    },\n    \"mpiData\": {\n      \"@id\": \"adyen:mpiData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nationality\": {\n      \"@id\": \"adyen:nationality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orderReference\": {\n      \"@id\": \"adyen:orderReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platformChargebackLogic\": {\n      \"@id\": \"adyen:platformChargebackLogic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recurring\": {\n      \"@id\": \"adyen:recurring\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recurringProcessingModel\": {\n      \"@id\": \"adyen:recurringProcessingModel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"adyen:reference\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"selectedBrand\": {\n      \"@id\": \"adyen:selectedBrand\",\n      \"@type\": \"xsd:string\"\n    },\n    \"selectedRecurringDetailReference\": {\n      \"@id\": \"adyen:selectedRecurringDetailReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionId\": {\n      \"@id\": \"adyen:sessionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperEmail\": {\n      \"@id\": \"adyen:shopperEmail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperIP\": {\n      \"@id\": \"adyen:shopperIP\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperInteraction\": {\n      \"@id\": \"adyen:shopperInteraction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperLocale\": {\n      \"@id\": \"adyen:shopperLocale\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperName\": {\n      \"@id\": \"adyen:shopperName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperReference\": {\n      \"@id\": \"adyen:shopperReference\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperStatement\": {\n      \"@id\": \"adyen:shopperStatement\",\n      \"@type\": \"xsd:string\"\n    },\n    \"socialSecurityNumber\": {\n      \"@id\": \"adyen:socialSecurityNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"splits\": {\n      \"@id\": \"adyen:splits\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"store\": {\n      \"@id\": \"adyen:store\",\n      \"@type\": \"xsd:string\"\n    },\n    \"telephoneNumber\": {\n      \"@id\": \"adyen:telephoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDS2RequestData\": {\n      \"@id\": \"adyen:threeDS2RequestData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDSAuthenticationOnly\": {\n      \"@id\": \"adyen:threeDSAuthenticationOnly\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"totalsGroup\": {\n      \"@id\": \"adyen:totalsGroup\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trustedShopper\": {\n    \
  \  \"@id\": \"adyen:trustedShopper\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payments-payment-request-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
