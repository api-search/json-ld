---
api_specs:
- filename: regions-open-banking-openapi.yml
  format: yaml
  label: Regions Open Banking API
  slug: regions-open-banking-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/regions-financial/refs/heads/main/openapi/regions-open-banking-openapi.yml
class_count: 32
classes:
- id
- type
- BankAccount
- accountId
- accountType
- accountNumber
- nickname
- status
- currency
- BankOrCreditUnion
- transactionId
- transactionDate
- postedDate
- amount
- description
- merchantName
- merchantCategory
- Person
- customerId
- name
- email
- phone
- address
- Payment
- paymentId
- paymentType
- paymentStatus
- consentId
- thirdPartyName
- scopes
- grantedAt
- expiresAt
context_file: json-ld/regions-financial-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/regions-financial/refs/heads/main/json-ld/regions-financial-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Regions Financial from regions-financial.
layout: jsonld
name: Regions Financial Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
- prefix: rgn
  uri: https://api-evangelist.github.io/regions-financial/vocab#
properties:
- container: ''
  name: FinancialTransaction
  type: schema:TransferAction
- container: ''
  name: Consent
  type: schema:AgreeAction
property_count: 2
provider_name: regions-financial
provider_slug: regions-financial
slug: regions-financial-context
source_filename: regions-financial-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n    \"rgn\": \"https://api-evangelist.github.io/regions-financial/vocab#\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"BankAccount\": \"schema:BankAccount\",\n    \"accountId\": \"schema:identifier\",\n    \"accountType\": \"rgn:accountType\",\n    \"accountNumber\": \"schema:accountId\",\n    \"nickname\": \"schema:name\",\n    \"status\": \"schema:status\",\n    \"currency\": \"schema:currency\",\n    \"BankOrCreditUnion\": \"schema:BankOrCreditUnion\",\n    \"FinancialTransaction\": {\n      \"@id\": \"rgn:FinancialTransaction\",\n      \"@type\": \"schema:TransferAction\"\n    },\n    \"transactionId\": \"schema:identifier\",\n    \"transactionDate\": \"schema:startTime\",\n    \"postedDate\": \"schema:endTime\",\n    \"amount\": \"schema:price\",\n    \"description\": \"schema:description\",\n    \"merchantName\"\
  : \"schema:agent\",\n    \"merchantCategory\": \"rgn:merchantCategoryCode\",\n    \"Person\": \"schema:Person\",\n    \"customerId\": \"schema:identifier\",\n    \"name\": \"schema:name\",\n    \"email\": \"schema:email\",\n    \"phone\": \"schema:telephone\",\n    \"address\": \"schema:address\",\n    \"Payment\": \"schema:PayAction\",\n    \"paymentId\": \"schema:identifier\",\n    \"paymentType\": \"rgn:paymentType\",\n    \"paymentStatus\": \"schema:actionStatus\",\n    \"Consent\": {\n      \"@id\": \"rgn:DataSharingConsent\",\n      \"@type\": \"schema:AgreeAction\"\n    },\n    \"consentId\": \"schema:identifier\",\n    \"thirdPartyName\": \"schema:participant\",\n    \"scopes\": \"rgn:dataScopes\",\n    \"grantedAt\": \"schema:startTime\",\n    \"expiresAt\": \"schema:expires\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/regions-financial/refs/heads/main/json-ld/regions-financial-context.jsonld
tags:
- Banking
- Financial Services
- Open Banking
- FDX
- Consumer Banking
- Wealth Management
- Fortune 500
- JSON-LD
- Linked Data
- Semantic Web
---
