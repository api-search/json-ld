---
class_count: 2
classes:
- Transaction
- description
context_file: json-ld/adyen-funds-transaction-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-funds-transaction-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Funds Transaction from Adyen.
layout: jsonld
name: Adyen Funds Transaction Context
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
  name: amount
  type: string
- container: ''
  name: bankAccountDetail
  type: string
- container: ''
  name: captureMerchantReference
  type: string
- container: ''
  name: capturePspReference
  type: string
- container: ''
  name: creationDate
  type: dateTime
- container: ''
  name: destinationAccountCode
  type: string
- container: ''
  name: disputePspReference
  type: string
- container: ''
  name: disputeReasonCode
  type: string
- container: ''
  name: merchantReference
  type: string
- container: ''
  name: paymentPspReference
  type: string
- container: ''
  name: payoutPspReference
  type: string
- container: ''
  name: pspReference
  type: string
- container: ''
  name: sourceAccountCode
  type: string
- container: ''
  name: transactionStatus
  type: string
- container: ''
  name: transferCode
  type: string
property_count: 15
provider_name: Adyen
provider_slug: adyen
slug: adyen-funds-transaction-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Transaction\": \"adyen:Transaction\",\n    \"amount\": {\n      \"@id\": \"adyen:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankAccountDetail\": {\n      \"@id\": \"adyen:bankAccountDetail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"captureMerchantReference\": {\n      \"@id\": \"adyen:captureMerchantReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"capturePspReference\": {\n      \"@id\": \"adyen:capturePspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationDate\": {\n      \"@id\": \"adyen:creationDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"description\": \"schema:description\",\n    \"destinationAccountCode\": {\n      \"@id\": \"adyen:destinationAccountCode\",\n \
  \     \"@type\": \"xsd:string\"\n    },\n    \"disputePspReference\": {\n      \"@id\": \"adyen:disputePspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"disputeReasonCode\": {\n      \"@id\": \"adyen:disputeReasonCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantReference\": {\n      \"@id\": \"adyen:merchantReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentPspReference\": {\n      \"@id\": \"adyen:paymentPspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payoutPspReference\": {\n      \"@id\": \"adyen:payoutPspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pspReference\": {\n      \"@id\": \"adyen:pspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceAccountCode\": {\n      \"@id\": \"adyen:sourceAccountCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transactionStatus\": {\n      \"@id\": \"adyen:transactionStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transferCode\": {\n     \
  \ \"@id\": \"adyen:transferCode\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-funds-transaction-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
