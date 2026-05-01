---
api_specs:
- filename: aoc-data-api.yaml
  format: yaml
  label: Architect of the Capitol Data API
  slug: aoc-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/architect-of-the-capitol/refs/heads/main/openapi/aoc-data-api.yaml
class_count: 9
classes:
- Building
- BuildingList
- Coordinates
- Artwork
- ArtworkList
- PreservationProject
- PreservationProjectList
- VisitorInfo
- AccessibilityInfo
context_file: json-ld/aoc-data-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/architect-of-the-capitol/refs/heads/main/json-ld/aoc-data-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aoc Data Api from Architect of the Capitol.
layout: jsonld
name: Aoc Data Api Context
namespaces:
- prefix: aoc
  uri: https://www.aoc.gov/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties: []
property_count: 0
provider_name: Architect of the Capitol
provider_slug: architect-of-the-capitol
slug: aoc-data-api-context
source_filename: aoc-data-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aoc\": \"https://www.aoc.gov/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Building\": \"aoc:Building\",\n    \"BuildingList\": \"aoc:BuildingList\",\n    \"Coordinates\": \"aoc:Coordinates\",\n    \"Artwork\": \"aoc:Artwork\",\n    \"ArtworkList\": \"aoc:ArtworkList\",\n    \"PreservationProject\": \"aoc:PreservationProject\",\n    \"PreservationProjectList\": \"aoc:PreservationProjectList\",\n    \"VisitorInfo\": \"aoc:VisitorInfo\",\n    \"AccessibilityInfo\": \"aoc:AccessibilityInfo\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/architect-of-the-capitol/refs/heads/main/json-ld/aoc-data-api-context.jsonld
tags:
- Federal Government
- Capitol Hill
- Congress
- Historic Preservation
- Government Services
- JSON-LD
- Linked Data
- Semantic Web
---
