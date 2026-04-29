---
api_specs:
- filename: alpha-vantage-openapi.yml
  format: yaml
  label: Alpha Vantage Market Data API
  slug: market-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/alpha-vantage/refs/heads/main/openapi/alpha-vantage-openapi.yml
class_count: 0
classes: []
context_file: json-ld/alpha-vantage-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/alpha-vantage/refs/heads/main/json-ld/alpha-vantage-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Alpha Vantage from Alpha Vantage.
layout: jsonld
name: Alpha Vantage Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/FND/
- prefix: av
  uri: https://www.alphavantage.co/vocab/
properties:
- container: ''
  name: symbol
  type: string
- container: ''
  name: open
  type: decimal
- container: ''
  name: high
  type: decimal
- container: ''
  name: low
  type: decimal
- container: ''
  name: close
  type: decimal
- container: ''
  name: volume
  type: integer
- container: ''
  name: price
  type: decimal
- container: ''
  name: changePercent
  type: string
- container: ''
  name: latestTradingDay
  type: date
- container: ''
  name: previousClose
  type: decimal
- container: ''
  name: Name
  type: string
- container: ''
  name: Description
  type: string
- container: ''
  name: Exchange
  type: string
- container: ''
  name: Currency
  type: string
- container: ''
  name: Country
  type: string
- container: ''
  name: Sector
  type: string
- container: ''
  name: Industry
  type: string
- container: ''
  name: MarketCapitalization
  type: decimal
- container: ''
  name: PERatio
  type: decimal
- container: ''
  name: EPS
  type: decimal
- container: ''
  name: DividendYield
  type: decimal
- container: ''
  name: Beta
  type: decimal
- container: ''
  name: title
  type: string
- container: ''
  name: url
  type: reference
- container: ''
  name: overallSentimentScore
  type: decimal
- container: ''
  name: overallSentimentLabel
  type: string
- container: ''
  name: fromCurrencyCode
  type: string
- container: ''
  name: toCurrencyCode
  type: string
- container: ''
  name: exchangeRate
  type: decimal
- container: ''
  name: date
  type: date
- container: ''
  name: value
  type: decimal
- container: ''
  name: interval
  type: string
- container: ''
  name: unit
  type: string
- container: ''
  name: Note
  type: string
- container: ''
  name: Information
  type: string
property_count: 35
provider_name: Alpha Vantage
provider_slug: alpha-vantage
slug: alpha-vantage-context
source_filename: alpha-vantage-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/FND/\",\n    \"av\": \"https://www.alphavantage.co/vocab/\",\n    \"symbol\": {\"@id\": \"av:tickerSymbol\", \"@type\": \"xsd:string\"},\n    \"open\": {\"@id\": \"av:openPrice\", \"@type\": \"xsd:decimal\"},\n    \"high\": {\"@id\": \"av:highPrice\", \"@type\": \"xsd:decimal\"},\n    \"low\": {\"@id\": \"av:lowPrice\", \"@type\": \"xsd:decimal\"},\n    \"close\": {\"@id\": \"av:closePrice\", \"@type\": \"xsd:decimal\"},\n    \"volume\": {\"@id\": \"av:tradingVolume\", \"@type\": \"xsd:integer\"},\n    \"price\": {\"@id\": \"schema:price\", \"@type\": \"xsd:decimal\"},\n    \"changePercent\": {\"@id\": \"av:changePercent\", \"@type\": \"xsd:string\"},\n    \"latestTradingDay\": {\"@id\": \"av:latestTradingDay\", \"@type\": \"xsd:date\"},\n    \"previousClose\": {\"@id\": \"av:previousClose\"\
  , \"@type\": \"xsd:decimal\"},\n    \"Name\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n    \"Description\": {\"@id\": \"schema:description\", \"@type\": \"xsd:string\"},\n    \"Exchange\": {\"@id\": \"av:stockExchange\", \"@type\": \"xsd:string\"},\n    \"Currency\": {\"@id\": \"schema:currency\", \"@type\": \"xsd:string\"},\n    \"Country\": {\"@id\": \"schema:addressCountry\", \"@type\": \"xsd:string\"},\n    \"Sector\": {\"@id\": \"av:sector\", \"@type\": \"xsd:string\"},\n    \"Industry\": {\"@id\": \"av:industry\", \"@type\": \"xsd:string\"},\n    \"MarketCapitalization\": {\"@id\": \"av:marketCap\", \"@type\": \"xsd:decimal\"},\n    \"PERatio\": {\"@id\": \"av:peRatio\", \"@type\": \"xsd:decimal\"},\n    \"EPS\": {\"@id\": \"av:earningsPerShare\", \"@type\": \"xsd:decimal\"},\n    \"DividendYield\": {\"@id\": \"av:dividendYield\", \"@type\": \"xsd:decimal\"},\n    \"Beta\": {\"@id\": \"av:beta\", \"@type\": \"xsd:decimal\"},\n    \"title\": {\"@id\": \"schema:headline\"\
  , \"@type\": \"xsd:string\"},\n    \"url\": {\"@id\": \"schema:url\", \"@type\": \"@id\"},\n    \"overallSentimentScore\": {\"@id\": \"av:sentimentScore\", \"@type\": \"xsd:decimal\"},\n    \"overallSentimentLabel\": {\"@id\": \"av:sentimentLabel\", \"@type\": \"xsd:string\"},\n    \"fromCurrencyCode\": {\"@id\": \"av:fromCurrency\", \"@type\": \"xsd:string\"},\n    \"toCurrencyCode\": {\"@id\": \"av:toCurrency\", \"@type\": \"xsd:string\"},\n    \"exchangeRate\": {\"@id\": \"schema:price\", \"@type\": \"xsd:decimal\"},\n    \"date\": {\"@id\": \"schema:startDate\", \"@type\": \"xsd:date\"},\n    \"value\": {\"@id\": \"schema:value\", \"@type\": \"xsd:decimal\"},\n    \"interval\": {\"@id\": \"av:reportingInterval\", \"@type\": \"xsd:string\"},\n    \"unit\": {\"@id\": \"schema:unitText\", \"@type\": \"xsd:string\"},\n    \"Note\": {\"@id\": \"av:rateLimitNote\", \"@type\": \"xsd:string\"},\n    \"Information\": {\"@id\": \"av:errorInformation\", \"@type\": \"xsd:string\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/alpha-vantage/refs/heads/main/json-ld/alpha-vantage-context.jsonld
tags:
- Financial
- Market Data
- Stocks
- Technical Indicators
- Economic Data
- Sentiment Analysis
- JSON-LD
- Linked Data
- Semantic Web
---
