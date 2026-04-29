---
class_count: 1
classes:
- response_error
context_file: json-ld/amadeus-travel-recommendations-response_error-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus-traveler-media/refs/heads/main/json-ld/amadeus-travel-recommendations-response_error-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Travel Recommendations Response_Error from Amadeus Traveler Media.
layout: jsonld
name: Amadeus Travel Recommendations Response_Error Context
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
  name: errors
  type: string
property_count: 1
provider_name: Amadeus Traveler Media
provider_slug: amadeus-traveler-media
slug: amadeus-travel-recommendations-response_error-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amadeus\": \"https://amadeus.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"response_error\": \"amadeus:response_error\",\n    \"errors\": {\n      \"@id\": \"amadeus:errors\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus-traveler-media/refs/heads/main/json-ld/amadeus-travel-recommendations-response_error-context.jsonld
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
