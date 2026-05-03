---
api_specs:
- filename: teller-openapi.yml
  format: yaml
  label: Teller API
  slug: teller-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/teller/refs/heads/main/openapi/teller-openapi.yml
class_count: 2
classes:
- name
- description
context_file: json-ld/teller-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/teller/refs/heads/main/json-ld/teller-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Teller from Teller.
layout: jsonld
name: Teller Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
- prefix: teller
  uri: https://teller.io/vocabulary/
properties:
- container: ''
  name: BankAccount
  type: ''
- container: ''
  name: BankAccountDetails
  type: ''
- container: ''
  name: AccountBalance
  type: ''
- container: ''
  name: BankTransaction
  type: ''
- container: ''
  name: AccountOwner
  type: ''
- container: ''
  name: FinancialInstitution
  type: ''
- container: ''
  name: Enrollment
  type: ''
property_count: 7
provider_name: Teller
provider_slug: teller
slug: teller-context
source_filename: teller-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n    \"teller\": \"https://teller.io/vocabulary/\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"BankAccount\": {\n      \"@id\": \"schema:BankAccount\",\n      \"@context\": {\n        \"accountId\": \"teller:accountId\",\n        \"enrollmentId\": \"teller:enrollmentId\",\n        \"accountType\": \"schema:accountType\",\n        \"lastFour\": \"teller:lastFour\",\n        \"currency\": \"schema:currency\",\n        \"status\": \"teller:accountStatus\",\n        \"institution\": \"teller:institution\"\n      }\n    },\n    \"BankAccountDetails\": {\n      \"@id\": \"teller:BankAccountDetails\",\n      \"@context\": {\n        \"accountNumber\": \"schema:accountId\",\n        \"routingNumbers\": \"teller:routingNumbers\"\n      }\n    },\n    \"AccountBalance\": {\n      \"@id\": \"schema:MonetaryAmount\"\
  ,\n      \"@context\": {\n        \"available\": \"teller:availableBalance\",\n        \"ledger\": \"teller:ledgerBalance\",\n        \"currency\": \"schema:currency\"\n      }\n    },\n    \"BankTransaction\": {\n      \"@id\": \"schema:MoneyTransfer\",\n      \"@context\": {\n        \"transactionId\": \"teller:transactionId\",\n        \"amount\": \"schema:amount\",\n        \"date\": \"schema:validFrom\",\n        \"description\": \"schema:description\",\n        \"status\": \"teller:transactionStatus\",\n        \"transactionType\": \"teller:transactionType\",\n        \"category\": \"teller:category\",\n        \"counterparty\": \"teller:counterparty\"\n      }\n    },\n    \"AccountOwner\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"names\": \"schema:alternateName\",\n        \"addresses\": \"schema:address\",\n        \"phoneNumbers\": \"schema:telephone\",\n        \"emails\": \"schema:email\"\n      }\n    },\n    \"FinancialInstitution\": {\n    \
  \  \"@id\": \"schema:BankOrCreditUnion\",\n      \"@context\": {\n        \"institutionId\": \"teller:institutionId\",\n        \"products\": \"teller:supportedProducts\"\n      }\n    },\n    \"Enrollment\": {\n      \"@id\": \"teller:Enrollment\",\n      \"@context\": {\n        \"enrollmentId\": \"teller:enrollmentId\",\n        \"accessToken\": \"teller:accessToken\",\n        \"institution\": \"teller:institution\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/teller/refs/heads/main/json-ld/teller-context.jsonld
tags:
- Banking
- Financial Data
- FinTech
- Open Banking
- Transactions
- Unified API
- JSON-LD
- Linked Data
- Semantic Web
---
