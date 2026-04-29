---
api_specs:
- filename: cta-train-tracker-openapi.yml
  format: yaml
  label: CTA Train Tracker API
  slug: train-tracker-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/chicago-transit-authority/refs/heads/main/openapi/cta-train-tracker-openapi.yml
- filename: cta-bus-tracker-openapi.yml
  format: yaml
  label: CTA Bus Tracker API
  slug: bus-tracker-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/chicago-transit-authority/refs/heads/main/openapi/cta-bus-tracker-openapi.yml
class_count: 0
classes: []
context_file: json-ld/chicago-transit-authority-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/chicago-transit-authority/refs/heads/main/json-ld/chicago-transit-authority-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Chicago Transit Authority from Chicago Transit Authority.
layout: jsonld
name: Chicago Transit Authority Context
namespaces:
- prefix: cta
  uri: https://www.transitchicago.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: TrainArrival
  type: ''
- container: ''
  name: BusPrediction
  type: ''
- container: ''
  name: Vehicle
  type: ''
- container: ''
  name: Alert
  type: ''
property_count: 4
provider_name: Chicago Transit Authority
provider_slug: chicago-transit-authority
slug: chicago-transit-authority-context
source_filename: chicago-transit-authority-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cta\": \"https://www.transitchicago.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"TrainArrival\": {\n      \"@id\": \"cta:TrainArrival\",\n      \"@context\": {\n        \"stationId\": \"cta:staId\",\n        \"stationName\": \"schema:name\",\n        \"stopId\": \"cta:stpId\",\n        \"runNumber\": \"cta:runNumber\",\n        \"route\": \"cta:route\",\n        \"destination\": \"cta:destination\",\n        \"predictionTime\": {\n          \"@id\": \"cta:predictionTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"arrivalTime\": {\n          \"@id\": \"cta:arrivalTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"isApproaching\": {\n          \"@id\": \"cta:isApproaching\",\n          \"@type\": \"xsd:boolean\"\
  \n        },\n        \"isScheduled\": {\n          \"@id\": \"cta:isScheduled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isDelayed\": {\n          \"@id\": \"cta:isDelayed\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"latitude\": {\n          \"@id\": \"geo:lat\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"longitude\": {\n          \"@id\": \"geo:long\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"heading\": \"cta:heading\"\n      }\n    },\n\n    \"BusPrediction\": {\n      \"@id\": \"cta:BusPrediction\",\n      \"@context\": {\n        \"stopId\": \"cta:stpid\",\n        \"stopName\": \"schema:name\",\n        \"vehicleId\": \"cta:vid\",\n        \"route\": \"cta:rt\",\n        \"destination\": \"cta:des\",\n        \"predictionTime\": {\n          \"@id\": \"cta:predictionTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"predictionMinutes\": {\n          \"@id\": \"cta:prdctdn\",\n       \
  \   \"@type\": \"xsd:integer\"\n        },\n        \"delayed\": {\n          \"@id\": \"cta:dly\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Vehicle\": {\n      \"@id\": \"cta:Vehicle\",\n      \"@context\": {\n        \"vehicleId\": \"cta:vid\",\n        \"route\": \"cta:rt\",\n        \"destination\": \"cta:des\",\n        \"latitude\": {\n          \"@id\": \"geo:lat\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"longitude\": {\n          \"@id\": \"geo:long\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"heading\": \"cta:hdg\",\n        \"speed\": \"cta:spd\",\n        \"timestamp\": {\n          \"@id\": \"cta:tmstmp\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Alert\": {\n      \"@id\": \"cta:Alert\",\n      \"@context\": {\n        \"alertId\": \"cta:alertId\",\n        \"headline\": \"schema:headline\",\n        \"description\": \"schema:description\",\n        \"severity\": \"\
  cta:severityScore\",\n        \"impact\": \"cta:impact\",\n        \"startDate\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endDate\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/chicago-transit-authority/refs/heads/main/json-ld/chicago-transit-authority-context.jsonld
tags:
- Bus
- Bus Tracker
- Chicago
- CTA
- Customer Alerts
- GTFS
- L Train
- Open Data
- Public Transit
- Real-Time
- Train
- Train Tracker
- Transit
- Transportation
- JSON-LD
- Linked Data
- Semantic Web
---
