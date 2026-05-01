---
api_specs:
- filename: dmi-open-data-api-openapi.yml
  format: yaml
  label: DMI Open Data API
  slug: dmi-open-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/danish-meteorological-institutes/refs/heads/main/openapi/dmi-open-data-api-openapi.yml
class_count: 2
classes:
- Observation
- Station
context_file: json-ld/dmi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/danish-meteorological-institutes/refs/heads/main/json-ld/dmi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dmi from Danish Meteorological Institutes.
layout: jsonld
name: Dmi Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: geo
  uri: http://www.opengis.net/ont/geosparql#
- prefix: dmi
  uri: https://schema.dmi.dk/
properties:
- container: ''
  name: stationId
  type: schema:Text
- container: ''
  name: parameterId
  type: schema:Text
- container: ''
  name: observed
  type: schema:DateTime
- container: ''
  name: value
  type: schema:Number
- container: ''
  name: name
  type: schema:Text
- container: ''
  name: country
  type: schema:Text
- container: ''
  name: geometry
  type: ''
- container: ''
  name: coordinates
  type: ''
property_count: 8
provider_name: Danish Meteorological Institutes
provider_slug: danish-meteorological-institutes
slug: dmi-context
source_filename: dmi-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.dmi.dk/\",\n    \"schema\": \"https://schema.org/\",\n    \"geo\": \"http://www.opengis.net/ont/geosparql#\",\n    \"dmi\": \"https://schema.dmi.dk/\",\n    \"Observation\": \"dmi:Observation\",\n    \"Station\": \"dmi:Station\",\n    \"stationId\": {\"@id\": \"dmi:stationId\", \"@type\": \"schema:Text\"},\n    \"parameterId\": {\"@id\": \"dmi:parameterId\", \"@type\": \"schema:Text\"},\n    \"observed\": {\"@id\": \"dmi:observed\", \"@type\": \"schema:DateTime\"},\n    \"value\": {\"@id\": \"schema:value\", \"@type\": \"schema:Number\"},\n    \"name\": {\"@id\": \"schema:name\", \"@type\": \"schema:Text\"},\n    \"country\": {\"@id\": \"schema:addressCountry\", \"@type\": \"schema:Text\"},\n    \"geometry\": {\"@id\": \"geo:hasGeometry\"},\n    \"coordinates\": {\"@id\": \"geo:asGeoJSON\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/danish-meteorological-institutes/refs/heads/main/json-ld/dmi-context.jsonld
tags:
- Climate
- Environment
- Lightning
- Meteorological
- Ocean
- Open Data
- Weather
- JSON-LD
- Linked Data
- Semantic Web
---
