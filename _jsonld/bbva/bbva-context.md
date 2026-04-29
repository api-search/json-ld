---
class_count: 0
classes: []
context_file: json-ld/bbva-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/bbva/refs/heads/main/json-ld/bbva-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Bbva from BBVA.
layout: jsonld
name: Bbva Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: BankAccount
  type: reference
- container: ''
  name: Payment
  type: reference
- container: ''
  name: accountId
  type: string
- container: ''
  name: iban
  type: string
- container: ''
  name: currency
  type: string
- container: ''
  name: balance
  type: decimal
- container: ''
  name: amount
  type: decimal
- container: ''
  name: paymentReference
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: transactionDate
  type: dateTime
property_count: 10
provider_name: BBVA
provider_slug: bbva
slug: bbva-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"BankAccount\": {\n      \"@id\": \"fibo:FBC/FinancialInstruments/FinancialInstruments/BankAccount\",\n      \"@type\": \"@id\"\n    },\n    \"Payment\": {\n      \"@id\": \"schema:PayAction\",\n      \"@type\": \"@id\"\n    },\n    \"accountId\": {\n      \"@id\": \"fibo:accountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iban\": {\n      \"@id\": \"schema:accountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currency\": {\n      \"@id\": \"schema:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"balance\": {\n      \"@id\": \"schema:amount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"amount\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"paymentReference\": {\n      \"@id\": \"schema:confirmationNumber\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"schema:addressCountry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transactionDate\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/bbva/refs/heads/main/json-ld/bbva-context.jsonld
tags:
- Banking
- Financial Services
- Open Banking
- PSD2
- Spain
- Mexico
- JSON-LD
- Linked Data
- Semantic Web
---
