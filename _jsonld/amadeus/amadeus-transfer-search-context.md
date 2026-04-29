---
class_count: 0
classes: []
context_file: json-ld/amadeus-transfer-search-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus/refs/heads/main/json-ld/amadeus-transfer-search-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Transfer Search from Amadeus.
layout: jsonld
name: Amadeus Transfer Search Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: line
  type: string
- container: ''
  name: zip
  type: string
- container: ''
  name: countryCode
  type: string
- container: ''
  name: cityName
  type: string
- container: ''
  name: stateCode
  type: string
property_count: 5
provider_name: Amadeus
provider_slug: amadeus
slug: amadeus-transfer-search-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"line\": {\n      \"@id\": \"schema:line\",\n      \"@type\": \"xsd:string\"\n    },\n    \"zip\": {\n      \"@id\": \"schema:zip\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryCode\": {\n      \"@id\": \"schema:countryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cityName\": {\n      \"@id\": \"schema:cityName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stateCode\": {\n      \"@id\": \"schema:stateCode\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus/refs/heads/main/json-ld/amadeus-transfer-search-context.jsonld
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
