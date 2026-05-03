---
api_specs:
- filename: traiana-harmony-trade-processing-openapi.yml
  format: yaml
  label: Traiana Harmony Trade Processing API
  slug: harmony-trade-processing
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/traiana/refs/heads/main/openapi/traiana-harmony-trade-processing-openapi.yml
- filename: traiana-harmony-creditlink-openapi.yml
  format: yaml
  label: Traiana Harmony CreditLink API
  slug: harmony-creditlink
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/traiana/refs/heads/main/openapi/traiana-harmony-creditlink-openapi.yml
- filename: traiana-harmony-netlink-openapi.yml
  format: yaml
  label: Traiana Harmony NetLink API
  slug: harmony-netlink
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/traiana/refs/heads/main/openapi/traiana-harmony-netlink-openapi.yml
class_count: 22
classes:
- Trade
- Allocation
- GiveUp
- CreditLimit
- NettingSession
- Settlement
- MatchResult
- Breach
- DesignationNotice
- CreditUtilization
- CompressionRun
- tradeId
- externalTradeId
- assetClass
- side
- counterpartyId
- counterpartyName
- executingBrokerId
- primeBrokerId
- clientId
- status
- relationshipType
context_file: json-ld/traiana-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/traiana/refs/heads/main/json-ld/traiana-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Traiana from Traiana.
layout: jsonld
name: Traiana Context
namespaces:
- prefix: traiana
  uri: https://www.cmegroup.com/services/traiana#
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: instrument
  type: reference
- container: ''
  name: quantity
  type: decimal
- container: ''
  name: price
  type: decimal
- container: ''
  name: currency
  type: string
- container: ''
  name: tradeDate
  type: date
- container: ''
  name: settlementDate
  type: date
- container: ''
  name: effectiveDate
  type: date
- container: ''
  name: expiryDate
  type: date
- container: ''
  name: limitAmount
  type: decimal
- container: ''
  name: currentUtilization
  type: decimal
- container: ''
  name: utilizationPercentage
  type: decimal
- container: ''
  name: compressionRatio
  type: decimal
- container: ''
  name: originalTradeCount
  type: integer
- container: ''
  name: nettedTradeCount
  type: integer
- container: ''
  name: payAmount
  type: decimal
- container: ''
  name: receiveAmount
  type: decimal
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
property_count: 18
provider_name: Traiana
provider_slug: traiana
slug: traiana-context
source_filename: traiana-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"traiana\": \"https://www.cmegroup.com/services/traiana#\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n    \"Trade\": \"traiana:Trade\",\n    \"Allocation\": \"traiana:Allocation\",\n    \"GiveUp\": \"traiana:GiveUp\",\n    \"CreditLimit\": \"traiana:CreditLimit\",\n    \"NettingSession\": \"traiana:NettingSession\",\n    \"Settlement\": \"traiana:Settlement\",\n    \"MatchResult\": \"traiana:MatchResult\",\n    \"Breach\": \"traiana:Breach\",\n    \"DesignationNotice\": \"traiana:DesignationNotice\",\n    \"CreditUtilization\": \"traiana:CreditUtilization\",\n    \"CompressionRun\": \"traiana:CompressionRun\",\n    \"tradeId\": \"traiana:tradeId\",\n    \"externalTradeId\": \"traiana:externalTradeId\",\n    \"assetClass\": \"traiana:assetClass\",\n    \"instrument\": {\n      \"@id\": \"traiana:instrument\",\n      \"@type\": \"@id\"\n    },\n    \"side\": \"traiana:side\",\n    \"quantity\"\
  : {\n      \"@id\": \"traiana:quantity\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"price\": {\n      \"@id\": \"traiana:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"currency\": {\n      \"@id\": \"traiana:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"counterpartyId\": \"traiana:counterpartyId\",\n    \"counterpartyName\": \"traiana:counterpartyName\",\n    \"executingBrokerId\": \"traiana:executingBrokerId\",\n    \"primeBrokerId\": \"traiana:primeBrokerId\",\n    \"clientId\": \"traiana:clientId\",\n    \"tradeDate\": {\n      \"@id\": \"traiana:tradeDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"settlementDate\": {\n      \"@id\": \"traiana:settlementDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"effectiveDate\": {\n      \"@id\": \"traiana:effectiveDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"expiryDate\": {\n      \"@id\": \"traiana:expiryDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"status\": \"traiana:status\",\n \
  \   \"limitAmount\": {\n      \"@id\": \"traiana:limitAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"currentUtilization\": {\n      \"@id\": \"traiana:currentUtilization\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"utilizationPercentage\": {\n      \"@id\": \"traiana:utilizationPercentage\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"relationshipType\": \"traiana:relationshipType\",\n    \"compressionRatio\": {\n      \"@id\": \"traiana:compressionRatio\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"originalTradeCount\": {\n      \"@id\": \"traiana:originalTradeCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"nettedTradeCount\": {\n      \"@id\": \"traiana:nettedTradeCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"payAmount\": {\n      \"@id\": \"traiana:payAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"receiveAmount\": {\n      \"@id\": \"traiana:receiveAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"createdAt\":\
  \ {\n      \"@id\": \"traiana:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"traiana:updatedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/traiana/refs/heads/main/json-ld/traiana-context.jsonld
tags:
- Fintech
- Foreign Exchange
- Post-Trade Processing
- Risk Management
- JSON-LD
- Linked Data
- Semantic Web
---
