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
- Guest
- email
context_file: json-ld/amadeus-hotel-booking-guest-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/json-ld/amadeus-hotel-booking-guest-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Hotel Booking Guest from Amadeus Reservations.
layout: jsonld
name: Amadeus Hotel Booking Guest Context
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
  name: frequentTraveler
  type: ''
- container: ''
  name: phone
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: childAge
  type: integer
property_count: 6
provider_name: Amadeus Reservations
provider_slug: amadeus-reservations
slug: amadeus-hotel-booking-guest-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amadeus\": \"https://amadeus.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Guest\": \"amadeus:Guest\",\n    \"frequentTraveler\": {\n      \"@id\": \"amadeus:frequentTraveler\",\n      \"@container\": \"@set\"\n    },\n    \"phone\": {\n      \"@id\": \"amadeus:phone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": \"schema:email\",\n    \"title\": {\n      \"@id\": \"amadeus:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstName\": {\n      \"@id\": \"amadeus:firstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"amadeus:lastName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"childAge\": {\n      \"@id\": \"amadeus:childAge\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/json-ld/amadeus-hotel-booking-guest-context.jsonld
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
