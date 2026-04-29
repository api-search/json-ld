---
class_count: 10
classes:
- Document
- Body
- Paragraph
- ContentControl
- Table
- Comment
- Section
- Style
- Range
- DocumentProperties
context_file: json-ld/microsoft-word-javascript-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/microsoft-word/refs/heads/main/json-ld/microsoft-word-javascript-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Microsoft Word Javascript Api from Microsoft Word.
layout: jsonld
name: Microsoft Word Javascript Api Context
namespaces:
- prefix: msword
  uri: https://developer.microsoft.com/schema/word/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: text
  type: string
- container: ''
  name: style
  type: string
- container: ''
  name: alignment
  type: string
- container: ''
  name: firstLineIndent
  type: double
- container: ''
  name: lineSpacing
  type: double
- container: ''
  name: outlineLevel
  type: integer
- container: ''
  name: isListItem
  type: boolean
- container: ''
  name: tag
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: appearance
  type: string
- container: ''
  name: cannotDelete
  type: boolean
- container: ''
  name: cannotEdit
  type: boolean
- container: ''
  name: rowCount
  type: integer
- container: ''
  name: columnCount
  type: integer
- container: ''
  name: headerRowCount
  type: integer
- container: ''
  name: authorName
  type: string
- container: ''
  name: authorEmail
  type: string
- container: ''
  name: content
  type: string
- container: ''
  name: createdDate
  type: dateTime
- container: ''
  name: resolved
  type: boolean
- container: ''
  name: saved
  type: boolean
- container: ''
  name: changeTrackingMode
  type: string
- container: ''
  name: subject
  type: string
- container: ''
  name: author
  type: string
- container: ''
  name: keywords
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: revisionNumber
  type: string
property_count: 27
provider_name: Microsoft Word
provider_slug: microsoft-word
slug: microsoft-word-javascript-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"msword\": \"https://developer.microsoft.com/schema/word/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Document\": \"msword:Document\",\n    \"Body\": \"msword:Body\",\n    \"Paragraph\": \"msword:Paragraph\",\n    \"ContentControl\": \"msword:ContentControl\",\n    \"Table\": \"msword:Table\",\n    \"Comment\": \"msword:Comment\",\n    \"Section\": \"msword:Section\",\n    \"Style\": \"msword:Style\",\n    \"Range\": \"msword:Range\",\n    \"DocumentProperties\": \"msword:DocumentProperties\",\n\n    \"text\": {\n      \"@id\": \"schema:text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"style\": {\n      \"@id\": \"msword:style\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alignment\": {\n      \"@id\": \"msword:alignment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstLineIndent\": {\n      \"@id\"\
  : \"msword:first_line_indent\",\n      \"@type\": \"xsd:double\"\n    },\n    \"lineSpacing\": {\n      \"@id\": \"msword:line_spacing\",\n      \"@type\": \"xsd:double\"\n    },\n    \"outlineLevel\": {\n      \"@id\": \"msword:outline_level\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"isListItem\": {\n      \"@id\": \"msword:is_list_item\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"tag\": {\n      \"@id\": \"msword:tag\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"appearance\": {\n      \"@id\": \"msword:appearance\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cannotDelete\": {\n      \"@id\": \"msword:cannot_delete\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"cannotEdit\": {\n      \"@id\": \"msword:cannot_edit\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"rowCount\": {\n      \"@id\": \"msword:row_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"\
  columnCount\": {\n      \"@id\": \"msword:column_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"headerRowCount\": {\n      \"@id\": \"msword:header_row_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"authorName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authorEmail\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"content\": {\n      \"@id\": \"schema:text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdDate\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"resolved\": {\n      \"@id\": \"msword:resolved\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"saved\": {\n      \"@id\": \"msword:saved\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"changeTrackingMode\": {\n      \"@id\": \"msword:change_tracking_mode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subject\": {\n      \"@id\": \"dcterms:subject\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"author\": {\n      \"@id\": \"schema:author\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keywords\": {\n      \"@id\": \"schema:keywords\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"msword:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revisionNumber\": {\n      \"@id\": \"msword:revision_number\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/microsoft-word/refs/heads/main/json-ld/microsoft-word-javascript-api-context.jsonld
tags:
- Documents
- Microsoft 365
- Office
- Productivity
- Word Processing
- JSON-LD
- Linked Data
- Semantic Web
---
