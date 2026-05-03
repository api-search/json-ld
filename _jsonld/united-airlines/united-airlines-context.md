---
api_specs:
- filename: united-airlines-ndc-openapi.yml
  format: yaml
  label: United Airlines NDC API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-airlines/main/openapi/united-airlines-ndc-openapi.yml
class_count: 0
classes: []
context_file: json-ld/united-airlines-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/united-airlines/refs/heads/main/json-ld/united-airlines-context.jsonld
description: JSON-LD context defining the semantic vocabulary for United Airlines from United Airlines.
layout: jsonld
name: United Airlines Context
namespaces:
- prefix: ua
  uri: https://schema.united.com/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Booking
  type: reference
- container: ''
  name: bookingId
  type: string
- container: ''
  name: recordLocator
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: FlightOffer
  type: reference
- container: ''
  name: offerId
  type: string
- container: ''
  name: fareType
  type: string
- container: ''
  name: fareClass
  type: string
- container: ''
  name: holdEligible
  type: boolean
- container: ''
  name: FlightSegment
  type: reference
- container: ''
  name: flightNumber
  type: string
- container: ''
  name: origin
  type: reference
- container: ''
  name: destination
  type: reference
- container: ''
  name: departureTime
  type: dateTime
- container: ''
  name: arrivalTime
  type: dateTime
- container: ''
  name: aircraft
  type: string
- container: ''
  name: operatingCarrier
  type: string
- container: ''
  name: Passenger
  type: reference
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: mileagePlusNumber
  type: string
- container: ''
  name: knownTravelerNumber
  type: string
- container: ''
  name: Price
  type: reference
- container: ''
  name: total
  type: decimal
- container: ''
  name: base
  type: decimal
- container: ''
  name: taxes
  type: decimal
- container: ''
  name: currency
  type: string
- container: ''
  name: FlightStatus
  type: reference
- container: ''
  name: scheduledDeparture
  type: dateTime
- container: ''
  name: estimatedDeparture
  type: dateTime
- container: ''
  name: actualDeparture
  type: dateTime
- container: ''
  name: scheduledArrival
  type: dateTime
- container: ''
  name: estimatedArrival
  type: dateTime
- container: ''
  name: actualArrival
  type: dateTime
- container: ''
  name: departureGate
  type: string
- container: ''
  name: arrivalGate
  type: string
- container: ''
  name: delayMinutes
  type: integer
- container: set
  name: passengers
  type: reference
- container: set
  name: itineraries
  type: reference
- container: list
  name: segments
  type: reference
- container: ''
  name: price
  type: reference
property_count: 41
provider_name: United Airlines
provider_slug: united-airlines
slug: united-airlines-context
source_filename: united-airlines-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ua\": \"https://schema.united.com/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Booking\": {\n      \"@id\": \"ua:Booking\",\n      \"@type\": \"@id\",\n      \"subClassOf\": \"schema:Order\"\n    },\n    \"bookingId\": { \"@id\": \"ua:bookingId\", \"@type\": \"xsd:string\" },\n    \"recordLocator\": { \"@id\": \"ua:recordLocator\", \"@type\": \"xsd:string\" },\n    \"status\": { \"@id\": \"ua:status\", \"@type\": \"xsd:string\" },\n\n    \"FlightOffer\": {\n      \"@id\": \"ua:FlightOffer\",\n      \"@type\": \"@id\",\n      \"subClassOf\": \"schema:Offer\"\n    },\n    \"offerId\": { \"@id\": \"ua:offerId\", \"@type\": \"xsd:string\" },\n    \"fareType\": { \"@id\": \"ua:fareType\", \"@type\": \"xsd:string\" },\n    \"fareClass\": { \"@id\": \"ua:fareClass\", \"@type\": \"xsd:string\" },\n    \"holdEligible\": { \"@id\": \"ua:holdEligible\", \"@type\": \"xsd:boolean\"\
  \ },\n\n    \"FlightSegment\": {\n      \"@id\": \"ua:FlightSegment\",\n      \"@type\": \"@id\",\n      \"subClassOf\": \"schema:Trip\"\n    },\n    \"flightNumber\": { \"@id\": \"ua:flightNumber\", \"@type\": \"xsd:string\" },\n    \"origin\": { \"@id\": \"schema:departureAirport\", \"@type\": \"@id\" },\n    \"destination\": { \"@id\": \"schema:arrivalAirport\", \"@type\": \"@id\" },\n    \"departureTime\": { \"@id\": \"schema:departureTime\", \"@type\": \"xsd:dateTime\" },\n    \"arrivalTime\": { \"@id\": \"schema:arrivalTime\", \"@type\": \"xsd:dateTime\" },\n    \"aircraft\": { \"@id\": \"ua:aircraft\", \"@type\": \"xsd:string\" },\n    \"operatingCarrier\": { \"@id\": \"ua:operatingCarrier\", \"@type\": \"xsd:string\" },\n\n    \"Passenger\": {\n      \"@id\": \"ua:Passenger\",\n      \"@type\": \"@id\",\n      \"subClassOf\": \"schema:Person\"\n    },\n    \"firstName\": { \"@id\": \"schema:givenName\", \"@type\": \"xsd:string\" },\n    \"lastName\": { \"@id\": \"schema:familyName\"\
  , \"@type\": \"xsd:string\" },\n    \"mileagePlusNumber\": { \"@id\": \"ua:mileagePlusNumber\", \"@type\": \"xsd:string\" },\n    \"knownTravelerNumber\": { \"@id\": \"ua:knownTravelerNumber\", \"@type\": \"xsd:string\" },\n\n    \"Price\": {\n      \"@id\": \"ua:Price\",\n      \"@type\": \"@id\",\n      \"subClassOf\": \"schema:PriceSpecification\"\n    },\n    \"total\": { \"@id\": \"schema:price\", \"@type\": \"xsd:decimal\" },\n    \"base\": { \"@id\": \"ua:basePrice\", \"@type\": \"xsd:decimal\" },\n    \"taxes\": { \"@id\": \"ua:taxAmount\", \"@type\": \"xsd:decimal\" },\n    \"currency\": { \"@id\": \"schema:priceCurrency\", \"@type\": \"xsd:string\" },\n\n    \"FlightStatus\": {\n      \"@id\": \"ua:FlightStatus\",\n      \"@type\": \"@id\",\n      \"subClassOf\": \"schema:Trip\"\n    },\n    \"scheduledDeparture\": { \"@id\": \"ua:scheduledDeparture\", \"@type\": \"xsd:dateTime\" },\n    \"estimatedDeparture\": { \"@id\": \"ua:estimatedDeparture\", \"@type\": \"xsd:dateTime\"\
  \ },\n    \"actualDeparture\": { \"@id\": \"ua:actualDeparture\", \"@type\": \"xsd:dateTime\" },\n    \"scheduledArrival\": { \"@id\": \"ua:scheduledArrival\", \"@type\": \"xsd:dateTime\" },\n    \"estimatedArrival\": { \"@id\": \"ua:estimatedArrival\", \"@type\": \"xsd:dateTime\" },\n    \"actualArrival\": { \"@id\": \"ua:actualArrival\", \"@type\": \"xsd:dateTime\" },\n    \"departureGate\": { \"@id\": \"ua:departureGate\", \"@type\": \"xsd:string\" },\n    \"arrivalGate\": { \"@id\": \"ua:arrivalGate\", \"@type\": \"xsd:string\" },\n    \"delayMinutes\": { \"@id\": \"ua:delayMinutes\", \"@type\": \"xsd:integer\" },\n\n    \"passengers\": { \"@id\": \"ua:hasPassenger\", \"@type\": \"@id\", \"@container\": \"@set\" },\n    \"itineraries\": { \"@id\": \"ua:hasItinerary\", \"@type\": \"@id\", \"@container\": \"@set\" },\n    \"segments\": { \"@id\": \"ua:hasSegment\", \"@type\": \"@id\", \"@container\": \"@list\" },\n    \"price\": { \"@id\": \"ua:hasPrice\", \"@type\": \"@id\" }\n  }\n\
  }\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/united-airlines/refs/heads/main/json-ld/united-airlines-context.jsonld
tags:
- Airlines
- Travel
- Flight Booking
- NDC
- Loyalty
- Fortune 100
- JSON-LD
- Linked Data
- Semantic Web
---
