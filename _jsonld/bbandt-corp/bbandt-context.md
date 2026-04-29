---
class_count: 0
classes: []
context_file: json-ld/bbandt-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/bbandt-corp/refs/heads/main/json-ld/bbandt-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Bbandt from BB&T Corp (Truist).
layout: jsonld
name: Bbandt Context
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
  name: Transaction
  type: reference
- container: ''
  name: accountId
  type: string
- container: ''
  name: accountType
  type: string
- container: ''
  name: balance
  type: decimal
- container: ''
  name: currency
  type: string
- container: ''
  name: transactionId
  type: string
- container: ''
  name: amount
  type: decimal
- container: ''
  name: transactionDate
  type: dateTime
- container: ''
  name: description
  type: string
- container: ''
  name: category
  type: string
property_count: 11
provider_name: BB&T Corp (Truist)
provider_slug: bbandt-corp
slug: bbandt-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"BankAccount\": {\n      \"@id\": \"fibo:FBC/FinancialInstruments/FinancialInstruments/BankAccount\",\n      \"@type\": \"@id\"\n    },\n    \"Transaction\": {\n      \"@id\": \"schema:MoneyTransfer\",\n      \"@type\": \"@id\"\n    },\n    \"accountId\": {\n      \"@id\": \"fibo:accountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountType\": {\n      \"@id\": \"schema:additionalType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"balance\": {\n      \"@id\": \"schema:amount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"currency\": {\n      \"@id\": \"schema:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transactionId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\"\
  : \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"transactionDate\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"schema:category\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/bbandt-corp/refs/heads/main/json-ld/bbandt-context.jsonld
tags:
- Banking
- Financial Services
- Open Banking
- Truist
- BB&T
- JSON-LD
- Linked Data
- Semantic Web
---
