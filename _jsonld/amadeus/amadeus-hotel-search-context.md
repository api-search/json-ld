---
class_count: 0
classes: []
context_file: json-ld/amadeus-hotel-search-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus/refs/heads/main/json-ld/amadeus-hotel-search-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Hotel Search from Amadeus.
layout: jsonld
name: Amadeus Hotel Search Context
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
  name: available
  type: boolean
- container: ''
  name: self
  type: string
- container: ''
  name: offers
  type: ''
- container: ''
  name: hotel
  type: string
- container: ''
  name: data
  type: string
- container: ''
  name: errors
  type: ''
property_count: 7
provider_name: Amadeus
provider_slug: amadeus
slug: amadeus-hotel-search-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"type\": {\n      \"@id\": \"schema:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"available\": {\n      \"@id\": \"schema:available\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"self\": {\n      \"@id\": \"schema:self\",\n      \"@type\": \"xsd:string\"\n    },\n    \"offers\": {\n      \"@id\": \"schema:offers\"\n    },\n    \"hotel\": {\n      \"@id\": \"schema:hotel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"schema:data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errors\": {\n      \"@id\": \"schema:errors\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus/refs/heads/main/json-ld/amadeus-hotel-search-context.jsonld
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
