---
api_specs:
- filename: amadeus-reservations-hotel-booking-openapi.yaml
  format: yaml
  label: Hotel Booking API
  slug: hotel-booking-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/openapi/amadeus-reservations-hotel-booking-openapi.yaml
- filename: amadeus-reservations-flight-create-orders-openapi.yaml
  format: yaml
  label: Flight Create Orders API
  slug: flight-create-orders-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/openapi/amadeus-reservations-flight-create-orders-openapi.yaml
- filename: amadeus-reservations-flight-order-management-openapi.yaml
  format: yaml
  label: Flight Order Management API
  slug: flight-order-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/openapi/amadeus-reservations-flight-order-management-openapi.yaml
- filename: amadeus-reservations-transfer-booking-openapi.yaml
  format: yaml
  label: Transfer Booking API
  slug: transfer-booking-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/openapi/amadeus-reservations-transfer-booking-openapi.yaml
- filename: amadeus-reservations-transfer-management-openapi.yaml
  format: yaml
  label: Transfer Management API
  slug: transfer-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/openapi/amadeus-reservations-transfer-management-openapi.yaml
class_count: 46
classes:
- TicketingAgreement
- Price
- ChargeableSeat
- AirlineRemark
- FormOfIdentification
- Extended_Price
- Co2Emission
- BaggageAllowance
- GeneralRemark
- AirTravelDocumentCommon
- Tax
- Collection_Meta_Link
- FormOfPayment
- BaseName
- Fee
- Error_400
- AssociatedRecordCommon
- Address
- Dictionaries
- Phone
- Stakeholder
- Remarks
- Error_500
- OriginalFlightStop
- OtherMethod
- Document
- EmergencyContact
- CreditCardCommon
- FlightSegment
- CreditCard
- Issue
- AircraftEquipment
- ContactDictionary
- FlightOrder
- B2bWallet
- LoyaltyProgram
- ElementaryPrice
- OriginalFlightEndPoint
- AllotmentDetails
- LocationValue
- FlightOffer
- Error_404
- AutomatedProcessCommon
- Discount
- OperatingFlight
- name
context_file: json-ld/amadeus-flight-order-management-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/json-ld/amadeus-flight-order-management-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Flight Order Management from Amadeus Reservations.
layout: jsonld
name: Amadeus Flight Order Management Context
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
  name: option
  type: string
- container: ''
  name: delay
  type: string
- container: ''
  name: dateTime
  type: string
- container: set
  name: segmentIds
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
  name: id
  type: string
- container: ''
  name: number
  type: string
- container: ''
  name: subType
  type: string
- container: ''
  name: keyword
  type: string
- container: ''
  name: airlineCode
  type: string
- container: ''
  name: text
  type: string
- container: set
  name: travelerIds
  type: string
- container: set
  name: flightOfferIds
  type: string
- container: ''
  name: identificationType
  type: string
- container: ''
  name: carrierCode
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
  name: quantity
  type: integer
- container: ''
  name: category
  type: string
- container: ''
  name: documentType
  type: string
- container: ''
  name: documentNumber
  type: string
- container: ''
  name: documentStatus
  type: string
- container: ''
  name: amount
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: count
  type: integer
- container: ''
  name: links
  type: reference
- container: ''
  name: b2bWallet
  type: string
- container: ''
  name: creditCard
  type: string
- container: ''
  name: other
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
  name: type
  type: string
- container: set
  name: errors
  type: string
- container: ''
  name: reference
  type: string
- container: ''
  name: creationDate
  type: string
- container: ''
  name: originSystemCode
  type: string
- container: set
  name: lines
  type: string
- container: ''
  name: postalCode
  type: string
- container: ''
  name: countryCode
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
  name: deviceType
  type: string
- container: ''
  name: countryCallingCode
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
- container: set
  name: general
  type: string
- container: set
  name: airline
  type: string
- container: ''
  name: iataCode
  type: string
- container: ''
  name: duration
  type: string
- container: ''
  name: method
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
  name: addresseeName
  type: string
- container: ''
  name: brand
  type: string
- container: ''
  name: holder
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
  name: bookingStatus
  type: string
- container: ''
  name: segmentType
  type: string
- container: ''
  name: isFlown
  type: boolean
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
  type: reference
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
  name: queuingOfficeId
  type: string
- container: ''
  name: ownerOfficeId
  type: string
- container: set
  name: associatedRecords
  type: string
- container: set
  name: flightOffers
  type: string
- container: set
  name: travelers
  type: string
- container: ''
  name: remarks
  type: string
- container: set
  name: formOfPayments
  type: string
- container: ''
  name: ticketingAgreement
  type: string
- container: set
  name: automatedProcess
  type: string
- container: set
  name: contacts
  type: string
- container: set
  name: tickets
  type: string
- container: set
  name: formOfIdentifications
  type: string
- container: ''
  name: cardId
  type: string
- container: ''
  name: cardUsageName
  type: string
- container: ''
  name: cardFriendlyName
  type: string
- container: set
  name: reportingData
  type: ''
- container: ''
  name: virtualCreditCardDetails
  type: string
- container: ''
  name: programOwner
  type: string
- container: ''
  name: currencyCode
  type: string
- container: ''
  name: terminal
  type: string
- container: ''
  name: tourName
  type: string
- container: ''
  name: tourReference
  type: string
- container: ''
  name: cityCode
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
  type: ''
- container: ''
  name: price
  type: string
- container: ''
  name: pricingOptions
  type: reference
- container: set
  name: validatingAirlineCodes
  type: string
- container: set
  name: travelerPricings
  type: string
- container: ''
  name: queue
  type: reference
- container: ''
  name: travelerType
  type: string
- container: ''
  name: cardNumber
  type: string
- container: ''
  name: certificateNumber
  type: string
property_count: 126
provider_name: Amadeus Reservations
provider_slug: amadeus-reservations
slug: amadeus-flight-order-management-context
source_filename: amadeus-flight-order-management-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amadeus\": \"https://amadeus.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"TicketingAgreement\": \"amadeus:TicketingAgreement\",\n    \"Price\": \"amadeus:Price\",\n    \"ChargeableSeat\": \"amadeus:ChargeableSeat\",\n    \"AirlineRemark\": \"amadeus:AirlineRemark\",\n    \"FormOfIdentification\": \"amadeus:FormOfIdentification\",\n    \"Extended_Price\": \"amadeus:Extended_Price\",\n    \"Co2Emission\": \"amadeus:Co2Emission\",\n    \"BaggageAllowance\": \"amadeus:BaggageAllowance\",\n    \"GeneralRemark\": \"amadeus:GeneralRemark\",\n    \"AirTravelDocumentCommon\": \"amadeus:AirTravelDocumentCommon\",\n    \"Tax\": \"amadeus:Tax\",\n    \"Collection_Meta_Link\": \"amadeus:Collection_Meta_Link\",\n    \"FormOfPayment\": \"amadeus:FormOfPayment\",\n    \"BaseName\": \"amadeus:BaseName\",\n    \"Fee\": \"\
  amadeus:Fee\",\n    \"Error_400\": \"amadeus:Error_400\",\n    \"AssociatedRecordCommon\": \"amadeus:AssociatedRecordCommon\",\n    \"Address\": \"amadeus:Address\",\n    \"Dictionaries\": \"amadeus:Dictionaries\",\n    \"Phone\": \"amadeus:Phone\",\n    \"Stakeholder\": \"amadeus:Stakeholder\",\n    \"Remarks\": \"amadeus:Remarks\",\n    \"Error_500\": \"amadeus:Error_500\",\n    \"OriginalFlightStop\": \"amadeus:OriginalFlightStop\",\n    \"OtherMethod\": \"amadeus:OtherMethod\",\n    \"Document\": \"amadeus:Document\",\n    \"EmergencyContact\": \"amadeus:EmergencyContact\",\n    \"CreditCardCommon\": \"amadeus:CreditCardCommon\",\n    \"FlightSegment\": \"amadeus:FlightSegment\",\n    \"CreditCard\": \"amadeus:CreditCard\",\n    \"Issue\": \"amadeus:Issue\",\n    \"AircraftEquipment\": \"amadeus:AircraftEquipment\",\n    \"ContactDictionary\": \"amadeus:ContactDictionary\",\n    \"FlightOrder\": \"amadeus:FlightOrder\",\n    \"B2bWallet\": \"amadeus:B2bWallet\",\n    \"LoyaltyProgram\"\
  : \"amadeus:LoyaltyProgram\",\n    \"ElementaryPrice\": \"amadeus:ElementaryPrice\",\n    \"OriginalFlightEndPoint\": \"amadeus:OriginalFlightEndPoint\",\n    \"AllotmentDetails\": \"amadeus:AllotmentDetails\",\n    \"LocationValue\": \"amadeus:LocationValue\",\n    \"FlightOffer\": \"amadeus:FlightOffer\",\n    \"Error_404\": \"amadeus:Error_404\",\n    \"AutomatedProcessCommon\": \"amadeus:AutomatedProcessCommon\",\n    \"Discount\": \"amadeus:Discount\",\n    \"OperatingFlight\": \"amadeus:OperatingFlight\",\n    \"option\": {\n      \"@id\": \"amadeus:option\",\n      \"@type\": \"xsd:string\"\n    },\n    \"delay\": {\n      \"@id\": \"amadeus:delay\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateTime\": {\n      \"@id\": \"amadeus:dateTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"segmentIds\": {\n      \"@id\": \"amadeus:segmentIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currency\": {\n      \"@id\": \"amadeus:currency\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"total\": {\n      \"@id\": \"amadeus:total\",\n      \"@type\": \"xsd:string\"\n    },\n    \"base\": {\n      \"@id\": \"amadeus:base\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fees\": {\n      \"@id\": \"amadeus:fees\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxes\": {\n      \"@id\": \"amadeus:taxes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"refundableTaxes\": {\n      \"@id\": \"amadeus:refundableTaxes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"amadeus:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"number\": {\n      \"@id\": \"amadeus:number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subType\": {\n      \"@id\": \"amadeus:subType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keyword\": {\n      \"@id\": \"amadeus:keyword\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airlineCode\": {\n\
  \      \"@id\": \"amadeus:airlineCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"text\": {\n      \"@id\": \"amadeus:text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"travelerIds\": {\n      \"@id\": \"amadeus:travelerIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flightOfferIds\": {\n      \"@id\": \"amadeus:flightOfferIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"identificationType\": {\n      \"@id\": \"amadeus:identificationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carrierCode\": {\n      \"@id\": \"amadeus:carrierCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"weight\": {\n      \"@id\": \"amadeus:weight\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"weightUnit\": {\n      \"@id\": \"amadeus:weightUnit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cabin\": {\n      \"@id\": \"amadeus:cabin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quantity\": {\n\
  \      \"@id\": \"amadeus:quantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"category\": {\n      \"@id\": \"amadeus:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"documentType\": {\n      \"@id\": \"amadeus:documentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"documentNumber\": {\n      \"@id\": \"amadeus:documentNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"documentStatus\": {\n      \"@id\": \"amadeus:documentStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"amadeus:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"amadeus:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"count\": {\n      \"@id\": \"amadeus:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"links\": {\n      \"@id\": \"amadeus:links\",\n      \"@type\": \"@id\"\n    },\n    \"b2bWallet\": {\n      \"@id\": \"amadeus:b2bWallet\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creditCard\"\
  : {\n      \"@id\": \"amadeus:creditCard\",\n      \"@type\": \"xsd:string\"\n    },\n    \"other\": {\n      \"@id\": \"amadeus:other\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstName\": {\n      \"@id\": \"amadeus:firstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"amadeus:lastName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"middleName\": {\n      \"@id\": \"amadeus:middleName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"amadeus:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errors\": {\n      \"@id\": \"amadeus:errors\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"amadeus:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationDate\": {\n      \"@id\": \"amadeus:creationDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"originSystemCode\": {\n      \"@id\": \"amadeus:originSystemCode\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"lines\": {\n      \"@id\": \"amadeus:lines\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postalCode\": {\n      \"@id\": \"amadeus:postalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryCode\": {\n      \"@id\": \"amadeus:countryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cityName\": {\n      \"@id\": \"amadeus:cityName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stateName\": {\n      \"@id\": \"amadeus:stateName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postalBox\": {\n      \"@id\": \"amadeus:postalBox\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locations\": {\n      \"@id\": \"amadeus:locations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aircraft\": {\n      \"@id\": \"amadeus:aircraft\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencies\": {\n      \"@id\": \"amadeus:currencies\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carriers\": {\n\
  \      \"@id\": \"amadeus:carriers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceType\": {\n      \"@id\": \"amadeus:deviceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryCallingCode\": {\n      \"@id\": \"amadeus:countryCallingCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateOfBirth\": {\n      \"@id\": \"amadeus:dateOfBirth\",\n      \"@type\": \"xsd:date\"\n    },\n    \"gender\": {\n      \"@id\": \"amadeus:gender\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"documents\": {\n      \"@id\": \"amadeus:documents\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"general\": {\n      \"@id\": \"amadeus:general\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airline\": {\n      \"@id\": \"amadeus:airline\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iataCode\": {\n      \"@id\": \"amadeus:iataCode\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"duration\": {\n      \"@id\": \"amadeus:duration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"method\": {\n      \"@id\": \"amadeus:method\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuanceDate\": {\n      \"@id\": \"amadeus:issuanceDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"expiryDate\": {\n      \"@id\": \"amadeus:expiryDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"issuanceCountry\": {\n      \"@id\": \"amadeus:issuanceCountry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuanceLocation\": {\n      \"@id\": \"amadeus:issuanceLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nationality\": {\n      \"@id\": \"amadeus:nationality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"birthPlace\": {\n      \"@id\": \"amadeus:birthPlace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"addresseeName\": {\n      \"@id\": \"amadeus:addresseeName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brand\"\
  : {\n      \"@id\": \"amadeus:brand\",\n      \"@type\": \"xsd:string\"\n    },\n    \"holder\": {\n      \"@id\": \"amadeus:holder\",\n      \"@type\": \"xsd:string\"\n    },\n    \"departure\": {\n      \"@id\": \"amadeus:departure\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arrival\": {\n      \"@id\": \"amadeus:arrival\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operating\": {\n      \"@id\": \"amadeus:operating\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stops\": {\n      \"@id\": \"amadeus:stops\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bookingStatus\": {\n      \"@id\": \"amadeus:bookingStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"segmentType\": {\n      \"@id\": \"amadeus:segmentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isFlown\": {\n      \"@id\": \"amadeus:isFlown\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"status\": {\n      \"@id\": \"amadeus:status\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"title\": {\n      \"@id\": \"amadeus:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detail\": {\n      \"@id\": \"amadeus:detail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"amadeus:source\",\n      \"@type\": \"@id\"\n    },\n    \"address\": {\n      \"@id\": \"amadeus:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"language\": {\n      \"@id\": \"amadeus:language\",\n      \"@type\": \"xsd:string\"\n    },\n    \"purpose\": {\n      \"@id\": \"amadeus:purpose\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queuingOfficeId\": {\n      \"@id\": \"amadeus:queuingOfficeId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ownerOfficeId\": {\n      \"@id\": \"amadeus:ownerOfficeId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"associatedRecords\": {\n      \"@id\": \"amadeus:associatedRecords\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flightOffers\": {\n      \"@id\":\
  \ \"amadeus:flightOffers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"travelers\": {\n      \"@id\": \"amadeus:travelers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"remarks\": {\n      \"@id\": \"amadeus:remarks\",\n      \"@type\": \"xsd:string\"\n    },\n    \"formOfPayments\": {\n      \"@id\": \"amadeus:formOfPayments\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ticketingAgreement\": {\n      \"@id\": \"amadeus:ticketingAgreement\",\n      \"@type\": \"xsd:string\"\n    },\n    \"automatedProcess\": {\n      \"@id\": \"amadeus:automatedProcess\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contacts\": {\n      \"@id\": \"amadeus:contacts\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tickets\": {\n      \"@id\": \"amadeus:tickets\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"formOfIdentifications\": {\n      \"@id\": \"amadeus:formOfIdentifications\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cardId\": {\n      \"@id\": \"amadeus:cardId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cardUsageName\": {\n      \"@id\": \"amadeus:cardUsageName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cardFriendlyName\": {\n      \"@id\": \"amadeus:cardFriendlyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reportingData\": {\n      \"@id\": \"amadeus:reportingData\",\n      \"@container\": \"@set\"\n    },\n    \"virtualCreditCardDetails\": {\n      \"@id\": \"amadeus:virtualCreditCardDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"programOwner\": {\n      \"@id\": \"amadeus:programOwner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencyCode\": {\n      \"@id\": \"amadeus:currencyCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"terminal\": {\n      \"@id\": \"amadeus:terminal\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"tourName\": {\n      \"@id\": \"amadeus:tourName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tourReference\": {\n      \"@id\": \"amadeus:tourReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cityCode\": {\n      \"@id\": \"amadeus:cityCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instantTicketingRequired\": {\n      \"@id\": \"amadeus:instantTicketingRequired\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"disablePricing\": {\n      \"@id\": \"amadeus:disablePricing\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"nonHomogeneous\": {\n      \"@id\": \"amadeus:nonHomogeneous\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"oneWay\": {\n      \"@id\": \"amadeus:oneWay\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"paymentCardRequired\": {\n      \"@id\": \"amadeus:paymentCardRequired\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lastTicketingDate\": {\n      \"@id\": \"amadeus:lastTicketingDate\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"lastTicketingDateTime\": {\n      \"@id\": \"amadeus:lastTicketingDateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"numberOfBookableSeats\": {\n      \"@id\": \"amadeus:numberOfBookableSeats\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"itineraries\": {\n      \"@id\": \"amadeus:itineraries\",\n      \"@container\": \"@set\"\n    },\n    \"price\": {\n      \"@id\": \"amadeus:price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pricingOptions\": {\n      \"@id\": \"amadeus:pricingOptions\",\n      \"@type\": \"@id\"\n    },\n    \"validatingAirlineCodes\": {\n      \"@id\": \"amadeus:validatingAirlineCodes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"travelerPricings\": {\n      \"@id\": \"amadeus:travelerPricings\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queue\": {\n      \"@id\": \"amadeus:queue\",\n      \"@type\": \"@id\"\n    },\n\
  \    \"travelerType\": {\n      \"@id\": \"amadeus:travelerType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cardNumber\": {\n      \"@id\": \"amadeus:cardNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certificateNumber\": {\n      \"@id\": \"amadeus:certificateNumber\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/json-ld/amadeus-flight-order-management-context.jsonld
tags:
- Booking
- Flights
- Hotels
- Reservations
- Travel
- JSON-LD
- Linked Data
- Semantic Web
---
