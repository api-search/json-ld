---
api_specs:
- filename: cryptoquant-openapi.yml
  format: yaml
  label: CryptoQuant API
  slug: cryptoquant-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cryptoquant/refs/heads/main/openapi/cryptoquant-openapi.yml
class_count: 8
classes:
- TimeSeriesPoint
- OhlcvPoint
- ExchangeFlow
- MinerFlow
- NetworkIndicator
- window
- exchange
- miner
context_file: json-ld/cryptoquant-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cryptoquant/refs/heads/main/json-ld/cryptoquant-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cryptoquant from CryptoQuant.
layout: jsonld
name: Cryptoquant Context
namespaces:
- prefix: cq
  uri: https://cryptoquant.com/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: date
  type: dateTime
- container: ''
  name: value
  type: double
- container: ''
  name: open
  type: double
- container: ''
  name: high
  type: double
- container: ''
  name: low
  type: double
- container: ''
  name: close
  type: double
- container: ''
  name: volume
  type: double
- container: ''
  name: symbol
  type: ''
property_count: 8
provider_name: CryptoQuant
provider_slug: cryptoquant
slug: cryptoquant-context
source_filename: cryptoquant-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cq\": \"https://cryptoquant.com/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"TimeSeriesPoint\": \"cq:TimeSeriesPoint\",\n    \"OhlcvPoint\": \"cq:OhlcvPoint\",\n    \"ExchangeFlow\": \"cq:ExchangeFlow\",\n    \"MinerFlow\": \"cq:MinerFlow\",\n    \"NetworkIndicator\": \"cq:NetworkIndicator\",\n    \"date\": {\"@id\": \"schema:dateRecorded\", \"@type\": \"xsd:dateTime\"},\n    \"value\": {\"@id\": \"schema:value\", \"@type\": \"xsd:double\"},\n    \"open\": {\"@id\": \"cq:openPrice\", \"@type\": \"xsd:double\"},\n    \"high\": {\"@id\": \"cq:highPrice\", \"@type\": \"xsd:double\"},\n    \"low\": {\"@id\": \"cq:lowPrice\", \"@type\": \"xsd:double\"},\n    \"close\": {\"@id\": \"cq:closePrice\", \"@type\": \"xsd:double\"},\n    \"volume\": {\"@id\": \"cq:tradedVolume\", \"@type\": \"xsd:double\"},\n    \"window\": \"cq:resolution\",\n    \"exchange\": \"cq:exchange\"\
  ,\n    \"miner\": \"cq:miner\",\n    \"symbol\": {\"@id\": \"schema:tickerSymbol\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cryptoquant/refs/heads/main/json-ld/cryptoquant-context.jsonld
tags:
- Blockchain
- Cryptocurrency
- On-Chain Analytics
- Market Data
- Derivatives
- JSON-LD
- Linked Data
- Semantic Web
---
