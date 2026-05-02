---
api_specs:
- filename: level2-strategy-builder-openapi.yml
  format: yaml
  label: Level2 Strategy Builder API
  slug: strategy-builder-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/level2/refs/heads/main/openapi/level2-strategy-builder-openapi.yml
- filename: level2-tradestation-integration-openapi.yml
  format: yaml
  label: Level2 TradeStation Integration API
  slug: tradestation-integration-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/level2/refs/heads/main/openapi/level2-tradestation-integration-openapi.yml
class_count: 0
classes: []
context_file: json-ld/level2-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/level2/refs/heads/main/json-ld/level2-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Level2 from level2.
layout: jsonld
name: Level2 Context
namespaces:
- prefix: level2
  uri: https://trylevel2.com/ns/
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
  name: TradingStrategy
  type: ''
- container: ''
  name: StrategyCondition
  type: ''
- container: ''
  name: BacktestResult
  type: ''
- container: ''
  name: FinancialInstrument
  type: ''
- container: ''
  name: OHLCCandle
  type: ''
- container: ''
  name: CandlestickPattern
  type: ''
- container: ''
  name: BrokerUser
  type: ''
property_count: 7
provider_name: level2
provider_slug: level2
slug: level2-context
source_filename: level2-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"level2\": \"https://trylevel2.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n\n    \"TradingStrategy\": {\n      \"@id\": \"level2:TradingStrategy\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"instrument\": \"level2:instrument\",\n        \"instrumentType\": \"level2:instrumentType\",\n        \"timeframe\": \"level2:timeframe\",\n        \"status\": \"level2:strategyStatus\",\n        \"definition\": \"level2:strategyDefinition\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"deployedAt\"\
  : {\n          \"@id\": \"level2:deployedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"entryConditions\": {\n          \"@id\": \"level2:entryConditions\",\n          \"@container\": \"@set\"\n        },\n        \"exitConditions\": {\n          \"@id\": \"level2:exitConditions\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"StrategyCondition\": {\n      \"@id\": \"level2:StrategyCondition\",\n      \"@context\": {\n        \"indicator\": \"level2:indicator\",\n        \"operator\": \"level2:operator\",\n        \"compareValue\": \"level2:compareValue\",\n        \"logicalOperator\": \"level2:logicalOperator\",\n        \"parameters\": \"level2:conditionParameters\"\n      }\n    },\n\n    \"BacktestResult\": {\n      \"@id\": \"level2:BacktestResult\",\n      \"@context\": {\n        \"strategyId\": {\n          \"@id\": \"level2:strategyReference\",\n          \"@type\": \"@id\"\n        },\n        \"startDate\": {\n          \"@id\"\
  : \"level2:backtestStartDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"endDate\": {\n          \"@id\": \"level2:backtestEndDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"initialCapital\": {\n          \"@id\": \"level2:initialCapital\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"finalCapital\": {\n          \"@id\": \"level2:finalCapital\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"totalReturn\": {\n          \"@id\": \"level2:totalReturn\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"totalTrades\": {\n          \"@id\": \"level2:totalTrades\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"winRate\": {\n          \"@id\": \"level2:winRate\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"maxDrawdown\": {\n          \"@id\": \"level2:maxDrawdown\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"sharpeRatio\": {\n          \"@id\": \"level2:sharpeRatio\"\
  ,\n          \"@type\": \"xsd:decimal\"\n        },\n        \"profitFactor\": {\n          \"@id\": \"level2:profitFactor\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"FinancialInstrument\": {\n      \"@id\": \"level2:FinancialInstrument\",\n      \"@context\": {\n        \"ticker\": \"level2:tickerSymbol\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"sector\": \"level2:sector\",\n        \"industry\": \"level2:industry\",\n        \"exchange\": \"level2:exchange\",\n        \"country\": \"schema:addressCountry\",\n        \"marketCap\": {\n          \"@id\": \"level2:marketCapitalization\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"website\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"OHLCCandle\": {\n      \"@id\": \"level2:OHLCCandle\",\n      \"@context\": {\n        \"timestamp\": {\n          \"@id\": \"dcterms:date\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"open\": {\n          \"@id\": \"level2:openPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"high\": {\n          \"@id\": \"level2:highPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"low\": {\n          \"@id\": \"level2:lowPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"close\": {\n          \"@id\": \"level2:closePrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"volume\": {\n          \"@id\": \"level2:tradingVolume\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"CandlestickPattern\": {\n      \"@id\": \"level2:CandlestickPattern\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"level2:patternSignal\",\n        \"confidence\": {\n          \"@id\": \"level2:confidence\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"BrokerUser\": {\n      \"@id\"\
  : \"level2:BrokerUser\",\n      \"@context\": {\n        \"externalId\": \"level2:externalIdentifier\",\n        \"email\": \"schema:email\",\n        \"displayName\": \"schema:name\",\n        \"status\": \"level2:accountStatus\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/level2/refs/heads/main/json-ld/level2-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
