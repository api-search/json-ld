---
class_count: 0
classes: []
context_file: json-ld/amadeus-flight-offers-search-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus/refs/heads/main/json-ld/amadeus-flight-offers-search-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Flight Offers Search from Amadeus.
layout: jsonld
name: Amadeus Flight Offers Search Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
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
  type: ''
property_count: 6
provider_name: Amadeus
provider_slug: amadeus
slug: amadeus-flight-offers-search-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"errors\": {\n      \"@id\": \"schema:errors\"\n    },\n    \"status\": {\n      \"@id\": \"schema:status\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"code\": {\n      \"@id\": \"schema:code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"title\": {\n      \"@id\": \"schema:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detail\": {\n      \"@id\": \"schema:detail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"schema:source\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus/refs/heads/main/json-ld/amadeus-flight-offers-search-context.jsonld
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
