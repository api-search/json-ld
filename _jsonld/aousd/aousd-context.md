---
class_count: 5
classes:
- USDLayer
- USDPrim
- USDProperty
- name
- documentation
context_file: json-ld/aousd-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aousd/refs/heads/main/json-ld/aousd-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aousd from Alliance for OpenUSD.
layout: jsonld
name: Aousd Context
namespaces:
- prefix: usd
  uri: https://api-evangelist.github.io/aousd/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: identifier
  type: string
- container: ''
  name: realPath
  type: string
- container: ''
  name: fileFormat
  type: string
- container: ''
  name: defaultPrim
  type: string
- container: ''
  name: startTimeCode
  type: decimal
- container: ''
  name: endTimeCode
  type: decimal
- container: ''
  name: framesPerSecond
  type: decimal
- container: ''
  name: metersPerUnit
  type: decimal
- container: ''
  name: upAxis
  type: string
- container: set
  name: subLayerPaths
  type: string
- container: ''
  name: path
  type: string
- container: ''
  name: typeName
  type: string
- container: ''
  name: specifier
  type: string
- container: ''
  name: active
  type: boolean
- container: ''
  name: hidden
  type: boolean
- container: ''
  name: kind
  type: string
- container: ''
  name: purpose
  type: string
- container: ''
  name: instanceable
  type: boolean
property_count: 18
provider_name: Alliance for OpenUSD
provider_slug: aousd
slug: aousd-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"usd\": \"https://api-evangelist.github.io/aousd/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"USDLayer\": \"usd:USDLayer\",\n    \"USDPrim\": \"usd:USDPrim\",\n    \"USDProperty\": \"usd:USDProperty\",\n\n    \"identifier\": {\"@id\": \"dcterms:identifier\", \"@type\": \"xsd:string\"},\n    \"name\": \"schema:name\",\n    \"documentation\": \"schema:description\",\n    \"realPath\": {\"@id\": \"usd:real_path\", \"@type\": \"xsd:string\"},\n    \"fileFormat\": {\"@id\": \"usd:file_format\", \"@type\": \"xsd:string\"},\n    \"defaultPrim\": {\"@id\": \"usd:default_prim\", \"@type\": \"xsd:string\"},\n    \"startTimeCode\": {\"@id\": \"usd:start_time_code\", \"@type\": \"xsd:decimal\"},\n    \"endTimeCode\": {\"@id\": \"usd:end_time_code\", \"@type\": \"xsd:decimal\"},\n    \"framesPerSecond\": {\"@id\": \"usd:frames_per_second\"\
  , \"@type\": \"xsd:decimal\"},\n    \"metersPerUnit\": {\"@id\": \"usd:meters_per_unit\", \"@type\": \"xsd:decimal\"},\n    \"upAxis\": {\"@id\": \"usd:up_axis\", \"@type\": \"xsd:string\"},\n    \"subLayerPaths\": {\"@id\": \"usd:sub_layer_paths\", \"@container\": \"@set\", \"@type\": \"xsd:string\"},\n    \"path\": {\"@id\": \"usd:path\", \"@type\": \"xsd:string\"},\n    \"typeName\": {\"@id\": \"usd:type_name\", \"@type\": \"xsd:string\"},\n    \"specifier\": {\"@id\": \"usd:specifier\", \"@type\": \"xsd:string\"},\n    \"active\": {\"@id\": \"usd:active\", \"@type\": \"xsd:boolean\"},\n    \"hidden\": {\"@id\": \"usd:hidden\", \"@type\": \"xsd:boolean\"},\n    \"kind\": {\"@id\": \"usd:kind\", \"@type\": \"xsd:string\"},\n    \"purpose\": {\"@id\": \"usd:purpose\", \"@type\": \"xsd:string\"},\n    \"instanceable\": {\"@id\": \"usd:instanceable\", \"@type\": \"xsd:boolean\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aousd/refs/heads/main/json-ld/aousd-context.jsonld
tags:
- 3D
- Interoperability
- Linux Foundation
- Metaverse
- OpenUSD
- Specification
- Standards
- USD
- Visual Effects
- JSON-LD
- Linked Data
- Semantic Web
---
