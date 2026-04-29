---
class_count: 1
classes:
- response_locationScore
context_file: json-ld/amadeus-location-score-response_location-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus-traveler-media/refs/heads/main/json-ld/amadeus-location-score-response_location-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Location Score Response_Location from Amadeus Traveler Media.
layout: jsonld
name: Amadeus Location Score Response_Location Context
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
  name: meta
  type: string
- container: set
  name: data
  type: string
- container: set
  name: warnings
  type: string
property_count: 3
provider_name: Amadeus Traveler Media
provider_slug: amadeus-traveler-media
slug: amadeus-location-score-response_location-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amadeus\": \"https://amadeus.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"response_locationScore\": \"amadeus:response_locationScore\",\n    \"meta\": {\n      \"@id\": \"amadeus:meta\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"amadeus:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"warnings\": {\n      \"@id\": \"amadeus:warnings\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus-traveler-media/refs/heads/main/json-ld/amadeus-location-score-response_location-context.jsonld
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
