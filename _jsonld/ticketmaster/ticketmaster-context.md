---
api_specs:
- filename: ticketmaster-discovery-openapi.yml
  format: yaml
  label: Ticketmaster Discovery API
  slug: ticketmaster-discovery-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ticketmaster/refs/heads/main/openapi/ticketmaster-discovery-openapi.yml
- filename: ticketmaster-commerce-openapi.yml
  format: yaml
  label: Ticketmaster Commerce API
  slug: ticketmaster-commerce-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ticketmaster/refs/heads/main/openapi/ticketmaster-commerce-openapi.yml
class_count: 31
classes:
- Event
- id
- name
- url
- locale
- startDate
- endDate
- eventStatus
- Venue
- city
- state
- country
- postalCode
- address
- location
- longitude
- latitude
- Attraction
- PriceRange
- priceRanges
- min
- max
- currency
- Image
- images
- width
- height
- ratio
- totalElements
- totalPages
- size
context_file: json-ld/ticketmaster-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ticketmaster/refs/heads/main/json-ld/ticketmaster-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ticketmaster from Ticketmaster.
layout: jsonld
name: Ticketmaster Context
namespaces:
- prefix: tm
  uri: https://developer.ticketmaster.com/ontology/
properties:
- container: ''
  name: dates
  type: reference
- container: ''
  name: Classification
  type: reference
- container: ''
  name: segment
  type: reference
- container: ''
  name: genre
  type: reference
- container: ''
  name: subGenre
  type: reference
- container: ''
  name: promoter
  type: reference
- container: ''
  name: page
  type: reference
property_count: 7
provider_name: Ticketmaster
provider_slug: ticketmaster
slug: ticketmaster-context
source_filename: ticketmaster-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"tm\": \"https://developer.ticketmaster.com/ontology/\",\n\n    \"Event\": \"Event\",\n    \"id\": \"@id\",\n    \"name\": \"name\",\n    \"url\": \"url\",\n    \"locale\": \"inLanguage\",\n\n    \"dates\": {\n      \"@id\": \"tm:dates\",\n      \"@type\": \"@id\"\n    },\n    \"startDate\": \"startDate\",\n    \"endDate\": \"endDate\",\n    \"eventStatus\": \"eventStatus\",\n\n    \"Venue\": \"Place\",\n    \"city\": \"addressLocality\",\n    \"state\": \"addressRegion\",\n    \"country\": \"addressCountry\",\n    \"postalCode\": \"postalCode\",\n    \"address\": \"address\",\n    \"location\": \"geo\",\n    \"longitude\": \"longitude\",\n    \"latitude\": \"latitude\",\n\n    \"Attraction\": \"Person\",\n\n    \"Classification\": {\n      \"@id\": \"tm:Classification\",\n      \"@type\": \"@id\"\n    },\n    \"segment\": {\n      \"@id\": \"tm:segment\",\n      \"@type\": \"@id\"\n    },\n    \"genre\":\
  \ {\n      \"@id\": \"tm:genre\",\n      \"@type\": \"@id\"\n    },\n    \"subGenre\": {\n      \"@id\": \"tm:subGenre\",\n      \"@type\": \"@id\"\n    },\n\n    \"PriceRange\": \"PriceSpecification\",\n    \"priceRanges\": \"offers\",\n    \"min\": \"minPrice\",\n    \"max\": \"maxPrice\",\n    \"currency\": \"priceCurrency\",\n\n    \"Image\": \"ImageObject\",\n    \"images\": \"image\",\n    \"width\": \"width\",\n    \"height\": \"height\",\n    \"ratio\": \"tm:ratio\",\n\n    \"promoter\": {\n      \"@id\": \"tm:promoter\",\n      \"@type\": \"@id\"\n    },\n\n    \"page\": {\n      \"@id\": \"tm:page\",\n      \"@type\": \"@id\"\n    },\n    \"totalElements\": \"tm:totalElements\",\n    \"totalPages\": \"tm:totalPages\",\n    \"size\": \"tm:pageSize\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ticketmaster/refs/heads/main/json-ld/ticketmaster-context.jsonld
tags:
- Commerce
- Concerts
- Entertainment
- Events
- Sports
- Tickets
- Venues
- JSON-LD
- Linked Data
- Semantic Web
---
