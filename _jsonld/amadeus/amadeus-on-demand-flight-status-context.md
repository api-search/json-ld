---
class_count: 0
classes: []
context_file: json-ld/amadeus-on-demand-flight-status-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus/refs/heads/main/json-ld/amadeus-on-demand-flight-status-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus On Demand Flight Status from Amadeus.
layout: jsonld
name: Amadeus On Demand Flight Status Context
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
  name: scheduledDepartureDate
  type: date
- container: ''
  name: flightDesignator
  type: string
- container: ''
  name: flightPoints
  type: ''
- container: ''
  name: segments
  type: ''
- container: ''
  name: legs
  type: ''
- container: ''
  name: carrierCode
  type: string
- container: ''
  name: flightNumber
  type: integer
- container: ''
  name: operationalSuffix
  type: string
- container: ''
  name: iataCode
  type: string
- container: ''
  name: departure
  type: string
- container: ''
  name: arrival
  type: string
property_count: 12
provider_name: Amadeus
provider_slug: amadeus
slug: amadeus-on-demand-flight-status-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"type\": {\n      \"@id\": \"schema:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scheduledDepartureDate\": {\n      \"@id\": \"schema:scheduledDepartureDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"flightDesignator\": {\n      \"@id\": \"schema:flightDesignator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flightPoints\": {\n      \"@id\": \"schema:flightPoints\"\n    },\n    \"segments\": {\n      \"@id\": \"schema:segments\"\n    },\n    \"legs\": {\n      \"@id\": \"schema:legs\"\n    },\n    \"carrierCode\": {\n      \"@id\": \"schema:carrierCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flightNumber\": {\n      \"@id\": \"schema:flightNumber\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"operationalSuffix\": {\n      \"@id\": \"schema:operationalSuffix\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"iataCode\": {\n      \"@id\": \"schema:iataCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"departure\": {\n      \"@id\": \"schema:departure\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arrival\": {\n      \"@id\": \"schema:arrival\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus/refs/heads/main/json-ld/amadeus-on-demand-flight-status-context.jsonld
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
