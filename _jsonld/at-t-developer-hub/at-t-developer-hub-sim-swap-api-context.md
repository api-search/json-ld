---
class_count: 4
classes:
- SimSwapCheckRequest
- SimSwapCheckResponse
- SimSwapDateRequest
- SimSwapDateResponse
context_file: json-ld/at-t-developer-hub-sim-swap-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/at-t-developer-hub/refs/heads/main/json-ld/at-t-developer-hub-sim-swap-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for At T Developer Hub Sim Swap Api from AT&T Developer Hub.
layout: jsonld
name: At T Developer Hub Sim Swap Api Context
namespaces:
- prefix: att
  uri: https://att.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: phoneNumber
  type: string
- container: ''
  name: maxAge
  type: integer
- container: ''
  name: swapped
  type: boolean
- container: ''
  name: latestSimChange
  type: dateTime
property_count: 4
provider_name: AT&T Developer Hub
provider_slug: at-t-developer-hub
slug: at-t-developer-hub-sim-swap-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"att\": \"https://att.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"SimSwapCheckRequest\": \"att:SimSwapCheckRequest\",\n    \"SimSwapCheckResponse\": \"att:SimSwapCheckResponse\",\n    \"SimSwapDateRequest\": \"att:SimSwapDateRequest\",\n    \"SimSwapDateResponse\": \"att:SimSwapDateResponse\",\n    \"phoneNumber\": {\n      \"@id\": \"att:phoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxAge\": {\n      \"@id\": \"att:maxAge\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"swapped\": {\n      \"@id\": \"att:swapped\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"latestSimChange\": {\n      \"@id\": \"att:latestSimChange\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/at-t-developer-hub/refs/heads/main/json-ld/at-t-developer-hub-sim-swap-api-context.jsonld
tags:
- 5G
- Network APIs
- CAMARA
- Connectivity
- Telecommunications
- Edge Computing
- Device Status
- SIM Swap
- JSON-LD
- Linked Data
- Semantic Web
---
