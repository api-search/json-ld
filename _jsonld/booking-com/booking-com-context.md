---
api_specs:
- filename: booking-com-demand-api-openapi.yml
  format: yaml
  label: Booking.com Demand API
  slug: demand-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/booking-com/refs/heads/main/openapi/booking-com-demand-api-openapi.yml
- filename: booking-com-car-rentals-api-openapi.yml
  format: yaml
  label: Booking.com Car Rentals API
  slug: car-rentals-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/booking-com/refs/heads/main/openapi/booking-com-car-rentals-api-openapi.yml
- filename: booking-com-connectivity-content-api-openapi.yml
  format: yaml
  label: Booking.com Connectivity Content API
  slug: connectivity-content-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/booking-com/refs/heads/main/openapi/booking-com-connectivity-content-api-openapi.yml
- filename: booking-com-connectivity-reservations-api-openapi.yml
  format: yaml
  label: Booking.com Connectivity Reservations API
  slug: connectivity-reservations-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/booking-com/refs/heads/main/openapi/booking-com-connectivity-reservations-api-openapi.yml
- filename: booking-com-connectivity-rates-availability-api-openapi.yml
  format: yaml
  label: Booking.com Connectivity Rates and Availability API
  slug: connectivity-rates-availability-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/booking-com/refs/heads/main/openapi/booking-com-connectivity-rates-availability-api-openapi.yml
- filename: booking-com-connectivity-promotions-api-openapi.yml
  format: yaml
  label: Booking.com Connectivity Promotions API
  slug: connectivity-promotions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/booking-com/refs/heads/main/openapi/booking-com-connectivity-promotions-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/booking-com-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/booking-com/refs/heads/main/json-ld/booking-com-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Booking Com from booking-com.
layout: jsonld
name: Booking Com Context
namespaces:
- prefix: booking
  uri: https://developers.booking.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
properties:
- container: ''
  name: Accommodation
  type: ''
- container: ''
  name: Room
  type: ''
- container: ''
  name: Order
  type: ''
- container: ''
  name: Booker
  type: ''
- container: ''
  name: Review
  type: ''
- container: ''
  name: CarRental
  type: ''
- container: ''
  name: Vehicle
  type: ''
- container: ''
  name: Depot
  type: ''
- container: ''
  name: Promotion
  type: ''
- container: ''
  name: Price
  type: ''
property_count: 10
provider_name: booking-com
provider_slug: booking-com
slug: booking-com-context
source_filename: booking-com-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"booking\": \"https://developers.booking.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n\n    \"Accommodation\": {\n      \"@id\": \"schema:LodgingBusiness\",\n      \"@context\": {\n        \"accommodation_id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"address\": \"schema:streetAddress\",\n        \"city\": \"schema:addressLocality\",\n        \"country\": \"schema:addressCountry\",\n        \"zip\": \"schema:postalCode\",\n        \"latitude\": \"geo:lat\",\n        \"longitude\": \"geo:long\",\n        \"star_rating\": \"schema:starRating\",\n        \"review_score\": \"schema:ratingValue\",\n        \"total_reviews\": \"schema:reviewCount\",\n        \"currency\": \"schema:priceCurrency\"\
  ,\n        \"checkin_from\": \"schema:checkinTime\",\n        \"checkout_until\": \"schema:checkoutTime\",\n        \"photos\": {\n          \"@id\": \"schema:photo\",\n          \"@container\": \"@set\"\n        },\n        \"facilities\": {\n          \"@id\": \"schema:amenityFeature\",\n          \"@container\": \"@set\"\n        },\n        \"rooms\": {\n          \"@id\": \"schema:containsPlace\",\n          \"@container\": \"@set\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Room\": {\n      \"@id\": \"schema:HotelRoom\",\n      \"@context\": {\n        \"room_id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"max_occupancy\": \"schema:occupancy\",\n        \"room_size\": \"schema:floorSize\",\n        \"bed_configurations\": {\n          \"@id\": \"schema:bed\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Order\": {\n      \"@id\": \"schema:Reservation\"\
  ,\n      \"@context\": {\n        \"order_id\": \"schema:reservationId\",\n        \"status\": \"schema:reservationStatus\",\n        \"accommodation_id\": \"schema:reservationFor\",\n        \"checkin\": {\n          \"@id\": \"schema:checkinTime\",\n          \"@type\": \"xsd:date\"\n        },\n        \"checkout\": {\n          \"@id\": \"schema:checkoutTime\",\n          \"@type\": \"xsd:date\"\n        },\n        \"total_price\": \"schema:totalPrice\",\n        \"booker\": \"schema:underName\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modified_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Booker\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"first_name\": \"schema:givenName\",\n        \"last_name\": \"schema:familyName\",\n        \"email\": \"schema:email\",\n        \"telephone\": \"\
  schema:telephone\",\n        \"country\": \"schema:nationality\"\n      }\n    },\n\n    \"Review\": {\n      \"@id\": \"schema:Review\",\n      \"@context\": {\n        \"review_id\": \"schema:identifier\",\n        \"score\": \"schema:ratingValue\",\n        \"title\": \"schema:headline\",\n        \"positive\": \"schema:positiveNotes\",\n        \"negative\": \"schema:negativeNotes\",\n        \"author\": \"schema:author\",\n        \"date\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:date\"\n        },\n        \"language\": \"schema:inLanguage\"\n      }\n    },\n\n    \"CarRental\": {\n      \"@id\": \"schema:RentalCarReservation\",\n      \"@context\": {\n        \"offer_id\": \"schema:identifier\",\n        \"pickup_date\": {\n          \"@id\": \"schema:pickupTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"dropoff_date\": {\n          \"@id\": \"schema:dropoffTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"\
  pickup_depot\": \"schema:pickupLocation\",\n        \"dropoff_depot\": \"schema:dropoffLocation\",\n        \"vehicle\": \"schema:reservationFor\"\n      }\n    },\n\n    \"Vehicle\": {\n      \"@id\": \"schema:Car\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"schema:vehicleType\",\n        \"transmission\": \"schema:vehicleTransmission\",\n        \"fuel_type\": \"schema:fuelType\",\n        \"seats\": \"schema:seatingCapacity\",\n        \"image_url\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Depot\": {\n      \"@id\": \"schema:Place\",\n      \"@context\": {\n        \"depot_id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"address\": \"schema:streetAddress\",\n        \"city\": \"schema:addressLocality\",\n        \"country\": \"schema:addressCountry\",\n        \"latitude\": \"geo:lat\",\n        \"longitude\": \"geo:long\",\n        \"phone\": \"schema:telephone\"\
  ,\n        \"opening_hours\": \"schema:openingHours\"\n      }\n    },\n\n    \"Promotion\": {\n      \"@id\": \"schema:Offer\",\n      \"@context\": {\n        \"promotion_id\": \"schema:identifier\",\n        \"promotion_type\": \"schema:category\",\n        \"discount_percentage\": \"schema:discount\",\n        \"bookable_from\": {\n          \"@id\": \"schema:validFrom\",\n          \"@type\": \"xsd:date\"\n        },\n        \"bookable_until\": {\n          \"@id\": \"schema:validThrough\",\n          \"@type\": \"xsd:date\"\n        },\n        \"status\": \"schema:availability\"\n      }\n    },\n\n    \"Price\": {\n      \"@id\": \"schema:PriceSpecification\",\n      \"@context\": {\n        \"amount\": \"schema:price\",\n        \"currency\": \"schema:priceCurrency\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/booking-com/refs/heads/main/json-ld/booking-com-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
