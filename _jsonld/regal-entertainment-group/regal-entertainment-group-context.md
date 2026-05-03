---
api_specs:
- filename: regal-cinema-openapi.yml
  format: yaml
  label: Regal Cinema API
  slug: regal-cinema-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/regal-entertainment-group/refs/heads/main/openapi/regal-cinema-openapi.yml
class_count: 35
classes:
- id
- type
- Movie
- title
- synopsis
- rating
- runtime
- releaseDate
- genres
- poster
- trailerUrl
- cast
- director
- Theatre
- theatreName
- address
- phone
- amenities
- screens
- coordinates
- lat
- lng
- Showtime
- startTime
- format
- seatsAvailable
- TicketOrder
- orderId
- confirmationCode
- totalAmount
- LoyaltyMember
- memberId
- tier
- creditBalance
- lifetimeCredits
context_file: json-ld/regal-entertainment-group-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/regal-entertainment-group/refs/heads/main/json-ld/regal-entertainment-group-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Regal Entertainment Group from regal-entertainment-group.
layout: jsonld
name: Regal Entertainment Group Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: regal
  uri: https://api-evangelist.github.io/regal-entertainment-group/vocab#
properties: []
property_count: 0
provider_name: regal-entertainment-group
provider_slug: regal-entertainment-group
slug: regal-entertainment-group-context
source_filename: regal-entertainment-group-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"regal\": \"https://api-evangelist.github.io/regal-entertainment-group/vocab#\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"Movie\": \"schema:Movie\",\n    \"title\": \"schema:name\",\n    \"synopsis\": \"schema:description\",\n    \"rating\": \"schema:contentRating\",\n    \"runtime\": \"schema:duration\",\n    \"releaseDate\": \"schema:datePublished\",\n    \"genres\": \"schema:genre\",\n    \"poster\": \"schema:image\",\n    \"trailerUrl\": \"schema:trailer\",\n    \"cast\": \"schema:actor\",\n    \"director\": \"schema:director\",\n    \"Theatre\": \"schema:MovieTheater\",\n    \"theatreName\": \"schema:name\",\n    \"address\": \"schema:address\",\n    \"phone\": \"schema:telephone\",\n    \"amenities\": \"schema:amenityFeature\",\n    \"screens\": \"regal:screens\",\n    \"coordinates\": \"schema:geo\",\n    \"lat\": \"schema:latitude\",\n    \"lng\": \"schema:longitude\"\
  ,\n    \"Showtime\": \"schema:ScreeningEvent\",\n    \"startTime\": \"schema:startDate\",\n    \"format\": \"regal:screeningFormat\",\n    \"seatsAvailable\": \"schema:remainingAttendeeCapacity\",\n    \"TicketOrder\": \"schema:Order\",\n    \"orderId\": \"schema:orderNumber\",\n    \"confirmationCode\": \"schema:confirmationNumber\",\n    \"totalAmount\": \"schema:price\",\n    \"LoyaltyMember\": \"schema:Person\",\n    \"memberId\": \"schema:identifier\",\n    \"tier\": \"regal:loyaltyTier\",\n    \"creditBalance\": \"regal:loyaltyCreditBalance\",\n    \"lifetimeCredits\": \"regal:lifetimeLoyaltyCredits\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/regal-entertainment-group/refs/heads/main/json-ld/regal-entertainment-group-context.jsonld
tags:
- Cinema
- Entertainment
- Movies
- Ticketing
- Loyalty
- Theatre
- Fortune 500
- JSON-LD
- Linked Data
- Semantic Web
---
