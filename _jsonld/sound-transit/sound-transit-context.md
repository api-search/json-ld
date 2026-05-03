---
api_specs:
- filename: sound-transit-onebusaway-openapi.yml
  format: yaml
  label: Sound Transit OneBusAway API
  slug: sound-transit-onebusaway-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sound-transit/refs/heads/main/openapi/sound-transit-onebusaway-openapi.yml
class_count: 7
classes:
- Stop
- Route
- Trip
- Agency
- Vehicle
- ArrivalTime
- id
context_file: json-ld/sound-transit-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sound-transit/refs/heads/main/json-ld/sound-transit-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sound Transit from Sound Transit.
layout: jsonld
name: Sound Transit Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: gtfs
  uri: http://vocab.gtfs.org/terms#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: name
  type: string
- container: ''
  name: lat
  type: double
- container: ''
  name: lon
  type: double
- container: ''
  name: direction
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: locationType
  type: integer
- container: set
  name: routeIds
  type: reference
- container: ''
  name: wheelchairBoarding
  type: string
- container: ''
  name: shortName
  type: string
- container: ''
  name: longName
  type: string
- container: ''
  name: routeShortName
  type: string
- container: ''
  name: tripHeadsign
  type: string
- container: ''
  name: scheduledArrivalTime
  type: integer
- container: ''
  name: predictedArrivalTime
  type: integer
- container: ''
  name: predicted
  type: boolean
property_count: 15
provider_name: Sound Transit
provider_slug: sound-transit
slug: sound-transit-context
source_filename: sound-transit-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"gtfs\": \"http://vocab.gtfs.org/terms#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Stop\": \"gtfs:Stop\",\n    \"Route\": \"gtfs:Route\",\n    \"Trip\": \"gtfs:Trip\",\n    \"Agency\": \"gtfs:Agency\",\n    \"Vehicle\": \"schema:Vehicle\",\n    \"ArrivalTime\": \"gtfs:StopTime\",\n\n    \"id\": \"@id\",\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lat\": {\n      \"@id\": \"schema:latitude\",\n      \"@type\": \"xsd:double\"\n    },\n    \"lon\": {\n      \"@id\": \"schema:longitude\",\n      \"@type\": \"xsd:double\"\n    },\n    \"direction\": {\n      \"@id\": \"gtfs:direction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"gtfs:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locationType\": {\n      \"@id\": \"gtfs:locationType\",\n      \"@type\": \"xsd:integer\"\n\
  \    },\n    \"routeIds\": {\n      \"@id\": \"gtfs:servesRoute\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"wheelchairBoarding\": {\n      \"@id\": \"gtfs:wheelchairAccessible\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shortName\": {\n      \"@id\": \"gtfs:shortName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"longName\": {\n      \"@id\": \"gtfs:longName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"routeShortName\": {\n      \"@id\": \"gtfs:shortName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tripHeadsign\": {\n      \"@id\": \"gtfs:headsign\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scheduledArrivalTime\": {\n      \"@id\": \"gtfs:arrivalTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"predictedArrivalTime\": {\n      \"@id\": \"gtfs:realTimeArrivalTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"predicted\": {\n      \"@id\": \"gtfs:realTimeAvailable\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n\
  }\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sound-transit/refs/heads/main/json-ld/sound-transit-context.jsonld
tags:
- Transit
- Transportation
- GTFS
- Real-Time
- Public Transit
- Government
- Seattle
- JSON-LD
- Linked Data
- Semantic Web
---
