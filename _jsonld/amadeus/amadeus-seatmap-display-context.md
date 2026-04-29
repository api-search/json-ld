---
class_count: 0
classes: []
context_file: json-ld/amadeus-seatmap-display-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus/refs/heads/main/json-ld/amadeus-seatmap-display-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Seatmap Display from Amadeus.
layout: jsonld
name: Amadeus Seatmap Display Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: departure
  type: string
- container: ''
  name: arrival
  type: string
- container: ''
  name: carrierCode
  type: string
- container: ''
  name: number
  type: string
- container: ''
  name: aircraft
  type: string
- container: ''
  name: operating
  type: string
- container: ''
  name: duration
  type: string
- container: ''
  name: stops
  type: ''
- container: ''
  name: iataCode
  type: string
- container: ''
  name: terminal
  type: string
- container: ''
  name: at
  type: dateTime
- container: ''
  name: newAircraft
  type: string
- container: ''
  name: arrivalAt
  type: dateTime
- container: ''
  name: departureAt
  type: dateTime
property_count: 14
provider_name: Amadeus
provider_slug: amadeus
slug: amadeus-seatmap-display-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"departure\": {\n      \"@id\": \"schema:departure\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arrival\": {\n      \"@id\": \"schema:arrival\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carrierCode\": {\n      \"@id\": \"schema:carrierCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"number\": {\n      \"@id\": \"schema:number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aircraft\": {\n      \"@id\": \"schema:aircraft\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operating\": {\n      \"@id\": \"schema:operating\",\n      \"@type\": \"xsd:string\"\n    },\n    \"duration\": {\n      \"@id\": \"schema:duration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stops\": {\n      \"@id\": \"schema:stops\"\n    },\n    \"iataCode\": {\n      \"@id\": \"schema:iataCode\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"terminal\": {\n      \"@id\": \"schema:terminal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"at\": {\n      \"@id\": \"schema:at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"newAircraft\": {\n      \"@id\": \"schema:newAircraft\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arrivalAt\": {\n      \"@id\": \"schema:arrivalAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"departureAt\": {\n      \"@id\": \"schema:departureAt\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus/refs/heads/main/json-ld/amadeus-seatmap-display-context.jsonld
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
