---
api_specs:
- filename: state-street-alpha-data-platform-openapi.yml
  format: yaml
  label: Alpha Data Platform API
  slug: alpha-data-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/state-street/refs/heads/main/openapi/state-street-alpha-data-platform-openapi.yml
- filename: state-street-fund-connect-openapi.yml
  format: yaml
  label: Fund Connect API
  slug: fund-connect-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/state-street/refs/heads/main/openapi/state-street-fund-connect-openapi.yml
class_count: 15
classes:
- Portfolio
- Position
- Transaction
- Performance
- RiskAnalytics
- ETFOrder
- portfolioName
- portfolioType
- benchmarkId
- custodian
- securityName
- assetClass
- fundId
- ticker
- creationUnit
context_file: json-ld/state-street-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/state-street/refs/heads/main/json-ld/state-street-context.jsonld
description: JSON-LD context defining the semantic vocabulary for State Street from State Street.
layout: jsonld
name: State Street Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
- prefix: statestreet
  uri: https://developer.statestreet.com/ontology/
properties:
- container: ''
  name: portfolioId
  type: schema:Identifier
- container: ''
  name: baseCurrency
  type: schema:Text
- container: ''
  name: inceptionDate
  type: schema:Date
- container: ''
  name: totalMarketValue
  type: schema:MonetaryAmount
- container: ''
  name: securityId
  type: schema:Identifier
- container: ''
  name: quantity
  type: schema:Number
- container: ''
  name: marketValue
  type: schema:MonetaryAmount
- container: ''
  name: price
  type: schema:Number
- container: ''
  name: currency
  type: schema:Text
- container: ''
  name: costBasis
  type: schema:MonetaryAmount
- container: ''
  name: unrealizedGainLoss
  type: schema:Number
- container: ''
  name: weight
  type: schema:Number
- container: ''
  name: tradeDate
  type: schema:Date
- container: ''
  name: settlementDate
  type: schema:Date
- container: ''
  name: netAmount
  type: schema:MonetaryAmount
- container: ''
  name: isin
  type: schema:Identifier
- container: ''
  name: portfolioReturn
  type: schema:Number
- container: ''
  name: benchmarkReturn
  type: schema:Number
- container: ''
  name: activeReturn
  type: schema:Number
- container: ''
  name: trackingError
  type: schema:Number
property_count: 20
provider_name: State Street
provider_slug: state-street
slug: state-street-context
source_filename: state-street-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n    \"statestreet\": \"https://developer.statestreet.com/ontology/\",\n\n    \"Portfolio\": \"fibo:Portfolio\",\n    \"Position\": \"fibo:SecurityPosition\",\n    \"Transaction\": \"fibo:Trade\",\n    \"Performance\": \"fibo:PortfolioPerformance\",\n    \"RiskAnalytics\": \"fibo:RiskMeasure\",\n    \"ETFOrder\": \"fibo:Order\",\n\n    \"portfolioId\": {\n      \"@id\": \"statestreet:portfolioId\",\n      \"@type\": \"schema:Identifier\"\n    },\n    \"portfolioName\": \"schema:name\",\n    \"portfolioType\": \"statestreet:portfolioType\",\n    \"baseCurrency\": {\n      \"@id\": \"schema:currency\",\n      \"@type\": \"schema:Text\"\n    },\n    \"inceptionDate\": {\n      \"@id\": \"schema:foundingDate\",\n      \"@type\": \"schema:Date\"\n    },\n    \"totalMarketValue\": {\n      \"@id\": \"statestreet:totalMarketValue\",\n\
  \      \"@type\": \"schema:MonetaryAmount\"\n    },\n    \"benchmarkId\": \"statestreet:benchmarkId\",\n    \"custodian\": \"schema:provider\",\n    \"securityId\": {\n      \"@id\": \"fibo:hasIdentifier\",\n      \"@type\": \"schema:Identifier\"\n    },\n    \"securityName\": \"schema:name\",\n    \"assetClass\": \"fibo:AssetClass\",\n    \"quantity\": {\n      \"@id\": \"fibo:lotSize\",\n      \"@type\": \"schema:Number\"\n    },\n    \"marketValue\": {\n      \"@id\": \"fibo:marketValue\",\n      \"@type\": \"schema:MonetaryAmount\"\n    },\n    \"price\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"schema:Number\"\n    },\n    \"currency\": {\n      \"@id\": \"schema:priceCurrency\",\n      \"@type\": \"schema:Text\"\n    },\n    \"costBasis\": {\n      \"@id\": \"fibo:costBasis\",\n      \"@type\": \"schema:MonetaryAmount\"\n    },\n    \"unrealizedGainLoss\": {\n      \"@id\": \"fibo:unrealizedGainLoss\",\n      \"@type\": \"schema:Number\"\n    },\n    \"weight\": {\n\
  \      \"@id\": \"fibo:portfolioWeight\",\n      \"@type\": \"schema:Number\"\n    },\n    \"tradeDate\": {\n      \"@id\": \"fibo:tradeDate\",\n      \"@type\": \"schema:Date\"\n    },\n    \"settlementDate\": {\n      \"@id\": \"fibo:settlementDate\",\n      \"@type\": \"schema:Date\"\n    },\n    \"netAmount\": {\n      \"@id\": \"fibo:netAmount\",\n      \"@type\": \"schema:MonetaryAmount\"\n    },\n    \"fundId\": \"statestreet:fundId\",\n    \"ticker\": \"statestreet:ticker\",\n    \"isin\": {\n      \"@id\": \"fibo:ISIN\",\n      \"@type\": \"schema:Identifier\"\n    },\n    \"creationUnit\": \"statestreet:creationUnit\",\n    \"portfolioReturn\": {\n      \"@id\": \"fibo:timeWeightedReturn\",\n      \"@type\": \"schema:Number\"\n    },\n    \"benchmarkReturn\": {\n      \"@id\": \"fibo:benchmarkReturn\",\n      \"@type\": \"schema:Number\"\n    },\n    \"activeReturn\": {\n      \"@id\": \"fibo:activeReturn\",\n      \"@type\": \"schema:Number\"\n    },\n    \"trackingError\":\
  \ {\n      \"@id\": \"fibo:trackingError\",\n      \"@type\": \"schema:Number\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/state-street/refs/heads/main/json-ld/state-street-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
