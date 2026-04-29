---
class_count: 0
classes: []
context_file: json-ld/amadeus-flight-check-in-links-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus/refs/heads/main/json-ld/amadeus-flight-check-in-links-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Flight Check In Links from Amadeus.
layout: jsonld
name: Amadeus Flight Check In Links Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: type
  type: string
- container: ''
  name: id
  type: ''
- container: ''
  name: href
  type: reference
- container: ''
  name: channel
  type: string
- container: ''
  name: parameters
  type: string
- container: ''
  name: description
  type: ''
- container: ''
  name: format
  type: string
- container: ''
  name: errors
  type: ''
property_count: 8
provider_name: Amadeus
provider_slug: amadeus
slug: amadeus-flight-check-in-links-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"type\": {\n      \"@id\": \"schema:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"@id\"\n    },\n    \"href\": {\n      \"@id\": \"schema:href\",\n      \"@type\": \"@id\"\n    },\n    \"channel\": {\n      \"@id\": \"schema:channel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parameters\": {\n      \"@id\": \"schema:parameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"format\": {\n      \"@id\": \"schema:format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errors\": {\n      \"@id\": \"schema:errors\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus/refs/heads/main/json-ld/amadeus-flight-check-in-links-context.jsonld
tags:
- Airlines
- Aviation
- Booking
- Destinations
- Flights
- Hospitality
- Hotels
- Market Insights
- Tourism
- Transfers
- Travel
- JSON-LD
- Linked Data
- Semantic Web
---
