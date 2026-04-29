---
class_count: 1
classes:
- GeographicCoordinates
context_file: json-ld/adyen-terminal-geographic-coordinates-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-geographic-coordinates-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Geographic Coordinates from Adyen.
layout: jsonld
name: Adyen Terminal Geographic Coordinates Context
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
  name: Latitude
  type: string
- container: ''
  name: Longitude
  type: string
property_count: 2
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-geographic-coordinates-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"GeographicCoordinates\": \"adyen:GeographicCoordinates\",\n    \"Latitude\": {\n      \"@id\": \"adyen:Latitude\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Longitude\": {\n      \"@id\": \"adyen:Longitude\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-geographic-coordinates-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
