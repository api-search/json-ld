---
api_specs:
- filename: charles-schwab-trader-api-openapi.yml
  format: yaml
  label: Charles Schwab Trader API
  slug: trader-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/charles-schwab/refs/heads/main/openapi/charles-schwab-trader-api-openapi.yml
- filename: charles-schwab-market-data-api-openapi.yml
  format: yaml
  label: Charles Schwab Market Data API
  slug: market-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/charles-schwab/refs/heads/main/openapi/charles-schwab-market-data-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/charles-schwab-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/charles-schwab/refs/heads/main/json-ld/charles-schwab-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Charles Schwab from Charles Schwab.
layout: jsonld
name: Charles Schwab Context
namespaces:
- prefix: schwab
  uri: https://developer.schwab.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Account
  type: ''
- container: ''
  name: Order
  type: ''
- container: ''
  name: Position
  type: ''
- container: ''
  name: Quote
  type: ''
- container: ''
  name: Instrument
  type: ''
property_count: 5
provider_name: Charles Schwab
provider_slug: charles-schwab
slug: charles-schwab-context
source_filename: charles-schwab-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schwab\": \"https://developer.schwab.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Account\": {\n      \"@id\": \"schwab:Account\",\n      \"@context\": {\n        \"accountNumber\": \"schwab:accountNumber\",\n        \"type\": \"schwab:accountType\",\n        \"isDayTrader\": {\n          \"@id\": \"schwab:isDayTrader\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"roundTrips\": {\n          \"@id\": \"schwab:roundTrips\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Order\": {\n      \"@id\": \"schwab:Order\",\n      \"@context\": {\n        \"orderId\": \"schwab:orderId\",\n        \"session\": \"schwab:session\",\n        \"duration\": \"schwab:duration\",\n        \"orderType\": \"schwab:orderType\",\n        \"quantity\": {\n          \"@id\": \"schwab:quantity\"\
  ,\n          \"@type\": \"xsd:decimal\"\n        },\n        \"filledQuantity\": {\n          \"@id\": \"schwab:filledQuantity\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"status\": \"schwab:status\",\n        \"enteredTime\": {\n          \"@id\": \"schwab:enteredTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"closeTime\": {\n          \"@id\": \"schwab:closeTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Position\": {\n      \"@id\": \"schwab:Position\",\n      \"@context\": {\n        \"longQuantity\": {\n          \"@id\": \"schwab:longQuantity\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"shortQuantity\": {\n          \"@id\": \"schwab:shortQuantity\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"marketValue\": {\n          \"@id\": \"schwab:marketValue\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"averagePrice\": {\n          \"@id\": \"schwab:averagePrice\"\
  ,\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"Quote\": {\n      \"@id\": \"schwab:Quote\",\n      \"@context\": {\n        \"symbol\": \"schema:tickerSymbol\",\n        \"bidPrice\": {\n          \"@id\": \"schwab:bidPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"askPrice\": {\n          \"@id\": \"schwab:askPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"lastPrice\": {\n          \"@id\": \"schwab:lastPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"totalVolume\": {\n          \"@id\": \"schwab:totalVolume\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Instrument\": {\n      \"@id\": \"schwab:Instrument\",\n      \"@context\": {\n        \"symbol\": \"schema:tickerSymbol\",\n        \"cusip\": \"schwab:cusip\",\n        \"description\": \"schema:description\",\n        \"assetType\": \"schwab:assetType\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/charles-schwab/refs/heads/main/json-ld/charles-schwab-context.jsonld
tags:
- Accounts
- Banking
- Brokerage
- Financial Services
- Investing
- Market Data
- OAuth 2.0
- Orders
- Trading
- JSON-LD
- Linked Data
- Semantic Web
---
