---
api_specs:
- filename: microsoft-excel-graph-api.yaml
  format: yaml
  label: Microsoft Graph Excel API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-excel/refs/heads/main/openapi/microsoft-excel-graph-api.yaml
class_count: 9
classes:
- Worksheet
- Table
- TableRow
- TableColumn
- Chart
- Range
- NamedItem
- name
- description
context_file: json-ld/microsoft-excel-graph-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/microsoft-excel/refs/heads/main/json-ld/microsoft-excel-graph-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Microsoft Excel Graph Api from Microsoft Excel.
layout: jsonld
name: Microsoft Excel Graph Api Context
namespaces:
- prefix: ms
  uri: https://graph.microsoft.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: position
  type: integer
- container: ''
  name: visibility
  type: string
- container: ''
  name: showHeaders
  type: boolean
- container: ''
  name: showTotals
  type: boolean
- container: ''
  name: style
  type: string
- container: ''
  name: index
  type: integer
- container: set
  name: values
  type: ''
- container: ''
  name: height
  type: double
- container: ''
  name: width
  type: double
- container: ''
  name: left
  type: double
- container: ''
  name: top
  type: double
- container: ''
  name: address
  type: string
- container: ''
  name: cellCount
  type: integer
- container: ''
  name: columnCount
  type: integer
- container: ''
  name: rowCount
  type: integer
- container: ''
  name: hidden
  type: boolean
- container: ''
  name: visible
  type: boolean
- container: ''
  name: type
  type: string
- container: ''
  name: value
  type: string
property_count: 20
provider_name: Microsoft Excel
provider_slug: microsoft-excel
slug: microsoft-excel-graph-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ms\": \"https://graph.microsoft.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Worksheet\": \"ms:Worksheet\",\n    \"Table\": \"ms:Table\",\n    \"TableRow\": \"ms:TableRow\",\n    \"TableColumn\": \"ms:TableColumn\",\n    \"Chart\": \"ms:Chart\",\n    \"Range\": \"ms:Range\",\n    \"NamedItem\": \"ms:NamedItem\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"id\": { \"@id\": \"ms:id\", \"@type\": \"xsd:string\" },\n    \"position\": { \"@id\": \"ms:position\", \"@type\": \"xsd:integer\" },\n    \"visibility\": { \"@id\": \"ms:visibility\", \"@type\": \"xsd:string\" },\n    \"showHeaders\": { \"@id\": \"ms:showHeaders\", \"@type\": \"xsd:boolean\" },\n    \"showTotals\": { \"@id\": \"ms:showTotals\", \"@type\": \"xsd:boolean\" },\n    \"style\": { \"@id\": \"ms:style\"\
  , \"@type\": \"xsd:string\" },\n    \"index\": { \"@id\": \"ms:index\", \"@type\": \"xsd:integer\" },\n    \"values\": { \"@id\": \"ms:values\", \"@container\": \"@set\" },\n    \"height\": { \"@id\": \"ms:height\", \"@type\": \"xsd:double\" },\n    \"width\": { \"@id\": \"ms:width\", \"@type\": \"xsd:double\" },\n    \"left\": { \"@id\": \"ms:left\", \"@type\": \"xsd:double\" },\n    \"top\": { \"@id\": \"ms:top\", \"@type\": \"xsd:double\" },\n    \"address\": { \"@id\": \"ms:address\", \"@type\": \"xsd:string\" },\n    \"cellCount\": { \"@id\": \"ms:cellCount\", \"@type\": \"xsd:integer\" },\n    \"columnCount\": { \"@id\": \"ms:columnCount\", \"@type\": \"xsd:integer\" },\n    \"rowCount\": { \"@id\": \"ms:rowCount\", \"@type\": \"xsd:integer\" },\n    \"hidden\": { \"@id\": \"ms:hidden\", \"@type\": \"xsd:boolean\" },\n    \"visible\": { \"@id\": \"ms:visible\", \"@type\": \"xsd:boolean\" },\n    \"type\": { \"@id\": \"ms:type\", \"@type\": \"xsd:string\" },\n    \"value\": { \"@id\"\
  : \"ms:value\", \"@type\": \"xsd:string\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/microsoft-excel/refs/heads/main/json-ld/microsoft-excel-graph-api-context.jsonld
tags:
- Automation
- Data Analysis
- Microsoft
- Microsoft 365
- Office
- Spreadsheets
- JSON-LD
- Linked Data
- Semantic Web
---
