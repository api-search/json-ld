---
class_count: 1
classes:
- BankAccount
context_file: json-ld/adyen-payments-bank-account-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payments-bank-account-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Payments Bank Account from Adyen.
layout: jsonld
name: Adyen Payments Bank Account Context
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
  name: bankAccountNumber
  type: string
- container: ''
  name: bankCity
  type: string
- container: ''
  name: bankLocationId
  type: string
- container: ''
  name: bankName
  type: string
- container: ''
  name: bic
  type: string
- container: ''
  name: countryCode
  type: string
- container: ''
  name: iban
  type: string
- container: ''
  name: ownerName
  type: string
- container: ''
  name: taxId
  type: string
property_count: 9
provider_name: Adyen
provider_slug: adyen
slug: adyen-payments-bank-account-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"BankAccount\": \"adyen:BankAccount\",\n    \"bankAccountNumber\": {\n      \"@id\": \"adyen:bankAccountNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankCity\": {\n      \"@id\": \"adyen:bankCity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankLocationId\": {\n      \"@id\": \"adyen:bankLocationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankName\": {\n      \"@id\": \"adyen:bankName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bic\": {\n      \"@id\": \"adyen:bic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryCode\": {\n      \"@id\": \"adyen:countryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iban\": {\n      \"@id\": \"adyen:iban\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"ownerName\": {\n      \"@id\": \"adyen:ownerName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxId\": {\n      \"@id\": \"adyen:taxId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payments-bank-account-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
