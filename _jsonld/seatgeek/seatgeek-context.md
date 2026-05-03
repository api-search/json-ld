---
api_specs:
- filename: seatgeek-platform-openapi.yml
  format: yaml
  label: SeatGeek Platform API
  slug: seatgeek-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/seatgeek/refs/heads/main/openapi/seatgeek-platform-openapi.yml
class_count: 27
classes:
- Event
- Performer
- Venue
- Taxonomy
- id
- title
- short_title
- datetime_utc
- datetime_local
- datetime_tbd
- status
- url
- score
- stats
- listing_count
- average_price
- lowest_price
- highest_price
- city
- state
- country
- address
- postal_code
- lat
- lon
- slug
- capacity
context_file: json-ld/seatgeek-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/seatgeek/refs/heads/main/json-ld/seatgeek-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Seatgeek from SeatGeek.
layout: jsonld
name: Seatgeek Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: seatgeek
  uri: https://seatgeek.com/vocab/
properties:
- container: ''
  name: venue
  type: schema:EventVenue
- container: set
  name: performers
  type: ''
- container: set
  name: taxonomies
  type: ''
- container: set
  name: genres
  type: ''
property_count: 4
provider_name: SeatGeek
provider_slug: seatgeek
slug: seatgeek-context
source_filename: seatgeek-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"seatgeek\": \"https://seatgeek.com/vocab/\",\n    \"Event\": \"schema:Event\",\n    \"Performer\": \"schema:PerformingGroup\",\n    \"Venue\": \"schema:EventVenue\",\n    \"Taxonomy\": \"schema:Thing\",\n    \"id\": \"@id\",\n    \"title\": \"schema:name\",\n    \"short_title\": \"schema:alternateName\",\n    \"datetime_utc\": \"schema:startDate\",\n    \"datetime_local\": \"seatgeek:localDateTime\",\n    \"datetime_tbd\": \"seatgeek:dateTimeTBD\",\n    \"status\": \"schema:eventStatus\",\n    \"url\": \"schema:url\",\n    \"score\": \"seatgeek:popularityScore\",\n    \"venue\": {\n      \"@id\": \"schema:location\",\n      \"@type\": \"schema:EventVenue\"\n    },\n    \"performers\": {\n      \"@id\": \"schema:performer\",\n      \"@container\": \"@set\"\n    },\n    \"taxonomies\": {\n      \"@id\": \"schema:genre\",\n      \"\
  @container\": \"@set\"\n    },\n    \"stats\": \"seatgeek:ticketStats\",\n    \"listing_count\": \"seatgeek:listingCount\",\n    \"average_price\": \"schema:price\",\n    \"lowest_price\": \"seatgeek:lowestPrice\",\n    \"highest_price\": \"seatgeek:highestPrice\",\n    \"city\": \"schema:addressLocality\",\n    \"state\": \"schema:addressRegion\",\n    \"country\": \"schema:addressCountry\",\n    \"address\": \"schema:streetAddress\",\n    \"postal_code\": \"schema:postalCode\",\n    \"lat\": \"schema:latitude\",\n    \"lon\": \"schema:longitude\",\n    \"slug\": \"schema:identifier\",\n    \"capacity\": \"schema:maximumAttendeeCapacity\",\n    \"genres\": {\n      \"@id\": \"schema:genre\",\n      \"@container\": \"@set\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/seatgeek/refs/heads/main/json-ld/seatgeek-context.jsonld
tags:
- Events
- Tickets
- Live Events
- Concerts
- Sports
- Venues
- Ticketing
- JSON-LD
- Linked Data
- Semantic Web
---
