---
api_specs:
- filename: flightaware-aeroapi-openapi.yml
  format: yaml
  label: FlightAware AeroAPI
  slug: flightaware-aeroapi
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rockwell-collins/refs/heads/main/openapi/flightaware-aeroapi-openapi.yml
class_count: 3
classes:
- FlightAlert
- FlightPosition
- FlightTrack
context_file: json-ld/rockwell-collins-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/rockwell-collins/refs/heads/main/json-ld/rockwell-collins-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Rockwell Collins from Rockwell Collins.
layout: jsonld
name: Rockwell Collins Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: aeroapi
  uri: https://api-evangelist.github.io/rockwell-collins/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Flight
  type: reference
- container: ''
  name: Airport
  type: reference
- container: ''
  name: Airline
  type: reference
- container: ''
  name: ident
  type: string
- container: ''
  name: fa_flight_id
  type: string
- container: ''
  name: operator
  type: reference
- container: ''
  name: registration
  type: string
- container: ''
  name: aircraft_type
  type: string
- container: ''
  name: origin
  type: reference
- container: ''
  name: destination
  type: reference
- container: ''
  name: scheduled_out
  type: dateTime
- container: ''
  name: actual_out
  type: dateTime
- container: ''
  name: scheduled_on
  type: dateTime
- container: ''
  name: actual_on
  type: dateTime
- container: ''
  name: departure_delay
  type: integer
- container: ''
  name: arrival_delay
  type: integer
- container: ''
  name: status
  type: string
- container: ''
  name: progress_percent
  type: integer
- container: ''
  name: latitude
  type: double
- container: ''
  name: longitude
  type: double
- container: ''
  name: altitude
  type: integer
- container: ''
  name: groundspeed
  type: integer
- container: ''
  name: heading
  type: integer
- container: ''
  name: name
  type: string
- container: ''
  name: iataCode
  type: string
- container: ''
  name: icaoCode
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: timezone
  type: string
- container: ''
  name: elevation
  type: integer
- container: ''
  name: url
  type: reference
property_count: 31
provider_name: Rockwell Collins
provider_slug: rockwell-collins
slug: rockwell-collins-context
source_filename: rockwell-collins-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"aeroapi\": \"https://api-evangelist.github.io/rockwell-collins/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Flight\": {\n      \"@id\": \"schema:Flight\",\n      \"@type\": \"@id\"\n    },\n    \"Airport\": {\n      \"@id\": \"schema:Airport\",\n      \"@type\": \"@id\"\n    },\n    \"Airline\": {\n      \"@id\": \"schema:Airline\",\n      \"@type\": \"@id\"\n    },\n    \"FlightAlert\": \"aeroapi:FlightAlert\",\n    \"FlightPosition\": \"aeroapi:FlightPosition\",\n    \"FlightTrack\": \"aeroapi:FlightTrack\",\n\n    \"ident\": {\n      \"@id\": \"schema:flightNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fa_flight_id\": {\n      \"@id\": \"aeroapi:flightAwareFlightId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operator\": {\n      \"@id\": \"schema:airline\",\n      \"@type\": \"@id\"\n    },\n    \"registration\": {\n      \"@id\": \"\
  aeroapi:registration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aircraft_type\": {\n      \"@id\": \"schema:vehicleModelDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"origin\": {\n      \"@id\": \"schema:departureAirport\",\n      \"@type\": \"@id\"\n    },\n    \"destination\": {\n      \"@id\": \"schema:arrivalAirport\",\n      \"@type\": \"@id\"\n    },\n    \"scheduled_out\": {\n      \"@id\": \"schema:departureTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"actual_out\": {\n      \"@id\": \"aeroapi:actualDepartureTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"scheduled_on\": {\n      \"@id\": \"schema:arrivalTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"actual_on\": {\n      \"@id\": \"aeroapi:actualArrivalTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"departure_delay\": {\n      \"@id\": \"aeroapi:departureDelay\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"arrival_delay\": {\n      \"@id\": \"aeroapi:arrivalDelay\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"status\": {\n      \"@id\": \"schema:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"progress_percent\": {\n      \"@id\": \"aeroapi:progressPercent\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"latitude\": {\n      \"@id\": \"schema:latitude\",\n      \"@type\": \"xsd:double\"\n    },\n    \"longitude\": {\n      \"@id\": \"schema:longitude\",\n      \"@type\": \"xsd:double\"\n    },\n    \"altitude\": {\n      \"@id\": \"aeroapi:altitude\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"groundspeed\": {\n      \"@id\": \"aeroapi:groundSpeed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"heading\": {\n      \"@id\": \"aeroapi:heading\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iataCode\": {\n      \"@id\": \"schema:iataCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"icaoCode\": {\n      \"@id\": \"aeroapi:icaoCode\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"schema:addressLocality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"schema:addressCountry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timezone\": {\n      \"@id\": \"aeroapi:timezone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"elevation\": {\n      \"@id\": \"aeroapi:elevation\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/rockwell-collins/refs/heads/main/json-ld/rockwell-collins-context.jsonld
tags:
- Avionics
- Aerospace
- Defense
- Aviation
- Flight Deck
- JSON-LD
- Linked Data
- Semantic Web
---
