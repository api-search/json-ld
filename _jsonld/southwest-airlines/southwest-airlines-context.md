---
class_count: 8
classes:
- Airline
- Flight
- FlightReservation
- BoardingPass
- Airport
- Passenger
- LoyaltyProgram
- Fare
context_file: json-ld/southwest-airlines-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/southwest-airlines/refs/heads/main/json-ld/southwest-airlines-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Southwest Airlines from Southwest Airlines.
layout: jsonld
name: Southwest Airlines Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: swa
  uri: https://api-evangelist.github.io/southwest-airlines/vocab#
properties:
- container: ''
  name: flightNumber
  type: string
- container: ''
  name: departureAirport
  type: reference
- container: ''
  name: arrivalAirport
  type: reference
- container: ''
  name: departureTime
  type: dateTime
- container: ''
  name: arrivalTime
  type: dateTime
- container: ''
  name: aircraft
  type: reference
- container: ''
  name: flightStatus
  type: string
- container: ''
  name: fareClass
  type: string
- container: ''
  name: fareAmount
  type: decimal
- container: ''
  name: confirmationNumber
  type: string
- container: ''
  name: boardingGroup
  type: string
- container: ''
  name: boardingPosition
  type: integer
- container: ''
  name: rapidRewardsNumber
  type: string
- container: ''
  name: pointsBalance
  type: integer
- container: ''
  name: tierStatus
  type: string
- container: ''
  name: iataCode
  type: string
property_count: 16
provider_name: Southwest Airlines
provider_slug: southwest-airlines
slug: southwest-airlines-context
source_filename: southwest-airlines-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"swa\": \"https://api-evangelist.github.io/southwest-airlines/vocab#\",\n\n    \"Airline\": \"schema:Airline\",\n    \"Flight\": \"schema:Flight\",\n    \"FlightReservation\": \"schema:FlightReservation\",\n    \"BoardingPass\": \"schema:Ticket\",\n    \"Airport\": \"schema:Airport\",\n    \"Passenger\": \"schema:Person\",\n    \"LoyaltyProgram\": \"schema:ProgramMembership\",\n    \"Fare\": \"schema:Offer\",\n\n    \"flightNumber\": {\n      \"@id\": \"schema:flightNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"departureAirport\": {\n      \"@id\": \"schema:departureAirport\",\n      \"@type\": \"@id\"\n    },\n    \"arrivalAirport\": {\n      \"@id\": \"schema:arrivalAirport\",\n      \"@type\": \"@id\"\n    },\n    \"departureTime\": {\n      \"@id\": \"schema:departureTime\",\n      \"@type\": \"xsd:dateTime\"\n   \
  \ },\n    \"arrivalTime\": {\n      \"@id\": \"schema:arrivalTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"aircraft\": {\n      \"@id\": \"schema:vehicle\",\n      \"@type\": \"@id\"\n    },\n    \"flightStatus\": {\n      \"@id\": \"swa:flightStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fareClass\": {\n      \"@id\": \"swa:fareClass\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fareAmount\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"confirmationNumber\": {\n      \"@id\": \"swa:confirmationNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"boardingGroup\": {\n      \"@id\": \"swa:boardingGroup\",\n      \"@type\": \"xsd:string\"\n    },\n    \"boardingPosition\": {\n      \"@id\": \"swa:boardingPosition\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"rapidRewardsNumber\": {\n      \"@id\": \"swa:rapidRewardsNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pointsBalance\": {\n      \"@id\": \"\
  swa:pointsBalance\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"tierStatus\": {\n      \"@id\": \"swa:tierStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iataCode\": {\n      \"@id\": \"schema:iataCode\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/southwest-airlines/refs/heads/main/json-ld/southwest-airlines-context.jsonld
tags:
- Fortune 500
- Airlines
- Aviation
- Travel
- JSON-LD
- Linked Data
- Semantic Web
---
