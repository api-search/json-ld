---
class_count: 0
classes: []
context_file: json-ld/amadeus-transfer-management-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus/refs/heads/main/json-ld/amadeus-transfer-management-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Transfer Management from Amadeus.
layout: jsonld
name: Amadeus Transfer Management Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: confirmNbr
  type: string
- container: ''
  name: reservationStatus
  type: string
- container: ''
  name: errors
  type: ''
property_count: 3
provider_name: Amadeus
provider_slug: amadeus
slug: amadeus-transfer-management-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"confirmNbr\": {\n      \"@id\": \"schema:confirmNbr\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reservationStatus\": {\n      \"@id\": \"schema:reservationStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errors\": {\n      \"@id\": \"schema:errors\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus/refs/heads/main/json-ld/amadeus-transfer-management-context.jsonld
tags:
- Airlines
- Aviation
- Booking
- Destinations
- Flights
- Hospitality
- Hotels
- Market Insights
- Tourism
- Transfers
- Travel
- JSON-LD
- Linked Data
- Semantic Web
---
