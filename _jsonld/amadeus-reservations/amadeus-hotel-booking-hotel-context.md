---
class_count: 6
classes:
- HotelProduct
- HotelProduct_PaymentPolicy
- HotelBooking
- HotelOrder
- HotelProduct_DepositPolicy
- description
context_file: json-ld/amadeus-hotel-booking-hotel-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/json-ld/amadeus-hotel-booking-hotel-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Hotel Booking Hotel from Amadeus Reservations.
layout: jsonld
name: Amadeus Hotel Booking Hotel Context
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
  name: checkInDate
  type: date
- container: ''
  name: checkOutDate
  type: date
- container: ''
  name: roomQuantity
  type: integer
- container: ''
  name: rateCode
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: commission
  type: reference
- container: ''
  name: room
  type: reference
- container: ''
  name: guests
  type: string
- container: ''
  name: price
  type: string
- container: ''
  name: policies
  type: reference
- container: ''
  name: rateFamilyEstimated
  type: reference
- container: set
  name: creditCards
  type: string
- container: set
  name: methods
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: bookingStatus
  type: string
- container: set
  name: roomAssociations
  type: string
- container: ''
  name: hotelOffer
  type: string
- container: ''
  name: hotel
  type: reference
- container: set
  name: hotelProviderInformation
  type: ''
- container: ''
  name: payment
  type: string
- container: ''
  name: travelAgentId
  type: string
- container: ''
  name: arrivalInformation
  type: reference
- container: set
  name: hotelBookings
  type: string
- container: set
  name: associatedRecords
  type: ''
- container: ''
  name: self
  type: string
- container: ''
  name: amount
  type: string
- container: ''
  name: deadline
  type: dateTime
- container: ''
  name: acceptedPayments
  type: string
property_count: 29
provider_name: Amadeus Reservations
provider_slug: amadeus-reservations
slug: amadeus-hotel-booking-hotel-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amadeus\": \"https://amadeus.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"HotelProduct\": \"amadeus:HotelProduct\",\n    \"HotelProduct_PaymentPolicy\": \"amadeus:HotelProduct_PaymentPolicy\",\n    \"HotelBooking\": \"amadeus:HotelBooking\",\n    \"HotelOrder\": \"amadeus:HotelOrder\",\n    \"HotelProduct_DepositPolicy\": \"amadeus:HotelProduct_DepositPolicy\",\n    \"checkInDate\": {\n      \"@id\": \"amadeus:checkInDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"checkOutDate\": {\n      \"@id\": \"amadeus:checkOutDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"roomQuantity\": {\n      \"@id\": \"amadeus:roomQuantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"rateCode\": {\n      \"@id\": \"amadeus:rateCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\"\
  : \"amadeus:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"commission\": {\n      \"@id\": \"amadeus:commission\",\n      \"@type\": \"@id\"\n    },\n    \"room\": {\n      \"@id\": \"amadeus:room\",\n      \"@type\": \"@id\"\n    },\n    \"guests\": {\n      \"@id\": \"amadeus:guests\",\n      \"@type\": \"xsd:string\"\n    },\n    \"price\": {\n      \"@id\": \"amadeus:price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policies\": {\n      \"@id\": \"amadeus:policies\",\n      \"@type\": \"@id\"\n    },\n    \"rateFamilyEstimated\": {\n      \"@id\": \"amadeus:rateFamilyEstimated\",\n      \"@type\": \"@id\"\n    },\n    \"creditCards\": {\n      \"@id\": \"amadeus:creditCards\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"methods\": {\n      \"@id\": \"amadeus:methods\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"amadeus:type\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"id\": {\n      \"@id\": \"amadeus:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bookingStatus\": {\n      \"@id\": \"amadeus:bookingStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roomAssociations\": {\n      \"@id\": \"amadeus:roomAssociations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hotelOffer\": {\n      \"@id\": \"amadeus:hotelOffer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hotel\": {\n      \"@id\": \"amadeus:hotel\",\n      \"@type\": \"@id\"\n    },\n    \"hotelProviderInformation\": {\n      \"@id\": \"amadeus:hotelProviderInformation\",\n      \"@container\": \"@set\"\n    },\n    \"payment\": {\n      \"@id\": \"amadeus:payment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"travelAgentId\": {\n      \"@id\": \"amadeus:travelAgentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arrivalInformation\": {\n      \"@id\": \"amadeus:arrivalInformation\",\n      \"@type\": \"@id\"\n    },\n\
  \    \"hotelBookings\": {\n      \"@id\": \"amadeus:hotelBookings\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"associatedRecords\": {\n      \"@id\": \"amadeus:associatedRecords\",\n      \"@container\": \"@set\"\n    },\n    \"self\": {\n      \"@id\": \"amadeus:self\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"amadeus:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deadline\": {\n      \"@id\": \"amadeus:deadline\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"description\": \"schema:description\",\n    \"acceptedPayments\": {\n      \"@id\": \"amadeus:acceptedPayments\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/json-ld/amadeus-hotel-booking-hotel-context.jsonld
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
