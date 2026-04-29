---
class_count: 0
classes: []
context_file: json-ld/amadeus-tours-and-activities-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus/refs/heads/main/json-ld/amadeus-tours-and-activities-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Tours And Activities from Amadeus.
layout: jsonld
name: Amadeus Tours And Activities Context
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
  name: self
  type: string
- container: ''
  name: name
  type: ''
- container: ''
  name: shortDescription
  type: string
- container: ''
  name: description
  type: ''
- container: ''
  name: geoCode
  type: string
- container: ''
  name: rating
  type: string
- container: ''
  name: price
  type: string
- container: ''
  name: pictures
  type: ''
- container: ''
  name: bookingLink
  type: string
- container: ''
  name: minimumDuration
  type: string
- container: ''
  name: latitude
  type: decimal
- container: ''
  name: longitude
  type: decimal
- container: ''
  name: amount
  type: string
- container: ''
  name: currencyCode
  type: string
property_count: 16
provider_name: Amadeus
provider_slug: amadeus
slug: amadeus-tours-and-activities-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"type\": {\n      \"@id\": \"schema:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"@id\"\n    },\n    \"self\": {\n      \"@id\": \"schema:self\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"shortDescription\": {\n      \"@id\": \"schema:shortDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"geoCode\": {\n      \"@id\": \"schema:geoCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rating\": {\n      \"@id\": \"schema:rating\",\n      \"@type\": \"xsd:string\"\n    },\n    \"price\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pictures\": {\n      \"@id\": \"schema:pictures\"\n    },\n    \"bookingLink\": {\n\
  \      \"@id\": \"schema:bookingLink\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minimumDuration\": {\n      \"@id\": \"schema:minimumDuration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"latitude\": {\n      \"@id\": \"schema:latitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"longitude\": {\n      \"@id\": \"schema:longitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"amount\": {\n      \"@id\": \"schema:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencyCode\": {\n      \"@id\": \"schema:currencyCode\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus/refs/heads/main/json-ld/amadeus-tours-and-activities-context.jsonld
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
