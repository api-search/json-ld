---
api_specs:
- filename: servicecatalog
  format: yaml
  label: S&P Global Commodity Insights API
  slug: commodity-insights
  spec_type: OpenAPI
  url: https://developer.spglobal.com/commodityinsights/servicecatalog
- filename: s-and-p-global-kensho-link-openapi.yml
  format: yaml
  label: Kensho Link API
  slug: kensho-link
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/s-and-p-global/refs/heads/main/openapi/s-and-p-global-kensho-link-openapi.yml
class_count: 2
classes:
- symbol
- description
context_file: json-ld/s-and-p-global-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/s-and-p-global/refs/heads/main/json-ld/s-and-p-global-context.jsonld
description: JSON-LD context defining the semantic vocabulary for S And P Global from S&P Global.
layout: jsonld
name: S And P Global Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
- prefix: spg
  uri: https://api.spglobal.com/terms/
properties:
- container: ''
  name: MarketDataPoint
  type: reference
- container: ''
  name: assessDate
  type: date
- container: ''
  name: value
  type: decimal
- container: ''
  name: uom
  type: string
- container: ''
  name: currency
  type: string
- container: ''
  name: bate
  type: string
- container: ''
  name: commodityName
  type: string
- container: ''
  name: assessmentFrequency
  type: string
property_count: 8
provider_name: S&P Global
provider_slug: s-and-p-global
slug: s-and-p-global-context
source_filename: s-and-p-global-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n    \"spg\": \"https://api.spglobal.com/terms/\",\n\n    \"MarketDataPoint\": {\n      \"@id\": \"fibo:FinancialInstrument\",\n      \"@type\": \"@id\"\n    },\n    \"symbol\": \"dcterms:identifier\",\n    \"assessDate\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"value\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"uom\": {\n      \"@id\": \"schema:unitText\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currency\": {\n      \"@id\": \"schema:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bate\": {\n      \"@id\": \"spg:priceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"\
  commodityName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assessmentFrequency\": {\n      \"@id\": \"schema:duration\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/s-and-p-global/refs/heads/main/json-ld/s-and-p-global-context.jsonld
tags:
- Financial Data
- Credit Ratings
- Market Intelligence
- Commodity Insights
- Energy Markets
- Capital Markets
- Fortune 500
- JSON-LD
- Linked Data
- Semantic Web
---
