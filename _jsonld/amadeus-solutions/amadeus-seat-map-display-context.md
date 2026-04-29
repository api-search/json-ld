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
class_count: 48
classes:
- OperatingFlight
- FlightOffer
- Document
- Collection_Meta
- AircraftCabinAmenities
- BaseName
- LoyaltyProgram
- Error_400
- ElementaryPrice
- LocationValue
- Price
- FlightEndPoint
- SeatmapTravelerPricing
- EmergencyContact
- Address
- Phone
- Link
- FlightSegment
- Coordinates
- Discount
- FareRules
- SeatCharacteristicDictionary
- Deck
- Fee
- Amenity
- Issue
- FlightStop
- TermAndCondition
- QualifiedFreeText
- Error_404
- Tax
- Amenity_Seat
- Stakeholder
- ContactDictionary
- Co2Emission
- AircraftEquipment
- Error_500
- Facility
- Extended_Price
- DeckConfiguration
- Seat
- SeatMap
- Amenity_Media
- FacilityDictionary
- AvailableSeatsCounter
- BaggageAllowance
- name
- description
context_file: json-ld/amadeus-seat-map-display-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus-solutions/refs/heads/main/json-ld/amadeus-seat-map-display-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Seat Map Display from Amadeus Solutions.
layout: jsonld
name: Amadeus Seat Map Display Context
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
  name: carrierCode
  type: string
- container: ''
  name: number
  type: string
- container: ''
  name: suffix
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: id
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
- container: ''
  name: fareRules
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
  name: count
  type: integer
- container: ''
  name: links
  type: string
- container: ''
  name: power
  type: string
- container: ''
  name: seat
  type: string
- container: ''
  name: wifi
  type: string
- container: set
  name: entertainment
  type: string
- container: ''
  name: food
  type: string
- container: ''
  name: beverage
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
- container: ''
  name: programOwner
  type: string
- container: set
  name: errors
  type: string
- container: ''
  name: amount
  type: string
- container: ''
  name: currencyCode
  type: string
- container: ''
  name: cityCode
  type: string
- container: ''
  name: countryCode
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
  name: iataCode
  type: string
- container: ''
  name: terminal
  type: string
- container: ''
  name: at
  type: dateTime
- container: ''
  name: travelerId
  type: string
- container: ''
  name: seatAvailabilityStatus
  type: string
- container: ''
  name: addresseeName
  type: string
- container: ''
  name: text
  type: string
- container: ''
  name: category
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
  name: stateCode
  type: string
- container: ''
  name: stateName
  type: string
- container: ''
  name: postalBox
  type: string
- container: ''
  name: deviceType
  type: string
- container: ''
  name: countryCallingCode
  type: string
- container: ''
  name: areaCode
  type: string
- container: ''
  name: extension
  type: string
- container: ''
  name: href
  type: reference
- container: set
  name: methods
  type: string
- container: ''
  name: departure
  type: string
- container: ''
  name: arrival
  type: string
- container: ''
  name: aircraft
  type: string
- container: ''
  name: operating
  type: string
- container: ''
  name: duration
  type: string
- container: set
  name: stops
  type: string
- container: ''
  name: x
  type: integer
- container: ''
  name: y
  type: integer
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
- container: set
  name: rules
  type: string
- container: ''
  name: deckType
  type: string
- container: ''
  name: deckConfiguration
  type: string
- container: set
  name: facilities
  type: string
- container: set
  name: seats
  type: string
- container: ''
  name: isChargeable
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
  name: newAircraft
  type: string
- container: ''
  name: arrivalAt
  type: dateTime
- container: ''
  name: departureAt
  type: dateTime
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
  name: lang
  type: string
- container: ''
  name: legSpace
  type: integer
- container: ''
  name: spaceUnit
  type: string
- container: ''
  name: tilt
  type: string
- container: ''
  name: amenityType
  type: string
- container: set
  name: medias
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
  name: address
  type: string
- container: ''
  name: purpose
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
  name: column
  type: string
- container: ''
  name: row
  type: string
- container: ''
  name: position
  type: string
- container: ''
  name: coordinates
  type: string
- container: ''
  name: width
  type: integer
- container: ''
  name: length
  type: integer
- container: ''
  name: startSeatRow
  type: integer
- container: ''
  name: endSeatRow
  type: integer
- container: ''
  name: startWingsX
  type: integer
- container: ''
  name: endWingsX
  type: integer
- container: ''
  name: startWingsRow
  type: integer
- container: ''
  name: endWingsRow
  type: integer
- container: set
  name: exitRowsX
  type: string
- container: set
  name: characteristicsCodes
  type: string
- container: set
  name: travelerPricing
  type: string
- container: ''
  name: self
  type: string
- container: ''
  name: class
  type: string
- container: ''
  name: flightOfferId
  type: string
- container: ''
  name: segmentId
  type: string
- container: set
  name: decks
  type: string
- container: ''
  name: aircraftCabinAmenities
  type: string
- container: set
  name: availableSeatsCounters
  type: string
- container: ''
  name: mediaType
  type: string
- container: ''
  name: value
  type: integer
- container: ''
  name: excessRate
  type: string
- container: ''
  name: quantity
  type: integer
property_count: 136
provider_name: Amadeus Solutions
provider_slug: amadeus-solutions
slug: amadeus-seat-map-display-context
source_filename: amadeus-seat-map-display-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amadeus\": \"https://amadeus.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"OperatingFlight\": \"amadeus:OperatingFlight\",\n    \"FlightOffer\": \"amadeus:FlightOffer\",\n    \"Document\": \"amadeus:Document\",\n    \"Collection_Meta\": \"amadeus:Collection_Meta\",\n    \"AircraftCabinAmenities\": \"amadeus:AircraftCabinAmenities\",\n    \"BaseName\": \"amadeus:BaseName\",\n    \"LoyaltyProgram\": \"amadeus:LoyaltyProgram\",\n    \"Error_400\": \"amadeus:Error_400\",\n    \"ElementaryPrice\": \"amadeus:ElementaryPrice\",\n    \"LocationValue\": \"amadeus:LocationValue\",\n    \"Price\": \"amadeus:Price\",\n    \"FlightEndPoint\": \"amadeus:FlightEndPoint\",\n    \"SeatmapTravelerPricing\": \"amadeus:SeatmapTravelerPricing\",\n    \"EmergencyContact\": \"amadeus:EmergencyContact\",\n    \"Address\": \"amadeus:Address\"\
  ,\n    \"Phone\": \"amadeus:Phone\",\n    \"Link\": \"amadeus:Link\",\n    \"FlightSegment\": \"amadeus:FlightSegment\",\n    \"Coordinates\": \"amadeus:Coordinates\",\n    \"Discount\": \"amadeus:Discount\",\n    \"FareRules\": \"amadeus:FareRules\",\n    \"SeatCharacteristicDictionary\": \"amadeus:SeatCharacteristicDictionary\",\n    \"Deck\": \"amadeus:Deck\",\n    \"Fee\": \"amadeus:Fee\",\n    \"Amenity\": \"amadeus:Amenity\",\n    \"Issue\": \"amadeus:Issue\",\n    \"FlightStop\": \"amadeus:FlightStop\",\n    \"TermAndCondition\": \"amadeus:TermAndCondition\",\n    \"QualifiedFreeText\": \"amadeus:QualifiedFreeText\",\n    \"Error_404\": \"amadeus:Error_404\",\n    \"Tax\": \"amadeus:Tax\",\n    \"Amenity_Seat\": \"amadeus:Amenity_Seat\",\n    \"Stakeholder\": \"amadeus:Stakeholder\",\n    \"ContactDictionary\": \"amadeus:ContactDictionary\",\n    \"Co2Emission\": \"amadeus:Co2Emission\",\n    \"AircraftEquipment\": \"amadeus:AircraftEquipment\",\n    \"Error_500\": \"amadeus:Error_500\"\
  ,\n    \"Facility\": \"amadeus:Facility\",\n    \"Extended_Price\": \"amadeus:Extended_Price\",\n    \"DeckConfiguration\": \"amadeus:DeckConfiguration\",\n    \"Seat\": \"amadeus:Seat\",\n    \"SeatMap\": \"amadeus:SeatMap\",\n    \"Amenity_Media\": \"amadeus:Amenity_Media\",\n    \"FacilityDictionary\": \"amadeus:FacilityDictionary\",\n    \"AvailableSeatsCounter\": \"amadeus:AvailableSeatsCounter\",\n    \"BaggageAllowance\": \"amadeus:BaggageAllowance\",\n    \"carrierCode\": {\n      \"@id\": \"amadeus:carrierCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"number\": {\n      \"@id\": \"amadeus:number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"suffix\": {\n      \"@id\": \"amadeus:suffix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"amadeus:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"amadeus:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"amadeus:source\",\n  \
  \    \"@type\": \"xsd:string\"\n    },\n    \"instantTicketingRequired\": {\n      \"@id\": \"amadeus:instantTicketingRequired\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"disablePricing\": {\n      \"@id\": \"amadeus:disablePricing\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"nonHomogeneous\": {\n      \"@id\": \"amadeus:nonHomogeneous\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"oneWay\": {\n      \"@id\": \"amadeus:oneWay\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"paymentCardRequired\": {\n      \"@id\": \"amadeus:paymentCardRequired\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lastTicketingDate\": {\n      \"@id\": \"amadeus:lastTicketingDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"numberOfBookableSeats\": {\n      \"@id\": \"amadeus:numberOfBookableSeats\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"itineraries\": {\n      \"@id\": \"amadeus:itineraries\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"price\": {\n      \"@id\": \"amadeus:price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pricingOptions\": {\n      \"@id\": \"amadeus:pricingOptions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"validatingAirlineCodes\": {\n      \"@id\": \"amadeus:validatingAirlineCodes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"travelerPricings\": {\n      \"@id\": \"amadeus:travelerPricings\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fareRules\": {\n      \"@id\": \"amadeus:fareRules\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuanceDate\": {\n      \"@id\": \"amadeus:issuanceDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"expiryDate\": {\n      \"@id\": \"amadeus:expiryDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"issuanceCountry\": {\n      \"@id\": \"amadeus:issuanceCountry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuanceLocation\": {\n      \"@id\": \"amadeus:issuanceLocation\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"nationality\": {\n      \"@id\": \"amadeus:nationality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"birthPlace\": {\n      \"@id\": \"amadeus:birthPlace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"count\": {\n      \"@id\": \"amadeus:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"links\": {\n      \"@id\": \"amadeus:links\",\n      \"@type\": \"xsd:string\"\n    },\n    \"power\": {\n      \"@id\": \"amadeus:power\",\n      \"@type\": \"xsd:string\"\n    },\n    \"seat\": {\n      \"@id\": \"amadeus:seat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"wifi\": {\n      \"@id\": \"amadeus:wifi\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entertainment\": {\n      \"@id\": \"amadeus:entertainment\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"food\": {\n      \"@id\": \"amadeus:food\",\n      \"@type\": \"xsd:string\"\n    },\n    \"beverage\": {\n      \"@id\": \"amadeus:beverage\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"firstName\": {\n      \"@id\": \"amadeus:firstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"amadeus:lastName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"middleName\": {\n      \"@id\": \"amadeus:middleName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"programOwner\": {\n      \"@id\": \"amadeus:programOwner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errors\": {\n      \"@id\": \"amadeus:errors\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"amadeus:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencyCode\": {\n      \"@id\": \"amadeus:currencyCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cityCode\": {\n      \"@id\": \"amadeus:cityCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryCode\": {\n      \"@id\": \"amadeus:countryCode\",\n      \"@type\": \"xsd:string\"\n    },\n  \
  \  \"currency\": {\n      \"@id\": \"amadeus:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"total\": {\n      \"@id\": \"amadeus:total\",\n      \"@type\": \"xsd:string\"\n    },\n    \"base\": {\n      \"@id\": \"amadeus:base\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fees\": {\n      \"@id\": \"amadeus:fees\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxes\": {\n      \"@id\": \"amadeus:taxes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iataCode\": {\n      \"@id\": \"amadeus:iataCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"terminal\": {\n      \"@id\": \"amadeus:terminal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"at\": {\n      \"@id\": \"amadeus:at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"travelerId\": {\n      \"@id\": \"amadeus:travelerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"seatAvailabilityStatus\": {\n      \"@id\": \"amadeus:seatAvailabilityStatus\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"addresseeName\": {\n      \"@id\": \"amadeus:addresseeName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"text\": {\n      \"@id\": \"amadeus:text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"amadeus:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lines\": {\n      \"@id\": \"amadeus:lines\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postalCode\": {\n      \"@id\": \"amadeus:postalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cityName\": {\n      \"@id\": \"amadeus:cityName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stateCode\": {\n      \"@id\": \"amadeus:stateCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stateName\": {\n      \"@id\": \"amadeus:stateName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postalBox\": {\n      \"@id\": \"amadeus:postalBox\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceType\"\
  : {\n      \"@id\": \"amadeus:deviceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryCallingCode\": {\n      \"@id\": \"amadeus:countryCallingCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"areaCode\": {\n      \"@id\": \"amadeus:areaCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"extension\": {\n      \"@id\": \"amadeus:extension\",\n      \"@type\": \"xsd:string\"\n    },\n    \"href\": {\n      \"@id\": \"amadeus:href\",\n      \"@type\": \"@id\"\n    },\n    \"methods\": {\n      \"@id\": \"amadeus:methods\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"departure\": {\n      \"@id\": \"amadeus:departure\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arrival\": {\n      \"@id\": \"amadeus:arrival\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aircraft\": {\n      \"@id\": \"amadeus:aircraft\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operating\": {\n      \"@id\": \"amadeus:operating\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"duration\": {\n      \"@id\": \"amadeus:duration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stops\": {\n      \"@id\": \"amadeus:stops\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"x\": {\n      \"@id\": \"amadeus:x\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"y\": {\n      \"@id\": \"amadeus:y\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"subType\": {\n      \"@id\": \"amadeus:subType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"travelerType\": {\n      \"@id\": \"amadeus:travelerType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cardNumber\": {\n      \"@id\": \"amadeus:cardNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certificateNumber\": {\n      \"@id\": \"amadeus:certificateNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rules\": {\n      \"@id\": \"amadeus:rules\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deckType\":\
  \ {\n      \"@id\": \"amadeus:deckType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deckConfiguration\": {\n      \"@id\": \"amadeus:deckConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"facilities\": {\n      \"@id\": \"amadeus:facilities\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"seats\": {\n      \"@id\": \"amadeus:seats\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isChargeable\": {\n      \"@id\": \"amadeus:isChargeable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"status\": {\n      \"@id\": \"amadeus:status\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"code\": {\n      \"@id\": \"amadeus:code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"title\": {\n      \"@id\": \"amadeus:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detail\": {\n      \"@id\": \"amadeus:detail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"newAircraft\": {\n      \"@id\": \"amadeus:newAircraft\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"arrivalAt\": {\n      \"@id\": \"amadeus:arrivalAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"departureAt\": {\n      \"@id\": \"amadeus:departureAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"circumstances\": {\n      \"@id\": \"amadeus:circumstances\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notApplicable\": {\n      \"@id\": \"amadeus:notApplicable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"maxPenaltyAmount\": {\n      \"@id\": \"amadeus:maxPenaltyAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"descriptions\": {\n      \"@id\": \"amadeus:descriptions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lang\": {\n      \"@id\": \"amadeus:lang\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legSpace\": {\n      \"@id\": \"amadeus:legSpace\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"spaceUnit\": {\n      \"@id\": \"amadeus:spaceUnit\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"tilt\": {\n      \"@id\": \"amadeus:tilt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amenityType\": {\n      \"@id\": \"amadeus:amenityType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"medias\": {\n      \"@id\": \"amadeus:medias\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateOfBirth\": {\n      \"@id\": \"amadeus:dateOfBirth\",\n      \"@type\": \"xsd:date\"\n    },\n    \"gender\": {\n      \"@id\": \"amadeus:gender\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"documents\": {\n      \"@id\": \"amadeus:documents\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address\": {\n      \"@id\": \"amadeus:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"purpose\": {\n      \"@id\": \"amadeus:purpose\",\n      \"@type\": \"xsd:string\"\n    },\n    \"weight\": {\n      \"@id\": \"amadeus:weight\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"weightUnit\": {\n      \"@id\": \"amadeus:weightUnit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cabin\": {\n      \"@id\": \"amadeus:cabin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"column\": {\n      \"@id\": \"amadeus:column\",\n      \"@type\": \"xsd:string\"\n    },\n    \"row\": {\n      \"@id\": \"amadeus:row\",\n      \"@type\": \"xsd:string\"\n    },\n    \"position\": {\n      \"@id\": \"amadeus:position\",\n      \"@type\": \"xsd:string\"\n    },\n    \"coordinates\": {\n      \"@id\": \"amadeus:coordinates\",\n      \"@type\": \"xsd:string\"\n    },\n    \"width\": {\n      \"@id\": \"amadeus:width\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"length\": {\n      \"@id\": \"amadeus:length\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"startSeatRow\": {\n      \"@id\": \"amadeus:startSeatRow\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"endSeatRow\": {\n      \"@id\": \"amadeus:endSeatRow\",\n      \"@type\": \"xsd:integer\"\n \
  \   },\n    \"startWingsX\": {\n      \"@id\": \"amadeus:startWingsX\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"endWingsX\": {\n      \"@id\": \"amadeus:endWingsX\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"startWingsRow\": {\n      \"@id\": \"amadeus:startWingsRow\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"endWingsRow\": {\n      \"@id\": \"amadeus:endWingsRow\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"exitRowsX\": {\n      \"@id\": \"amadeus:exitRowsX\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"characteristicsCodes\": {\n      \"@id\": \"amadeus:characteristicsCodes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"travelerPricing\": {\n      \"@id\": \"amadeus:travelerPricing\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"self\": {\n      \"@id\": \"amadeus:self\",\n      \"@type\": \"xsd:string\"\n    },\n    \"class\": {\n      \"@id\":\
  \ \"amadeus:class\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flightOfferId\": {\n      \"@id\": \"amadeus:flightOfferId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"segmentId\": {\n      \"@id\": \"amadeus:segmentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"decks\": {\n      \"@id\": \"amadeus:decks\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aircraftCabinAmenities\": {\n      \"@id\": \"amadeus:aircraftCabinAmenities\",\n      \"@type\": \"xsd:string\"\n    },\n    \"availableSeatsCounters\": {\n      \"@id\": \"amadeus:availableSeatsCounters\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"mediaType\": {\n      \"@id\": \"amadeus:mediaType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"amadeus:value\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"excessRate\": {\n      \"@id\": \"amadeus:excessRate\",\n  \
  \    \"@type\": \"xsd:string\"\n    },\n    \"quantity\": {\n      \"@id\": \"amadeus:quantity\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus-solutions/refs/heads/main/json-ld/amadeus-seat-map-display-context.jsonld
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
