---
api_specs:
- filename: cloudrf-openapi.yml
  format: yaml
  label: CloudRF API
  slug: cloudrf-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cloudrf/refs/heads/main/openapi/cloudrf-openapi.yml
class_count: 0
classes: []
context_file: json-ld/cloudrf-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cloudrf/refs/heads/main/json-ld/cloudrf-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cloudrf from CloudRF.
layout: jsonld
name: Cloudrf Context
namespaces:
- prefix: crf
  uri: https://cloudrf.com/ns/
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
  name: Site
  type: ''
- container: ''
  name: Calculation
  type: ''
- container: ''
  name: Antenna
  type: ''
- container: ''
  name: Receiver
  type: ''
- container: ''
  name: CoverageResult
  type: ''
- container: ''
  name: NoiseMeasurement
  type: ''
property_count: 6
provider_name: CloudRF
provider_slug: cloudrf
slug: cloudrf-context
source_filename: cloudrf-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"crf\": \"https://cloudrf.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Site\": {\n      \"@id\": \"crf:Site\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"lat\": \"geo:lat\",\n        \"lon\": \"geo:long\",\n        \"alt\": \"schema:elevation\",\n        \"frequency\": \"crf:frequency\",\n        \"txw\": \"crf:transmitterPowerWatts\",\n        \"antenna\": \"crf:antenna\"\n      }\n    },\n\n    \"Calculation\": {\n      \"@id\": \"crf:Calculation\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"type\": \"crf:calculationType\",\n        \"site\": \"crf:Site\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\
  \n        },\n        \"resolution\": \"crf:resolution\",\n        \"model\": \"crf:propagationModel\"\n      }\n    },\n\n    \"Antenna\": {\n      \"@id\": \"crf:Antenna\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"gain\": \"crf:gainDbi\",\n        \"polarization\": \"crf:polarization\",\n        \"azimuth\": \"crf:azimuth\",\n        \"tilt\": \"crf:tilt\"\n      }\n    },\n\n    \"Receiver\": {\n      \"@id\": \"crf:Receiver\",\n      \"@context\": {\n        \"lat\": \"geo:lat\",\n        \"lon\": \"geo:long\",\n        \"alt\": \"schema:elevation\",\n        \"rxg\": \"crf:receiverGainDbi\",\n        \"rxs\": \"crf:receiverSensitivityDbm\"\n      }\n    },\n\n    \"CoverageResult\": {\n      \"@id\": \"crf:CoverageResult\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"calculationId\": \"crf:calculationId\",\n        \"format\": \"schema:encodingFormat\",\n        \"url\": \"schema:url\"\
  ,\n        \"bounds\": \"crf:bounds\"\n      }\n    },\n\n    \"NoiseMeasurement\": {\n      \"@id\": \"crf:NoiseMeasurement\",\n      \"@context\": {\n        \"lat\": \"geo:lat\",\n        \"lon\": \"geo:long\",\n        \"frequency\": \"crf:frequency\",\n        \"noiseFloor\": \"crf:noiseFloorDbm\",\n        \"timestamp\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cloudrf/refs/heads/main/json-ld/cloudrf-context.jsonld
tags:
- Coverage Modeling
- HF Propagation
- Mesh Network
- Radio Frequency
- RF
- Satellite
- Signal Analysis
- Telecommunications
- Wireless Planning
- JSON-LD
- Linked Data
- Semantic Web
---
