---
class_count: 2
classes:
- Transfer
- description
context_file: json-ld/adyen-transfers-transfer-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-transfers-transfer-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Transfers Transfer from Adyen.
layout: jsonld
name: Adyen Transfers Transfer Context
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
  name: accountHolder
  type: string
- container: ''
  name: amount
  type: string
- container: ''
  name: balanceAccount
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: categoryData
  type: string
- container: ''
  name: counterparty
  type: string
- container: ''
  name: creationDate
  type: dateTime
- container: ''
  name: direction
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: paymentInstrument
  type: string
- container: ''
  name: reason
  type: string
- container: ''
  name: reference
  type: string
- container: ''
  name: referenceForBeneficiary
  type: string
- container: ''
  name: status
  type: string
property_count: 14
provider_name: Adyen
provider_slug: adyen
slug: adyen-transfers-transfer-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Transfer\": \"adyen:Transfer\",\n    \"accountHolder\": {\n      \"@id\": \"adyen:accountHolder\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"adyen:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"balanceAccount\": {\n      \"@id\": \"adyen:balanceAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"adyen:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"categoryData\": {\n      \"@id\": \"adyen:categoryData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"counterparty\": {\n      \"@id\": \"adyen:counterparty\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationDate\": {\n      \"@id\": \"adyen:creationDate\",\n      \"@type\": \"\
  xsd:dateTime\"\n    },\n    \"description\": \"schema:description\",\n    \"direction\": {\n      \"@id\": \"adyen:direction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentInstrument\": {\n      \"@id\": \"adyen:paymentInstrument\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reason\": {\n      \"@id\": \"adyen:reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"adyen:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"referenceForBeneficiary\": {\n      \"@id\": \"adyen:referenceForBeneficiary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-transfers-transfer-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
