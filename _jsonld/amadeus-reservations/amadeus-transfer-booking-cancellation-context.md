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
- CancellationRule
context_file: json-ld/amadeus-transfer-booking-cancellation-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/json-ld/amadeus-transfer-booking-cancellation-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Transfer Booking Cancellation from Amadeus Reservations.
layout: jsonld
name: Amadeus Transfer Booking Cancellation Context
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
  name: ruleDescription
  type: string
- container: ''
  name: feeType
  type: string
- container: ''
  name: feeValue
  type: string
- container: ''
  name: currencyCode
  type: string
- container: ''
  name: metricType
  type: string
- container: ''
  name: metricMin
  type: string
- container: ''
  name: metricMax
  type: string
property_count: 7
provider_name: Amadeus Reservations
provider_slug: amadeus-reservations
slug: amadeus-transfer-booking-cancellation-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amadeus\": \"https://amadeus.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CancellationRule\": \"amadeus:CancellationRule\",\n    \"ruleDescription\": {\n      \"@id\": \"amadeus:ruleDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"feeType\": {\n      \"@id\": \"amadeus:feeType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"feeValue\": {\n      \"@id\": \"amadeus:feeValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencyCode\": {\n      \"@id\": \"amadeus:currencyCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metricType\": {\n      \"@id\": \"amadeus:metricType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metricMin\": {\n      \"@id\": \"amadeus:metricMin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metricMax\": {\n      \"@id\": \"amadeus:metricMax\",\n  \
  \    \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/json-ld/amadeus-transfer-booking-cancellation-context.jsonld
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
