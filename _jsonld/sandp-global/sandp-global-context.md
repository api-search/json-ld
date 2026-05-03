---
api_specs:
- filename: sandp-global-capital-iq-openapi.yml
  format: yaml
  label: S&P Capital IQ API
  slug: sandp-global-capital-iq-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sandp-global/refs/heads/main/openapi/sandp-global-capital-iq-openapi.yml
- filename: sandp-global-commodity-insights-openapi.yml
  format: yaml
  label: S&P Global Commodity Insights API
  slug: sandp-global-commodity-insights-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sandp-global/refs/heads/main/openapi/sandp-global-commodity-insights-openapi.yml
class_count: 0
classes: []
context_file: json-ld/sandp-global-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sandp-global/refs/heads/main/json-ld/sandp-global-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sandp Global from S&P Global.
layout: jsonld
name: Sandp Global Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: spglobal
  uri: https://api-evangelist.github.io/sandp-global/vocab#
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: PriceAssessment
  type: schema:Intangible
- container: ''
  name: FinancialDataRequest
  type: schema:SearchAction
- container: ''
  name: symbol
  type: string
- container: ''
  name: assessDate
  type: date
- container: ''
  name: value
  type: decimal
- container: ''
  name: unit
  type: string
- container: ''
  name: currency
  type: string
- container: ''
  name: mnemonic
  type: string
- container: ''
  name: identifier
  type: string
- container: ''
  name: Commodity
  type: schema:Product
- container: ''
  name: CreditRating
  type: schema:Rating
- container: ''
  name: Company
  type: ''
- container: ''
  name: periodType
  type: string
property_count: 13
provider_name: S&P Global
provider_slug: sandp-global
slug: sandp-global-context
source_filename: sandp-global-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"spglobal\": \"https://api-evangelist.github.io/sandp-global/vocab#\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"PriceAssessment\": {\n      \"@id\": \"spglobal:PriceAssessment\",\n      \"@type\": \"schema:Intangible\",\n      \"schema:description\": \"A benchmark commodity price assessed by S&P Global Commodity Insights editors\"\n    },\n\n    \"FinancialDataRequest\": {\n      \"@id\": \"spglobal:FinancialDataRequest\",\n      \"@type\": \"schema:SearchAction\",\n      \"schema:description\": \"A request to the Capital IQ API for financial or market data\"\n    },\n\n    \"symbol\": {\n      \"@id\": \"spglobal:plattsSymbol\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"assessDate\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:date\"\n    },\n\n    \"value\": {\n    \
  \  \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"unit\": {\n      \"@id\": \"schema:unitText\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"currency\": {\n      \"@id\": \"schema:priceCurrency\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"mnemonic\": {\n      \"@id\": \"spglobal:dataMnemonic\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"identifier\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"Commodity\": {\n      \"@id\": \"spglobal:Commodity\",\n      \"@type\": \"schema:Product\"\n    },\n\n    \"CreditRating\": {\n      \"@id\": \"spglobal:CreditRating\",\n      \"@type\": \"schema:Rating\"\n    },\n\n    \"Company\": {\n      \"@id\": \"schema:Organization\"\n    },\n\n    \"periodType\": {\n      \"@id\": \"spglobal:periodType\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sandp-global/refs/heads/main/json-ld/sandp-global-context.jsonld
tags:
- Financial Data
- Market Intelligence
- Commodity Insights
- Credit Ratings
- Analytics
- Fortune 500
- Enterprise
- JSON-LD
- Linked Data
- Semantic Web
---
