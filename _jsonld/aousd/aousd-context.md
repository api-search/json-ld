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
