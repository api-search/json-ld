---
class_count: 1
classes:
- UTMCoordinates
context_file: json-ld/adyen-terminal-utm-coordinates-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-utm-coordinates-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Utm Coordinates from Adyen.
layout: jsonld
name: Adyen Terminal Utm Coordinates Context
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
  name: UTMZone
  type: string
- container: ''
  name: UTMEastward
  type: string
- container: ''
  name: UTMNorthward
  type: string
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-utm-coordinates-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"UTMCoordinates\": \"adyen:UTMCoordinates\",\n    \"UTMZone\": {\n      \"@id\": \"adyen:UTMZone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UTMEastward\": {\n      \"@id\": \"adyen:UTMEastward\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UTMNorthward\": {\n      \"@id\": \"adyen:UTMNorthward\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-utm-coordinates-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
