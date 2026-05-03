---
api_specs:
- filename: the-color-api-openapi.yml
  format: yaml
  label: The Color API
  slug: the-color-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/the-color-api/refs/heads/main/openapi/the-color-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/the-color-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/the-color-api/refs/heads/main/json-ld/the-color-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for The Color Api from The Color API.
layout: jsonld
name: The Color Api Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: colorapi
  uri: https://www.thecolorapi.com/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: skos
  uri: http://www.w3.org/2004/02/skos/core#
properties:
- container: ''
  name: Color
  type: ''
- container: ''
  name: ColorScheme
  type: ''
- container: ''
  name: hex
  type: ''
- container: ''
  name: rgb
  type: ''
- container: ''
  name: hsl
  type: ''
- container: ''
  name: hsv
  type: ''
- container: ''
  name: cmyk
  type: ''
- container: ''
  name: XYZ
  type: ''
- container: ''
  name: value
  type: ''
- container: ''
  name: name
  type: ''
- container: ''
  name: image
  type: ''
- container: ''
  name: contrast
  type: ''
- container: ''
  name: mode
  type: ''
- container: ''
  name: count
  type: integer
- container: set
  name: colors
  type: ''
- container: ''
  name: seed
  type: ''
- container: ''
  name: r
  type: integer
- container: ''
  name: g
  type: integer
- container: ''
  name: b
  type: integer
- container: ''
  name: h
  type: integer
- container: ''
  name: s
  type: integer
- container: ''
  name: l
  type: integer
- container: ''
  name: exact_match_name
  type: boolean
- container: ''
  name: closest_named_hex
  type: ''
- container: ''
  name: distance
  type: integer
- container: set
  name: links
  type: ''
property_count: 26
provider_name: The Color API
provider_slug: the-color-api
slug: the-color-api-context
source_filename: the-color-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"colorapi\": \"https://www.thecolorapi.com/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"skos\": \"http://www.w3.org/2004/02/skos/core#\",\n\n    \"Color\": {\n      \"@id\": \"colorapi:Color\"\n    },\n    \"ColorScheme\": {\n      \"@id\": \"colorapi:ColorScheme\"\n    },\n\n    \"hex\": {\n      \"@id\": \"colorapi:hex\"\n    },\n    \"rgb\": {\n      \"@id\": \"colorapi:rgb\"\n    },\n    \"hsl\": {\n      \"@id\": \"colorapi:hsl\"\n    },\n    \"hsv\": {\n      \"@id\": \"colorapi:hsv\"\n    },\n    \"cmyk\": {\n      \"@id\": \"colorapi:cmyk\"\n    },\n    \"XYZ\": {\n      \"@id\": \"colorapi:XYZ\"\n    },\n\n    \"value\": {\n      \"@id\": \"schema:value\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"image\": {\n      \"@id\": \"schema:image\"\n    },\n    \"contrast\": {\n      \"\
  @id\": \"colorapi:contrast\"\n    },\n\n    \"mode\": {\n      \"@id\": \"colorapi:schemeMode\",\n      \"skos:definition\": \"Color wheel relationship used to generate a palette (monochrome, complement, analogic, triad, quad, etc.)\"\n    },\n    \"count\": {\n      \"@id\": \"schema:numberOfItems\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"colors\": {\n      \"@id\": \"colorapi:colors\",\n      \"@container\": \"@set\"\n    },\n    \"seed\": {\n      \"@id\": \"colorapi:seedColor\"\n    },\n\n    \"r\": {\n      \"@id\": \"colorapi:red\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"g\": {\n      \"@id\": \"colorapi:green\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"b\": {\n      \"@id\": \"colorapi:blue\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"h\": {\n      \"@id\": \"colorapi:hue\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"s\": {\n      \"@id\": \"colorapi:saturation\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"l\": {\n      \"@id\": \"\
  colorapi:lightness\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"exact_match_name\": {\n      \"@id\": \"colorapi:exactMatchName\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"closest_named_hex\": {\n      \"@id\": \"colorapi:closestNamedHex\"\n    },\n    \"distance\": {\n      \"@id\": \"colorapi:colorDistance\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"links\": {\n      \"@id\": \"schema:url\",\n      \"@container\": \"@set\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/the-color-api/refs/heads/main/json-ld/the-color-api-context.jsonld
tags:
- Colors
- Design
- Utilities
- JSON-LD
- Linked Data
- Semantic Web
---
