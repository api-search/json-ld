---
api_specs:
- filename: truist-personal-small-business-accounts-openapi.yml
  format: yaml
  label: Truist Personal and Small Business Accounts API
  slug: truist-personal-small-business-accounts-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/truist-financial/refs/heads/main/openapi/truist-personal-small-business-accounts-openapi.yml
- filename: truist-personal-small-business-transactions-openapi.yml
  format: yaml
  label: Truist Personal and Small Business Transactions API
  slug: truist-personal-small-business-transactions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/truist-financial/refs/heads/main/openapi/truist-personal-small-business-transactions-openapi.yml
- filename: truist-commercial-accounts-openapi.yml
  format: yaml
  label: Truist Commercial Accounts API
  slug: truist-commercial-accounts-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/truist-financial/refs/heads/main/openapi/truist-commercial-accounts-openapi.yml
- filename: truist-commercial-account-transactions-openapi.yml
  format: yaml
  label: Truist Commercial Account Transactions API
  slug: truist-commercial-account-transactions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/truist-financial/refs/heads/main/openapi/truist-commercial-account-transactions-openapi.yml
class_count: 10
classes:
- Account
- accountId
- accountName
- status
- AccountBalances
- Transaction
- transactionId
- description
- merchantName
- FinancialOrganization
context_file: json-ld/truist-financial-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/truist-financial/refs/heads/main/json-ld/truist-financial-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Truist Financial from Truist Financial.
layout: jsonld
name: Truist Financial Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/FND/
- prefix: truist
  uri: https://developer.truist.com/vocabulary/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: accountNumber
  type: string
- container: ''
  name: accountType
  type: string
- container: ''
  name: routingNumber
  type: string
- container: ''
  name: currency
  type: string
- container: ''
  name: openedDate
  type: date
- container: ''
  name: customerId
  type: string
- container: ''
  name: currentBalance
  type: decimal
- container: ''
  name: availableBalance
  type: decimal
- container: ''
  name: ledgerBalance
  type: decimal
- container: ''
  name: collectedBalance
  type: decimal
- container: ''
  name: asOfDateTime
  type: dateTime
- container: ''
  name: transactionDate
  type: date
- container: ''
  name: postedDate
  type: date
- container: ''
  name: amount
  type: decimal
- container: ''
  name: transactionType
  type: string
- container: ''
  name: merchantCategory
  type: string
- container: ''
  name: bankReferenceNumber
  type: string
- container: ''
  name: checkNumber
  type: string
- container: ''
  name: achTraceNumber
  type: string
- container: ''
  name: wireReferenceNumber
  type: string
- container: ''
  name: runningBalance
  type: decimal
- container: ''
  name: truistFinancial
  type: schema:BankOrPaymentService
property_count: 22
provider_name: Truist Financial
provider_slug: truist-financial
slug: truist-financial-context
source_filename: truist-financial-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/FND/\",\n    \"truist\": \"https://developer.truist.com/vocabulary/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Account\": \"schema:BankAccount\",\n    \"accountId\": \"schema:identifier\",\n    \"accountNumber\": {\n      \"@id\": \"schema:accountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountType\": {\n      \"@id\": \"truist:accountType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountName\": \"schema:name\",\n    \"routingNumber\": {\n      \"@id\": \"truist:routingNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": \"schema:status\",\n    \"currency\": {\n      \"@id\": \"schema:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"openedDate\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"customerId\": {\n      \"@id\"\
  : \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"AccountBalances\": \"truist:AccountBalances\",\n    \"currentBalance\": {\n      \"@id\": \"schema:balance\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"availableBalance\": {\n      \"@id\": \"truist:availableBalance\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"ledgerBalance\": {\n      \"@id\": \"truist:ledgerBalance\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"collectedBalance\": {\n      \"@id\": \"truist:collectedBalance\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"asOfDateTime\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"Transaction\": \"schema:MoneyTransfer\",\n    \"transactionId\": \"schema:identifier\",\n    \"transactionDate\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"postedDate\": {\n      \"@id\": \"truist:postedDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"amount\": {\n\
  \      \"@id\": \"schema:amount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"transactionType\": {\n      \"@id\": \"truist:transactionType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"merchantName\": \"schema:name\",\n    \"merchantCategory\": {\n      \"@id\": \"schema:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankReferenceNumber\": {\n      \"@id\": \"schema:orderNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checkNumber\": {\n      \"@id\": \"truist:checkNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"achTraceNumber\": {\n      \"@id\": \"truist:achTraceNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"wireReferenceNumber\": {\n      \"@id\": \"truist:wireReferenceNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"runningBalance\": {\n      \"@id\": \"truist:runningBalance\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"FinancialOrganization\": \"schema:BankOrPaymentService\"\
  ,\n    \"truistFinancial\": {\n      \"@id\": \"https://www.truist.com\",\n      \"@type\": \"schema:BankOrPaymentService\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/truist-financial/refs/heads/main/json-ld/truist-financial-context.jsonld
tags:
- Banking
- Financial Services
- Open Banking
- Commercial Banking
- Personal Banking
- Payments
- Accounts
- Transactions
- Fortune 500
- JSON-LD
- Linked Data
- Semantic Web
---
