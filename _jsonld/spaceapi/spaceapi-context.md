---
api_specs:
- filename: openapi.json
  format: json
  label: SpaceAPI Collector
  slug: spaceapi-collector
  spec_type: OpenAPI
  url: https://api.spaceapi.io/openapi.json
class_count: 8
classes:
- DirectoryEntry
- SpaceEntry
- Hackerspace
- Makerspace
- location
- address
- openingHours
- contact
context_file: json-ld/spaceapi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/spaceapi/refs/heads/main/json-ld/spaceapi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Spaceapi from SpaceAPI.
layout: jsonld
name: Spaceapi Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: spaceapi
  uri: https://spaceapi.io/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: items
  type: reference
- container: ''
  name: url
  type: reference
- container: ''
  name: valid
  type: boolean
- container: ''
  name: space
  type: ''
- container: ''
  name: lastSeen
  type: integer
- container: ''
  name: errMsg
  type: ''
- container: ''
  name: data
  type: ''
property_count: 7
provider_name: SpaceAPI
provider_slug: spaceapi
slug: spaceapi-context
source_filename: spaceapi-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"spaceapi\": \"https://spaceapi.io/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"DirectoryEntry\": \"spaceapi:DirectoryEntry\",\n    \"SpaceEntry\": \"spaceapi:SpaceEntry\",\n\n    \"items\": {\n      \"@id\": \"spaceapi:items\",\n      \"@type\": \"@id\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"valid\": {\n      \"@id\": \"spaceapi:valid\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"space\": {\n      \"@id\": \"schema:name\"\n    },\n    \"lastSeen\": {\n      \"@id\": \"spaceapi:lastSeen\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"errMsg\": {\n      \"@id\": \"spaceapi:errorMessage\"\n    },\n    \"data\": {\n      \"@id\": \"spaceapi:rawData\"\n    },\n\n    \"Hackerspace\": \"schema:LodgingBusiness\",\n    \"Makerspace\": \"schema:LodgingBusiness\",\n    \"location\": \"schema:location\"\
  ,\n    \"address\": \"schema:address\",\n    \"openingHours\": \"schema:openingHours\",\n    \"contact\": \"schema:contactPoint\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/spaceapi/refs/heads/main/json-ld/spaceapi-context.jsonld
tags:
- Co-Working
- Event Spaces
- Maker Spaces
- Hackerspaces
- Community
- Open Standard
- JSON-LD
- Linked Data
- Semantic Web
---
