---
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
