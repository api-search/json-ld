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
class_count: 37
classes:
- LocationValue
- AllotmentDetails
- Price
- Co2Emission
- OriginalFlightEndPoint
- FareRules
- Dictionaries
- CreditCardFee
- OtherServices
- LoyaltyProgram
- FlightOfferPricingIn
- BaseName
- Error_400
- OriginalFlightStop
- EmergencyContact
- Phone
- FlightSegment
- Stakeholder
- Error_500
- TermAndCondition
- ChargeableSeat
- ElementaryPrice
- Document
- Issue
- OperatingFlight
- Extended_Price
- Address
- Discount
- AircraftEquipment
- ContactDictionary
- BaggageAllowance
- FlightOffer
- Tax
- FlightOfferPricingOut
- Fee
- DetailedFareRules
- name
context_file: json-ld/amadeus-flight-offers-price-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus-solutions/refs/heads/main/json-ld/amadeus-flight-offers-price-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Flight Offers Price from Amadeus Solutions.
layout: jsonld
name: Amadeus Flight Offers Price Context
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
  name: cityCode
  type: string
- container: ''
  name: countryCode
  type: string
- container: ''
  name: tourName
  type: string
- container: ''
  name: tourReference
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
  name: weight
  type: integer
- container: ''
  name: weightUnit
  type: string
- container: ''
  name: cabin
  type: string
- container: ''
  name: iataCode
  type: string
- container: ''
  name: terminal
  type: string
- container: set
  name: rules
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
  name: brand
  type: string
- container: ''
  name: amount
  type: string
- container: ''
  name: flightOfferId
  type: string
- container: ''
  name: price
  type: string
- container: ''
  name: bookableByTraveler
  type: boolean
- container: ''
  name: bookableByItinerary
  type: boolean
- container: set
  name: segmentIds
  type: string
- container: set
  name: travelerIds
  type: string
- container: ''
  name: programOwner
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: type
  type: string
- container: set
  name: flightOffers
  type: string
- container: set
  name: payments
  type: string
- container: set
  name: travelers
  type: string
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: middleName
  type: string
- container: set
  name: errors
  type: string
- container: ''
  name: duration
  type: string
- container: ''
  name: addresseeName
  type: string
- container: ''
  name: number
  type: string
- container: ''
  name: text
  type: string
- container: ''
  name: deviceType
  type: string
- container: ''
  name: countryCallingCode
  type: string
- container: ''
  name: departure
  type: string
- container: ''
  name: arrival
  type: string
- container: ''
  name: carrierCode
  type: string
- container: ''
  name: operating
  type: string
- container: set
  name: stops
  type: string
- container: ''
  name: dateOfBirth
  type: date
- container: ''
  name: gender
  type: string
- container: set
  name: documents
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: circumstances
  type: string
- container: ''
  name: notApplicable
  type: boolean
- container: ''
  name: maxPenaltyAmount
  type: string
- container: set
  name: descriptions
  type: string
- container: ''
  name: currencyCode
  type: string
- container: ''
  name: issuanceDate
  type: date
- container: ''
  name: expiryDate
  type: date
- container: ''
  name: issuanceCountry
  type: string
- container: ''
  name: issuanceLocation
  type: string
- container: ''
  name: nationality
  type: string
- container: ''
  name: birthPlace
  type: string
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
- container: set
  name: lines
  type: string
- container: ''
  name: postalCode
  type: string
- container: ''
  name: cityName
  type: string
- container: ''
  name: stateName
  type: string
- container: ''
  name: postalBox
  type: string
- container: ''
  name: subType
  type: string
- container: ''
  name: travelerType
  type: string
- container: ''
  name: cardNumber
  type: string
- container: ''
  name: certificateNumber
  type: string
- container: ''
  name: address
  type: string
- container: ''
  name: language
  type: string
- container: ''
  name: purpose
  type: string
- container: ''
  name: quantity
  type: integer
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
  name: pricingOptions
  type: string
- container: set
  name: validatingAirlineCodes
  type: string
- container: set
  name: travelerPricings
  type: string
- container: ''
  name: bookingRequirements
  type: string
- container: ''
  name: fareBasis
  type: string
- container: ''
  name: fareNotes
  type: string
- container: ''
  name: segmentId
  type: string
property_count: 98
provider_name: Amadeus Solutions
provider_slug: amadeus-solutions
slug: amadeus-flight-offers-price-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amadeus\": \"https://amadeus.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"LocationValue\": \"amadeus:LocationValue\",\n    \"AllotmentDetails\": \"amadeus:AllotmentDetails\",\n    \"Price\": \"amadeus:Price\",\n    \"Co2Emission\": \"amadeus:Co2Emission\",\n    \"OriginalFlightEndPoint\": \"amadeus:OriginalFlightEndPoint\",\n    \"FareRules\": \"amadeus:FareRules\",\n    \"Dictionaries\": \"amadeus:Dictionaries\",\n    \"CreditCardFee\": \"amadeus:CreditCardFee\",\n    \"OtherServices\": \"amadeus:OtherServices\",\n    \"LoyaltyProgram\": \"amadeus:LoyaltyProgram\",\n    \"FlightOfferPricingIn\": \"amadeus:FlightOfferPricingIn\",\n    \"BaseName\": \"amadeus:BaseName\",\n    \"Error_400\": \"amadeus:Error_400\",\n    \"OriginalFlightStop\": \"amadeus:OriginalFlightStop\",\n    \"EmergencyContact\": \"amadeus:EmergencyContact\"\
  ,\n    \"Phone\": \"amadeus:Phone\",\n    \"FlightSegment\": \"amadeus:FlightSegment\",\n    \"Stakeholder\": \"amadeus:Stakeholder\",\n    \"Error_500\": \"amadeus:Error_500\",\n    \"TermAndCondition\": \"amadeus:TermAndCondition\",\n    \"ChargeableSeat\": \"amadeus:ChargeableSeat\",\n    \"ElementaryPrice\": \"amadeus:ElementaryPrice\",\n    \"Document\": \"amadeus:Document\",\n    \"Issue\": \"amadeus:Issue\",\n    \"OperatingFlight\": \"amadeus:OperatingFlight\",\n    \"Extended_Price\": \"amadeus:Extended_Price\",\n    \"Address\": \"amadeus:Address\",\n    \"Discount\": \"amadeus:Discount\",\n    \"AircraftEquipment\": \"amadeus:AircraftEquipment\",\n    \"ContactDictionary\": \"amadeus:ContactDictionary\",\n    \"BaggageAllowance\": \"amadeus:BaggageAllowance\",\n    \"FlightOffer\": \"amadeus:FlightOffer\",\n    \"Tax\": \"amadeus:Tax\",\n    \"FlightOfferPricingOut\": \"amadeus:FlightOfferPricingOut\",\n    \"Fee\": \"amadeus:Fee\",\n    \"DetailedFareRules\": \"amadeus:DetailedFareRules\"\
  ,\n    \"cityCode\": {\n      \"@id\": \"amadeus:cityCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryCode\": {\n      \"@id\": \"amadeus:countryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tourName\": {\n      \"@id\": \"amadeus:tourName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tourReference\": {\n      \"@id\": \"amadeus:tourReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currency\": {\n      \"@id\": \"amadeus:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"total\": {\n      \"@id\": \"amadeus:total\",\n      \"@type\": \"xsd:string\"\n    },\n    \"base\": {\n      \"@id\": \"amadeus:base\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fees\": {\n      \"@id\": \"amadeus:fees\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxes\": {\n      \"@id\": \"amadeus:taxes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"refundableTaxes\": {\n      \"@id\":\
  \ \"amadeus:refundableTaxes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"weight\": {\n      \"@id\": \"amadeus:weight\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"weightUnit\": {\n      \"@id\": \"amadeus:weightUnit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cabin\": {\n      \"@id\": \"amadeus:cabin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iataCode\": {\n      \"@id\": \"amadeus:iataCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"terminal\": {\n      \"@id\": \"amadeus:terminal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rules\": {\n      \"@id\": \"amadeus:rules\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locations\": {\n      \"@id\": \"amadeus:locations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aircraft\": {\n      \"@id\": \"amadeus:aircraft\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencies\": {\n      \"@id\": \"amadeus:currencies\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"carriers\": {\n      \"@id\": \"amadeus:carriers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brand\": {\n      \"@id\": \"amadeus:brand\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"amadeus:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flightOfferId\": {\n      \"@id\": \"amadeus:flightOfferId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"price\": {\n      \"@id\": \"amadeus:price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bookableByTraveler\": {\n      \"@id\": \"amadeus:bookableByTraveler\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"bookableByItinerary\": {\n      \"@id\": \"amadeus:bookableByItinerary\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"segmentIds\": {\n      \"@id\": \"amadeus:segmentIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"travelerIds\": {\n      \"@id\": \"amadeus:travelerIds\",\n      \"@container\": \"@set\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"programOwner\": {\n      \"@id\": \"amadeus:programOwner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"amadeus:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"amadeus:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flightOffers\": {\n      \"@id\": \"amadeus:flightOffers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payments\": {\n      \"@id\": \"amadeus:payments\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"travelers\": {\n      \"@id\": \"amadeus:travelers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstName\": {\n      \"@id\": \"amadeus:firstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"amadeus:lastName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"middleName\": {\n      \"@id\": \"amadeus:middleName\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"errors\": {\n      \"@id\": \"amadeus:errors\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"duration\": {\n      \"@id\": \"amadeus:duration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"addresseeName\": {\n      \"@id\": \"amadeus:addresseeName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"number\": {\n      \"@id\": \"amadeus:number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"text\": {\n      \"@id\": \"amadeus:text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceType\": {\n      \"@id\": \"amadeus:deviceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryCallingCode\": {\n      \"@id\": \"amadeus:countryCallingCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"departure\": {\n      \"@id\": \"amadeus:departure\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arrival\": {\n      \"@id\": \"amadeus:arrival\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  carrierCode\": {\n      \"@id\": \"amadeus:carrierCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operating\": {\n      \"@id\": \"amadeus:operating\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stops\": {\n      \"@id\": \"amadeus:stops\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateOfBirth\": {\n      \"@id\": \"amadeus:dateOfBirth\",\n      \"@type\": \"xsd:date\"\n    },\n    \"gender\": {\n      \"@id\": \"amadeus:gender\",\n      \"@type\": \"xsd:string\"\n    },\n    \"documents\": {\n      \"@id\": \"amadeus:documents\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"amadeus:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"circumstances\": {\n      \"@id\": \"amadeus:circumstances\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notApplicable\": {\n      \"@id\": \"amadeus:notApplicable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"maxPenaltyAmount\"\
  : {\n      \"@id\": \"amadeus:maxPenaltyAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"descriptions\": {\n      \"@id\": \"amadeus:descriptions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencyCode\": {\n      \"@id\": \"amadeus:currencyCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuanceDate\": {\n      \"@id\": \"amadeus:issuanceDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"expiryDate\": {\n      \"@id\": \"amadeus:expiryDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"issuanceCountry\": {\n      \"@id\": \"amadeus:issuanceCountry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuanceLocation\": {\n      \"@id\": \"amadeus:issuanceLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nationality\": {\n      \"@id\": \"amadeus:nationality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"birthPlace\": {\n      \"@id\": \"amadeus:birthPlace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\"\
  : {\n      \"@id\": \"amadeus:status\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"code\": {\n      \"@id\": \"amadeus:code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"title\": {\n      \"@id\": \"amadeus:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detail\": {\n      \"@id\": \"amadeus:detail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"amadeus:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lines\": {\n      \"@id\": \"amadeus:lines\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postalCode\": {\n      \"@id\": \"amadeus:postalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cityName\": {\n      \"@id\": \"amadeus:cityName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stateName\": {\n      \"@id\": \"amadeus:stateName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postalBox\": {\n      \"@id\": \"amadeus:postalBox\",\n      \"@type\": \"xsd:string\"\n    },\n  \
  \  \"subType\": {\n      \"@id\": \"amadeus:subType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"travelerType\": {\n      \"@id\": \"amadeus:travelerType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cardNumber\": {\n      \"@id\": \"amadeus:cardNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certificateNumber\": {\n      \"@id\": \"amadeus:certificateNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address\": {\n      \"@id\": \"amadeus:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"language\": {\n      \"@id\": \"amadeus:language\",\n      \"@type\": \"xsd:string\"\n    },\n    \"purpose\": {\n      \"@id\": \"amadeus:purpose\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quantity\": {\n      \"@id\": \"amadeus:quantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"instantTicketingRequired\": {\n      \"@id\": \"amadeus:instantTicketingRequired\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"disablePricing\": {\n      \"@id\": \"\
  amadeus:disablePricing\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"nonHomogeneous\": {\n      \"@id\": \"amadeus:nonHomogeneous\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"oneWay\": {\n      \"@id\": \"amadeus:oneWay\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"paymentCardRequired\": {\n      \"@id\": \"amadeus:paymentCardRequired\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lastTicketingDate\": {\n      \"@id\": \"amadeus:lastTicketingDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastTicketingDateTime\": {\n      \"@id\": \"amadeus:lastTicketingDateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"numberOfBookableSeats\": {\n      \"@id\": \"amadeus:numberOfBookableSeats\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"itineraries\": {\n      \"@id\": \"amadeus:itineraries\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pricingOptions\": {\n      \"@id\": \"amadeus:pricingOptions\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"validatingAirlineCodes\": {\n      \"@id\": \"amadeus:validatingAirlineCodes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"travelerPricings\": {\n      \"@id\": \"amadeus:travelerPricings\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bookingRequirements\": {\n      \"@id\": \"amadeus:bookingRequirements\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fareBasis\": {\n      \"@id\": \"amadeus:fareBasis\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fareNotes\": {\n      \"@id\": \"amadeus:fareNotes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"segmentId\": {\n      \"@id\": \"amadeus:segmentId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus-solutions/refs/heads/main/json-ld/amadeus-flight-offers-price-context.jsonld
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
