---
class_count: 8
classes:
- PaymentInstrumentGroupInfo
- PaymentInstrumentGroup
- PaymentInstrumentInfo
- PaymentInstrumentRequirement
- PaymentInstrumentRevealInfo
- PaymentInstrument
- PaymentInstrumentUpdateRequest
- description
context_file: json-ld/adyen-configuration-payment-instrument-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-payment-instrument-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Configuration Payment Instrument from Adyen.
layout: jsonld
name: Adyen Configuration Payment Instrument Context
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
  name: balancePlatform
  type: string
- container: ''
  name: properties
  type: reference
- container: ''
  name: reference
  type: string
- container: ''
  name: txVariant
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: balanceAccountId
  type: string
- container: ''
  name: bankAccount
  type: string
- container: ''
  name: card
  type: string
- container: ''
  name: issuingCountryCode
  type: string
- container: ''
  name: paymentInstrumentGroupId
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: statusReason
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: onlyForCrossBalancePlatform
  type: boolean
- container: ''
  name: paymentInstrumentType
  type: string
- container: ''
  name: cvc
  type: string
- container: ''
  name: expiration
  type: string
- container: ''
  name: pan
  type: string
- container: ''
  name: statusComment
  type: string
property_count: 19
provider_name: Adyen
provider_slug: adyen
slug: adyen-configuration-payment-instrument-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PaymentInstrumentGroupInfo\": \"adyen:PaymentInstrumentGroupInfo\",\n    \"PaymentInstrumentGroup\": \"adyen:PaymentInstrumentGroup\",\n    \"PaymentInstrumentInfo\": \"adyen:PaymentInstrumentInfo\",\n    \"PaymentInstrumentRequirement\": \"adyen:PaymentInstrumentRequirement\",\n    \"PaymentInstrumentRevealInfo\": \"adyen:PaymentInstrumentRevealInfo\",\n    \"PaymentInstrument\": \"adyen:PaymentInstrument\",\n    \"PaymentInstrumentUpdateRequest\": \"adyen:PaymentInstrumentUpdateRequest\",\n    \"balancePlatform\": {\n      \"@id\": \"adyen:balancePlatform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"properties\": {\n      \"@id\": \"adyen:properties\",\n      \"@type\": \"@id\"\
  \n    },\n    \"reference\": {\n      \"@id\": \"adyen:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"txVariant\": {\n      \"@id\": \"adyen:txVariant\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"balanceAccountId\": {\n      \"@id\": \"adyen:balanceAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankAccount\": {\n      \"@id\": \"adyen:bankAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"card\": {\n      \"@id\": \"adyen:card\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuingCountryCode\": {\n      \"@id\": \"adyen:issuingCountryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentInstrumentGroupId\": {\n      \"@id\": \"adyen:paymentInstrumentGroupId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusReason\": {\n      \"@id\": \"adyen:statusReason\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"onlyForCrossBalancePlatform\": {\n      \"@id\": \"adyen:onlyForCrossBalancePlatform\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"paymentInstrumentType\": {\n      \"@id\": \"adyen:paymentInstrumentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cvc\": {\n      \"@id\": \"adyen:cvc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiration\": {\n      \"@id\": \"adyen:expiration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pan\": {\n      \"@id\": \"adyen:pan\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusComment\": {\n      \"@id\": \"adyen:statusComment\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-payment-instrument-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
