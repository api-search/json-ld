---
api_specs:
- filename: microsoft-word-graph-api.yaml
  format: yaml
  label: Microsoft Graph Word API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-word/refs/heads/main/openapi/microsoft-word-graph-api.yaml
- filename: microsoft-word-javascript-api.yaml
  format: yaml
  label: Office JavaScript API for Word
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-word/refs/heads/main/openapi/microsoft-word-javascript-api.yaml
- filename: microsoft-word-open-xml-sdk.yaml
  format: yaml
  label: Open XML SDK for Word
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-word/refs/heads/main/openapi/microsoft-word-open-xml-sdk.yaml
class_count: 4
classes:
- WordDocument
- OpenXmlDocumentProperties
- OpenXmlParagraph
- OpenXmlTable
context_file: json-ld/microsoft-word-open-xml-sdk-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/microsoft-word/refs/heads/main/json-ld/microsoft-word-open-xml-sdk-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Microsoft Word Open Xml Sdk from Microsoft Word.
layout: jsonld
name: Microsoft Word Open Xml Sdk Context
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
  name: filename
  type: string
- container: ''
  name: paragraphCount
  type: integer
- container: ''
  name: tableCount
  type: integer
- container: ''
  name: imageCount
  type: integer
- container: ''
  name: sectionCount
  type: integer
- container: ''
  name: title
  type: string
- container: ''
  name: subject
  type: string
- container: ''
  name: creator
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: keywords
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: created
  type: dateTime
- container: ''
  name: modified
  type: dateTime
- container: ''
  name: revision
  type: string
- container: ''
  name: application
  type: string
- container: ''
  name: totalTime
  type: integer
- container: ''
  name: pages
  type: integer
- container: ''
  name: words
  type: integer
- container: ''
  name: characters
  type: integer
- container: ''
  name: styleId
  type: string
- container: ''
  name: bold
  type: boolean
- container: ''
  name: italic
  type: boolean
- container: ''
  name: fontSize
  type: double
property_count: 23
provider_name: Microsoft Word
provider_slug: microsoft-word
slug: microsoft-word-open-xml-sdk-context
source_filename: microsoft-word-open-xml-sdk-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"msword\": \"https://developer.microsoft.com/schema/word/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"WordDocument\": \"msword:WordDocument\",\n    \"OpenXmlDocumentProperties\": \"msword:OpenXmlDocumentProperties\",\n    \"OpenXmlParagraph\": \"msword:OpenXmlParagraph\",\n    \"OpenXmlTable\": \"msword:OpenXmlTable\",\n\n    \"filename\": {\n      \"@id\": \"msword:filename\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paragraphCount\": {\n      \"@id\": \"msword:paragraph_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"tableCount\": {\n      \"@id\": \"msword:table_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"imageCount\": {\n      \"@id\": \"msword:image_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sectionCount\": {\n      \"@id\": \"msword:section_count\",\n      \"@type\"\
  : \"xsd:integer\"\n    },\n    \"title\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subject\": {\n      \"@id\": \"dcterms:subject\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creator\": {\n      \"@id\": \"schema:creator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keywords\": {\n      \"@id\": \"schema:keywords\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"msword:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"created\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modified\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"revision\": {\n      \"@id\": \"msword:revision\",\n      \"@type\": \"xsd:string\"\n    },\n    \"application\": {\n      \"@id\": \"schema:softwareVersion\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"totalTime\": {\n      \"@id\": \"msword:total_time\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pages\": {\n      \"@id\": \"schema:numberOfPages\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"words\": {\n      \"@id\": \"schema:wordCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"characters\": {\n      \"@id\": \"msword:characters\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"styleId\": {\n      \"@id\": \"msword:style_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bold\": {\n      \"@id\": \"msword:bold\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"italic\": {\n      \"@id\": \"msword:italic\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"fontSize\": {\n      \"@id\": \"msword:font_size\",\n      \"@type\": \"xsd:double\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/microsoft-word/refs/heads/main/json-ld/microsoft-word-open-xml-sdk-context.jsonld
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
