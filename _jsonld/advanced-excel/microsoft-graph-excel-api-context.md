---
api_specs:
- filename: microsoft-graph-excel-api-openapi.yml
  format: yaml
  label: Microsoft Graph Excel API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/advanced-excel/refs/heads/main/openapi/microsoft-graph-excel-api-openapi.yml
class_count: 33
classes:
- Worksheet
- id
- name
- position
- visibility
- WorksheetInput
- WorksheetList
- value
- Range
- address
- values
- formulas
- RangeInput
- Table
- showHeaders
- showTotals
- TableList
- Chart
- chartType
- height
- width
- ChartInput
- type
- sourceData
- seriesBy
- ChartList
- Session
- persistChanges
- SessionInput
- ErrorResponse
- error
- code
- message
context_file: json-ld/microsoft-graph-excel-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/advanced-excel/refs/heads/main/json-ld/microsoft-graph-excel-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Microsoft Graph Excel Api from Advanced Excel.
layout: jsonld
name: Microsoft Graph Excel Api Context
namespaces:
- prefix: excel
  uri: https://graph.microsoft.com/v1.0/vocab/excel#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties: []
property_count: 0
provider_name: Advanced Excel
provider_slug: advanced-excel
slug: microsoft-graph-excel-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"excel\": \"https://graph.microsoft.com/v1.0/vocab/excel#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Worksheet\": \"excel:Worksheet\",\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"position\": \"excel:position\",\n    \"visibility\": \"excel:visibility\",\n    \"WorksheetInput\": \"excel:WorksheetInput\",\n    \"WorksheetList\": \"excel:WorksheetList\",\n    \"value\": \"excel:items\",\n    \"Range\": \"excel:Range\",\n    \"address\": \"excel:address\",\n    \"values\": \"excel:values\",\n    \"formulas\": \"excel:formulas\",\n    \"RangeInput\": \"excel:RangeInput\",\n    \"Table\": \"excel:Table\",\n    \"showHeaders\": \"excel:showHeaders\",\n    \"showTotals\": \"excel:showTotals\",\n    \"TableList\": \"excel:TableList\",\n    \"Chart\": \"excel:Chart\",\n    \"chartType\": \"excel:chartType\",\n    \"height\": \"excel:height\",\n    \"width\"\
  : \"excel:width\",\n    \"ChartInput\": \"excel:ChartInput\",\n    \"type\": \"@type\",\n    \"sourceData\": \"excel:sourceData\",\n    \"seriesBy\": \"excel:seriesBy\",\n    \"ChartList\": \"excel:ChartList\",\n    \"Session\": \"excel:Session\",\n    \"persistChanges\": \"excel:persistChanges\",\n    \"SessionInput\": \"excel:SessionInput\",\n    \"ErrorResponse\": \"excel:ErrorResponse\",\n    \"error\": \"excel:error\",\n    \"code\": \"excel:errorCode\",\n    \"message\": \"schema:description\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/advanced-excel/refs/heads/main/json-ld/microsoft-graph-excel-api-context.jsonld
tags:
- Automation
- Business Intelligence
- Data Analysis
- Data Processing
- Excel
- Microsoft
- Spreadsheets
- JSON-LD
- Linked Data
- Semantic Web
---
