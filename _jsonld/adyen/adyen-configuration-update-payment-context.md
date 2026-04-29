---
class_count: 2
classes:
- UpdatePaymentInstrument
- description
context_file: json-ld/adyen-configuration-update-payment-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-update-payment-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Configuration Update Payment from Adyen.
layout: jsonld
name: Adyen Configuration Update Payment Context
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
  name: balanceAccountId
  type: string
- container: ''
  name: bankAccount
  type: string
- container: ''
  name: card
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: issuingCountryCode
  type: string
- container: ''
  name: paymentInstrumentGroupId
  type: string
- container: ''
  name: reference
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: statusComment
  type: string
- container: ''
  name: statusReason
  type: string
- container: ''
  name: type
  type: string
property_count: 11
provider_name: Adyen
provider_slug: adyen
slug: adyen-configuration-update-payment-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"UpdatePaymentInstrument\": \"adyen:UpdatePaymentInstrument\",\n    \"balanceAccountId\": {\n      \"@id\": \"adyen:balanceAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankAccount\": {\n      \"@id\": \"adyen:bankAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"card\": {\n      \"@id\": \"adyen:card\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuingCountryCode\": {\n      \"@id\": \"adyen:issuingCountryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentInstrumentGroupId\": {\n      \"@id\": \"adyen:paymentInstrumentGroupId\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"reference\": {\n      \"@id\": \"adyen:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusComment\": {\n      \"@id\": \"adyen:statusComment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusReason\": {\n      \"@id\": \"adyen:statusReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-update-payment-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
