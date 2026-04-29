---
api_specs:
- filename: amadeus-reservations-hotel-booking-openapi.yaml
  format: yaml
  label: Hotel Booking API
  slug: hotel-booking-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/openapi/amadeus-reservations-hotel-booking-openapi.yaml
- filename: amadeus-reservations-flight-create-orders-openapi.yaml
  format: yaml
  label: Flight Create Orders API
  slug: flight-create-orders-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/openapi/amadeus-reservations-flight-create-orders-openapi.yaml
- filename: amadeus-reservations-flight-order-management-openapi.yaml
  format: yaml
  label: Flight Order Management API
  slug: flight-order-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/openapi/amadeus-reservations-flight-order-management-openapi.yaml
- filename: amadeus-reservations-transfer-booking-openapi.yaml
  format: yaml
  label: Transfer Booking API
  slug: transfer-booking-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/openapi/amadeus-reservations-transfer-booking-openapi.yaml
- filename: amadeus-reservations-transfer-management-openapi.yaml
  format: yaml
  label: Transfer Management API
  slug: transfer-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/openapi/amadeus-reservations-transfer-management-openapi.yaml
class_count: 2
classes:
- TravelSegmentLocation
- TravelSegment
context_file: json-ld/amadeus-transfer-booking-travel-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/json-ld/amadeus-transfer-booking-travel-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Transfer Booking Travel from Amadeus Reservations.
layout: jsonld
name: Amadeus Transfer Booking Travel Context
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
  name: uicCode
  type: string
- container: ''
  name: iataCode
  type: string
- container: ''
  name: localDateTime
  type: dateTime
- container: ''
  name: transportationType
  type: string
- container: ''
  name: transportationNumber
  type: string
- container: ''
  name: departure
  type: string
- container: ''
  name: arrival
  type: string
property_count: 7
provider_name: Amadeus Reservations
provider_slug: amadeus-reservations
slug: amadeus-transfer-booking-travel-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amadeus\": \"https://amadeus.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"TravelSegmentLocation\": \"amadeus:TravelSegmentLocation\",\n    \"TravelSegment\": \"amadeus:TravelSegment\",\n    \"uicCode\": {\n      \"@id\": \"amadeus:uicCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iataCode\": {\n      \"@id\": \"amadeus:iataCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"localDateTime\": {\n      \"@id\": \"amadeus:localDateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"transportationType\": {\n      \"@id\": \"amadeus:transportationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transportationNumber\": {\n      \"@id\": \"amadeus:transportationNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"departure\": {\n      \"@id\": \"amadeus:departure\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"arrival\": {\n      \"@id\": \"amadeus:arrival\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/json-ld/amadeus-transfer-booking-travel-context.jsonld
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
