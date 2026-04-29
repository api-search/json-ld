---
api_specs:
- filename: aspentech-inmation-web-openapi.yml
  format: yaml
  label: AspenTech Inmation Web API
  slug: inmation-web-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aspentech/refs/heads/main/openapi/aspentech-inmation-web-openapi.yml
class_count: 0
classes: []
context_file: json-ld/aspentech-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aspentech/refs/heads/main/json-ld/aspentech-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aspentech from AspenTech.
layout: jsonld
name: Aspentech Context
namespaces:
- prefix: aspentech
  uri: https://atdocs.inmation.com/api/
- prefix: schema
  uri: https://schema.org/
- prefix: sosa
  uri: http://www.w3.org/ns/sosa/
- prefix: ssn
  uri: http://www.w3.org/ns/ssn/
- prefix: qudt
  uri: http://qudt.org/schema/qudt/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: time
  uri: http://www.w3.org/2006/time#
properties:
- container: ''
  name: DataItem
  type: ''
- container: ''
  name: Sensor
  type: ''
- container: ''
  name: HistoricalData
  type: ''
property_count: 3
provider_name: AspenTech
provider_slug: aspentech
slug: aspentech-context
source_filename: aspentech-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aspentech\": \"https://atdocs.inmation.com/api/\",\n    \"schema\": \"https://schema.org/\",\n    \"sosa\": \"http://www.w3.org/ns/sosa/\",\n    \"ssn\": \"http://www.w3.org/ns/ssn/\",\n    \"qudt\": \"http://qudt.org/schema/qudt/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"time\": \"http://www.w3.org/2006/time#\",\n\n    \"DataItem\": {\n      \"@id\": \"sosa:Observation\",\n      \"@context\": {\n        \"path\": {\"@id\": \"aspentech:itemPath\", \"@type\": \"xsd:string\"},\n        \"value\": {\"@id\": \"sosa:hasSimpleResult\"},\n        \"quality\": {\"@id\": \"aspentech:opcQuality\", \"@type\": \"xsd:integer\"},\n        \"timestamp\": {\"@id\": \"sosa:resultTime\", \"@type\": \"xsd:dateTime\"},\n        \"engineeringUnit\": {\"@id\": \"qudt:unit\"},\n        \"itemType\": {\"@id\": \"aspentech:itemType\"},\n        \"name\": {\"@id\": \"schema:name\"},\n        \"description\": {\"@id\": \"schema:description\"\
  },\n        \"highLimit\": {\"@id\": \"aspentech:highLimit\", \"@type\": \"xsd:double\"},\n        \"lowLimit\": {\"@id\": \"aspentech:lowLimit\", \"@type\": \"xsd:double\"},\n        \"alarmHigh\": {\"@id\": \"aspentech:alarmHigh\", \"@type\": \"xsd:double\"},\n        \"alarmLow\": {\"@id\": \"aspentech:alarmLow\", \"@type\": \"xsd:double\"}\n      }\n    },\n\n    \"Sensor\": {\n      \"@id\": \"sosa:Sensor\",\n      \"@context\": {\n        \"path\": {\"@id\": \"aspentech:itemPath\"},\n        \"name\": {\"@id\": \"schema:name\"},\n        \"description\": {\"@id\": \"schema:description\"},\n        \"observes\": {\"@id\": \"sosa:observes\"}\n      }\n    },\n\n    \"HistoricalData\": {\n      \"@id\": \"sosa:ObservationCollection\",\n      \"@context\": {\n        \"path\": {\"@id\": \"aspentech:itemPath\"},\n        \"values\": {\"@id\": \"sosa:hasMember\", \"@container\": \"@set\"},\n        \"startTime\": {\"@id\": \"time:hasBeginning\", \"@type\": \"xsd:dateTime\"},\n        \"\
  endTime\": {\"@id\": \"time:hasEnd\", \"@type\": \"xsd:dateTime\"}\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aspentech/refs/heads/main/json-ld/aspentech-context.jsonld
tags:
- Industrial IoT
- Process Optimization
- Manufacturing
- Energy
- Chemicals
- Time Series
- JSON-LD
- Linked Data
- Semantic Web
---
