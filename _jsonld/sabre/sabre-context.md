---
api_specs:
- filename: sabre-bargain-finder-max-openapi.yml
  format: yaml
  label: Sabre Bargain Finder Max API
  slug: bargain-finder-max
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sabre/refs/heads/main/openapi/sabre-bargain-finder-max-openapi.yml
- filename: sabre-hotels-openapi.yml
  format: yaml
  label: Sabre Hotels API
  slug: hotels
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sabre/refs/heads/main/openapi/sabre-hotels-openapi.yml
class_count: 37
classes:
- FlightOffer
- HotelOffer
- HotelReservation
- FlightReservation
- Passenger
- Airport
- Airline
- flightNumber
- bookingClass
- cabinClass
- fareBasis
- hotelCode
- chainCode
- name
- description
- amenities
- images
- baseFare
- totalFare
- totalTaxes
- currencyCode
- amount
- firstName
- lastName
- email
- phone
- iataCode
- locationCode
- countryCode
- city
- stateProvince
- postalCode
- street
- confirmationNumber
- reservationStatus
- sequenceNumber
- validatingCarrier
context_file: json-ld/sabre-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sabre/refs/heads/main/json-ld/sabre-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sabre from Sabre.
layout: jsonld
name: Sabre Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: sabre
  uri: https://developer.sabre.com/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
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
  name: airline
  type: reference
- container: ''
  name: operatingAirline
  type: reference
- container: ''
  name: starRating
  type: schema:Rating
- container: ''
  name: address
  type: schema:PostalAddress
- container: ''
  name: checkIn
  type: date
- container: ''
  name: checkOut
  type: date
property_count: 10
provider_name: Sabre
provider_slug: sabre
slug: sabre-context
source_filename: sabre-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"sabre\": \"https://developer.sabre.com/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"FlightOffer\": \"schema:Flight\",\n    \"HotelOffer\": \"schema:LodgingBusiness\",\n    \"HotelReservation\": \"schema:LodgingReservation\",\n    \"FlightReservation\": \"schema:FlightReservation\",\n    \"Passenger\": \"schema:Person\",\n    \"Airport\": \"schema:Airport\",\n    \"Airline\": \"schema:Airline\",\n\n    \"departureAirport\": {\n      \"@id\": \"schema:departureAirport\",\n      \"@type\": \"@id\"\n    },\n    \"arrivalAirport\": {\n      \"@id\": \"schema:arrivalAirport\",\n      \"@type\": \"@id\"\n    },\n    \"departureTime\": {\n      \"@id\": \"schema:departureTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"arrivalTime\": {\n      \"@id\": \"schema:arrivalTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"flightNumber\": \"schema:flightNumber\"\
  ,\n    \"airline\": {\n      \"@id\": \"schema:provider\",\n      \"@type\": \"@id\"\n    },\n    \"operatingAirline\": {\n      \"@id\": \"sabre:operatingCarrier\",\n      \"@type\": \"@id\"\n    },\n    \"bookingClass\": \"sabre:bookingClass\",\n    \"cabinClass\": \"sabre:cabinClass\",\n    \"fareBasis\": \"sabre:fareBasisCode\",\n\n    \"hotelCode\": \"sabre:propertyCode\",\n    \"chainCode\": \"sabre:chainCode\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"starRating\": {\n      \"@id\": \"schema:starRating\",\n      \"@type\": \"schema:Rating\"\n    },\n    \"address\": {\n      \"@id\": \"schema:address\",\n      \"@type\": \"schema:PostalAddress\"\n    },\n    \"checkIn\": {\n      \"@id\": \"schema:checkinTime\",\n      \"@type\": \"xsd:date\"\n    },\n    \"checkOut\": {\n      \"@id\": \"schema:checkoutTime\",\n      \"@type\": \"xsd:date\"\n    },\n    \"amenities\": \"schema:amenityFeature\",\n    \"images\": \"schema:image\",\n\n \
  \   \"baseFare\": \"sabre:baseFare\",\n    \"totalFare\": \"sabre:totalFare\",\n    \"totalTaxes\": \"sabre:totalTaxes\",\n    \"currencyCode\": \"schema:currency\",\n    \"amount\": \"schema:price\",\n\n    \"firstName\": \"schema:givenName\",\n    \"lastName\": \"schema:familyName\",\n    \"email\": \"schema:email\",\n    \"phone\": \"schema:telephone\",\n\n    \"iataCode\": \"schema:iataCode\",\n    \"locationCode\": \"schema:iataCode\",\n    \"countryCode\": \"schema:addressCountry\",\n    \"city\": \"schema:addressLocality\",\n    \"stateProvince\": \"schema:addressRegion\",\n    \"postalCode\": \"schema:postalCode\",\n    \"street\": \"schema:streetAddress\",\n\n    \"confirmationNumber\": \"schema:reservationId\",\n    \"reservationStatus\": \"schema:reservationStatus\",\n    \"sequenceNumber\": \"sabre:sequenceNumber\",\n    \"validatingCarrier\": \"sabre:validatingCarrier\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sabre/refs/heads/main/json-ld/sabre-context.jsonld
tags:
- Travel
- GDS
- Airlines
- Hotels
- Car Rental
- Booking
- JSON-LD
- Linked Data
- Semantic Web
---
