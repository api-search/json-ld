---
api_specs:
- filename: foursquare-places-openapi.yml
  format: yaml
  label: Foursquare Places API
  slug: places-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/foursquare/refs/heads/main/openapi/foursquare-places-openapi.yml
class_count: 15
classes:
- Place
- name
- address
- locality
- region
- postcode
- country
- geocodes
- latitude
- longitude
- rating
- categories
- Tip
- text
- created_at
context_file: json-ld/foursquare-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/foursquare/refs/heads/main/json-ld/foursquare-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Foursquare from Foursquare.
layout: jsonld
name: Foursquare Context
namespaces:
- prefix: schema
  uri: https://schema.org/
properties: []
property_count: 0
provider_name: Foursquare
provider_slug: foursquare
slug: foursquare-context
source_filename: foursquare-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://raw.githubusercontent.com/api-evangelist/foursquare/refs/heads/main/vocabulary/foursquare-vocabulary.yml#\",\n    \"schema\": \"https://schema.org/\",\n    \"Place\": \"schema:Place\",\n    \"name\": \"schema:name\",\n    \"address\": \"schema:streetAddress\",\n    \"locality\": \"schema:addressLocality\",\n    \"region\": \"schema:addressRegion\",\n    \"postcode\": \"schema:postalCode\",\n    \"country\": \"schema:addressCountry\",\n    \"geocodes\": \"schema:geo\",\n    \"latitude\": \"schema:latitude\",\n    \"longitude\": \"schema:longitude\",\n    \"rating\": \"schema:aggregateRating\",\n    \"categories\": \"schema:additionalType\",\n    \"Tip\": \"schema:Review\",\n    \"text\": \"schema:reviewBody\",\n    \"created_at\": \"schema:dateCreated\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/foursquare/refs/heads/main/json-ld/foursquare-context.jsonld
tags:
- Locations
- Places
- Geocoding
- Recommendations
- Reviews
- Movement
- JSON-LD
- Linked Data
- Semantic Web
---
