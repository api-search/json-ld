---
class_count: 5
classes:
- FlightStatus
- Flight
- FlightList
- BookingRequest
- Booking
context_file: json-ld/american-airlines-runway-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/american-airlines/refs/heads/main/json-ld/american-airlines-runway-context.jsonld
description: JSON-LD context defining the semantic vocabulary for American Airlines Runway from American Airlines.
layout: jsonld
name: American Airlines Runway Context
namespaces:
- prefix: aa
  uri: https://aa.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: flightId
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: gate
  type: string
- container: ''
  name: delay
  type: integer
- container: ''
  name: id
  type: string
- container: ''
  name: flightNumber
  type: string
- container: ''
  name: origin
  type: string
- container: ''
  name: destination
  type: string
- container: ''
  name: departureTime
  type: dateTime
- container: ''
  name: arrivalTime
  type: dateTime
- container: set
  name: flights
  type: string
- container: set
  name: passengers
  type: string
property_count: 12
provider_name: American Airlines
provider_slug: american-airlines
slug: american-airlines-runway-context
source_filename: american-airlines-runway-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aa\": \"https://aa.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"FlightStatus\": \"aa:FlightStatus\",\n    \"flightId\": {\n      \"@id\": \"aa:flightId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"aa:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gate\": {\n      \"@id\": \"aa:gate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"delay\": {\n      \"@id\": \"aa:delay\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Flight\": \"aa:Flight\",\n    \"id\": {\n      \"@id\": \"aa:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flightNumber\": {\n      \"@id\": \"aa:flightNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"origin\": {\n      \"@id\": \"aa:origin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destination\": {\n      \"@id\": \"aa:destination\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"departureTime\": {\n      \"@id\": \"aa:departureTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"arrivalTime\": {\n      \"@id\": \"aa:arrivalTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"FlightList\": \"aa:FlightList\",\n    \"flights\": {\n      \"@id\": \"aa:flights\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BookingRequest\": \"aa:BookingRequest\",\n    \"passengers\": {\n      \"@id\": \"aa:passengers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Booking\": \"aa:Booking\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/american-airlines/refs/heads/main/json-ld/american-airlines-runway-context.jsonld
tags:
- Airlines
- Aviation
- Flights
- Travel
- Booking
- Developer Experience
- JSON-LD
- Linked Data
- Semantic Web
---
