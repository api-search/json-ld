---
api_specs:
- filename: siemens-building-operations-openapi.yml
  format: yaml
  label: Siemens Building Operations API
  slug: building-operations-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/siemens/refs/heads/main/openapi/siemens-building-operations-openapi.yml
class_count: 15
classes:
- Building
- Equipment
- DataPoint
- Alarm
- Schedule
- TrendRecord
- id
- name
- description
- type
- status
- severity
- location
- value
- quality
context_file: json-ld/siemens-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/siemens/refs/heads/main/json-ld/siemens-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Siemens from Siemens.
layout: jsonld
name: Siemens Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: siemens
  uri: https://developer.siemens.com/vocab/
- prefix: brick
  uri: https://brickschema.org/schema/Brick#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: unit
  type: reference
- container: ''
  name: writable
  type: boolean
- container: ''
  name: equipmentId
  type: reference
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: triggeredAt
  type: dateTime
- container: ''
  name: acknowledgedAt
  type: dateTime
- container: ''
  name: effectiveFrom
  type: dateTime
- container: ''
  name: effectiveTo
  type: dateTime
property_count: 8
provider_name: Siemens
provider_slug: siemens
slug: siemens-context
source_filename: siemens-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"siemens\": \"https://developer.siemens.com/vocab/\",\n    \"brick\": \"https://brickschema.org/schema/Brick#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Building\": \"schema:LodgingBusiness\",\n    \"Equipment\": \"brick:Equipment\",\n    \"DataPoint\": \"brick:Point\",\n    \"Alarm\": \"siemens:Alarm\",\n    \"Schedule\": \"siemens:Schedule\",\n    \"TrendRecord\": \"siemens:TrendRecord\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"type\": \"schema:additionalType\",\n    \"unit\": {\n      \"@id\": \"siemens:unit\",\n      \"@type\": \"@id\"\n    },\n    \"writable\": {\n      \"@id\": \"siemens:writable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"status\": \"siemens:operationalStatus\",\n    \"severity\": \"siemens:severity\",\n    \"location\": \"schema:location\",\n    \"equipmentId\"\
  : {\n      \"@id\": \"siemens:belongsToEquipment\",\n      \"@type\": \"@id\"\n    },\n    \"value\": \"schema:value\",\n    \"timestamp\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"quality\": \"siemens:dataQuality\",\n    \"triggeredAt\": {\n      \"@id\": \"siemens:triggeredAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"acknowledgedAt\": {\n      \"@id\": \"siemens:acknowledgedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"effectiveFrom\": {\n      \"@id\": \"schema:validFrom\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"effectiveTo\": {\n      \"@id\": \"schema:validThrough\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/siemens/refs/heads/main/json-ld/siemens-context.jsonld
tags:
- Automation
- Electrification
- Industry
- Manufacturing
- Building Automation
- Industrial IoT
- Smart Buildings
- Digital Twin
- JSON-LD
- Linked Data
- Semantic Web
---
