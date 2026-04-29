---
api_specs:
- filename: amadeus-solutions-flight-offers-search-openapi.yaml
  format: yaml
  label: Flight Offers Search API
  slug: flight-offers-search-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amadeus-solutions/refs/heads/main/openapi/amadeus-solutions-flight-offers-search-openapi.yaml
- filename: amadeus-solutions-flight-offers-price-openapi.yaml
  format: yaml
  label: Flight Offers Price API
  slug: flight-offers-price-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amadeus-solutions/refs/heads/main/openapi/amadeus-solutions-flight-offers-price-openapi.yaml
- filename: amadeus-solutions-branded-fares-upsell-openapi.yaml
  format: yaml
  label: Branded Fares Upsell API
  slug: branded-fares-upsell-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amadeus-solutions/refs/heads/main/openapi/amadeus-solutions-branded-fares-upsell-openapi.yaml
- filename: amadeus-solutions-seat-map-display-openapi.yaml
  format: yaml
  label: Seat Map Display API
  slug: seat-map-display-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amadeus-solutions/refs/heads/main/openapi/amadeus-solutions-seat-map-display-openapi.yaml
class_count: 22
classes:
- Co2Emission
- Collection_Meta_Upsell
- Payment
- OperatingFlight
- Price
- AircraftEquipment
- Error_400
- Fee
- Dictionaries
- Tax
- AllotmentDetails
- Extended_Price
- Issue
- OriginalFlightEndPoint
- ChargeableSeat
- BaggageAllowance
- OriginalFlightStop
- LocationValue
- FlightSegment
- FlightOffer
- Error_500
- FlightOfferUpsellIn
context_file: json-ld/amadeus-branded-fares-upsell-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus-solutions/refs/heads/main/json-ld/amadeus-branded-fares-upsell-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Branded Fares Upsell from Amadeus Solutions.
layout: jsonld
name: Amadeus Branded Fares Upsell Context
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
  name: weight
  type: integer
- container: ''
  name: weightUnit
  type: string
- container: ''
  name: cabin
  type: string
- container: ''
  name: count
  type: integer
- container: set
  name: oneWayUpselledCombinations
  type: string
- container: ''
  name: brand
  type: string
- container: ''
  name: binNumber
  type: integer
- container: set
  name: flightOfferIds
  type: string
- container: ''
  name: carrierCode
  type: string
- container: ''
  name: currency
  type: string
- container: ''
  name: total
  type: string
- container: ''
  name: base
  type: string
- container: set
  name: fees
  type: string
- container: set
  name: taxes
  type: string
- container: ''
  name: refundableTaxes
  type: string
- container: ''
  name: code
  type: string
- container: set
  name: errors
  type: string
- container: ''
  name: amount
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: locations
  type: string
- container: ''
  name: aircraft
  type: string
- container: ''
  name: currencies
  type: string
- container: ''
  name: carriers
  type: string
- container: ''
  name: tourName
  type: string
- container: ''
  name: tourReference
  type: string
- container: ''
  name: status
  type: integer
- container: ''
  name: title
  type: string
- container: ''
  name: detail
  type: string
- container: ''
  name: source
  type: string
- container: ''
  name: iataCode
  type: string
- container: ''
  name: terminal
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: number
  type: string
- container: ''
  name: quantity
  type: integer
- container: ''
  name: duration
  type: string
- container: ''
  name: cityCode
  type: string
- container: ''
  name: countryCode
  type: string
- container: ''
  name: departure
  type: string
- container: ''
  name: arrival
  type: string
- container: ''
  name: operating
  type: string
- container: set
  name: stops
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
  name: lastTicketingDateTime
  type: dateTime
- container: ''
  name: numberOfBookableSeats
  type: decimal
- container: set
  name: itineraries
  type: string
- container: ''
  name: price
  type: string
- container: ''
  name: pricingOptions
  type: string
- container: set
  name: validatingAirlineCodes
  type: string
- container: set
  name: travelerPricings
  type: string
- container: set
  name: flightOffers
  type: string
- container: set
  name: payments
  type: string
property_count: 56
provider_name: Amadeus Solutions
provider_slug: amadeus-solutions
slug: amadeus-branded-fares-upsell-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amadeus\": \"https://amadeus.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Co2Emission\": \"amadeus:Co2Emission\",\n    \"Collection_Meta_Upsell\": \"amadeus:Collection_Meta_Upsell\",\n    \"Payment\": \"amadeus:Payment\",\n    \"OperatingFlight\": \"amadeus:OperatingFlight\",\n    \"Price\": \"amadeus:Price\",\n    \"AircraftEquipment\": \"amadeus:AircraftEquipment\",\n    \"Error_400\": \"amadeus:Error_400\",\n    \"Fee\": \"amadeus:Fee\",\n    \"Dictionaries\": \"amadeus:Dictionaries\",\n    \"Tax\": \"amadeus:Tax\",\n    \"AllotmentDetails\": \"amadeus:AllotmentDetails\",\n    \"Extended_Price\": \"amadeus:Extended_Price\",\n    \"Issue\": \"amadeus:Issue\",\n    \"OriginalFlightEndPoint\": \"amadeus:OriginalFlightEndPoint\",\n    \"ChargeableSeat\": \"amadeus:ChargeableSeat\",\n    \"BaggageAllowance\"\
  : \"amadeus:BaggageAllowance\",\n    \"OriginalFlightStop\": \"amadeus:OriginalFlightStop\",\n    \"LocationValue\": \"amadeus:LocationValue\",\n    \"FlightSegment\": \"amadeus:FlightSegment\",\n    \"FlightOffer\": \"amadeus:FlightOffer\",\n    \"Error_500\": \"amadeus:Error_500\",\n    \"FlightOfferUpsellIn\": \"amadeus:FlightOfferUpsellIn\",\n    \"weight\": {\n      \"@id\": \"amadeus:weight\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"weightUnit\": {\n      \"@id\": \"amadeus:weightUnit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cabin\": {\n      \"@id\": \"amadeus:cabin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"count\": {\n      \"@id\": \"amadeus:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"oneWayUpselledCombinations\": {\n      \"@id\": \"amadeus:oneWayUpselledCombinations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brand\": {\n      \"@id\": \"amadeus:brand\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"binNumber\": {\n      \"@id\": \"amadeus:binNumber\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"flightOfferIds\": {\n      \"@id\": \"amadeus:flightOfferIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carrierCode\": {\n      \"@id\": \"amadeus:carrierCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currency\": {\n      \"@id\": \"amadeus:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"total\": {\n      \"@id\": \"amadeus:total\",\n      \"@type\": \"xsd:string\"\n    },\n    \"base\": {\n      \"@id\": \"amadeus:base\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fees\": {\n      \"@id\": \"amadeus:fees\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxes\": {\n      \"@id\": \"amadeus:taxes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"refundableTaxes\": {\n      \"@id\": \"amadeus:refundableTaxes\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"code\": {\n      \"@id\": \"amadeus:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errors\": {\n      \"@id\": \"amadeus:errors\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"amadeus:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"amadeus:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locations\": {\n      \"@id\": \"amadeus:locations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aircraft\": {\n      \"@id\": \"amadeus:aircraft\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencies\": {\n      \"@id\": \"amadeus:currencies\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carriers\": {\n      \"@id\": \"amadeus:carriers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tourName\": {\n      \"@id\": \"amadeus:tourName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tourReference\": {\n      \"@id\": \"amadeus:tourReference\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"amadeus:status\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"title\": {\n      \"@id\": \"amadeus:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detail\": {\n      \"@id\": \"amadeus:detail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"amadeus:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iataCode\": {\n      \"@id\": \"amadeus:iataCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"terminal\": {\n      \"@id\": \"amadeus:terminal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"amadeus:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"number\": {\n      \"@id\": \"amadeus:number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quantity\": {\n      \"@id\": \"amadeus:quantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"duration\": {\n      \"@id\": \"amadeus:duration\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"cityCode\": {\n      \"@id\": \"amadeus:cityCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryCode\": {\n      \"@id\": \"amadeus:countryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"departure\": {\n      \"@id\": \"amadeus:departure\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arrival\": {\n      \"@id\": \"amadeus:arrival\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operating\": {\n      \"@id\": \"amadeus:operating\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stops\": {\n      \"@id\": \"amadeus:stops\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instantTicketingRequired\": {\n      \"@id\": \"amadeus:instantTicketingRequired\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"disablePricing\": {\n      \"@id\": \"amadeus:disablePricing\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"nonHomogeneous\": {\n      \"@id\": \"amadeus:nonHomogeneous\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"\
  oneWay\": {\n      \"@id\": \"amadeus:oneWay\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"paymentCardRequired\": {\n      \"@id\": \"amadeus:paymentCardRequired\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lastTicketingDate\": {\n      \"@id\": \"amadeus:lastTicketingDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastTicketingDateTime\": {\n      \"@id\": \"amadeus:lastTicketingDateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"numberOfBookableSeats\": {\n      \"@id\": \"amadeus:numberOfBookableSeats\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"itineraries\": {\n      \"@id\": \"amadeus:itineraries\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"price\": {\n      \"@id\": \"amadeus:price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pricingOptions\": {\n      \"@id\": \"amadeus:pricingOptions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"validatingAirlineCodes\": {\n      \"@id\": \"amadeus:validatingAirlineCodes\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"travelerPricings\": {\n      \"@id\": \"amadeus:travelerPricings\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flightOffers\": {\n      \"@id\": \"amadeus:flightOffers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payments\": {\n      \"@id\": \"amadeus:payments\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus-solutions/refs/heads/main/json-ld/amadeus-branded-fares-upsell-context.jsonld
tags:
- Airlines
- Booking
- Flights
- GDS
- Hotels
- Travel
- Travel Technology
- JSON-LD
- Linked Data
- Semantic Web
---
