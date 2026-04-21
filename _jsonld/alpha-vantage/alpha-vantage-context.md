---
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
