---
api_specs:
- filename: walk-score-openapi.yml
  format: yaml
  label: Walk Score API
  slug: walk-score-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/walk-score/refs/heads/main/openapi/walk-score-openapi.yml
- filename: walk-score-transit-openapi.yml
  format: yaml
  label: Walk Score Transit API
  slug: walk-score-transit-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/walk-score/refs/heads/main/openapi/walk-score-transit-openapi.yml
class_count: 28
classes:
- WalkScore
- TransitScore
- BikeScore
- walkscore
- transit_score
- bike_score
- description
- snapped_lat
- snapped_lon
- TransitStop
- id
- name
- distance
- summary_text
- route_ids
- TransitRoute
- short_name
- long_name
- category
- color
- text_color
- stop_ids
- geometry_wkt
- SupportedCity
- city
- state
- country
- population
context_file: json-ld/walk-score-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/walk-score/refs/heads/main/json-ld/walk-score-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Walk Score from Walk Score.
layout: jsonld
name: Walk Score Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: gtfs
  uri: http://vocab.gtfs.org/terms#
- prefix: ws
  uri: https://www.walkscore.com/vocab/
properties:
- container: ''
  name: updated
  type: dateTime
- container: ''
  name: lat
  type: decimal
- container: ''
  name: lon
  type: decimal
- container: ''
  name: ws_link
  type: reference
- container: ''
  name: logo_url
  type: reference
- container: ''
  name: agency
  type: gtfs:Agency
- container: ''
  name: agency_url
  type: reference
property_count: 7
provider_name: Walk Score
provider_slug: walk-score
slug: walk-score-context
source_filename: walk-score-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"gtfs\": \"http://vocab.gtfs.org/terms#\",\n    \"ws\": \"https://www.walkscore.com/vocab/\",\n\n    \"WalkScore\": \"ws:WalkScore\",\n    \"TransitScore\": \"ws:TransitScore\",\n    \"BikeScore\": \"ws:BikeScore\",\n    \"walkscore\": \"ws:walkScore\",\n    \"transit_score\": \"ws:transitScore\",\n    \"bike_score\": \"ws:bikeScore\",\n    \"description\": \"schema:description\",\n    \"updated\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"lat\": {\n      \"@id\": \"geo:lat\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"lon\": {\n      \"@id\": \"geo:long\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"snapped_lat\": \"ws:snappedLat\",\n    \"snapped_lon\": \"ws:snappedLon\",\n\n    \"ws_link\": {\n      \"@id\"\
  : \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"logo_url\": {\n      \"@id\": \"schema:logo\",\n      \"@type\": \"@id\"\n    },\n\n    \"TransitStop\": \"gtfs:Stop\",\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"distance\": \"schema:distance\",\n    \"summary_text\": \"schema:description\",\n    \"route_ids\": \"gtfs:routeIds\",\n\n    \"TransitRoute\": \"gtfs:Route\",\n    \"short_name\": \"gtfs:shortName\",\n    \"long_name\": \"gtfs:longName\",\n    \"category\": \"gtfs:routeType\",\n    \"agency\": {\n      \"@id\": \"gtfs:agency\",\n      \"@type\": \"gtfs:Agency\"\n    },\n    \"agency_url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"color\": \"gtfs:color\",\n    \"text_color\": \"gtfs:textColor\",\n    \"stop_ids\": \"gtfs:stopIds\",\n    \"geometry_wkt\": \"schema:polygon\",\n\n    \"SupportedCity\": \"schema:City\",\n    \"city\": \"schema:name\",\n    \"state\": \"schema:addressRegion\",\n    \"country\": \"schema:addressCountry\"\
  ,\n    \"population\": \"schema:population\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/walk-score/refs/heads/main/json-ld/walk-score-context.jsonld
tags:
- Walkability
- Transit
- Bikeability
- Location
- Real Estate
- Urban Planning
- Transportation
- JSON-LD
- Linked Data
- Semantic Web
---
