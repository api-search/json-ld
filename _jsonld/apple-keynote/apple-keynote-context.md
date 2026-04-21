---
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
