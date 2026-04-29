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
class_count: 1
classes:
- Address
context_file: json-ld/amadeus-hotel-booking-address-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/json-ld/amadeus-hotel-booking-address-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Hotel Booking Address from Amadeus Reservations.
layout: jsonld
name: Amadeus Hotel Booking Address Context
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
  name: lines
  type: string
- container: ''
  name: postalCode
  type: string
- container: ''
  name: countryCode
  type: string
- container: ''
  name: cityName
  type: string
- container: ''
  name: stateCode
  type: string
property_count: 5
provider_name: Amadeus Reservations
provider_slug: amadeus-reservations
slug: amadeus-hotel-booking-address-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amadeus\": \"https://amadeus.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Address\": \"amadeus:Address\",\n    \"lines\": {\n      \"@id\": \"amadeus:lines\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postalCode\": {\n      \"@id\": \"amadeus:postalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryCode\": {\n      \"@id\": \"amadeus:countryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cityName\": {\n      \"@id\": \"amadeus:cityName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stateCode\": {\n      \"@id\": \"amadeus:stateCode\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/json-ld/amadeus-hotel-booking-address-context.jsonld
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
