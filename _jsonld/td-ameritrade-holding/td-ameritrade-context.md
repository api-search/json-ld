---
api_specs:
- filename: td-ameritrade-accounts-trading-openapi.yml
  format: yaml
  label: TD Ameritrade Accounts and Trading API
  slug: accounts-and-trading
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/td-ameritrade-holding/refs/heads/main/openapi/td-ameritrade-accounts-trading-openapi.yml
class_count: 35
classes:
- BrokerageAccount
- TradeOrder
- SecurityPosition
- MarketQuote
- PriceHistory
- Candle
- OptionChain
- Watchlist
- SecurityInstrument
- Transaction
- MarketMover
- accountId
- orderId
- orderType
- session
- duration
- status
- symbol
- cusip
- bidPrice
- askPrice
- lastPrice
- totalVolume
- openPrice
- closePrice
- highPrice
- lowPrice
- netChange
- quantity
- instruction
- assetType
- enteredTime
- closeTime
- watchlistId
- transactionId
context_file: json-ld/td-ameritrade-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/td-ameritrade-holding/refs/heads/main/json-ld/td-ameritrade-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Td Ameritrade from TD Ameritrade Holding.
layout: jsonld
name: Td Ameritrade Context
namespaces:
- prefix: finra
  uri: https://www.finra.org/vocabulary/
- prefix: tdameritrade
  uri: https://developer.tdameritrade.com/vocabulary/
properties: []
property_count: 0
provider_name: TD Ameritrade Holding
provider_slug: td-ameritrade-holding
slug: td-ameritrade-context
source_filename: td-ameritrade-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"finra\": \"https://www.finra.org/vocabulary/\",\n    \"tdameritrade\": \"https://developer.tdameritrade.com/vocabulary/\",\n    \"BrokerageAccount\": \"finra:BrokerageAccount\",\n    \"TradeOrder\": \"finra:TradeOrder\",\n    \"SecurityPosition\": \"finra:SecurityPosition\",\n    \"MarketQuote\": \"schema:PriceSpecification\",\n    \"PriceHistory\": \"tdameritrade:PriceHistory\",\n    \"Candle\": \"tdameritrade:Candle\",\n    \"OptionChain\": \"tdameritrade:OptionChain\",\n    \"Watchlist\": \"schema:ItemList\",\n    \"SecurityInstrument\": \"finra:SecurityInstrument\",\n    \"Transaction\": \"schema:Order\",\n    \"MarketMover\": \"tdameritrade:MarketMover\",\n    \"accountId\": \"schema:identifier\",\n    \"orderId\": \"schema:orderNumber\",\n    \"orderType\": \"tdameritrade:orderType\",\n    \"session\": \"tdameritrade:tradingSession\",\n    \"duration\": \"tdameritrade:orderDuration\",\n    \"status\"\
  : \"schema:orderStatus\",\n    \"symbol\": \"schema:tickerSymbol\",\n    \"cusip\": \"finra:cusip\",\n    \"bidPrice\": \"schema:bidPrice\",\n    \"askPrice\": \"schema:offeredPrice\",\n    \"lastPrice\": \"schema:price\",\n    \"totalVolume\": \"schema:numberOfItems\",\n    \"openPrice\": \"tdameritrade:openPrice\",\n    \"closePrice\": \"tdameritrade:closePrice\",\n    \"highPrice\": \"tdameritrade:highPrice\",\n    \"lowPrice\": \"tdameritrade:lowPrice\",\n    \"netChange\": \"tdameritrade:netChange\",\n    \"quantity\": \"schema:quantity\",\n    \"instruction\": \"tdameritrade:tradeInstruction\",\n    \"assetType\": \"tdameritrade:assetType\",\n    \"enteredTime\": \"schema:orderDate\",\n    \"closeTime\": \"schema:orderDeliveryDate\",\n    \"watchlistId\": \"schema:identifier\",\n    \"transactionId\": \"schema:identifier\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/td-ameritrade-holding/refs/heads/main/json-ld/td-ameritrade-context.jsonld
tags:
- Finance
- Brokerage
- Trading
- Market Data
- Investment
- Charles Schwab
- Deprecated
- JSON-LD
- Linked Data
- Semantic Web
---
