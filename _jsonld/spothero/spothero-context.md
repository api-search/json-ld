---
api_specs:
- filename: spothero-parking-openapi.yml
  format: yaml
  label: SpotHero Parking API
  slug: spothero-parking-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spothero/refs/heads/main/openapi/spothero-parking-openapi.yml
class_count: 38
classes:
- reservation_id
- facility_id
- partner_reference
- barcode
- barcode_format
- confirmation_code
- Reservation
- Facility
- SearchResult
- Rate
- Driver
- Vehicle
- Price
- Address
- Coordinates
- OperatingHours
- name
- description
- address
- starts
- ends
- status
- price
- amount
- currency
- driver
- vehicle
- latitude
- longitude
- rating
- capacity
- phone
- amenities
- facility_type
- operator
- distance_miles
- created_at
- updated_at
context_file: json-ld/spothero-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/spothero/refs/heads/main/json-ld/spothero-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Spothero from SpotHero.
layout: jsonld
name: Spothero Context
namespaces:
- prefix: spothero
  uri: https://api.spothero.com/vocab#
properties: []
property_count: 0
provider_name: SpotHero
provider_slug: spothero
slug: spothero-context
source_filename: spothero-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"spothero\": \"https://api.spothero.com/vocab#\",\n    \"reservation_id\": \"spothero:reservationId\",\n    \"facility_id\": \"spothero:facilityId\",\n    \"partner_reference\": \"spothero:partnerReference\",\n    \"barcode\": \"spothero:barcode\",\n    \"barcode_format\": \"spothero:barcodeFormat\",\n    \"confirmation_code\": \"spothero:confirmationCode\",\n    \"Reservation\": \"spothero:Reservation\",\n    \"Facility\": \"ParkingFacility\",\n    \"SearchResult\": \"spothero:SearchResult\",\n    \"Rate\": \"spothero:Rate\",\n    \"Driver\": \"Person\",\n    \"Vehicle\": \"Vehicle\",\n    \"Price\": \"PriceSpecification\",\n    \"Address\": \"PostalAddress\",\n    \"Coordinates\": \"GeoCoordinates\",\n    \"OperatingHours\": \"OpeningHoursSpecification\",\n    \"name\": \"name\",\n    \"description\": \"description\",\n    \"address\": \"address\",\n    \"starts\": \"startDate\",\n    \"ends\": \"endDate\"\
  ,\n    \"status\": \"spothero:reservationStatus\",\n    \"price\": \"priceSpecification\",\n    \"amount\": \"price\",\n    \"currency\": \"priceCurrency\",\n    \"driver\": \"customer\",\n    \"vehicle\": \"vehicle\",\n    \"latitude\": \"latitude\",\n    \"longitude\": \"longitude\",\n    \"rating\": \"ratingValue\",\n    \"capacity\": \"totalPaymentDue\",\n    \"phone\": \"telephone\",\n    \"amenities\": \"amenityFeature\",\n    \"facility_type\": \"spothero:facilityType\",\n    \"operator\": \"operator\",\n    \"distance_miles\": \"spothero:distanceMiles\",\n    \"created_at\": \"dateCreated\",\n    \"updated_at\": \"dateModified\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/spothero/refs/heads/main/json-ld/spothero-context.jsonld
tags:
- Parking
- Mobility
- Transportation
- Navigation
- Reservations
- JSON-LD
- Linked Data
- Semantic Web
---
