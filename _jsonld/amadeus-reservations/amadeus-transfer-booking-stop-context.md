---
class_count: 1
classes:
- StopOver
context_file: json-ld/amadeus-transfer-booking-stop-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/json-ld/amadeus-transfer-booking-stop-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Transfer Booking Stop from Amadeus Reservations.
layout: jsonld
name: Amadeus Transfer Booking Stop Context
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
  name: duration
  type: string
- container: ''
  name: sequenceNumber
  type: decimal
- container: ''
  name: location
  type: string
property_count: 3
provider_name: Amadeus Reservations
provider_slug: amadeus-reservations
slug: amadeus-transfer-booking-stop-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amadeus\": \"https://amadeus.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"StopOver\": \"amadeus:StopOver\",\n    \"duration\": {\n      \"@id\": \"amadeus:duration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sequenceNumber\": {\n      \"@id\": \"amadeus:sequenceNumber\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"location\": {\n      \"@id\": \"amadeus:location\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/json-ld/amadeus-transfer-booking-stop-context.jsonld
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
