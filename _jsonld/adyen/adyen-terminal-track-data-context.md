---
class_count: 1
classes:
- TrackData
context_file: json-ld/adyen-terminal-track-data-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-track-data-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Track Data from Adyen.
layout: jsonld
name: Adyen Terminal Track Data Context
namespaces:
- prefix: adyen
  uri: https://docs.adyen.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: TrackNumb
  type: integer
- container: ''
  name: TrackFormat
  type: string
- container: ''
  name: TrackValue
  type: string
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-track-data-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"TrackData\": \"adyen:TrackData\",\n    \"TrackNumb\": {\n      \"@id\": \"adyen:TrackNumb\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"TrackFormat\": {\n      \"@id\": \"adyen:TrackFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TrackValue\": {\n      \"@id\": \"adyen:TrackValue\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-track-data-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
