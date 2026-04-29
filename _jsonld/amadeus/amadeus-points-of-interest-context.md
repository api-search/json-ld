---
class_count: 0
classes: []
context_file: json-ld/amadeus-points-of-interest-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus/refs/heads/main/json-ld/amadeus-points-of-interest-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Points Of Interest from Amadeus.
layout: jsonld
name: Amadeus Points Of Interest Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: id
  type: ''
- container: ''
  name: self
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: subType
  type: string
- container: ''
  name: name
  type: ''
- container: ''
  name: geoCode
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: tags
  type: ''
- container: ''
  name: rank
  type: string
- container: ''
  name: latitude
  type: decimal
- container: ''
  name: longitude
  type: decimal
- container: ''
  name: errors
  type: ''
property_count: 12
provider_name: Amadeus
provider_slug: amadeus
slug: amadeus-points-of-interest-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"id\": {\n      \"@id\": \"@id\"\n    },\n    \"self\": {\n      \"@id\": \"schema:self\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"schema:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subType\": {\n      \"@id\": \"schema:subType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"geoCode\": {\n      \"@id\": \"schema:geoCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"schema:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"schema:tags\"\n    },\n    \"rank\": {\n      \"@id\": \"schema:rank\",\n      \"@type\": \"xsd:string\"\n    },\n    \"latitude\": {\n      \"@id\": \"schema:latitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"longitude\": {\n\
  \      \"@id\": \"schema:longitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"errors\": {\n      \"@id\": \"schema:errors\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus/refs/heads/main/json-ld/amadeus-points-of-interest-context.jsonld
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
