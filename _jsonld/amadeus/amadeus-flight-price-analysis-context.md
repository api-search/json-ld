---
class_count: 0
classes: []
context_file: json-ld/amadeus-flight-price-analysis-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus/refs/heads/main/json-ld/amadeus-flight-price-analysis-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Flight Price Analysis from Amadeus.
layout: jsonld
name: Amadeus Flight Price Analysis Context
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
  name: origin
  type: ''
- container: ''
  name: destination
  type: ''
- container: ''
  name: departureDate
  type: string
- container: ''
  name: transportType
  type: string
- container: ''
  name: currencyCode
  type: string
- container: ''
  name: oneWay
  type: boolean
- container: ''
  name: priceMetrics
  type: ''
- container: ''
  name: errors
  type: ''
property_count: 9
provider_name: Amadeus
provider_slug: amadeus
slug: amadeus-flight-price-analysis-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"type\": {\n      \"@id\": \"schema:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"origin\": {\n      \"@id\": \"schema:origin\"\n    },\n    \"destination\": {\n      \"@id\": \"schema:destination\"\n    },\n    \"departureDate\": {\n      \"@id\": \"schema:departureDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transportType\": {\n      \"@id\": \"schema:transportType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencyCode\": {\n      \"@id\": \"schema:currencyCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"oneWay\": {\n      \"@id\": \"schema:oneWay\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"priceMetrics\": {\n      \"@id\": \"schema:priceMetrics\"\n    },\n    \"errors\": {\n      \"@id\": \"schema:errors\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus/refs/heads/main/json-ld/amadeus-flight-price-analysis-context.jsonld
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
