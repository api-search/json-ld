---
class_count: 0
classes: []
context_file: json-ld/amadeus-flight-choice-prediction-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus/refs/heads/main/json-ld/amadeus-flight-choice-prediction-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Flight Choice Prediction from Amadeus.
layout: jsonld
name: Amadeus Flight Choice Prediction Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: type
  type: string
- container: ''
  name: id
  type: ''
- container: ''
  name: choiceProbability
  type: string
- container: ''
  name: source
  type: string
- container: ''
  name: instantTicketingRequired
  type: boolean
- container: ''
  name: disablePricing
  type: boolean
- container: ''
  name: nonHomogeneous
  type: boolean
- container: ''
  name: oneWay
  type: boolean
- container: ''
  name: paymentCardRequired
  type: boolean
- container: ''
  name: lastTicketingDate
  type: string
- container: ''
  name: numberOfBookableSeats
  type: decimal
- container: ''
  name: itineraries
  type: ''
- container: ''
  name: price
  type: string
- container: ''
  name: pricingOptions
  type: ''
- container: ''
  name: validatingAirlineCodes
  type: ''
- container: ''
  name: travelerPricings
  type: ''
- container: ''
  name: fareRules
  type: string
property_count: 17
provider_name: Amadeus
provider_slug: amadeus
slug: amadeus-flight-choice-prediction-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"type\": {\n      \"@id\": \"schema:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"@id\"\n    },\n    \"choiceProbability\": {\n      \"@id\": \"schema:choiceProbability\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"schema:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instantTicketingRequired\": {\n      \"@id\": \"schema:instantTicketingRequired\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"disablePricing\": {\n      \"@id\": \"schema:disablePricing\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"nonHomogeneous\": {\n      \"@id\": \"schema:nonHomogeneous\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"oneWay\": {\n      \"@id\": \"schema:oneWay\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"paymentCardRequired\": {\n      \"@id\"\
  : \"schema:paymentCardRequired\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lastTicketingDate\": {\n      \"@id\": \"schema:lastTicketingDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"numberOfBookableSeats\": {\n      \"@id\": \"schema:numberOfBookableSeats\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"itineraries\": {\n      \"@id\": \"schema:itineraries\"\n    },\n    \"price\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pricingOptions\": {\n      \"@id\": \"schema:pricingOptions\"\n    },\n    \"validatingAirlineCodes\": {\n      \"@id\": \"schema:validatingAirlineCodes\"\n    },\n    \"travelerPricings\": {\n      \"@id\": \"schema:travelerPricings\"\n    },\n    \"fareRules\": {\n      \"@id\": \"schema:fareRules\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus/refs/heads/main/json-ld/amadeus-flight-choice-prediction-context.jsonld
tags:
- Airlines
- Aviation
- Booking
- Destinations
- Flights
- Hospitality
- Hotels
- Market Insights
- Tourism
- Transfers
- Travel
- JSON-LD
- Linked Data
- Semantic Web
---
