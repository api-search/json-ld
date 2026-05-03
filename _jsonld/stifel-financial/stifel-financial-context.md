---
class_count: 13
classes:
- FinancialAccount
- InvestmentAccount
- BrokerageAccount
- WealthTracker
- accountNumber
- accountBalance
- holdings
- advisor
- institution
- currency
- name
- description
- url
context_file: json-ld/stifel-financial-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/stifel-financial/refs/heads/main/json-ld/stifel-financial-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Stifel Financial from Stifel Financial.
layout: jsonld
name: Stifel Financial Context
namespaces:
- prefix: stifel
  uri: https://www.stifel.com/vocab#
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
properties: []
property_count: 0
provider_name: Stifel Financial
provider_slug: stifel-financial
slug: stifel-financial-context
source_filename: stifel-financial-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"stifel\": \"https://www.stifel.com/vocab#\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n\n    \"FinancialAccount\": \"BankAccount\",\n    \"InvestmentAccount\": \"stifel:InvestmentAccount\",\n    \"BrokerageAccount\": \"stifel:BrokerageAccount\",\n    \"WealthTracker\": \"stifel:WealthTracker\",\n\n    \"accountNumber\": \"accountNumber\",\n    \"accountBalance\": \"value\",\n    \"holdings\": \"stifel:holdings\",\n    \"advisor\": \"advisor\",\n    \"institution\": \"bankOrCreditUnion\",\n    \"currency\": \"currency\",\n\n    \"name\": \"name\",\n    \"description\": \"description\",\n    \"url\": \"url\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/stifel-financial/refs/heads/main/json-ld/stifel-financial-context.jsonld
tags:
- Finance
- Wealth Management
- Investment Banking
- Open Banking
- Financial Services
- JSON-LD
- Linked Data
- Semantic Web
---
