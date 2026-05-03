---
api_specs:
- filename: truelayer-payments-openapi.yml
  format: yaml
  label: TrueLayer Payments API
  slug: payments-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/truelayer/refs/heads/main/openapi/truelayer-payments-openapi.yml
class_count: 25
classes:
- Payment
- Mandate
- Payout
- Refund
- MerchantAccount
- id
- amount_in_minor
- currency
- status
- payment_method
- beneficiary
- user
- name
- email
- phone
- account_identifier
- sort_code
- account_number
- iban
- available_balance_in_minor
- metadata
- reference
- constraints
- type
- resource_token
context_file: json-ld/truelayer-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/truelayer/refs/heads/main/json-ld/truelayer-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Truelayer from TrueLayer.
layout: jsonld
name: Truelayer Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: date_of_birth
  type: date
- container: ''
  name: created_at
  type: dateTime
- container: ''
  name: executed_at
  type: dateTime
- container: ''
  name: settled_at
  type: dateTime
- container: ''
  name: merchant_account_id
  type: reference
property_count: 5
provider_name: TrueLayer
provider_slug: truelayer
slug: truelayer-context
source_filename: truelayer-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.truelayer.com/\",\n    \"schema\": \"https://schema.org/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Payment\": \"schema:PayAction\",\n    \"Mandate\": \"schema:SubscribeAction\",\n    \"Payout\": \"schema:TransferAction\",\n    \"Refund\": \"schema:RefundAction\",\n    \"MerchantAccount\": \"schema:BankAccount\",\n\n    \"id\": \"@id\",\n    \"amount_in_minor\": \"paymentAmountMinorUnits\",\n    \"currency\": \"schema:priceCurrency\",\n    \"status\": \"schema:status\",\n    \"payment_method\": \"schema:paymentMethod\",\n    \"beneficiary\": \"schema:recipient\",\n    \"user\": \"schema:customer\",\n    \"name\": \"schema:name\",\n    \"email\": \"schema:email\",\n    \"phone\": \"schema:telephone\",\n    \"date_of_birth\": {\n      \"@id\": \"schema:birthDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"created_at\": {\n      \"@id\"\
  : \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"executed_at\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"settled_at\": {\n      \"@id\": \"schema:dateReceived\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"account_identifier\": \"schema:bankAccountType\",\n    \"sort_code\": \"bankSortCode\",\n    \"account_number\": \"schema:accountId\",\n    \"iban\": \"bankIBAN\",\n    \"merchant_account_id\": {\n      \"@id\": \"schema:financialProduct\",\n      \"@type\": \"@id\"\n    },\n    \"available_balance_in_minor\": \"accountBalanceMinorUnits\",\n    \"metadata\": \"schema:additionalProperty\",\n    \"reference\": \"schema:paymentStatus\",\n    \"constraints\": \"paymentConstraints\",\n    \"type\": \"schema:additionalType\",\n    \"resource_token\": \"accessToken\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/truelayer/refs/heads/main/json-ld/truelayer-context.jsonld
tags:
- Data API
- Financial Services
- Open Banking
- Payments
- PSD2
- UK Banking
- VRP
- JSON-LD
- Linked Data
- Semantic Web
---
