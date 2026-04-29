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
class_count: 1
classes:
- Meta
context_file: json-ld/amadeus-travel-recommendations-meta-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus-traveler-media/refs/heads/main/json-ld/amadeus-travel-recommendations-meta-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Travel Recommendations Meta from Amadeus Traveler Media.
layout: jsonld
name: Amadeus Travel Recommendations Meta Context
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
property_count: 2
provider_name: Amadeus Traveler Media
provider_slug: amadeus-traveler-media
slug: amadeus-travel-recommendations-meta-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amadeus\": \"https://amadeus.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Meta\": \"amadeus:Meta\",\n    \"count\": {\n      \"@id\": \"amadeus:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"links\": {\n      \"@id\": \"amadeus:links\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus-traveler-media/refs/heads/main/json-ld/amadeus-travel-recommendations-meta-context.jsonld
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
