---
api_specs:
- filename: tomtom-maps-openapi.yml
  format: yaml
  label: TomTom Maps API
  slug: tomtom-maps-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tomtom/refs/heads/main/openapi/tomtom-maps-openapi.yml
- filename: tomtom-search-openapi.yml
  format: yaml
  label: TomTom Search API
  slug: tomtom-search-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tomtom/refs/heads/main/openapi/tomtom-search-openapi.yml
- filename: tomtom-routing-openapi.yml
  format: yaml
  label: TomTom Routing API
  slug: tomtom-routing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tomtom/refs/heads/main/openapi/tomtom-routing-openapi.yml
- filename: tomtom-traffic-openapi.yml
  format: yaml
  label: TomTom Traffic API
  slug: tomtom-traffic-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tomtom/refs/heads/main/openapi/tomtom-traffic-openapi.yml
class_count: 18
classes:
- Route
- Incident
- Place
- Address
- GeoCoordinate
- latitude
- longitude
- lengthInMeters
- trafficDelayInSeconds
- currentSpeed
- freeFlowSpeed
- magnitudeOfDelay
- iconCategory
- from
- to
- name
- description
- id
context_file: json-ld/tomtom-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tomtom/refs/heads/main/json-ld/tomtom-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tomtom from TomTom.
layout: jsonld
name: Tomtom Context
namespaces:
- prefix: tomtom
  uri: https://developer.tomtom.com/#
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: travelTimeInSeconds
  type: integer
- container: ''
  name: departureTime
  type: dateTime
- container: ''
  name: arrivalTime
  type: dateTime
- container: ''
  name: url
  type: reference
property_count: 4
provider_name: TomTom
provider_slug: tomtom
slug: tomtom-context
source_filename: tomtom-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"tomtom\": \"https://developer.tomtom.com/#\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Route\": \"schema:Trip\",\n    \"Incident\": \"schema:TrafficCondition\",\n    \"Place\": \"schema:Place\",\n    \"Address\": \"schema:PostalAddress\",\n    \"GeoCoordinate\": \"schema:GeoCoordinates\",\n    \"latitude\": \"geo:lat\",\n    \"longitude\": \"geo:long\",\n    \"lengthInMeters\": \"schema:distance\",\n    \"travelTimeInSeconds\": {\n      \"@id\": \"schema:travelTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"departureTime\": {\n      \"@id\": \"schema:departureTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"arrivalTime\": {\n      \"@id\": \"schema:arrivalTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"trafficDelayInSeconds\": \"tomtom:trafficDelay\",\n    \"currentSpeed\": \"tomtom:currentSpeed\",\n\
  \    \"freeFlowSpeed\": \"tomtom:freeFlowSpeed\",\n    \"magnitudeOfDelay\": \"tomtom:delayMagnitude\",\n    \"iconCategory\": \"tomtom:incidentCategory\",\n    \"from\": \"schema:startLocation\",\n    \"to\": \"schema:endLocation\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"id\": \"@id\",\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tomtom/refs/heads/main/json-ld/tomtom-context.jsonld
tags:
- Maps
- Traffic
- Transportation
- Navigation
- Location
- Geospatial
- Routing
- Geocoding
- JSON-LD
- Linked Data
- Semantic Web
---
