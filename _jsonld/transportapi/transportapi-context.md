---
api_specs:
- filename: transportapi-openapi.yml
  format: yaml
  label: TransportAPI
  slug: transportapi
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/transportapi/refs/heads/main/openapi/transportapi-openapi.yml
class_count: 29
classes:
- TransportStop
- TrainStation
- BusStop
- Departure
- Journey
- RoutePart
- Place
- id
- name
- atcocode
- station_code
- latitude
- longitude
- mode
- line
- line_name
- operator
- operator_name
- aimed_departure_time
- expected_departure_time
- from_point_name
- to_point_name
- departure_datetime
- arrival_datetime
- duration
- coordinates
- type
- distance
- description
context_file: json-ld/transportapi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/transportapi/refs/heads/main/json-ld/transportapi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Transportapi from TransportAPI.
layout: jsonld
name: Transportapi Context
namespaces:
- prefix: tapi
  uri: https://transportapi.com/vocab/
- prefix: gtfs
  uri: http://vocab.gtfs.org/terms#
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
properties: []
property_count: 0
provider_name: TransportAPI
provider_slug: transportapi
slug: transportapi-context
source_filename: transportapi-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"tapi\": \"https://transportapi.com/vocab/\",\n    \"gtfs\": \"http://vocab.gtfs.org/terms#\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"TransportStop\": \"gtfs:Stop\",\n    \"TrainStation\": \"schema:TrainStation\",\n    \"BusStop\": \"schema:BusStop\",\n    \"Departure\": \"tapi:Departure\",\n    \"Journey\": \"tapi:Journey\",\n    \"RoutePart\": \"tapi:RoutePart\",\n    \"Place\": \"schema:Place\",\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"atcocode\": \"tapi:atcocode\",\n    \"station_code\": \"tapi:crsCode\",\n    \"latitude\": \"geo:lat\",\n    \"longitude\": \"geo:long\",\n    \"mode\": \"gtfs:routeType\",\n    \"line\": \"gtfs:route\",\n    \"line_name\": \"schema:name\",\n    \"operator\": \"schema:provider\",\n    \"operator_name\": \"schema:name\",\n    \"aimed_departure_time\": \"gtfs:departureTime\",\n    \"expected_departure_time\": \"tapi:expectedDepartureTime\"\
  ,\n    \"from_point_name\": \"schema:departureAirport\",\n    \"to_point_name\": \"schema:arrivalAirport\",\n    \"departure_datetime\": \"schema:departureTime\",\n    \"arrival_datetime\": \"schema:arrivalTime\",\n    \"duration\": \"schema:duration\",\n    \"coordinates\": \"geo:lat\",\n    \"type\": \"schema:additionalType\",\n    \"distance\": \"schema:distance\",\n    \"description\": \"schema:description\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/transportapi/refs/heads/main/json-ld/transportapi-context.jsonld
tags:
- Public Transit
- Transport
- UK
- Real-Time
- Journey Planning
- Bus
- Rail
- JSON-LD
- Linked Data
- Semantic Web
---
