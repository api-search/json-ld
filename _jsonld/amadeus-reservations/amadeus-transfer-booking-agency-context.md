---
class_count: 1
classes:
- Agency
context_file: json-ld/amadeus-transfer-booking-agency-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/json-ld/amadeus-transfer-booking-agency-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Transfer Booking Agency from Amadeus Reservations.
layout: jsonld
name: Amadeus Transfer Booking Agency Context
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
- container: set
  name: contacts
  type: ''
property_count: 1
provider_name: Amadeus Reservations
provider_slug: amadeus-reservations
slug: amadeus-transfer-booking-agency-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amadeus\": \"https://amadeus.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Agency\": \"amadeus:Agency\",\n    \"contacts\": {\n      \"@id\": \"amadeus:contacts\",\n      \"@container\": \"@set\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/json-ld/amadeus-transfer-booking-agency-context.jsonld
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
