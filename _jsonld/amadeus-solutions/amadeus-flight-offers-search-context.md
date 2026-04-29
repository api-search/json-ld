---
class_count: 32
classes:
- OriginalFlightEndPoint
- OriginalFlightStop
- Error_400
- OperatingFlight
- ExtendedPricingOptions
- Collection_Meta
- DateTimeType
- GetFlightOffersQuery
- SearchCriteria
- BaggageAllowance
- ConnectionRestriction
- Issue
- FlightOffer
- AllotmentDetails
- FlightFilters
- LocationValue
- CarrierRestrictions
- CabinRestriction
- Co2Emission
- Collection_Meta_Link
- Price
- Extended_Price
- AircraftEquipment
- OriginDestinationLight
- Tax
- Extended_PricingOptions
- Dictionaries
- FlightSegment
- ChargeableSeat
- Fee
- TravelerInfo
- Error_500
context_file: json-ld/amadeus-flight-offers-search-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus-solutions/refs/heads/main/json-ld/amadeus-flight-offers-search-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Flight Offers Search from Amadeus Solutions.
layout: jsonld
name: Amadeus Flight Offers Search Context
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
  name: iataCode
  type: string
- container: ''
  name: terminal
  type: string
- container: ''
  name: duration
  type: string
- container: set
  name: errors
  type: string
- container: ''
  name: carrierCode
  type: string
- container: ''
  name: includedCheckedBagsOnly
  type: boolean
- container: ''
  name: refundableFare
  type: boolean
- container: ''
  name: noRestrictionFare
  type: boolean
- container: ''
  name: noPenaltyFare
  type: boolean
- container: ''
  name: count
  type: integer
- container: set
  name: oneWayCombinations
  type: string
- container: ''
  name: date
  type: date
- container: ''
  name: time
  type: string
- container: ''
  name: currencyCode
  type: string
- container: set
  name: originDestinations
  type: string
- container: set
  name: travelers
  type: string
- container: set
  name: sources
  type: string
- container: ''
  name: searchCriteria
  type: string
- container: ''
  name: excludeAllotments
  type: boolean
- container: ''
  name: addOneWayOffers
  type: boolean
- container: ''
  name: maxFlightOffers
  type: decimal
- container: ''
  name: maxPrice
  type: integer
- container: ''
  name: allowAlternativeFareOptions
  type: boolean
- container: ''
  name: oneFlightOfferPerDay
  type: boolean
- container: ''
  name: additionalInformation
  type: string
- container: ''
  name: pricingOptions
  type: string
- container: ''
  name: flightFilters
  type: string
- container: ''
  name: quantity
  type: integer
- container: ''
  name: weight
  type: integer
- container: ''
  name: weightUnit
  type: string
- container: ''
  name: maxNumberOfConnections
  type: decimal
- container: ''
  name: nonStopPreferred
  type: boolean
- container: ''
  name: airportChangeAllowed
  type: boolean
- container: ''
  name: technicalStopsAllowed
  type: boolean
- container: ''
  name: status
  type: integer
- container: ''
  name: code
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
  name: type
  type: string
- container: ''
  name: id
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
- container: set
  name: validatingAirlineCodes
  type: string
- container: set
  name: travelerPricings
  type: string
- container: ''
  name: tourName
  type: string
- container: ''
  name: tourReference
  type: string
- container: ''
  name: crossBorderAllowed
  type: boolean
- container: ''
  name: moreOvernightsAllowed
  type: boolean
- container: ''
  name: returnToDepartureAirport
  type: boolean
- container: ''
  name: railSegmentAllowed
  type: boolean
- container: ''
  name: busSegmentAllowed
  type: boolean
- container: ''
  name: maxFlightTime
  type: decimal
- container: ''
  name: carrierRestrictions
  type: string
- container: set
  name: cabinRestrictions
  type: string
- container: ''
  name: connectionRestriction
  type: string
- container: ''
  name: cityCode
  type: string
- container: ''
  name: countryCode
  type: string
- container: ''
  name: blacklistedInEUAllowed
  type: boolean
- container: set
  name: excludedCarrierCodes
  type: string
- container: set
  name: includedCarrierCodes
  type: string
- container: ''
  name: cabin
  type: string
- container: set
  name: originDestinationIds
  type: string
- container: ''
  name: links
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
  name: originLocationCode
  type: string
- container: ''
  name: destinationLocationCode
  type: string
- container: set
  name: includedConnectionPoints
  type: string
- container: set
  name: excludedConnectionPoints
  type: string
- container: ''
  name: amount
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
  name: departure
  type: string
- container: ''
  name: arrival
  type: string
- container: ''
  name: number
  type: string
- container: ''
  name: operating
  type: string
- container: set
  name: stops
  type: string
- container: ''
  name: travelerType
  type: string
- container: ''
  name: associatedAdultId
  type: string
property_count: 94
provider_name: Amadeus Solutions
provider_slug: amadeus-solutions
slug: amadeus-flight-offers-search-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amadeus\": \"https://amadeus.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"OriginalFlightEndPoint\": \"amadeus:OriginalFlightEndPoint\",\n    \"OriginalFlightStop\": \"amadeus:OriginalFlightStop\",\n    \"Error_400\": \"amadeus:Error_400\",\n    \"OperatingFlight\": \"amadeus:OperatingFlight\",\n    \"ExtendedPricingOptions\": \"amadeus:ExtendedPricingOptions\",\n    \"Collection_Meta\": \"amadeus:Collection_Meta\",\n    \"DateTimeType\": \"amadeus:DateTimeType\",\n    \"GetFlightOffersQuery\": \"amadeus:GetFlightOffersQuery\",\n    \"SearchCriteria\": \"amadeus:SearchCriteria\",\n    \"BaggageAllowance\": \"amadeus:BaggageAllowance\",\n    \"ConnectionRestriction\": \"amadeus:ConnectionRestriction\",\n    \"Issue\": \"amadeus:Issue\",\n    \"FlightOffer\": \"amadeus:FlightOffer\",\n    \"AllotmentDetails\"\
  : \"amadeus:AllotmentDetails\",\n    \"FlightFilters\": \"amadeus:FlightFilters\",\n    \"LocationValue\": \"amadeus:LocationValue\",\n    \"CarrierRestrictions\": \"amadeus:CarrierRestrictions\",\n    \"CabinRestriction\": \"amadeus:CabinRestriction\",\n    \"Co2Emission\": \"amadeus:Co2Emission\",\n    \"Collection_Meta_Link\": \"amadeus:Collection_Meta_Link\",\n    \"Price\": \"amadeus:Price\",\n    \"Extended_Price\": \"amadeus:Extended_Price\",\n    \"AircraftEquipment\": \"amadeus:AircraftEquipment\",\n    \"OriginDestinationLight\": \"amadeus:OriginDestinationLight\",\n    \"Tax\": \"amadeus:Tax\",\n    \"Extended_PricingOptions\": \"amadeus:Extended_PricingOptions\",\n    \"Dictionaries\": \"amadeus:Dictionaries\",\n    \"FlightSegment\": \"amadeus:FlightSegment\",\n    \"ChargeableSeat\": \"amadeus:ChargeableSeat\",\n    \"Fee\": \"amadeus:Fee\",\n    \"TravelerInfo\": \"amadeus:TravelerInfo\",\n    \"Error_500\": \"amadeus:Error_500\",\n    \"iataCode\": {\n      \"@id\": \"\
  amadeus:iataCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"terminal\": {\n      \"@id\": \"amadeus:terminal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"duration\": {\n      \"@id\": \"amadeus:duration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errors\": {\n      \"@id\": \"amadeus:errors\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carrierCode\": {\n      \"@id\": \"amadeus:carrierCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"includedCheckedBagsOnly\": {\n      \"@id\": \"amadeus:includedCheckedBagsOnly\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"refundableFare\": {\n      \"@id\": \"amadeus:refundableFare\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"noRestrictionFare\": {\n      \"@id\": \"amadeus:noRestrictionFare\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"noPenaltyFare\": {\n      \"@id\": \"amadeus:noPenaltyFare\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"count\": {\n      \"@id\"\
  : \"amadeus:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"oneWayCombinations\": {\n      \"@id\": \"amadeus:oneWayCombinations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"date\": {\n      \"@id\": \"amadeus:date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"time\": {\n      \"@id\": \"amadeus:time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencyCode\": {\n      \"@id\": \"amadeus:currencyCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"originDestinations\": {\n      \"@id\": \"amadeus:originDestinations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"travelers\": {\n      \"@id\": \"amadeus:travelers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sources\": {\n      \"@id\": \"amadeus:sources\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"searchCriteria\": {\n      \"@id\": \"amadeus:searchCriteria\",\n  \
  \    \"@type\": \"xsd:string\"\n    },\n    \"excludeAllotments\": {\n      \"@id\": \"amadeus:excludeAllotments\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"addOneWayOffers\": {\n      \"@id\": \"amadeus:addOneWayOffers\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"maxFlightOffers\": {\n      \"@id\": \"amadeus:maxFlightOffers\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"maxPrice\": {\n      \"@id\": \"amadeus:maxPrice\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"allowAlternativeFareOptions\": {\n      \"@id\": \"amadeus:allowAlternativeFareOptions\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"oneFlightOfferPerDay\": {\n      \"@id\": \"amadeus:oneFlightOfferPerDay\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"additionalInformation\": {\n      \"@id\": \"amadeus:additionalInformation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pricingOptions\": {\n      \"@id\": \"amadeus:pricingOptions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flightFilters\"\
  : {\n      \"@id\": \"amadeus:flightFilters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quantity\": {\n      \"@id\": \"amadeus:quantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"weight\": {\n      \"@id\": \"amadeus:weight\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"weightUnit\": {\n      \"@id\": \"amadeus:weightUnit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxNumberOfConnections\": {\n      \"@id\": \"amadeus:maxNumberOfConnections\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"nonStopPreferred\": {\n      \"@id\": \"amadeus:nonStopPreferred\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"airportChangeAllowed\": {\n      \"@id\": \"amadeus:airportChangeAllowed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"technicalStopsAllowed\": {\n      \"@id\": \"amadeus:technicalStopsAllowed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"status\": {\n      \"@id\": \"amadeus:status\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"code\":\
  \ {\n      \"@id\": \"amadeus:code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"title\": {\n      \"@id\": \"amadeus:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detail\": {\n      \"@id\": \"amadeus:detail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"amadeus:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"amadeus:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"amadeus:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instantTicketingRequired\": {\n      \"@id\": \"amadeus:instantTicketingRequired\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"disablePricing\": {\n      \"@id\": \"amadeus:disablePricing\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"nonHomogeneous\": {\n      \"@id\": \"amadeus:nonHomogeneous\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"oneWay\": {\n      \"@id\": \"amadeus:oneWay\",\n      \"@type\": \"xsd:boolean\"\n    },\n\
  \    \"paymentCardRequired\": {\n      \"@id\": \"amadeus:paymentCardRequired\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lastTicketingDate\": {\n      \"@id\": \"amadeus:lastTicketingDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastTicketingDateTime\": {\n      \"@id\": \"amadeus:lastTicketingDateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"numberOfBookableSeats\": {\n      \"@id\": \"amadeus:numberOfBookableSeats\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"itineraries\": {\n      \"@id\": \"amadeus:itineraries\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"price\": {\n      \"@id\": \"amadeus:price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"validatingAirlineCodes\": {\n      \"@id\": \"amadeus:validatingAirlineCodes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"travelerPricings\": {\n      \"@id\": \"amadeus:travelerPricings\",\n      \"@container\": \"@set\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"tourName\": {\n      \"@id\": \"amadeus:tourName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tourReference\": {\n      \"@id\": \"amadeus:tourReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"crossBorderAllowed\": {\n      \"@id\": \"amadeus:crossBorderAllowed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"moreOvernightsAllowed\": {\n      \"@id\": \"amadeus:moreOvernightsAllowed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"returnToDepartureAirport\": {\n      \"@id\": \"amadeus:returnToDepartureAirport\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"railSegmentAllowed\": {\n      \"@id\": \"amadeus:railSegmentAllowed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"busSegmentAllowed\": {\n      \"@id\": \"amadeus:busSegmentAllowed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"maxFlightTime\": {\n      \"@id\": \"amadeus:maxFlightTime\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"carrierRestrictions\"\
  : {\n      \"@id\": \"amadeus:carrierRestrictions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cabinRestrictions\": {\n      \"@id\": \"amadeus:cabinRestrictions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectionRestriction\": {\n      \"@id\": \"amadeus:connectionRestriction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cityCode\": {\n      \"@id\": \"amadeus:cityCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryCode\": {\n      \"@id\": \"amadeus:countryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"blacklistedInEUAllowed\": {\n      \"@id\": \"amadeus:blacklistedInEUAllowed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"excludedCarrierCodes\": {\n      \"@id\": \"amadeus:excludedCarrierCodes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"includedCarrierCodes\": {\n      \"@id\": \"amadeus:includedCarrierCodes\",\n      \"@container\": \"@set\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"cabin\": {\n      \"@id\": \"amadeus:cabin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"originDestinationIds\": {\n      \"@id\": \"amadeus:originDestinationIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"links\": {\n      \"@id\": \"amadeus:links\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currency\": {\n      \"@id\": \"amadeus:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"total\": {\n      \"@id\": \"amadeus:total\",\n      \"@type\": \"xsd:string\"\n    },\n    \"base\": {\n      \"@id\": \"amadeus:base\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fees\": {\n      \"@id\": \"amadeus:fees\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxes\": {\n      \"@id\": \"amadeus:taxes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"refundableTaxes\": {\n      \"@id\": \"amadeus:refundableTaxes\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"originLocationCode\": {\n      \"@id\": \"amadeus:originLocationCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destinationLocationCode\": {\n      \"@id\": \"amadeus:destinationLocationCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"includedConnectionPoints\": {\n      \"@id\": \"amadeus:includedConnectionPoints\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"excludedConnectionPoints\": {\n      \"@id\": \"amadeus:excludedConnectionPoints\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"amadeus:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locations\": {\n      \"@id\": \"amadeus:locations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aircraft\": {\n      \"@id\": \"amadeus:aircraft\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencies\": {\n      \"@id\": \"amadeus:currencies\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carriers\"\
  : {\n      \"@id\": \"amadeus:carriers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"departure\": {\n      \"@id\": \"amadeus:departure\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arrival\": {\n      \"@id\": \"amadeus:arrival\",\n      \"@type\": \"xsd:string\"\n    },\n    \"number\": {\n      \"@id\": \"amadeus:number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operating\": {\n      \"@id\": \"amadeus:operating\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stops\": {\n      \"@id\": \"amadeus:stops\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"travelerType\": {\n      \"@id\": \"amadeus:travelerType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"associatedAdultId\": {\n      \"@id\": \"amadeus:associatedAdultId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus-solutions/refs/heads/main/json-ld/amadeus-flight-offers-search-context.jsonld
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
