---
class_count: 2
classes:
- ServiceProvider
- name
context_file: json-ld/amadeus-transfer-booking-service-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/json-ld/amadeus-transfer-booking-service-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Transfer Booking Service from Amadeus Reservations.
layout: jsonld
name: Amadeus Transfer Booking Service Context
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
  name: code
  type: string
- container: ''
  name: logoUrl
  type: string
- container: ''
  name: termsUrl
  type: string
- container: ''
  name: isPreferred
  type: boolean
- container: ''
  name: contacts
  type: string
- container: set
  name: settings
  type: string
- container: ''
  name: businessIdentification
  type: string
property_count: 7
provider_name: Amadeus Reservations
provider_slug: amadeus-reservations
slug: amadeus-transfer-booking-service-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amadeus\": \"https://amadeus.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ServiceProvider\": \"amadeus:ServiceProvider\",\n    \"code\": {\n      \"@id\": \"amadeus:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"logoUrl\": {\n      \"@id\": \"amadeus:logoUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"termsUrl\": {\n      \"@id\": \"amadeus:termsUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isPreferred\": {\n      \"@id\": \"amadeus:isPreferred\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"contacts\": {\n      \"@id\": \"amadeus:contacts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"settings\": {\n      \"@id\": \"amadeus:settings\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"businessIdentification\"\
  : {\n      \"@id\": \"amadeus:businessIdentification\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/json-ld/amadeus-transfer-booking-service-context.jsonld
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
