---
class_count: 29
classes:
- ElectronicTrading
- FixedIncomeInstrument
- Trade
- Quote
- Order
- PriceData
- TradeReport
- Allocation
- RFQSession
- AiEXExecution
- Organization
- FinancialProduct
- name
- description
- url
- identifier
- tradeId
- assetClass
- instrument
- cusip
- isin
- price
- quantity
- counterpartyId
- executionType
- settlementDate
- tradeDate
- reportingStatus
- mifdiiApplicable
context_file: json-ld/tradeweb-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tradeweb/refs/heads/main/json-ld/tradeweb-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tradeweb from Tradeweb.
layout: jsonld
name: Tradeweb Context
namespaces:
- prefix: tradeweb
  uri: https://www.tradeweb.com/ns/
- prefix: fixp
  uri: https://www.fixtrading.org/ns/
- prefix: finance
  uri: https://schema.org/
properties: []
property_count: 0
provider_name: Tradeweb
provider_slug: tradeweb
slug: tradeweb-context
source_filename: tradeweb-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"tradeweb\": \"https://www.tradeweb.com/ns/\",\n    \"fixp\": \"https://www.fixtrading.org/ns/\",\n    \"finance\": \"https://schema.org/\",\n\n    \"ElectronicTrading\": \"tradeweb:ElectronicTrading\",\n    \"FixedIncomeInstrument\": \"tradeweb:FixedIncomeInstrument\",\n    \"Trade\": \"tradeweb:Trade\",\n    \"Quote\": \"tradeweb:Quote\",\n    \"Order\": \"tradeweb:Order\",\n    \"PriceData\": \"tradeweb:PriceData\",\n    \"TradeReport\": \"tradeweb:TradeReport\",\n    \"Allocation\": \"tradeweb:Allocation\",\n    \"RFQSession\": \"tradeweb:RFQSession\",\n    \"AiEXExecution\": \"tradeweb:AiEXExecution\",\n\n    \"Organization\": \"schema:Organization\",\n    \"FinancialProduct\": \"schema:FinancialProduct\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"identifier\": \"schema:identifier\",\n\n    \"tradeId\": \"tradeweb:tradeId\",\n\
  \    \"assetClass\": \"tradeweb:assetClass\",\n    \"instrument\": \"tradeweb:instrument\",\n    \"cusip\": \"tradeweb:cusip\",\n    \"isin\": \"tradeweb:isin\",\n    \"price\": \"schema:price\",\n    \"quantity\": \"tradeweb:quantity\",\n    \"counterpartyId\": \"tradeweb:counterpartyId\",\n    \"executionType\": \"tradeweb:executionType\",\n    \"settlementDate\": \"tradeweb:settlementDate\",\n    \"tradeDate\": \"tradeweb:tradeDate\",\n    \"reportingStatus\": \"tradeweb:reportingStatus\",\n    \"mifdiiApplicable\": \"tradeweb:mifidiiApplicable\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tradeweb/refs/heads/main/json-ld/tradeweb-context.jsonld
tags:
- Electronic Trading
- Financial Markets
- Fixed Income
- Market Data
- OTC Trading
- JSON-LD
- Linked Data
- Semantic Web
---
