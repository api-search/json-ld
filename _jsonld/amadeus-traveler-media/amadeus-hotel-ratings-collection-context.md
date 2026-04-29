---
api_specs:
- filename: amadeus-traveler-media-points-of-interest-openapi.yaml
  format: yaml
  label: Points of Interest API
  slug: points-of-interest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amadeus-traveler-media/refs/heads/main/openapi/amadeus-traveler-media-points-of-interest-openapi.yaml
- filename: amadeus-traveler-media-hotel-ratings-openapi.yaml
  format: yaml
  label: Hotel Ratings API
  slug: hotel-ratings-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amadeus-traveler-media/refs/heads/main/openapi/amadeus-traveler-media-hotel-ratings-openapi.yaml
- filename: amadeus-traveler-media-travel-recommendations-openapi.yaml
  format: yaml
  label: Travel Recommendations API
  slug: travel-recommendations-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amadeus-traveler-media/refs/heads/main/openapi/amadeus-traveler-media-travel-recommendations-openapi.yaml
- filename: amadeus-traveler-media-location-score-openapi.yaml
  format: yaml
  label: Location Score API
  slug: location-score-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amadeus-traveler-media/refs/heads/main/openapi/amadeus-traveler-media-location-score-openapi.yaml
class_count: 2
classes:
- CollectionMeta
- CollectionLinks
context_file: json-ld/amadeus-hotel-ratings-collection-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus-traveler-media/refs/heads/main/json-ld/amadeus-hotel-ratings-collection-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Hotel Ratings Collection from Amadeus Traveler Media.
layout: jsonld
name: Amadeus Hotel Ratings Collection Context
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
  name: count
  type: integer
- container: ''
  name: links
  type: string
- container: ''
  name: self
  type: reference
- container: ''
  name: next
  type: reference
- container: ''
  name: previous
  type: reference
- container: ''
  name: last
  type: reference
- container: ''
  name: first
  type: reference
- container: ''
  name: up
  type: reference
property_count: 8
provider_name: Amadeus Traveler Media
provider_slug: amadeus-traveler-media
slug: amadeus-hotel-ratings-collection-context
source_filename: amadeus-hotel-ratings-collection-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amadeus\": \"https://amadeus.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CollectionMeta\": \"amadeus:CollectionMeta\",\n    \"CollectionLinks\": \"amadeus:CollectionLinks\",\n    \"count\": {\n      \"@id\": \"amadeus:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"links\": {\n      \"@id\": \"amadeus:links\",\n      \"@type\": \"xsd:string\"\n    },\n    \"self\": {\n      \"@id\": \"amadeus:self\",\n      \"@type\": \"@id\"\n    },\n    \"next\": {\n      \"@id\": \"amadeus:next\",\n      \"@type\": \"@id\"\n    },\n    \"previous\": {\n      \"@id\": \"amadeus:previous\",\n      \"@type\": \"@id\"\n    },\n    \"last\": {\n      \"@id\": \"amadeus:last\",\n      \"@type\": \"@id\"\n    },\n    \"first\": {\n      \"@id\": \"amadeus:first\",\n      \"@type\": \"@id\"\n    },\n    \"up\": {\n\
  \      \"@id\": \"amadeus:up\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus-traveler-media/refs/heads/main/json-ld/amadeus-hotel-ratings-collection-context.jsonld
tags:
- Content
- Destination
- Media
- Photos
- Points of Interest
- Tourism
- Travel
- JSON-LD
- Linked Data
- Semantic Web
---
