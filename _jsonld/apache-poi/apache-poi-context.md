---
api_specs:
- filename: apache-poi-api.yaml
  format: yaml
  label: Apache POI
  slug: apache-poi
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-poi/refs/heads/main/openapi/apache-poi-api.yaml
class_count: 16
classes:
- WorkbookList
- Workbook
- WorkbookRequest
- SheetList
- Sheet
- CellData
- Cell
- DocumentRequest
- Document
- Paragraph
- PresentationRequest
- Presentation
- Slide
- Shape
- ConversionRequest
- ConversionResult
context_file: json-ld/apache-poi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-poi/refs/heads/main/json-ld/apache-poi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Poi from Apache POI.
layout: jsonld
name: Apache Poi Context
namespaces:
- prefix: poi
  uri: https://poi.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: workbooks
  type: ''
- container: ''
  name: total
  type: integer
- container: ''
  name: id
  type: string
- container: ''
  name: name
  type: schema:name
- container: ''
  name: format
  type: string
- container: ''
  name: sheetCount
  type: integer
- container: ''
  name: createdAt
  type: string
- container: set
  name: sheets
  type: ''
- container: ''
  name: index
  type: integer
- container: ''
  name: rowCount
  type: integer
- container: ''
  name: columnCount
  type: integer
- container: set
  name: rows
  type: ''
- container: ''
  name: range
  type: string
- container: ''
  name: address
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: formula
  type: string
- container: ''
  name: content
  type: string
- container: set
  name: paragraphs
  type: ''
- container: ''
  name: pageCount
  type: integer
- container: ''
  name: text
  type: string
- container: ''
  name: style
  type: string
- container: ''
  name: slideCount
  type: integer
- container: set
  name: slides
  type: ''
- container: ''
  name: title
  type: string
- container: set
  name: shapes
  type: ''
- container: ''
  name: sourceId
  type: string
- container: ''
  name: sourceType
  type: string
- container: ''
  name: targetFormat
  type: string
- container: ''
  name: url
  type: schema:url
- container: ''
  name: size
  type: integer
property_count: 31
provider_name: Apache POI
provider_slug: apache-poi
slug: apache-poi-context
source_filename: apache-poi-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"poi\": \"https://poi.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"WorkbookList\": \"poi:WorkbookList\",\n    \"Workbook\": \"poi:Workbook\",\n    \"WorkbookRequest\": \"poi:WorkbookRequest\",\n    \"SheetList\": \"poi:SheetList\",\n    \"Sheet\": \"poi:Sheet\",\n    \"CellData\": \"poi:CellData\",\n    \"Cell\": \"poi:Cell\",\n    \"DocumentRequest\": \"poi:DocumentRequest\",\n    \"Document\": \"poi:Document\",\n    \"Paragraph\": \"poi:Paragraph\",\n    \"PresentationRequest\": \"poi:PresentationRequest\",\n    \"Presentation\": \"poi:Presentation\",\n    \"Slide\": \"poi:Slide\",\n    \"Shape\": \"poi:Shape\",\n    \"ConversionRequest\": \"poi:ConversionRequest\",\n    \"ConversionResult\": \"poi:ConversionResult\",\n    \"workbooks\": {\n      \"@id\": \"poi:workbooks\",\n      \"@container\": \"@set\"\n    },\n    \"total\": {\n      \"@id\"\
  : \"poi:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"id\": {\n      \"@id\": \"poi:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"poi:name\",\n      \"@type\": \"schema:name\"\n    },\n    \"format\": {\n      \"@id\": \"poi:format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sheetCount\": {\n      \"@id\": \"poi:sheetCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"createdAt\": {\n      \"@id\": \"poi:createdAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sheets\": {\n      \"@id\": \"poi:sheets\",\n      \"@container\": \"@set\"\n    },\n    \"index\": {\n      \"@id\": \"poi:index\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"rowCount\": {\n      \"@id\": \"poi:rowCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"columnCount\": {\n      \"@id\": \"poi:columnCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"rows\": {\n      \"@id\": \"poi:rows\",\n      \"@container\": \"@set\"\n    },\n    \"\
  range\": {\n      \"@id\": \"poi:range\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address\": {\n      \"@id\": \"poi:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"poi:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"poi:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"formula\": {\n      \"@id\": \"poi:formula\",\n      \"@type\": \"xsd:string\"\n    },\n    \"content\": {\n      \"@id\": \"poi:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paragraphs\": {\n      \"@id\": \"poi:paragraphs\",\n      \"@container\": \"@set\"\n    },\n    \"pageCount\": {\n      \"@id\": \"poi:pageCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"text\": {\n      \"@id\": \"poi:text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"style\": {\n      \"@id\": \"poi:style\",\n      \"@type\": \"xsd:string\"\n    },\n    \"slideCount\": {\n      \"@id\": \"poi:slideCount\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"slides\": {\n      \"@id\": \"poi:slides\",\n      \"@container\": \"@set\"\n    },\n    \"title\": {\n      \"@id\": \"poi:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shapes\": {\n      \"@id\": \"poi:shapes\",\n      \"@container\": \"@set\"\n    },\n    \"sourceId\": {\n      \"@id\": \"poi:sourceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceType\": {\n      \"@id\": \"poi:sourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetFormat\": {\n      \"@id\": \"poi:targetFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"poi:url\",\n      \"@type\": \"schema:url\"\n    },\n    \"size\": {\n      \"@id\": \"poi:size\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-poi/refs/heads/main/json-ld/apache-poi-context.jsonld
tags:
- Document Processing
- Excel
- Java
- Microsoft Office
- PowerPoint
- Word
- Apache
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
