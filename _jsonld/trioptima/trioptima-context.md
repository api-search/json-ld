---
api_specs:
- filename: trioptima-trireduce-api-openapi.yml
  format: yaml
  label: Trioptima triReduce API
  slug: trireduce-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trioptima/refs/heads/main/openapi/trioptima-trireduce-api-openapi.yml
class_count: 16
classes:
- CompressionCycle
- Trade
- RiskData
- DeltaLadder
- CompressionResults
- id
- type
- assetClass
- currency
- status
- description
- tradeId
- counterpartyId
- payReceive
- clearingHouse
- tenor
context_file: json-ld/trioptima-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/trioptima/refs/heads/main/json-ld/trioptima-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Trioptima from Trioptima.
layout: jsonld
name: Trioptima Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
- prefix: trioptima
  uri: https://osttra.com/vocab/trioptima#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: submissionDeadline
  type: dateTime
- container: ''
  name: optimizationDate
  type: date
- container: ''
  name: settlementDate
  type: date
- container: ''
  name: participantCount
  type: integer
- container: ''
  name: notional
  type: double
- container: ''
  name: maturityDate
  type: date
- container: ''
  name: startDate
  type: date
- container: ''
  name: fixedRate
  type: double
- container: ''
  name: originalNotional
  type: double
- container: ''
  name: compressedNotional
  type: double
- container: ''
  name: notionalReduction
  type: double
- container: ''
  name: reductionPercentage
  type: double
- container: ''
  name: tradesTerminated
  type: integer
- container: ''
  name: newTradesCreated
  type: integer
- container: ''
  name: dv01
  type: double
- container: ''
  name: tolerance
  type: double
- container: list
  name: deltaLadder
  type: ''
property_count: 17
provider_name: Trioptima
provider_slug: trioptima
slug: trioptima-context
source_filename: trioptima-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n    \"trioptima\": \"https://osttra.com/vocab/trioptima#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"CompressionCycle\": \"trioptima:CompressionCycle\",\n    \"Trade\": \"trioptima:Trade\",\n    \"RiskData\": \"trioptima:RiskData\",\n    \"DeltaLadder\": \"trioptima:DeltaLadder\",\n    \"CompressionResults\": \"trioptima:CompressionResults\",\n\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n\n    \"assetClass\": \"trioptima:assetClass\",\n    \"currency\": \"fibo:FBC/FinancialInstruments/FinancialInstruments/currency\",\n    \"status\": \"trioptima:cycleStatus\",\n    \"submissionDeadline\": {\n      \"@id\": \"trioptima:submissionDeadline\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"optimizationDate\": {\n      \"@id\": \"trioptima:optimizationDate\",\n      \"@type\": \"xsd:date\"\n    },\n  \
  \  \"settlementDate\": {\n      \"@id\": \"trioptima:settlementDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"participantCount\": {\n      \"@id\": \"trioptima:participantCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"description\": \"schema:description\",\n\n    \"tradeId\": \"trioptima:tradeId\",\n    \"counterpartyId\": \"trioptima:counterpartyId\",\n    \"notional\": {\n      \"@id\": \"trioptima:notional\",\n      \"@type\": \"xsd:double\"\n    },\n    \"maturityDate\": {\n      \"@id\": \"trioptima:maturityDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"startDate\": {\n      \"@id\": \"trioptima:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"fixedRate\": {\n      \"@id\": \"trioptima:fixedRate\",\n      \"@type\": \"xsd:double\"\n    },\n    \"payReceive\": \"trioptima:payReceive\",\n    \"clearingHouse\": \"trioptima:clearingHouse\",\n\n    \"originalNotional\": { \"@id\": \"trioptima:originalNotional\", \"@type\": \"xsd:double\" },\n    \"compressedNotional\"\
  : { \"@id\": \"trioptima:compressedNotional\", \"@type\": \"xsd:double\" },\n    \"notionalReduction\": { \"@id\": \"trioptima:notionalReduction\", \"@type\": \"xsd:double\" },\n    \"reductionPercentage\": { \"@id\": \"trioptima:reductionPercentage\", \"@type\": \"xsd:double\" },\n    \"tradesTerminated\": { \"@id\": \"trioptima:tradesTerminated\", \"@type\": \"xsd:integer\" },\n    \"newTradesCreated\": { \"@id\": \"trioptima:newTradesCreated\", \"@type\": \"xsd:integer\" },\n\n    \"tenor\": \"trioptima:tenor\",\n    \"dv01\": { \"@id\": \"trioptima:dv01\", \"@type\": \"xsd:double\" },\n    \"tolerance\": { \"@id\": \"trioptima:tolerance\", \"@type\": \"xsd:double\" },\n    \"deltaLadder\": {\n      \"@id\": \"trioptima:deltaLadder\",\n      \"@container\": \"@list\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/trioptima/refs/heads/main/json-ld/trioptima-context.jsonld
tags:
- CME Group
- Derivatives
- Financial Services
- OSTTRA
- Portfolio Compression
- Post-Trade Services
- Reconciliation
- Risk Management
- JSON-LD
- Linked Data
- Semantic Web
---
