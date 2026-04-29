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
- PaymentInput
- PaymentOutput
context_file: json-ld/amadeus-hotel-booking-payment-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/json-ld/amadeus-hotel-booking-payment-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Hotel Booking Payment from Amadeus Reservations.
layout: jsonld
name: Amadeus Hotel Booking Payment Context
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
  name: iataTravelAgency
  type: reference
- container: ''
  name: method
  type: string
- container: ''
  name: paymentCard
  type: reference
- container: ''
  name: billBack
  type: reference
- container: ''
  name: b2bWallet
  type: reference
property_count: 5
provider_name: Amadeus Reservations
provider_slug: amadeus-reservations
slug: amadeus-hotel-booking-payment-context
source_filename: amadeus-hotel-booking-payment-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amadeus\": \"https://amadeus.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PaymentInput\": \"amadeus:PaymentInput\",\n    \"PaymentOutput\": \"amadeus:PaymentOutput\",\n    \"iataTravelAgency\": {\n      \"@id\": \"amadeus:iataTravelAgency\",\n      \"@type\": \"@id\"\n    },\n    \"method\": {\n      \"@id\": \"amadeus:method\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentCard\": {\n      \"@id\": \"amadeus:paymentCard\",\n      \"@type\": \"@id\"\n    },\n    \"billBack\": {\n      \"@id\": \"amadeus:billBack\",\n      \"@type\": \"@id\"\n    },\n    \"b2bWallet\": {\n      \"@id\": \"amadeus:b2bWallet\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/json-ld/amadeus-hotel-booking-payment-context.jsonld
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
