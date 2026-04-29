---
api_specs:
- filename: apple-keynote-icloud-openapi.yaml
  format: yaml
  label: Keynote iCloud API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apple-keynote/refs/heads/main/openapi/apple-keynote-icloud-openapi.yaml
class_count: 9
classes:
- ExportRequest
- Apple Keynote Presentation
- title
- description
- author
- createdDate
- modifiedDate
- Slide
- Theme
context_file: json-ld/apple-keynote-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apple-keynote/refs/heads/main/json-ld/apple-keynote-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apple Keynote from Apple Keynote.
layout: jsonld
name: Apple Keynote Context
namespaces:
- prefix: keynote
  uri: https://www.apple.com/keynote/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: format
  type: string
- container: ''
  name: includeNotes
  type: boolean
- container: ''
  name: slideRange
  type: string
- container: ''
  name: theme
  type: string
- container: ''
  name: slideSize
  type: string
- container: set
  name: slides
  type: ''
- container: ''
  name: metadata
  type: string
- container: ''
  name: slideNumber
  type: integer
- container: ''
  name: layout
  type: string
- container: ''
  name: skipped
  type: boolean
- container: ''
  name: notes
  type: string
- container: ''
  name: backgroundColor
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: identifier
  type: string
- container: ''
  name: category
  type: string
- container: set
  name: colorScheme
  type: ''
- container: ''
  name: fontFamily
  type: string
property_count: 17
provider_name: Apple Keynote
provider_slug: apple-keynote
slug: apple-keynote-context
source_filename: apple-keynote-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"keynote\": \"https://www.apple.com/keynote/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ExportRequest\": \"keynote:ExportRequest\",\n    \"format\": {\n      \"@id\": \"keynote:format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"includeNotes\": {\n      \"@id\": \"keynote:includeNotes\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"slideRange\": {\n      \"@id\": \"keynote:slideRange\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Apple Keynote Presentation\": \"keynote:Apple Keynote Presentation\",\n    \"title\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"author\": \"schema:author\",\n    \"createdDate\": \"schema:dateCreated\",\n    \"modifiedDate\": \"schema:dateModified\",\n    \"theme\": {\n      \"@id\": \"keynote:theme\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"slideSize\": {\n      \"@id\": \"keynote:slideSize\",\n      \"@type\": \"xsd:string\"\n    },\n    \"slides\": {\n      \"@id\": \"keynote:slides\",\n      \"@container\": \"@set\"\n    },\n    \"metadata\": {\n      \"@id\": \"keynote:metadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Slide\": \"keynote:Slide\",\n    \"slideNumber\": {\n      \"@id\": \"keynote:slideNumber\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"layout\": {\n      \"@id\": \"keynote:layout\",\n      \"@type\": \"xsd:string\"\n    },\n    \"skipped\": {\n      \"@id\": \"keynote:skipped\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"notes\": {\n      \"@id\": \"keynote:notes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"backgroundColor\": {\n      \"@id\": \"keynote:backgroundColor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Theme\": \"keynote:Theme\",\n    \"name\": {\n      \"@id\": \"keynote:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"identifier\": {\n      \"\
  @id\": \"keynote:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"keynote:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"colorScheme\": {\n      \"@id\": \"keynote:colorScheme\",\n      \"@container\": \"@set\"\n    },\n    \"fontFamily\": {\n      \"@id\": \"keynote:fontFamily\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apple-keynote/refs/heads/main/json-ld/apple-keynote-context.jsonld
tags:
- Apple
- Design
- iWork
- Presentations
- Productivity
- Slides
- JSON-LD
- Linked Data
- Semantic Web
---
