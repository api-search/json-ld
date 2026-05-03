---
api_specs:
- filename: tradestation-api-openapi.yml
  format: yaml
  label: TradeStation API
  slug: tradestation-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tradestation/refs/heads/main/openapi/tradestation-api-openapi.yml
- filename: tradestation-streaming-asyncapi.yml
  format: yaml
  label: TradeStation Streaming API
  slug: tradestation-streaming
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/tradestation/refs/heads/main/asyncapi/tradestation-streaming-asyncapi.yml
class_count: 0
classes: []
context_file: json-ld/tradestation-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tradestation/refs/heads/main/json-ld/tradestation-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tradestation from TradeStation.
layout: jsonld
name: Tradestation Context
namespaces:
- prefix: ts
  uri: https://api.tradestation.com/vocab/
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
  name: Account
  type: ''
- container: ''
  name: Balance
  type: ''
- container: ''
  name: Position
  type: ''
- container: ''
  name: Order
  type: ''
- container: ''
  name: Quote
  type: ''
- container: ''
  name: Symbol
  type: ''
- container: ''
  name: Bar
  type: ''
- container: ''
  name: Wallet
  type: ''
property_count: 8
provider_name: TradeStation
provider_slug: tradestation
slug: tradestation-context
source_filename: tradestation-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ts\": \"https://api.tradestation.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n\n    \"Account\": {\n      \"@id\": \"ts:Account\",\n      \"@context\": {\n        \"accountId\": \"ts:accountId\",\n        \"accountType\": \"ts:accountType\",\n        \"status\": \"schema:status\",\n        \"statusDescription\": \"schema:description\"\n      }\n    },\n\n    \"Balance\": {\n      \"@id\": \"ts:Balance\",\n      \"@context\": {\n        \"accountId\": \"ts:accountId\",\n        \"cashBalance\": {\n          \"@id\": \"ts:cashBalance\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"equity\": {\n          \"@id\": \"ts:equity\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"marketValue\": {\n          \"@id\": \"ts:marketValue\"\
  ,\n          \"@type\": \"xsd:decimal\"\n        },\n        \"buyingPower\": {\n          \"@id\": \"ts:buyingPower\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"realizedProfitLoss\": {\n          \"@id\": \"ts:realizedProfitLoss\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"unrealizedProfitLoss\": {\n          \"@id\": \"ts:unrealizedProfitLoss\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"Position\": {\n      \"@id\": \"ts:Position\",\n      \"@context\": {\n        \"symbol\": \"schema:tickerSymbol\",\n        \"quantity\": {\n          \"@id\": \"ts:quantity\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"averagePrice\": {\n          \"@id\": \"ts:averagePrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"marketValue\": {\n          \"@id\": \"ts:marketValue\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"unrealizedProfitLoss\": {\n          \"@id\": \"ts:unrealizedProfitLoss\"\
  ,\n          \"@type\": \"xsd:decimal\"\n        },\n        \"assetType\": \"ts:assetType\",\n        \"longShort\": \"ts:longShort\"\n      }\n    },\n\n    \"Order\": {\n      \"@id\": \"ts:Order\",\n      \"@context\": {\n        \"orderId\": \"ts:orderId\",\n        \"accountId\": \"ts:accountId\",\n        \"symbol\": \"schema:tickerSymbol\",\n        \"quantity\": {\n          \"@id\": \"ts:quantity\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"orderType\": \"ts:orderType\",\n        \"tradeAction\": \"ts:tradeAction\",\n        \"status\": \"schema:orderStatus\",\n        \"limitPrice\": {\n          \"@id\": \"ts:limitPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"stopPrice\": {\n          \"@id\": \"ts:stopPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"filledPrice\": {\n          \"@id\": \"ts:filledPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"timeInForce\": \"ts:timeInForce\",\n        \"\
  openedDateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"closedDateTime\": {\n          \"@id\": \"ts:closedDateTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Quote\": {\n      \"@id\": \"ts:Quote\",\n      \"@context\": {\n        \"symbol\": \"schema:tickerSymbol\",\n        \"last\": {\n          \"@id\": \"ts:lastPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"bid\": {\n          \"@id\": \"ts:bidPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"ask\": {\n          \"@id\": \"ts:askPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"volume\": {\n          \"@id\": \"ts:volume\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"open\": {\n          \"@id\": \"ts:openPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"high\": {\n          \"@id\": \"ts:highPrice\",\n          \"@type\": \"xsd:decimal\"\
  \n        },\n        \"low\": {\n          \"@id\": \"ts:lowPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"close\": {\n          \"@id\": \"ts:closePrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"tradeTime\": {\n          \"@id\": \"ts:tradeTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Symbol\": {\n      \"@id\": \"ts:Symbol\",\n      \"@context\": {\n        \"name\": \"schema:tickerSymbol\",\n        \"description\": \"schema:description\",\n        \"exchange\": \"schema:exchange\",\n        \"category\": \"ts:category\",\n        \"currency\": {\n          \"@id\": \"schema:priceCurrency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"country\": \"schema:countryOfOrigin\",\n        \"pointValue\": {\n          \"@id\": \"ts:pointValue\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"minMove\": {\n          \"@id\": \"ts:minMove\",\n          \"@type\": \"xsd:decimal\"\n\
  \        },\n        \"expirationDate\": {\n          \"@id\": \"ts:expirationDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"strikePrice\": {\n          \"@id\": \"ts:strikePrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"optionType\": \"ts:optionType\",\n        \"underlying\": \"ts:underlying\"\n      }\n    },\n\n    \"Bar\": {\n      \"@id\": \"ts:Bar\",\n      \"@context\": {\n        \"open\": {\n          \"@id\": \"ts:openPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"high\": {\n          \"@id\": \"ts:highPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"low\": {\n          \"@id\": \"ts:lowPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"close\": {\n          \"@id\": \"ts:closePrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"volume\": {\n          \"@id\": \"ts:volume\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"timeStamp\": {\n    \
  \      \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Wallet\": {\n      \"@id\": \"ts:Wallet\",\n      \"@context\": {\n        \"currency\": \"schema:priceCurrency\",\n        \"balance\": {\n          \"@id\": \"ts:balance\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"available\": {\n          \"@id\": \"ts:available\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tradestation/refs/heads/main/json-ld/tradestation-context.jsonld
tags:
- Brokerage
- Cryptocurrency
- Finance
- Futures
- Market Data
- Options
- Stocks
- Trading
- JSON-LD
- Linked Data
- Semantic Web
---
