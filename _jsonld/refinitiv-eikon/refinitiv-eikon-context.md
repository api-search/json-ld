---
api_specs:
- filename: swagger.yaml
  format: yaml
  label: Refinitiv Data Platform APIs
  slug: ''
  spec_type: OpenAPI
  url: https://api.refinitiv.com/streaming-pricing/docs/swagger.yaml
class_count: 6
classes:
- name
- description
- url
- NewsArticle
- Organization
- currency
context_file: json-ld/refinitiv-eikon-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/refinitiv-eikon/refs/heads/main/json-ld/refinitiv-eikon-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Refinitiv Eikon from Refinitiv Eikon.
layout: jsonld
name: Refinitiv Eikon Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/FND/
- prefix: refinitiv
  uri: https://developers.lseg.com/vocabulary/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: FinancialInstrument
  type: ''
- container: ''
  name: ric
  type: string
- container: ''
  name: permId
  type: string
- container: ''
  name: isin
  type: string
- container: ''
  name: ticker
  type: string
- container: ''
  name: EsgScore
  type: ''
- container: ''
  name: environmentPillarScore
  type: decimal
- container: ''
  name: socialPillarScore
  type: decimal
- container: ''
  name: governancePillarScore
  type: decimal
- container: ''
  name: storyId
  type: string
- container: ''
  name: sourceCode
  type: string
- container: ''
  name: PricingData
  type: ''
- container: ''
  name: lastPrice
  type: decimal
- container: ''
  name: bidPrice
  type: decimal
- container: ''
  name: askPrice
  type: decimal
- container: ''
  name: tradeVolume
  type: integer
- container: ''
  name: Exchange
  type: ''
property_count: 17
provider_name: Refinitiv Eikon
provider_slug: refinitiv-eikon
slug: refinitiv-eikon-context
source_filename: refinitiv-eikon-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/FND/\",\n    \"refinitiv\": \"https://developers.lseg.com/vocabulary/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"FinancialInstrument\": {\n      \"@id\": \"schema:FinancialProduct\",\n      \"description\": \"A financial instrument traded on a market.\"\n    },\n    \"ric\": {\n      \"@id\": \"refinitiv:ric\",\n      \"@type\": \"xsd:string\",\n      \"description\": \"Reuters Instrument Code — primary identifier in the Refinitiv data ecosystem.\"\n    },\n    \"permId\": {\n      \"@id\": \"refinitiv:permId\",\n      \"@type\": \"xsd:string\",\n      \"description\": \"Permanent Identifier (PermID) — globally unique LSEG identifier.\"\n    },\n    \"isin\": {\n      \"@id\": \"schema:identifier\",\n   \
  \   \"@type\": \"xsd:string\",\n      \"description\": \"International Securities Identification Number.\"\n    },\n    \"ticker\": {\n      \"@id\": \"schema:tickerSymbol\",\n      \"@type\": \"xsd:string\",\n      \"description\": \"Exchange ticker symbol.\"\n    },\n    \"EsgScore\": {\n      \"@id\": \"refinitiv:EsgScore\",\n      \"description\": \"Environmental, Social, and Governance score for a company.\"\n    },\n    \"environmentPillarScore\": {\n      \"@id\": \"refinitiv:environmentPillarScore\",\n      \"@type\": \"xsd:decimal\",\n      \"description\": \"Score for environmental performance.\"\n    },\n    \"socialPillarScore\": {\n      \"@id\": \"refinitiv:socialPillarScore\",\n      \"@type\": \"xsd:decimal\",\n      \"description\": \"Score for social performance.\"\n    },\n    \"governancePillarScore\": {\n      \"@id\": \"refinitiv:governancePillarScore\",\n      \"@type\": \"xsd:decimal\",\n      \"description\": \"Score for corporate governance performance.\"\n  \
  \  },\n    \"NewsArticle\": \"schema:NewsArticle\",\n    \"storyId\": {\n      \"@id\": \"refinitiv:storyId\",\n      \"@type\": \"xsd:string\",\n      \"description\": \"Unique identifier for a news story in the Refinitiv news archive.\"\n    },\n    \"sourceCode\": {\n      \"@id\": \"refinitiv:sourceCode\",\n      \"@type\": \"xsd:string\",\n      \"description\": \"Code identifying the news source provider.\"\n    },\n    \"PricingData\": {\n      \"@id\": \"refinitiv:PricingData\",\n      \"description\": \"A point-in-time or historical pricing observation for a financial instrument.\"\n    },\n    \"lastPrice\": {\n      \"@id\": \"refinitiv:lastPrice\",\n      \"@type\": \"xsd:decimal\",\n      \"description\": \"Last traded price.\"\n    },\n    \"bidPrice\": {\n      \"@id\": \"refinitiv:bidPrice\",\n      \"@type\": \"xsd:decimal\",\n      \"description\": \"Best bid price.\"\n    },\n    \"askPrice\": {\n      \"@id\": \"refinitiv:askPrice\",\n      \"@type\": \"xsd:decimal\"\
  ,\n      \"description\": \"Best ask price.\"\n    },\n    \"tradeVolume\": {\n      \"@id\": \"refinitiv:tradeVolume\",\n      \"@type\": \"xsd:integer\",\n      \"description\": \"Accumulated trading volume.\"\n    },\n    \"Exchange\": {\n      \"@id\": \"schema:ExchangeRateSpecification\",\n      \"description\": \"A financial exchange where instruments are traded.\"\n    },\n    \"Organization\": \"schema:Organization\",\n    \"currency\": \"schema:currency\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/refinitiv-eikon/refs/heads/main/json-ld/refinitiv-eikon-context.jsonld
tags:
- Analytics
- Financial Data
- Financial News
- Market Data
- Real-Time Data
- Trading
- JSON-LD
- Linked Data
- Semantic Web
---
