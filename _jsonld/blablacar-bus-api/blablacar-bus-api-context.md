---
api_specs:
- filename: blablacar-bus-api-openapi.yaml
  format: yaml
  label: BlaBlaCar Bus API
  slug: blablacar-bus-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/blablacar-bus-api/refs/heads/main/openapi/blablacar-bus-api-openapi.yaml
class_count: 13
classes:
- name
- city
- country_code
- latitude
- longitude
- address
- departure_datetime
- arrival_datetime
- Booking
- Route
- Station
- Ticket
- Trip
context_file: json-ld/blablacar-bus-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/blablacar-bus-api/refs/heads/main/json-ld/blablacar-bus-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Blablacar Bus Api from BlaBlaCar Bus API.
layout: jsonld
name: Blablacar Bus Api Context
namespaces:
- prefix: bbc
  uri: https://bus-api.blablacar.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: booking_id
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: partner_reference
  type: string
- container: ''
  name: total_price
  type: ''
- container: ''
  name: amount
  type: integer
- container: ''
  name: currency
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: from_station_id
  type: string
- container: ''
  name: to_station_id
  type: string
- container: ''
  name: duration_minutes
  type: integer
- container: ''
  name: distance_km
  type: integer
- container: ''
  name: ticket_id
  type: string
- container: ''
  name: passenger_name
  type: string
- container: ''
  name: from_station
  type: string
- container: ''
  name: to_station
  type: string
- container: ''
  name: seat_number
  type: string
- container: ''
  name: qr_code
  type: string
- container: ''
  name: route_id
  type: string
- container: ''
  name: available_seats
  type: integer
- container: ''
  name: price
  type: ''
property_count: 20
provider_name: BlaBlaCar Bus API
provider_slug: blablacar-bus-api
slug: blablacar-bus-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"bbc\": \"https://bus-api.blablacar.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"booking_id\": {\n      \"@id\": \"bbc:booking_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"bbc:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partner_reference\": {\n      \"@id\": \"bbc:partner_reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"total_price\": {\n      \"@id\": \"bbc:total_price\"\n    },\n    \"amount\": {\n      \"@id\": \"bbc:amount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"currency\": {\n      \"@id\": \"bbc:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"bbc:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"from_station_id\": {\n      \"@id\": \"bbc:from_station_id\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"to_station_id\": {\n      \"@id\": \"bbc:to_station_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"duration_minutes\": {\n      \"@id\": \"bbc:duration_minutes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"distance_km\": {\n      \"@id\": \"bbc:distance_km\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": \"schema:name\",\n    \"city\": \"schema:addressLocality\",\n    \"country_code\": \"schema:addressCountry\",\n    \"latitude\": \"schema:latitude\",\n    \"longitude\": \"schema:longitude\",\n    \"address\": \"schema:address\",\n    \"ticket_id\": {\n      \"@id\": \"bbc:ticket_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"passenger_name\": {\n      \"@id\": \"bbc:passenger_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"departure_datetime\": \"schema:departureTime\",\n    \"from_station\": {\n      \"@id\": \"bbc:from_station\",\n      \"@type\": \"xsd:string\"\n    },\n    \"to_station\": {\n      \"@id\": \"bbc:to_station\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"seat_number\": {\n      \"@id\": \"bbc:seat_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"qr_code\": {\n      \"@id\": \"bbc:qr_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"route_id\": {\n      \"@id\": \"bbc:route_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arrival_datetime\": \"schema:arrivalTime\",\n    \"available_seats\": {\n      \"@id\": \"bbc:available_seats\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"price\": {\n      \"@id\": \"bbc:price\"\n    },\n    \"Booking\": \"bbc:Booking\",\n    \"Route\": \"bbc:Route\",\n    \"Station\": \"bbc:Station\",\n    \"Ticket\": \"bbc:Ticket\",\n    \"Trip\": \"bbc:Trip\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/blablacar-bus-api/refs/heads/main/json-ld/blablacar-bus-api-context.jsonld
tags:
- Booking
- Buses
- Coach
- Europe
- Mobility
- Ticketing
- Transportation
- Travel
- JSON-LD
- Linked Data
- Semantic Web
---
