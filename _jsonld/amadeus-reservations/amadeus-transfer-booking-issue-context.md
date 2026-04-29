---
class_count: 1
classes:
- Issue
context_file: json-ld/amadeus-transfer-booking-issue-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/json-ld/amadeus-transfer-booking-issue-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Transfer Booking Issue from Amadeus Reservations.
layout: jsonld
name: Amadeus Transfer Booking Issue Context
namespaces:
- prefix: amadeus
  uri: https://amadeus.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: status
  type: integer
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
  type: reference
property_count: 5
provider_name: Amadeus Reservations
provider_slug: amadeus-reservations
slug: amadeus-transfer-booking-issue-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amadeus\": \"https://amadeus.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Issue\": \"amadeus:Issue\",\n    \"status\": {\n      \"@id\": \"amadeus:status\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"code\": {\n      \"@id\": \"amadeus:code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"title\": {\n      \"@id\": \"amadeus:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detail\": {\n      \"@id\": \"amadeus:detail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"amadeus:source\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/json-ld/amadeus-transfer-booking-issue-context.jsonld
tags:
- Booking
- Flights
- Hotels
- Reservations
- Travel
- JSON-LD
- Linked Data
- Semantic Web
---
