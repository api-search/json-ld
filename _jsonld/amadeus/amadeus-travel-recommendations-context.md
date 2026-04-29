---
class_count: 0
classes: []
context_file: json-ld/amadeus-travel-recommendations-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus/refs/heads/main/json-ld/amadeus-travel-recommendations-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Travel Recommendations from Amadeus.
layout: jsonld
name: Amadeus Travel Recommendations Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: warnings
  type: ''
- container: ''
  name: data
  type: ''
- container: ''
  name: meta
  type: string
- container: ''
  name: errors
  type: ''
property_count: 4
provider_name: Amadeus
provider_slug: amadeus
slug: amadeus-travel-recommendations-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"warnings\": {\n      \"@id\": \"schema:warnings\"\n    },\n    \"data\": {\n      \"@id\": \"schema:data\"\n    },\n    \"meta\": {\n      \"@id\": \"schema:meta\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errors\": {\n      \"@id\": \"schema:errors\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus/refs/heads/main/json-ld/amadeus-travel-recommendations-context.jsonld
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
