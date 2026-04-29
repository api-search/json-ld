---
class_count: 2
classes:
- TransferInfo
- description
context_file: json-ld/adyen-transfers-transfer-info-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-transfers-transfer-info-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Transfers Transfer Info from Adyen.
layout: jsonld
name: Adyen Transfers Transfer Info Context
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
  name: balanceAccountId
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: counterparty
  type: string
- container: ''
  name: paymentInstrumentId
  type: string
- container: ''
  name: priority
  type: string
- container: ''
  name: reference
  type: string
- container: ''
  name: referenceForBeneficiary
  type: string
- container: ''
  name: ultimateParty
  type: string
property_count: 9
provider_name: Adyen
provider_slug: adyen
slug: adyen-transfers-transfer-info-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"TransferInfo\": \"adyen:TransferInfo\",\n    \"amount\": {\n      \"@id\": \"adyen:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"balanceAccountId\": {\n      \"@id\": \"adyen:balanceAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"adyen:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"counterparty\": {\n      \"@id\": \"adyen:counterparty\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"paymentInstrumentId\": {\n      \"@id\": \"adyen:paymentInstrumentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"priority\": {\n      \"@id\": \"adyen:priority\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n\
  \      \"@id\": \"adyen:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"referenceForBeneficiary\": {\n      \"@id\": \"adyen:referenceForBeneficiary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ultimateParty\": {\n      \"@id\": \"adyen:ultimateParty\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-transfers-transfer-info-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
