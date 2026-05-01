---
api_specs:
- filename: decentro-kyc-api-openapi.yml
  format: yaml
  label: Decentro KYC & Onboarding API
  slug: kyc-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/decentro/refs/heads/main/openapi/decentro-kyc-api-openapi.yml
- filename: decentro-payments-api-openapi.yml
  format: yaml
  label: Decentro Payments API
  slug: payments-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/decentro/refs/heads/main/openapi/decentro-payments-api-openapi.yml
- filename: decentro-virtual-accounts-api-openapi.yml
  format: yaml
  label: Decentro Virtual Accounts API
  slug: virtual-accounts-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/decentro/refs/heads/main/openapi/decentro-virtual-accounts-api-openapi.yml
- filename: decentro-ledger-api-openapi.yml
  format: yaml
  label: Decentro Ledger API
  slug: ledger-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/decentro/refs/heads/main/openapi/decentro-ledger-api-openapi.yml
class_count: 4
classes:
- VirtualAccount
- Payout
- Mandate
- JournalEntry
context_file: json-ld/decentro-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/decentro/refs/heads/main/json-ld/decentro-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Decentro from Decentro.
layout: jsonld
name: Decentro Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: decentro
  uri: https://schema.decentro.tech/
properties:
- container: ''
  name: account_number
  type: schema:Text
- container: ''
  name: ifsc
  type: schema:Text
- container: ''
  name: balance
  type: schema:Number
- container: ''
  name: amount
  type: schema:Number
- container: ''
  name: currency
  type: schema:Text
- container: ''
  name: status
  type: schema:Text
- container: ''
  name: transfer_type
  type: schema:Text
- container: ''
  name: purpose_message
  type: schema:Text
property_count: 8
provider_name: Decentro
provider_slug: decentro
slug: decentro-context
source_filename: decentro-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.decentro.tech/\",\n    \"schema\": \"https://schema.org/\",\n    \"decentro\": \"https://schema.decentro.tech/\",\n    \"VirtualAccount\": \"decentro:VirtualAccount\",\n    \"Payout\": \"decentro:Payout\",\n    \"Mandate\": \"decentro:Mandate\",\n    \"JournalEntry\": \"decentro:JournalEntry\",\n    \"account_number\": {\"@id\": \"schema:accountId\", \"@type\": \"schema:Text\"},\n    \"ifsc\": {\"@id\": \"decentro:ifsc\", \"@type\": \"schema:Text\"},\n    \"balance\": {\"@id\": \"schema:amount\", \"@type\": \"schema:Number\"},\n    \"amount\": {\"@id\": \"schema:amount\", \"@type\": \"schema:Number\"},\n    \"currency\": {\"@id\": \"schema:priceCurrency\", \"@type\": \"schema:Text\"},\n    \"status\": {\"@id\": \"decentro:status\", \"@type\": \"schema:Text\"},\n    \"transfer_type\": {\"@id\": \"decentro:transferType\", \"@type\": \"schema:Text\"},\n    \"purpose_message\": {\"@id\": \"schema:description\"\
  , \"@type\": \"schema:Text\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/decentro/refs/heads/main/json-ld/decentro-context.jsonld
tags:
- Banking
- Banking-as-a-Service
- FinTech
- India
- KYC
- Ledger
- Payments
- UPI
- Virtual Accounts
- JSON-LD
- Linked Data
- Semantic Web
---
