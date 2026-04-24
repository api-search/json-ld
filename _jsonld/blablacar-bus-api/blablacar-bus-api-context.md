---
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
