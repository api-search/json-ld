---
class_count: 2
classes:
- Equipment
- description
context_file: json-ld/amadeus-transfer-booking-equipment-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/json-ld/amadeus-transfer-booking-equipment-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Transfer Booking Equipment from Amadeus Reservations.
layout: jsonld
name: Amadeus Transfer Booking Equipment Context
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
  name: itemId
  type: string
- container: ''
  name: quotation
  type: string
- container: ''
  name: converted
  type: string
- container: ''
  name: isBookable
  type: boolean
- container: ''
  name: taxIncluded
  type: boolean
- container: ''
  name: includedInTotal
  type: boolean
property_count: 7
provider_name: Amadeus Reservations
provider_slug: amadeus-reservations
slug: amadeus-transfer-booking-equipment-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amadeus\": \"https://amadeus.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Equipment\": \"amadeus:Equipment\",\n    \"code\": {\n      \"@id\": \"amadeus:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"itemId\": {\n      \"@id\": \"amadeus:itemId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"quotation\": {\n      \"@id\": \"amadeus:quotation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"converted\": {\n      \"@id\": \"amadeus:converted\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isBookable\": {\n      \"@id\": \"amadeus:isBookable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"taxIncluded\": {\n      \"@id\": \"amadeus:taxIncluded\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"includedInTotal\": {\n      \"@id\": \"amadeus:includedInTotal\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/json-ld/amadeus-transfer-booking-equipment-context.jsonld
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
