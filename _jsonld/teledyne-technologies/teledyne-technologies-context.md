---
api_specs:
- filename: teledyne-flir-camera-rest-openapi.yml
  format: yaml
  label: Teledyne FLIR Camera REST API
  slug: flir-camera-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/teledyne-technologies/refs/heads/main/openapi/teledyne-flir-camera-rest-openapi.yml
class_count: 26
classes:
- ThermalMeasurement
- name
- temperature
- unit
- timestamp
- x
- y
- SpotMeasurement
- BoxMeasurement
- LineMeasurement
- max
- min
- avg
- area
- width
- height
- points
- Alarm
- instance
- state
- triggered
- threshold
- associatedROI
- ThermalCamera
- imgformat
- ROI
context_file: json-ld/teledyne-technologies-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/teledyne-technologies/refs/heads/main/json-ld/teledyne-technologies-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Teledyne Technologies from Teledyne Technologies.
layout: jsonld
name: Teledyne Technologies Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: sosa
  uri: http://www.w3.org/ns/sosa/
- prefix: qudt
  uri: http://qudt.org/schema/qudt/
- prefix: teledyne
  uri: https://www.teledyne.com/
properties: []
property_count: 0
provider_name: Teledyne Technologies
provider_slug: teledyne-technologies
slug: teledyne-technologies-context
source_filename: teledyne-technologies-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"sosa\": \"http://www.w3.org/ns/sosa/\",\n    \"qudt\": \"http://qudt.org/schema/qudt/\",\n    \"teledyne\": \"https://www.teledyne.com/\",\n\n    \"ThermalMeasurement\": \"sosa:Observation\",\n    \"name\": \"schema:name\",\n    \"temperature\": \"qudt:numericValue\",\n    \"unit\": \"qudt:unit\",\n    \"timestamp\": \"sosa:resultTime\",\n    \"x\": \"schema:xPosition\",\n    \"y\": \"schema:yPosition\",\n\n    \"SpotMeasurement\": \"sosa:Observation\",\n    \"BoxMeasurement\": \"sosa:Observation\",\n    \"LineMeasurement\": \"sosa:Observation\",\n\n    \"max\": \"schema:maxValue\",\n    \"min\": \"schema:minValue\",\n    \"avg\": \"schema:value\",\n    \"area\": \"schema:spatialCoverage\",\n    \"width\": \"schema:width\",\n    \"height\": \"schema:height\",\n    \"points\": \"schema:value\",\n\n    \"Alarm\": \"sosa:Actuation\",\n    \"instance\": \"schema:identifier\",\n    \"state\"\
  : \"schema:status\",\n    \"triggered\": \"schema:active\",\n    \"threshold\": \"qudt:numericValue\",\n    \"associatedROI\": \"sosa:hasFeatureOfInterest\",\n\n    \"ThermalCamera\": \"schema:Product\",\n    \"imgformat\": \"schema:encodingFormat\",\n\n    \"ROI\": \"schema:spatialCoverage\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/teledyne-technologies/refs/heads/main/json-ld/teledyne-technologies-context.jsonld
tags:
- Aerospace
- Defense
- Digital Imaging
- Instrumentation
- Thermal Imaging
- Test and Measurement
- Fortune 500
- JSON-LD
- Linked Data
- Semantic Web
---
