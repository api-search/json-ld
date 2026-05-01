---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google Places API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-places/refs/heads/main/openapi/openapi.yml
class_count: 16
classes:
- Place
- name
- description
- address
- geo
- latitude
- longitude
- telephone
- url
- photo
- review
- aggregateRating
- ratingValue
- openingHoursSpecification
- priceRange
- type
context_file: json-ld/context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-places/refs/heads/main/json-ld/context.jsonld
description: JSON-LD context defining the semantic vocabulary for context from Google Places.
layout: jsonld
name: context Context
namespaces:
- prefix: places
  uri: https://places.googleapis.com/v1/
properties: []
property_count: 0
provider_name: Google Places
provider_slug: google-places
slug: context
source_filename: context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"places\": \"https://places.googleapis.com/v1/\",\n    \"Place\": \"schema:Place\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"address\": \"schema:address\",\n    \"geo\": \"schema:geo\",\n    \"latitude\": \"schema:latitude\",\n    \"longitude\": \"schema:longitude\",\n    \"telephone\": \"schema:telephone\",\n    \"url\": \"schema:url\",\n    \"photo\": \"schema:photo\",\n    \"review\": \"schema:review\",\n    \"aggregateRating\": \"schema:aggregateRating\",\n    \"ratingValue\": \"schema:ratingValue\",\n    \"openingHoursSpecification\": \"schema:openingHoursSpecification\",\n    \"priceRange\": \"schema:priceRange\",\n    \"type\": \"schema:additionalType\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-places/refs/heads/main/json-ld/context.jsonld
tags:
- Geolocation
- Google
- Locations
- Maps
- Places
- Points of Interest
- JSON-LD
- Linked Data
- Semantic Web
---
