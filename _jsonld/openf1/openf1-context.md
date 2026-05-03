---
api_specs:
- filename: openf1-openapi.yml
  format: yaml
  label: OpenF1 API
  slug: openf1
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openf1/refs/heads/main/openapi/openf1-openapi.yml
class_count: 0
classes: []
context_file: json-ld/openf1-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/openf1/refs/heads/main/json-ld/openf1-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Openf1 from OpenF1.
layout: jsonld
name: Openf1 Context
namespaces:
- prefix: openf1
  uri: https://api.openf1.org/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Session
  type: ''
- container: ''
  name: Driver
  type: ''
- container: ''
  name: Lap
  type: ''
- container: ''
  name: CarData
  type: ''
- container: ''
  name: PitStop
  type: ''
property_count: 5
provider_name: OpenF1
provider_slug: openf1
slug: openf1-context
source_filename: openf1-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"openf1\": \"https://api.openf1.org/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Session\": {\n      \"@id\": \"openf1:Session\",\n      \"@context\": {\n        \"session_key\": {\"@id\": \"openf1:sessionKey\", \"@type\": \"xsd:integer\"},\n        \"session_name\": \"schema:name\",\n        \"session_type\": \"openf1:sessionType\",\n        \"date_start\": {\"@id\": \"schema:startDate\", \"@type\": \"xsd:dateTime\"},\n        \"date_end\": {\"@id\": \"schema:endDate\", \"@type\": \"xsd:dateTime\"},\n        \"meeting_key\": {\"@id\": \"openf1:meetingKey\", \"@type\": \"xsd:integer\"},\n        \"circuit_short_name\": \"openf1:circuit\",\n        \"country_name\": \"schema:addressCountry\",\n        \"year\": {\"@id\": \"openf1:year\", \"@type\": \"xsd:integer\"}\n      }\n    },\n\n    \"Driver\": {\n  \
  \    \"@id\": \"openf1:Driver\",\n      \"@context\": {\n        \"driver_number\": {\"@id\": \"openf1:driverNumber\", \"@type\": \"xsd:integer\"},\n        \"full_name\": \"schema:name\",\n        \"first_name\": \"schema:givenName\",\n        \"last_name\": \"schema:familyName\",\n        \"name_acronym\": \"openf1:acronym\",\n        \"team_name\": \"openf1:team\",\n        \"team_colour\": \"openf1:teamColour\",\n        \"headshot_url\": {\"@id\": \"schema:image\", \"@type\": \"@id\"},\n        \"country_code\": \"schema:nationality\"\n      }\n    },\n\n    \"Lap\": {\n      \"@id\": \"openf1:Lap\",\n      \"@context\": {\n        \"lap_number\": {\"@id\": \"openf1:lapNumber\", \"@type\": \"xsd:integer\"},\n        \"lap_duration\": {\"@id\": \"openf1:lapDuration\", \"@type\": \"xsd:decimal\"},\n        \"duration_sector_1\": {\"@id\": \"openf1:sector1\", \"@type\": \"xsd:decimal\"},\n        \"duration_sector_2\": {\"@id\": \"openf1:sector2\", \"@type\": \"xsd:decimal\"},\n    \
  \    \"duration_sector_3\": {\"@id\": \"openf1:sector3\", \"@type\": \"xsd:decimal\"},\n        \"i1_speed\": {\"@id\": \"openf1:i1Speed\", \"@type\": \"xsd:integer\"},\n        \"i2_speed\": {\"@id\": \"openf1:i2Speed\", \"@type\": \"xsd:integer\"},\n        \"st_speed\": {\"@id\": \"openf1:stSpeed\", \"@type\": \"xsd:integer\"},\n        \"is_pit_out_lap\": {\"@id\": \"openf1:isPitOutLap\", \"@type\": \"xsd:boolean\"}\n      }\n    },\n\n    \"CarData\": {\n      \"@id\": \"openf1:CarData\",\n      \"@context\": {\n        \"rpm\": {\"@id\": \"openf1:rpm\", \"@type\": \"xsd:integer\"},\n        \"speed\": {\"@id\": \"openf1:speed\", \"@type\": \"xsd:integer\"},\n        \"n_gear\": {\"@id\": \"openf1:gear\", \"@type\": \"xsd:integer\"},\n        \"throttle\": {\"@id\": \"openf1:throttle\", \"@type\": \"xsd:integer\"},\n        \"brake\": {\"@id\": \"openf1:brake\", \"@type\": \"xsd:integer\"},\n        \"drs\": {\"@id\": \"openf1:drs\", \"@type\": \"xsd:integer\"},\n        \"date\"\
  : {\"@id\": \"dcterms:date\", \"@type\": \"xsd:dateTime\"}\n      }\n    },\n\n    \"PitStop\": {\n      \"@id\": \"openf1:PitStop\",\n      \"@context\": {\n        \"lap_number\": {\"@id\": \"openf1:lapNumber\", \"@type\": \"xsd:integer\"},\n        \"pit_duration\": {\"@id\": \"openf1:pitDuration\", \"@type\": \"xsd:decimal\"},\n        \"stop_duration\": {\"@id\": \"openf1:stopDuration\", \"@type\": \"xsd:decimal\"},\n        \"lane_duration\": {\"@id\": \"openf1:laneDuration\", \"@type\": \"xsd:decimal\"}\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/openf1/refs/heads/main/json-ld/openf1-context.jsonld
tags:
- Formula 1
- Motorsport
- Telemetry
- Real-Time
- Sports
- JSON-LD
- Linked Data
- Semantic Web
---
