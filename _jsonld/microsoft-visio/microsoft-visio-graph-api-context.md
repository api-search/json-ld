---
api_specs:
- filename: microsoft-visio-graph-api.yaml
  format: yaml
  label: Microsoft Graph Visio API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-visio/refs/heads/main/openapi/microsoft-visio-graph-api.yaml
class_count: 7
classes:
- VisioPage
- VisioShape
- ShapeDataItem
- VisioComment
- VisioHyperlink
- name
- description
context_file: json-ld/microsoft-visio-graph-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/microsoft-visio/refs/heads/main/json-ld/microsoft-visio-graph-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Microsoft Visio Graph Api from Microsoft Visio.
layout: jsonld
name: Microsoft Visio Graph Api Context
namespaces:
- prefix: ms
  uri: https://graph.microsoft.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: index
  type: integer
- container: ''
  name: height
  type: double
- container: ''
  name: width
  type: double
- container: ''
  name: text
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: label
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: format
  type: string
- container: ''
  name: author
  type: string
- container: ''
  name: date
  type: dateTime
- container: ''
  name: address
  type: reference
- container: ''
  name: subAddress
  type: string
property_count: 13
provider_name: Microsoft Visio
provider_slug: microsoft-visio
slug: microsoft-visio-graph-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ms\": \"https://graph.microsoft.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"VisioPage\": \"ms:VisioPage\",\n    \"VisioShape\": \"ms:VisioShape\",\n    \"ShapeDataItem\": \"ms:ShapeDataItem\",\n    \"VisioComment\": \"ms:VisioComment\",\n    \"VisioHyperlink\": \"ms:VisioHyperlink\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"id\": { \"@id\": \"ms:id\", \"@type\": \"xsd:string\" },\n    \"index\": { \"@id\": \"ms:index\", \"@type\": \"xsd:integer\" },\n    \"height\": { \"@id\": \"ms:height\", \"@type\": \"xsd:double\" },\n    \"width\": { \"@id\": \"ms:width\", \"@type\": \"xsd:double\" },\n    \"text\": { \"@id\": \"ms:text\", \"@type\": \"xsd:string\" },\n    \"type\": { \"@id\": \"ms:type\", \"@type\": \"xsd:string\" },\n    \"label\": { \"@id\": \"ms:label\"\
  , \"@type\": \"xsd:string\" },\n    \"value\": { \"@id\": \"ms:value\", \"@type\": \"xsd:string\" },\n    \"format\": { \"@id\": \"ms:format\", \"@type\": \"xsd:string\" },\n    \"author\": { \"@id\": \"ms:author\", \"@type\": \"xsd:string\" },\n    \"date\": { \"@id\": \"ms:date\", \"@type\": \"xsd:dateTime\" },\n    \"address\": { \"@id\": \"ms:address\", \"@type\": \"@id\" },\n    \"subAddress\": { \"@id\": \"ms:subAddress\", \"@type\": \"xsd:string\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/microsoft-visio/refs/heads/main/json-ld/microsoft-visio-graph-api-context.jsonld
tags:
- Business Process
- Diagramming
- Flowcharts
- Microsoft 365
- Visualization
- JSON-LD
- Linked Data
- Semantic Web
---
