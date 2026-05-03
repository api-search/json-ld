---
api_specs:
- filename: stitch-openapi.yml
  format: yaml
  label: Stitch GraphQL API
  slug: stitch-graphql
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stitch/refs/heads/main/openapi/stitch-openapi.yml
class_count: 20
classes:
- PaymentInitiationRequest
- BankAccount
- Transaction
- Disbursement
- MoneyAmount
- payerReference
- beneficiaryReference
- beneficiaryAccountNumber
- beneficiaryBankId
- bankId
- accountNumber
- availableBalance
- currentBalance
- quantity
- currency
- status
- url
- name
- id
- created
context_file: json-ld/stitch-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/stitch/refs/heads/main/json-ld/stitch-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Stitch from Stitch.
layout: jsonld
name: Stitch Context
namespaces:
- prefix: stitch
  uri: https://api.stitch.money/vocab#
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
properties: []
property_count: 0
provider_name: Stitch
provider_slug: stitch
slug: stitch-context
source_filename: stitch-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"stitch\": \"https://api.stitch.money/vocab#\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n\n    \"PaymentInitiationRequest\": \"stitch:PaymentInitiationRequest\",\n    \"BankAccount\": \"BankAccount\",\n    \"Transaction\": \"stitch:Transaction\",\n    \"Disbursement\": \"stitch:Disbursement\",\n    \"MoneyAmount\": \"MonetaryAmount\",\n\n    \"payerReference\": \"stitch:payerReference\",\n    \"beneficiaryReference\": \"stitch:beneficiaryReference\",\n    \"beneficiaryAccountNumber\": \"stitch:beneficiaryAccountNumber\",\n    \"beneficiaryBankId\": \"stitch:beneficiaryBankId\",\n    \"bankId\": \"stitch:bankId\",\n    \"accountNumber\": \"stitch:accountNumber\",\n    \"availableBalance\": \"stitch:availableBalance\",\n    \"currentBalance\": \"stitch:currentBalance\",\n    \"quantity\": \"value\",\n    \"currency\": \"currency\",\n\n    \"status\": \"stitch:status\",\n    \"url\": \"\
  url\",\n    \"name\": \"name\",\n    \"id\": \"@id\",\n    \"created\": \"dateCreated\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/stitch/refs/heads/main/json-ld/stitch-context.jsonld
tags:
- Africa
- Financial Data
- Open Banking
- Payments
- Unified API
- South Africa
- Nigeria
- JSON-LD
- Linked Data
- Semantic Web
---
