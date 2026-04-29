---
class_count: 1
classes:
- OutputText
context_file: json-ld/adyen-terminal-output-text-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-output-text-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Output Text from Adyen.
layout: jsonld
name: Adyen Terminal Output Text Context
namespaces:
- prefix: adyen
  uri: https://docs.adyen.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Text
  type: string
- container: ''
  name: CharacterSet
  type: integer
- container: ''
  name: Font
  type: string
- container: ''
  name: StartRow
  type: integer
- container: ''
  name: StartColumn
  type: integer
- container: ''
  name: Color
  type: string
- container: ''
  name: CharacterWidth
  type: string
- container: ''
  name: CharacterHeight
  type: string
- container: ''
  name: CharacterStyle
  type: string
- container: ''
  name: Alignment
  type: string
- container: ''
  name: EndOfLineFlag
  type: boolean
property_count: 11
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-output-text-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"OutputText\": \"adyen:OutputText\",\n    \"Text\": {\n      \"@id\": \"adyen:Text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CharacterSet\": {\n      \"@id\": \"adyen:CharacterSet\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Font\": {\n      \"@id\": \"adyen:Font\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StartRow\": {\n      \"@id\": \"adyen:StartRow\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"StartColumn\": {\n      \"@id\": \"adyen:StartColumn\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Color\": {\n      \"@id\": \"adyen:Color\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CharacterWidth\": {\n      \"@id\": \"adyen:CharacterWidth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CharacterHeight\"\
  : {\n      \"@id\": \"adyen:CharacterHeight\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CharacterStyle\": {\n      \"@id\": \"adyen:CharacterStyle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Alignment\": {\n      \"@id\": \"adyen:Alignment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EndOfLineFlag\": {\n      \"@id\": \"adyen:EndOfLineFlag\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-output-text-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
