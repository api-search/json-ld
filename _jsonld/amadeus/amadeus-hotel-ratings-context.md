---
class_count: 0
classes: []
context_file: json-ld/amadeus-hotel-ratings-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus/refs/heads/main/json-ld/amadeus-hotel-ratings-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Hotel Ratings from Amadeus.
layout: jsonld
name: Amadeus Hotel Ratings Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: hotelId
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: overallRating
  type: string
- container: ''
  name: numberOfRatings
  type: integer
- container: ''
  name: numberOfReviews
  type: integer
- container: ''
  name: sentiments
  type: ''
- container: ''
  name: count
  type: integer
- container: ''
  name: links
  type: string
- container: ''
  name: self
  type: reference
- container: ''
  name: next
  type: reference
- container: ''
  name: previous
  type: reference
- container: ''
  name: last
  type: reference
- container: ''
  name: first
  type: reference
- container: ''
  name: up
  type: reference
property_count: 14
provider_name: Amadeus
provider_slug: amadeus
slug: amadeus-hotel-ratings-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"hotelId\": {\n      \"@id\": \"schema:hotelId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"schema:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"overallRating\": {\n      \"@id\": \"schema:overallRating\",\n      \"@type\": \"xsd:string\"\n    },\n    \"numberOfRatings\": {\n      \"@id\": \"schema:numberOfRatings\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"numberOfReviews\": {\n      \"@id\": \"schema:numberOfReviews\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sentiments\": {\n      \"@id\": \"schema:sentiments\"\n    },\n    \"count\": {\n      \"@id\": \"schema:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"links\": {\n      \"@id\": \"schema:links\",\n      \"@type\": \"xsd:string\"\n    },\n    \"self\": {\n      \"@id\": \"schema:self\",\n      \"@type\"\
  : \"@id\"\n    },\n    \"next\": {\n      \"@id\": \"schema:next\",\n      \"@type\": \"@id\"\n    },\n    \"previous\": {\n      \"@id\": \"schema:previous\",\n      \"@type\": \"@id\"\n    },\n    \"last\": {\n      \"@id\": \"schema:last\",\n      \"@type\": \"@id\"\n    },\n    \"first\": {\n      \"@id\": \"schema:first\",\n      \"@type\": \"@id\"\n    },\n    \"up\": {\n      \"@id\": \"schema:up\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus/refs/heads/main/json-ld/amadeus-hotel-ratings-context.jsonld
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
