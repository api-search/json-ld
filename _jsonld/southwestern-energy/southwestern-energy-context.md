---
class_count: 8
classes:
- EnergyCompany
- NaturalGasWell
- GasReserve
- ProductionReport
- ShalePlay
- WellPad
- InvestorRelations
- SECFiling
context_file: json-ld/southwestern-energy-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/southwestern-energy/refs/heads/main/json-ld/southwestern-energy-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Southwestern Energy from Southwestern Energy.
layout: jsonld
name: Southwestern Energy Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: swn
  uri: https://api-evangelist.github.io/southwestern-energy/vocab#
properties:
- container: ''
  name: wellId
  type: string
- container: ''
  name: productionBcf
  type: decimal
- container: ''
  name: productionDate
  type: date
- container: ''
  name: reservesBcf
  type: decimal
- container: ''
  name: shaleFormation
  type: string
- container: ''
  name: wellStatus
  type: string
- container: ''
  name: grossAcreage
  type: decimal
- container: ''
  name: netAcreage
  type: decimal
- container: ''
  name: royaltyInterest
  type: decimal
- container: ''
  name: hedgePercentage
  type: decimal
- container: ''
  name: filingType
  type: string
- container: ''
  name: filingDate
  type: date
- container: ''
  name: expandEnergyTickerSymbol
  type: string
property_count: 13
provider_name: Southwestern Energy
provider_slug: southwestern-energy
slug: southwestern-energy-context
source_filename: southwestern-energy-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"swn\": \"https://api-evangelist.github.io/southwestern-energy/vocab#\",\n\n    \"EnergyCompany\": \"schema:Corporation\",\n    \"NaturalGasWell\": \"schema:Product\",\n    \"GasReserve\": \"schema:QuantitativeValue\",\n    \"ProductionReport\": \"schema:Report\",\n    \"ShalePlay\": \"schema:Place\",\n    \"WellPad\": \"schema:Place\",\n    \"InvestorRelations\": \"schema:WebPage\",\n    \"SECFiling\": \"schema:Report\",\n\n    \"wellId\": {\n      \"@id\": \"swn:wellId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productionBcf\": {\n      \"@id\": \"swn:productionBcf\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"productionDate\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"reservesBcf\": {\n      \"@id\": \"swn:reservesBcf\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"\
  shaleFormation\": {\n      \"@id\": \"swn:shaleFormation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"wellStatus\": {\n      \"@id\": \"swn:wellStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"grossAcreage\": {\n      \"@id\": \"swn:grossAcreage\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"netAcreage\": {\n      \"@id\": \"swn:netAcreage\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"royaltyInterest\": {\n      \"@id\": \"swn:royaltyInterest\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"hedgePercentage\": {\n      \"@id\": \"swn:hedgePercentage\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"filingType\": {\n      \"@id\": \"swn:filingType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filingDate\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:date\"\n    },\n    \"expandEnergyTickerSymbol\": {\n      \"@id\": \"schema:tickerSymbol\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/southwestern-energy/refs/heads/main/json-ld/southwestern-energy-context.jsonld
tags:
- Fortune 500
- Natural Gas
- Energy
- Oil And Gas
- JSON-LD
- Linked Data
- Semantic Web
---
