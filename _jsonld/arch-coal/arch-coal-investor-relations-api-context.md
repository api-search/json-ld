---
class_count: 5
classes:
- ErrorResponse
- ProductionReport
- EarningsReport
- Filing
- FilingList
context_file: json-ld/arch-coal-investor-relations-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/arch-coal/refs/heads/main/json-ld/arch-coal-investor-relations-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Arch Coal Investor Relations Api from Arch Coal.
layout: jsonld
name: Arch Coal Investor Relations Api Context
namespaces:
- prefix: arch
  uri: https://archresources.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: message
  type: string
- container: ''
  name: code
  type: integer
- container: ''
  name: year
  type: integer
- container: ''
  name: quarter
  type: integer
- container: ''
  name: totalTons
  type: integer
- container: ''
  name: metCoalTons
  type: integer
- container: ''
  name: thermalCoalTons
  type: integer
- container: ''
  name: averagePrice
  type: decimal
- container: ''
  name: revenue
  type: integer
- container: ''
  name: ebitda
  type: integer
- container: ''
  name: netIncome
  type: integer
- container: ''
  name: earningsPerShare
  type: decimal
- container: ''
  name: type
  type: string
- container: ''
  name: date
  type: date
- container: ''
  name: title
  type: string
- container: ''
  name: url
  type: string
- container: ''
  name: filings
  type: string
- container: ''
  name: totalCount
  type: integer
property_count: 18
provider_name: Arch Coal
provider_slug: arch-coal
slug: arch-coal-investor-relations-api-context
source_filename: arch-coal-investor-relations-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"arch\": \"https://archresources.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ErrorResponse\": \"arch:ErrorResponse\",\n    \"message\": {\n      \"@id\": \"arch:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"arch:code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ProductionReport\": \"arch:ProductionReport\",\n    \"year\": {\n      \"@id\": \"arch:year\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"quarter\": {\n      \"@id\": \"arch:quarter\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalTons\": {\n      \"@id\": \"arch:totalTons\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"metCoalTons\": {\n      \"@id\": \"arch:metCoalTons\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"thermalCoalTons\": {\n      \"@id\": \"arch:thermalCoalTons\",\n      \"@type\": \"xsd:integer\"\n    },\n   \
  \ \"averagePrice\": {\n      \"@id\": \"arch:averagePrice\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"EarningsReport\": \"arch:EarningsReport\",\n    \"revenue\": {\n      \"@id\": \"arch:revenue\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ebitda\": {\n      \"@id\": \"arch:ebitda\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"netIncome\": {\n      \"@id\": \"arch:netIncome\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"earningsPerShare\": {\n      \"@id\": \"arch:earningsPerShare\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"Filing\": \"arch:Filing\",\n    \"type\": {\n      \"@id\": \"arch:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"date\": {\n      \"@id\": \"arch:date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"title\": {\n      \"@id\": \"arch:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"arch:url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FilingList\": \"arch:FilingList\",\n    \"filings\"\
  : {\n      \"@id\": \"arch:filings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalCount\": {\n      \"@id\": \"arch:totalCount\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/arch-coal/refs/heads/main/json-ld/arch-coal-investor-relations-api-context.jsonld
tags:
- Mining
- Coal
- Metallurgical Coal
- Thermal Coal
- Energy
- Fortune 500
- JSON-LD
- Linked Data
- Semantic Web
---
