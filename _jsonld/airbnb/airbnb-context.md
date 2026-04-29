---
class_count: 0
classes: []
context_file: json-ld/airbnb-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/airbnb/refs/heads/main/json-ld/airbnb-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Airbnb from airbnb.
layout: jsonld
name: Airbnb Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: airbnb
  uri: https://raw.githubusercontent.com/api-evangelist/airbnb/refs/heads/main/json-schema/
properties:
- container: ''
  name: Listing
  type: ''
- container: ''
  name: id
  type: ''
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: property_type
  type: string
- container: ''
  name: bedrooms
  type: integer
- container: ''
  name: max_guests
  type: integer
- container: ''
  name: base_price
  type: decimal
- container: ''
  name: currency
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: Reservation
  type: ''
- container: ''
  name: check_in
  type: date
- container: ''
  name: check_out
  type: date
- container: ''
  name: guests
  type: integer
- container: ''
  name: total_price
  type: decimal
- container: ''
  name: Experience
  type: ''
- container: ''
  name: duration_hours
  type: decimal
- container: ''
  name: price_per_person
  type: decimal
- container: ''
  name: Guest
  type: ''
- container: ''
  name: first_name
  type: string
- container: ''
  name: last_name
  type: string
- container: ''
  name: email
  type: string
- container: ''
  name: Review
  type: ''
- container: ''
  name: rating
  type: integer
- container: ''
  name: body
  type: string
- container: ''
  name: Address
  type: ''
- container: ''
  name: street
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: latitude
  type: decimal
- container: ''
  name: longitude
  type: decimal
- container: ''
  name: created_at
  type: dateTime
- container: ''
  name: updated_at
  type: dateTime
property_count: 34
provider_name: airbnb
provider_slug: airbnb
slug: airbnb-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"airbnb\": \"https://raw.githubusercontent.com/api-evangelist/airbnb/refs/heads/main/json-schema/\",\n    \"Listing\": {\n      \"@id\": \"schema:LodgingBusiness\"\n    },\n    \"id\": {\n      \"@id\": \"@id\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"property_type\": {\n      \"@id\": \"schema:additionalType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bedrooms\": {\n      \"@id\": \"schema:numberOfRooms\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"max_guests\": {\n      \"@id\": \"schema:maximumAttendeeCapacity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"base_price\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n  \
  \  },\n    \"currency\": {\n      \"@id\": \"schema:priceCurrency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"schema:itemCondition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Reservation\": {\n      \"@id\": \"schema:LodgingReservation\"\n    },\n    \"check_in\": {\n      \"@id\": \"schema:checkinTime\",\n      \"@type\": \"xsd:date\"\n    },\n    \"check_out\": {\n      \"@id\": \"schema:checkoutTime\",\n      \"@type\": \"xsd:date\"\n    },\n    \"guests\": {\n      \"@id\": \"schema:partySize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"total_price\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"Experience\": {\n      \"@id\": \"schema:Event\"\n    },\n    \"duration_hours\": {\n      \"@id\": \"schema:duration\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"price_per_person\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"Guest\": {\n      \"@id\":\
  \ \"schema:Person\"\n    },\n    \"first_name\": {\n      \"@id\": \"schema:givenName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"last_name\": {\n      \"@id\": \"schema:familyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Review\": {\n      \"@id\": \"schema:Review\"\n    },\n    \"rating\": {\n      \"@id\": \"schema:ratingValue\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"body\": {\n      \"@id\": \"schema:reviewBody\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Address\": {\n      \"@id\": \"schema:PostalAddress\"\n    },\n    \"street\": {\n      \"@id\": \"schema:streetAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"schema:addressLocality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"schema:addressRegion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"schema:addressCountry\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"latitude\": {\n      \"@id\": \"schema:latitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"longitude\": {\n      \"@id\": \"schema:longitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"created_at\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updated_at\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/airbnb/refs/heads/main/json-ld/airbnb-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
