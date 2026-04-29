---
class_count: 0
classes: []
context_file: json-ld/binance-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/binance/refs/heads/main/json-ld/binance-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Binance from Binance.
layout: jsonld
name: Binance Context
namespaces:
- prefix: binance
  uri: https://api.binance.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
properties:
- container: ''
  name: TradingPair
  type: ''
- container: ''
  name: Order
  type: ''
- container: ''
  name: Trade
  type: ''
- container: ''
  name: Account
  type: ''
- container: ''
  name: Balance
  type: ''
- container: ''
  name: Kline
  type: ''
- container: ''
  name: PaymentOrder
  type: ''
- container: ''
  name: FuturesPosition
  type: ''
property_count: 8
provider_name: Binance
provider_slug: binance
slug: binance-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"binance\": \"https://api.binance.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n\n    \"TradingPair\": {\n      \"@id\": \"binance:TradingPair\",\n      \"@context\": {\n        \"symbol\": \"binance:symbol\",\n        \"baseAsset\": \"binance:baseAsset\",\n        \"quoteAsset\": \"binance:quoteAsset\",\n        \"status\": \"binance:status\",\n        \"baseAssetPrecision\": {\n          \"@id\": \"binance:baseAssetPrecision\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"quotePrecision\": {\n          \"@id\": \"binance:quotePrecision\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"isSpotTradingAllowed\": {\n          \"@id\": \"binance:isSpotTradingAllowed\",\n          \"@type\": \"xsd:boolean\"\n        },\n    \
  \    \"isMarginTradingAllowed\": {\n          \"@id\": \"binance:isMarginTradingAllowed\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Order\": {\n      \"@id\": \"binance:Order\",\n      \"@context\": {\n        \"orderId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:long\"\n        },\n        \"symbol\": \"binance:symbol\",\n        \"side\": \"binance:side\",\n        \"type\": \"binance:orderType\",\n        \"status\": \"binance:orderStatus\",\n        \"price\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"origQty\": {\n          \"@id\": \"binance:originalQuantity\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"executedQty\": {\n          \"@id\": \"binance:executedQuantity\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"time\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:long\"\n        },\n        \"updateTime\"\
  : {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:long\"\n        },\n        \"timeInForce\": \"binance:timeInForce\",\n        \"clientOrderId\": \"binance:clientOrderId\"\n      }\n    },\n\n    \"Trade\": {\n      \"@id\": \"binance:Trade\",\n      \"@context\": {\n        \"tradeId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:long\"\n        },\n        \"symbol\": \"binance:symbol\",\n        \"price\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"quantity\": {\n          \"@id\": \"binance:quantity\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"commission\": {\n          \"@id\": \"binance:commission\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"commissionAsset\": \"binance:commissionAsset\",\n        \"time\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:long\"\n        },\n        \"isBuyer\": {\n          \"\
  @id\": \"binance:isBuyer\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isMaker\": {\n          \"@id\": \"binance:isMaker\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Account\": {\n      \"@id\": \"binance:Account\",\n      \"@context\": {\n        \"uid\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:long\"\n        },\n        \"accountType\": \"binance:accountType\",\n        \"canTrade\": {\n          \"@id\": \"binance:canTrade\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"canWithdraw\": {\n          \"@id\": \"binance:canWithdraw\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"canDeposit\": {\n          \"@id\": \"binance:canDeposit\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"updateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:long\"\n        },\n        \"balances\": {\n          \"@id\": \"binance:balances\",\n  \
  \        \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Balance\": {\n      \"@id\": \"binance:Balance\",\n      \"@context\": {\n        \"asset\": \"binance:asset\",\n        \"free\": {\n          \"@id\": \"binance:freeBalance\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"locked\": {\n          \"@id\": \"binance:lockedBalance\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"Kline\": {\n      \"@id\": \"binance:Kline\",\n      \"@context\": {\n        \"symbol\": \"binance:symbol\",\n        \"interval\": \"binance:interval\",\n        \"openTime\": {\n          \"@id\": \"binance:openTime\",\n          \"@type\": \"xsd:long\"\n        },\n        \"closeTime\": {\n          \"@id\": \"binance:closeTime\",\n          \"@type\": \"xsd:long\"\n        },\n        \"open\": {\n          \"@id\": \"binance:openPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"high\": {\n          \"@id\": \"binance:highPrice\"\
  ,\n          \"@type\": \"xsd:decimal\"\n        },\n        \"low\": {\n          \"@id\": \"binance:lowPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"close\": {\n          \"@id\": \"binance:closePrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"volume\": {\n          \"@id\": \"binance:volume\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"numberOfTrades\": {\n          \"@id\": \"binance:numberOfTrades\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"PaymentOrder\": {\n      \"@id\": \"binance:PaymentOrder\",\n      \"@context\": {\n        \"merchantTradeNo\": \"binance:merchantTradeNo\",\n        \"prepayId\": {\n          \"@id\": \"schema:identifier\"\n        },\n        \"totalFee\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"currency\": {\n          \"@id\": \"schema:priceCurrency\"\n        },\n        \"orderStatus\": \"binance:orderStatus\"\
  ,\n        \"transactTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:long\"\n        },\n        \"checkoutUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"FuturesPosition\": {\n      \"@id\": \"binance:FuturesPosition\",\n      \"@context\": {\n        \"symbol\": \"binance:symbol\",\n        \"positionAmt\": {\n          \"@id\": \"binance:positionAmount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"entryPrice\": {\n          \"@id\": \"binance:entryPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"markPrice\": {\n          \"@id\": \"binance:markPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"unRealizedProfit\": {\n          \"@id\": \"binance:unrealizedProfit\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"liquidationPrice\": {\n          \"@id\": \"binance:liquidationPrice\",\n          \"@type\": \"xsd:decimal\"\n\
  \        },\n        \"leverage\": {\n          \"@id\": \"binance:leverage\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"marginType\": \"binance:marginType\",\n        \"positionSide\": \"binance:positionSide\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/binance/refs/heads/main/json-ld/binance-context.jsonld
tags:
- Cryptocurrency
- Exchange
- Trading
- Blockchain
- Finance
- DeFi
- Market Data
- JSON-LD
- Linked Data
- Semantic Web
---
