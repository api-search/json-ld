---
class_count: 1
classes:
- Warning
context_file: json-ld/amadeus-hotel-ratings-warning-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus-traveler-media/refs/heads/main/json-ld/amadeus-hotel-ratings-warning-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Hotel Ratings Warning from Amadeus Traveler Media.
layout: jsonld
name: Amadeus Hotel Ratings Warning Context
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
  name: code
  type: integer
- container: ''
  name: title
  type: string
- container: ''
  name: detail
  type: string
- container: ''
  name: source
  type: string
- container: ''
  name: documentation
  type: string
property_count: 5
provider_name: Amadeus Traveler Media
provider_slug: amadeus-traveler-media
slug: amadeus-hotel-ratings-warning-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amadeus\": \"https://amadeus.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Warning\": \"amadeus:Warning\",\n    \"code\": {\n      \"@id\": \"amadeus:code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"title\": {\n      \"@id\": \"amadeus:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detail\": {\n      \"@id\": \"amadeus:detail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"amadeus:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"documentation\": {\n      \"@id\": \"amadeus:documentation\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus-traveler-media/refs/heads/main/json-ld/amadeus-hotel-ratings-warning-context.jsonld
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
