---
api_specs:
- filename: amadeus-media-hotel-content-openapi.yaml
  format: yaml
  label: Hotel Content API
  slug: hotel-content-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amadeus-media/refs/heads/main/openapi/amadeus-media-hotel-content-openapi.yaml
- filename: amadeus-media-hotel-list-openapi.yaml
  format: yaml
  label: Hotel List API
  slug: hotel-list-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amadeus-media/refs/heads/main/openapi/amadeus-media-hotel-list-openapi.yaml
class_count: 4
classes:
- Error_404
- Error_500
- Error_400
- HotelSearchResponse
context_file: json-ld/amadeus-hotel-list-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus-media/refs/heads/main/json-ld/amadeus-hotel-list-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Hotel List from Amadeus Media.
layout: jsonld
name: Amadeus Hotel List Context
namespaces:
- prefix: amadeus
  uri: https://amadeus.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: errors
  type: ''
- container: ''
  name: status
  type: integer
- container: ''
  name: code
  type: integer
- container: ''
  name: title
  type: string
- container: ''
  name: detail
  type: string
- container: ''
  name: source
  type: reference
- container: ''
  name: parameter
  type: string
- container: ''
  name: pointer
  type: string
- container: ''
  name: example
  type: string
- container: ''
  name: documentation
  type: string
- container: set
  name: data
  type: string
- container: ''
  name: meta
  type: string
property_count: 12
provider_name: Amadeus Media
provider_slug: amadeus-media
slug: amadeus-hotel-list-context
source_filename: amadeus-hotel-list-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amadeus\": \"https://amadeus.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Error_404\": \"amadeus:Error_404\",\n    \"Error_500\": \"amadeus:Error_500\",\n    \"Error_400\": \"amadeus:Error_400\",\n    \"HotelSearchResponse\": \"amadeus:HotelSearchResponse\",\n    \"errors\": {\n      \"@id\": \"amadeus:errors\",\n      \"@container\": \"@set\"\n    },\n    \"status\": {\n      \"@id\": \"amadeus:status\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"code\": {\n      \"@id\": \"amadeus:code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"title\": {\n      \"@id\": \"amadeus:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detail\": {\n      \"@id\": \"amadeus:detail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"amadeus:source\",\n      \"@type\": \"@id\"\n\
  \    },\n    \"parameter\": {\n      \"@id\": \"amadeus:parameter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pointer\": {\n      \"@id\": \"amadeus:pointer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"example\": {\n      \"@id\": \"amadeus:example\",\n      \"@type\": \"xsd:string\"\n    },\n    \"documentation\": {\n      \"@id\": \"amadeus:documentation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"amadeus:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"meta\": {\n      \"@id\": \"amadeus:meta\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus-media/refs/heads/main/json-ld/amadeus-hotel-list-context.jsonld
tags:
- Content
- Hotels
- Images
- Media
- Travel
- JSON-LD
- Linked Data
- Semantic Web
---
