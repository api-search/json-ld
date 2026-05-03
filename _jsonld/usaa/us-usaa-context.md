---
class_count: 2
classes:
- BankAccount
- Transaction
context_file: json-ld/us-usaa-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/usaa/refs/heads/main/json-ld/us-usaa-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Us Usaa from USAA.
layout: jsonld
name: Us Usaa Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
- prefix: fdx
  uri: https://financialdataexchange.org/vocab/
properties:
- container: ''
  name: accountId
  type: string
- container: ''
  name: accountType
  type: string
- container: ''
  name: institutionName
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: amount
  type: decimal
- container: ''
  name: date
  type: date
- container: ''
  name: merchantName
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: pending
  type: boolean
- container: ''
  name: balances
  type: reference
- container: ''
  name: available
  type: decimal
- container: ''
  name: current
  type: decimal
property_count: 12
provider_name: USAA
provider_slug: usaa
slug: us-usaa-context
source_filename: us-usaa-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n    \"fdx\": \"https://financialdataexchange.org/vocab/\",\n\n    \"BankAccount\": \"fibo:BankAccount\",\n    \"Transaction\": \"schema:ExchangeRateSpecification\",\n\n    \"accountId\": {\n      \"@id\": \"fdx:accountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountType\": {\n      \"@id\": \"fdx:accountType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"institutionName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"date\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:date\"\n    },\n    \"merchantName\": {\n      \"\
  @id\": \"schema:seller\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"fdx:transactionCategory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pending\": {\n      \"@id\": \"fdx:transactionPending\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"balances\": {\n      \"@id\": \"fdx:balances\",\n      \"@type\": \"@id\"\n    },\n    \"available\": {\n      \"@id\": \"fdx:availableBalance\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"current\": {\n      \"@id\": \"fdx:currentBalance\",\n      \"@type\": \"xsd:decimal\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/usaa/refs/heads/main/json-ld/us-usaa-context.jsonld
tags:
- Financial Services
- Banking
- Insurance
- Military Finance
- Open Banking
- Fortune 100
- JSON-LD
- Linked Data
- Semantic Web
---
