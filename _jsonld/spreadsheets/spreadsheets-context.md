---
api_specs:
- filename: google-sheets-openapi.yml
  format: yaml
  label: Google Sheets API
  slug: google-sheets-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spreadsheets/refs/heads/main/openapi/google-sheets-openapi.yml
class_count: 32
classes:
- Spreadsheet
- Workbook
- Sheet
- Worksheet
- Range
- CellRange
- Table
- Chart
- spreadsheetId
- workbookId
- spreadsheetUrl
- title
- locale
- timeZone
- sheetId
- sheetType
- hidden
- index
- range
- majorDimension
- values
- rowCount
- columnCount
- frozenRowCount
- frozenColumnCount
- valueInputOption
- valueRenderOption
- session
- persistChanges
- address
- formulas
- numberFormat
context_file: json-ld/spreadsheets-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/spreadsheets/refs/heads/main/json-ld/spreadsheets-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Spreadsheets from Spreadsheets.
layout: jsonld
name: Spreadsheets Context
namespaces:
- prefix: sheets
  uri: https://developers.google.com/workspace/sheets/vocab#
- prefix: excel
  uri: https://learn.microsoft.com/graph/excel/vocab#
properties:
- container: ''
  name: A1Notation
  type: reference
property_count: 1
provider_name: Spreadsheets
provider_slug: spreadsheets
slug: spreadsheets-context
source_filename: spreadsheets-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"sheets\": \"https://developers.google.com/workspace/sheets/vocab#\",\n    \"excel\": \"https://learn.microsoft.com/graph/excel/vocab#\",\n    \"Spreadsheet\": \"sheets:Spreadsheet\",\n    \"Workbook\": \"excel:Workbook\",\n    \"Sheet\": \"sheets:Sheet\",\n    \"Worksheet\": \"excel:Worksheet\",\n    \"Range\": \"sheets:Range\",\n    \"CellRange\": \"excel:Range\",\n    \"Table\": \"excel:Table\",\n    \"Chart\": \"excel:Chart\",\n    \"spreadsheetId\": \"identifier\",\n    \"workbookId\": \"identifier\",\n    \"spreadsheetUrl\": \"url\",\n    \"title\": \"name\",\n    \"locale\": \"inLanguage\",\n    \"timeZone\": \"temporalCoverage\",\n    \"sheetId\": \"sheets:sheetId\",\n    \"sheetType\": \"sheets:sheetType\",\n    \"hidden\": \"sheets:hidden\",\n    \"index\": \"position\",\n    \"range\": \"sheets:a1NotationRange\",\n    \"majorDimension\": \"sheets:majorDimension\",\n    \"values\": \"sheets:cellValues\"\
  ,\n    \"rowCount\": \"sheets:rowCount\",\n    \"columnCount\": \"sheets:columnCount\",\n    \"frozenRowCount\": \"sheets:frozenRowCount\",\n    \"frozenColumnCount\": \"sheets:frozenColumnCount\",\n    \"valueInputOption\": \"sheets:valueInputOption\",\n    \"valueRenderOption\": \"sheets:valueRenderOption\",\n    \"session\": \"excel:sessionId\",\n    \"persistChanges\": \"excel:persistChanges\",\n    \"address\": \"excel:cellAddress\",\n    \"formulas\": \"excel:formulas\",\n    \"numberFormat\": \"excel:numberFormat\",\n    \"A1Notation\": {\n      \"@id\": \"sheets:A1Notation\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/spreadsheets/refs/heads/main/json-ld/spreadsheets-context.jsonld
tags:
- Spreadsheets
- Data
- Google Sheets
- Excel
- Productivity
- Automation
- JSON-LD
- Linked Data
- Semantic Web
---
