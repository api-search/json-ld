---
class_count: 0
classes: []
context_file: json-ld/amadeus-airline-routes-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus/refs/heads/main/json-ld/amadeus-airline-routes-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Airline Routes from Amadeus.
layout: jsonld
name: Amadeus Airline Routes Context
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
  name: subtype
  type: string
- container: ''
  name: name
  type: ''
- container: ''
  name: iataCode
  type: string
- container: ''
  name: geoCode
  type: ''
- container: ''
  name: address
  type: ''
- container: ''
  name: timeZone
  type: ''
- container: ''
  name: metrics
  type: ''
- container: ''
  name: count
  type: integer
- container: ''
  name: links
  type: ''
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
property_count: 14
provider_name: Amadeus
provider_slug: amadeus
slug: amadeus-airline-routes-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"type\": {\n      \"@id\": \"schema:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subtype\": {\n      \"@id\": \"schema:subtype\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"iataCode\": {\n      \"@id\": \"schema:iataCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"geoCode\": {\n      \"@id\": \"schema:geoCode\"\n    },\n    \"address\": {\n      \"@id\": \"schema:address\"\n    },\n    \"timeZone\": {\n      \"@id\": \"schema:timeZone\"\n    },\n    \"metrics\": {\n      \"@id\": \"schema:metrics\"\n    },\n    \"count\": {\n      \"@id\": \"schema:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"links\": {\n      \"@id\": \"schema:links\"\n    },\n    \"code\": {\n      \"@id\": \"schema:code\",\n      \"@type\": \"xsd:integer\"\n    },\n   \
  \ \"title\": {\n      \"@id\": \"schema:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detail\": {\n      \"@id\": \"schema:detail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"schema:source\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus/refs/heads/main/json-ld/amadeus-airline-routes-context.jsonld
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
