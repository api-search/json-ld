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
- response_recommendedLocation
context_file: json-ld/amadeus-travel-recommendations-response_recommended-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus-traveler-media/refs/heads/main/json-ld/amadeus-travel-recommendations-response_recommended-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Travel Recommendations Response_Recommended from Amadeus Traveler Media.
layout: jsonld
name: Amadeus Travel Recommendations Response_Recommended Context
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
- container: set
  name: warnings
  type: string
- container: set
  name: data
  type: string
- container: ''
  name: meta
  type: string
property_count: 3
provider_name: Amadeus Traveler Media
provider_slug: amadeus-traveler-media
slug: amadeus-travel-recommendations-response_recommended-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amadeus\": \"https://amadeus.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"response_recommendedLocation\": \"amadeus:response_recommendedLocation\",\n    \"warnings\": {\n      \"@id\": \"amadeus:warnings\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"amadeus:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"meta\": {\n      \"@id\": \"amadeus:meta\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus-traveler-media/refs/heads/main/json-ld/amadeus-travel-recommendations-response_recommended-context.jsonld
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
