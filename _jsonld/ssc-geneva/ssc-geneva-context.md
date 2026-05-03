---
api_specs:
- filename: ssc-geneva-fund-accounting-openapi.yml
  format: yaml
  label: SS&C Geneva Fund Accounting API
  slug: ssc-geneva-fund-accounting
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ssc-geneva/refs/heads/main/openapi/ssc-geneva-fund-accounting-openapi.yml
class_count: 23
classes:
- Portfolio
- Position
- Trade
- Investor
- NAVReport
- portfolioId
- name
- shortName
- fundType
- baseCurrency
- status
- investmentManager
- administrator
- positionId
- isin
- securityName
- assetClass
- quantity
- currency
- weightPercent
- tradeId
- transactionType
- price
context_file: json-ld/ssc-geneva-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ssc-geneva/refs/heads/main/json-ld/ssc-geneva-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ssc Geneva from SS&C Geneva.
layout: jsonld
name: Ssc Geneva Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/FND/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: geneva
  uri: https://www.ssctech.com/vocab/
properties:
- container: ''
  name: inceptionDate
  type: date
- container: ''
  name: aum
  type: decimal
- container: ''
  name: aumDate
  type: date
- container: ''
  name: portfolioId_ref
  type: reference
- container: ''
  name: marketValue
  type: decimal
- container: ''
  name: asOfDate
  type: date
- container: ''
  name: tradeDate
  type: date
- container: ''
  name: settlementDate
  type: date
- container: ''
  name: netAmount
  type: decimal
- container: ''
  name: totalNAV
  type: decimal
- container: ''
  name: navPerUnit
  type: decimal
- container: ''
  name: navDate
  type: date
property_count: 12
provider_name: SS&C Geneva
provider_slug: ssc-geneva
slug: ssc-geneva-context
source_filename: ssc-geneva-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/FND/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"geneva\": \"https://www.ssctech.com/vocab/\",\n\n    \"Portfolio\": \"fibo:InvestmentFund\",\n    \"Position\": \"fibo:HoldingOfSecurities\",\n    \"Trade\": \"fibo:SecuritiesTransaction\",\n    \"Investor\": \"fibo:Investor\",\n    \"NAVReport\": \"geneva:NAVReport\",\n\n    \"portfolioId\": \"schema:identifier\",\n    \"name\": \"schema:name\",\n    \"shortName\": \"schema:alternateName\",\n    \"fundType\": \"schema:additionalType\",\n    \"baseCurrency\": \"schema:currency\",\n    \"inceptionDate\": {\n      \"@id\": \"schema:foundingDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"status\": \"schema:status\",\n    \"investmentManager\": \"schema:organizer\",\n    \"administrator\": \"schema:provider\",\n    \"aum\": {\n      \"@id\": \"geneva:assetsUnderManagement\"\
  ,\n      \"@type\": \"xsd:decimal\"\n    },\n    \"aumDate\": {\n      \"@id\": \"geneva:aumAsOfDate\",\n      \"@type\": \"xsd:date\"\n    },\n\n    \"positionId\": \"schema:identifier\",\n    \"portfolioId_ref\": {\n      \"@id\": \"schema:isPartOf\",\n      \"@type\": \"@id\"\n    },\n    \"isin\": \"schema:identifier\",\n    \"securityName\": \"schema:name\",\n    \"assetClass\": \"schema:additionalType\",\n    \"quantity\": \"schema:value\",\n    \"marketValue\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"currency\": \"schema:currency\",\n    \"asOfDate\": {\n      \"@id\": \"schema:temporalCoverage\",\n      \"@type\": \"xsd:date\"\n    },\n    \"weightPercent\": \"geneva:portfolioWeight\",\n\n    \"tradeId\": \"schema:identifier\",\n    \"tradeDate\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"settlementDate\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"\
  transactionType\": \"schema:additionalType\",\n    \"price\": \"schema:price\",\n    \"netAmount\": {\n      \"@id\": \"schema:totalPrice\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"totalNAV\": {\n      \"@id\": \"geneva:totalNAV\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"navPerUnit\": {\n      \"@id\": \"geneva:navPerUnit\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"navDate\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:date\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ssc-geneva/refs/heads/main/json-ld/ssc-geneva-context.jsonld
tags:
- Fund Accounting
- Asset Management
- Portfolio Management
- Financial Services
- Hedge Funds
- NAV Calculation
- JSON-LD
- Linked Data
- Semantic Web
---
