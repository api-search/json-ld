---
class_count: 0
classes: []
context_file: json-ld/amadeus-safe-place-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus/refs/heads/main/json-ld/amadeus-safe-place-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Safe Place from Amadeus.
layout: jsonld
name: Amadeus Safe Place Context
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
  name: women
  type: integer
- container: ''
  name: physicalHarm
  type: integer
- container: ''
  name: theft
  type: integer
- container: ''
  name: politicalFreedom
  type: integer
- container: ''
  name: lgbtq
  type: integer
- container: ''
  name: medical
  type: integer
- container: ''
  name: overall
  type: integer
property_count: 13
provider_name: Amadeus
provider_slug: amadeus
slug: amadeus-safe-place-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"id\": {\n      \"@id\": \"@id\"\n    },\n    \"self\": {\n      \"@id\": \"schema:self\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"schema:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subType\": {\n      \"@id\": \"schema:subType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"geoCode\": {\n      \"@id\": \"schema:geoCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"women\": {\n      \"@id\": \"schema:women\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"physicalHarm\": {\n      \"@id\": \"schema:physicalHarm\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"theft\": {\n      \"@id\": \"schema:theft\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"politicalFreedom\": {\n      \"@id\": \"schema:politicalFreedom\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"lgbtq\": {\n      \"@id\": \"schema:lgbtq\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"medical\": {\n      \"@id\": \"schema:medical\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"overall\": {\n      \"@id\": \"schema:overall\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus/refs/heads/main/json-ld/amadeus-safe-place-context.jsonld
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
