---
api_specs:
- filename: stockdata-openapi.yml
  format: yaml
  label: StockData API
  slug: stockdata
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stockdata/refs/heads/main/openapi/stockdata-openapi.yml
class_count: 39
classes:
- ticker
- price
- day_high
- day_low
- day_open
- 52_week_high
- 52_week_low
- market_cap
- volume
- previous_close_price
- last_trade_time
- is_extended_hours_price
- mic_code
- exchange_short
- sentiment_score
- match_score
- relevance_score
- entity_key
- total_documents
- sentiment_avg
- published_at
- source
- snippet
- image_url
- uuid
- Quote
- OHLCV
- NewsArticle
- NewsEntity
- Entity
- Split
- Dividend
- name
- type
- currency
- country
- language
- industry
- url
context_file: json-ld/stockdata-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/stockdata/refs/heads/main/json-ld/stockdata-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Stockdata from StockData.
layout: jsonld
name: Stockdata Context
namespaces:
- prefix: stockdata
  uri: https://api.stockdata.org/v1/vocab#
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
properties: []
property_count: 0
provider_name: StockData
provider_slug: stockdata
slug: stockdata-context
source_filename: stockdata-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"stockdata\": \"https://api.stockdata.org/v1/vocab#\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n\n    \"ticker\": \"stockdata:ticker\",\n    \"price\": \"stockdata:price\",\n    \"day_high\": \"stockdata:dayHigh\",\n    \"day_low\": \"stockdata:dayLow\",\n    \"day_open\": \"stockdata:dayOpen\",\n    \"52_week_high\": \"stockdata:fiftyTwoWeekHigh\",\n    \"52_week_low\": \"stockdata:fiftyTwoWeekLow\",\n    \"market_cap\": \"stockdata:marketCap\",\n    \"volume\": \"stockdata:volume\",\n    \"previous_close_price\": \"stockdata:previousClosePrice\",\n    \"last_trade_time\": \"stockdata:lastTradeTime\",\n    \"is_extended_hours_price\": \"stockdata:isExtendedHoursPrice\",\n    \"mic_code\": \"stockdata:micCode\",\n    \"exchange_short\": \"stockdata:exchangeShort\",\n\n    \"sentiment_score\": \"stockdata:sentimentScore\",\n    \"match_score\": \"stockdata:matchScore\",\n    \"relevance_score\"\
  : \"stockdata:relevanceScore\",\n    \"entity_key\": \"stockdata:entityKey\",\n    \"total_documents\": \"stockdata:totalDocuments\",\n    \"sentiment_avg\": \"stockdata:sentimentAverage\",\n\n    \"published_at\": \"datePublished\",\n    \"source\": \"publisher\",\n    \"snippet\": \"description\",\n    \"image_url\": \"image\",\n    \"uuid\": \"identifier\",\n\n    \"Quote\": \"stockdata:Quote\",\n    \"OHLCV\": \"stockdata:OHLCV\",\n    \"NewsArticle\": \"Article\",\n    \"NewsEntity\": \"stockdata:NewsEntity\",\n    \"Entity\": \"stockdata:FinancialEntity\",\n    \"Split\": \"stockdata:StockSplit\",\n    \"Dividend\": \"stockdata:Dividend\",\n\n    \"name\": \"name\",\n    \"type\": \"@type\",\n    \"currency\": \"currency\",\n    \"country\": \"countryOfOrigin\",\n    \"language\": \"inLanguage\",\n    \"industry\": \"industry\",\n    \"url\": \"url\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/stockdata/refs/heads/main/json-ld/stockdata-context.jsonld
tags:
- Finance
- Financial Data
- Stock Market
- Market Data
- News
- Sentiment Analysis
- JSON-LD
- Linked Data
- Semantic Web
---
