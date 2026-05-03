---
api_specs:
- filename: stonex-payments-openapi.yml
  format: yaml
  label: StoneX Payments API
  slug: stonex-payments
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stonex/refs/heads/main/openapi/stonex-payments-openapi.yml
- filename: stonex-clearing-openapi.yml
  format: yaml
  label: StoneX Clearing API
  slug: stonex-clearing
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stonex/refs/heads/main/openapi/stonex-clearing-openapi.yml
class_count: 25
classes:
- Payment
- ClearingAccount
- Trade
- Position
- Balance
- Beneficiary
- FxRate
- sell_currency
- buy_currency
- exchange_rate
- buy_amount
- payment_reference
- value_date
- bank_code
- account_number
- cash_balance
- margin_used
- margin_available
- unrealized_pnl
- realized_pnl
- name
- status
- currency
- country
- created_at
context_file: json-ld/stonex-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/stonex/refs/heads/main/json-ld/stonex-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Stonex from StoneX.
layout: jsonld
name: Stonex Context
namespaces:
- prefix: stonex
  uri: https://www.stonex.com/vocab#
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
properties: []
property_count: 0
provider_name: StoneX
provider_slug: stonex
slug: stonex-context
source_filename: stonex-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"stonex\": \"https://www.stonex.com/vocab#\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n\n    \"Payment\": \"stonex:Payment\",\n    \"ClearingAccount\": \"stonex:ClearingAccount\",\n    \"Trade\": \"stonex:Trade\",\n    \"Position\": \"stonex:Position\",\n    \"Balance\": \"stonex:Balance\",\n    \"Beneficiary\": \"stonex:Beneficiary\",\n    \"FxRate\": \"stonex:FxRate\",\n\n    \"sell_currency\": \"stonex:sellCurrency\",\n    \"buy_currency\": \"stonex:buyCurrency\",\n    \"exchange_rate\": \"stonex:exchangeRate\",\n    \"buy_amount\": \"stonex:buyAmount\",\n    \"payment_reference\": \"stonex:paymentReference\",\n    \"value_date\": \"stonex:valueDate\",\n    \"bank_code\": \"stonex:bankCode\",\n    \"account_number\": \"stonex:accountNumber\",\n    \"cash_balance\": \"stonex:cashBalance\",\n    \"margin_used\": \"stonex:marginUsed\",\n    \"margin_available\": \"stonex:marginAvailable\"\
  ,\n    \"unrealized_pnl\": \"stonex:unrealizedPnl\",\n    \"realized_pnl\": \"stonex:realizedPnl\",\n\n    \"name\": \"name\",\n    \"status\": \"stonex:status\",\n    \"currency\": \"currency\",\n    \"country\": \"addressCountry\",\n    \"created_at\": \"dateCreated\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/stonex/refs/heads/main/json-ld/stonex-context.jsonld
tags:
- Finance
- Financial Services
- Payments
- Clearing
- Futures
- Trading
- Risk Management
- JSON-LD
- Linked Data
- Semantic Web
---
