---
api_specs:
- filename: vertiv-environet-alert-openapi.yml
  format: yaml
  label: Vertiv Environet Alert REST API
  slug: environet-alert-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vertiv/refs/heads/main/openapi/vertiv-environet-alert-openapi.yml
class_count: 7
classes:
- Alarm
- Device
- Sensor
- Rack
- Circuit
- Asset
- DataCenter
context_file: json-ld/vertiv-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/vertiv/refs/heads/main/json-ld/vertiv-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Vertiv from Vertiv.
layout: jsonld
name: Vertiv Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: vertiv
  uri: https://www.vertiv.com/vocabulary/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: alarmId
  type: string
- container: ''
  name: alarmSource
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: acknowledged
  type: boolean
- container: ''
  name: deviceId
  type: string
- container: ''
  name: deviceName
  type: string
- container: ''
  name: siteName
  type: string
- container: ''
  name: groupPath
  type: string
- container: ''
  name: sensorId
  type: string
- container: ''
  name: sensorName
  type: string
- container: ''
  name: sensorType
  type: string
- container: ''
  name: value
  type: decimal
- container: ''
  name: unit
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: lastUpdated
  type: dateTime
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: message
  type: string
- container: ''
  name: rackId
  type: string
- container: ''
  name: rackName
  type: string
- container: ''
  name: circuitId
  type: string
- container: ''
  name: circuitName
  type: string
- container: ''
  name: currentAmps
  type: decimal
- container: ''
  name: voltageVolts
  type: decimal
- container: ''
  name: powerWatts
  type: decimal
- container: ''
  name: assetId
  type: string
- container: ''
  name: assetName
  type: string
- container: ''
  name: assetType
  type: string
property_count: 27
provider_name: Vertiv
provider_slug: vertiv
slug: vertiv-context
source_filename: vertiv-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"vertiv\": \"https://www.vertiv.com/vocabulary/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Alarm\": \"vertiv:Alarm\",\n    \"Device\": \"vertiv:Device\",\n    \"Sensor\": \"vertiv:Sensor\",\n    \"Rack\": \"vertiv:Rack\",\n    \"Circuit\": \"vertiv:Circuit\",\n    \"Asset\": \"vertiv:Asset\",\n    \"DataCenter\": \"schema:Place\",\n\n    \"alarmId\": {\n      \"@id\": \"vertiv:alarmId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alarmSource\": {\n      \"@id\": \"vertiv:alarmSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"vertiv:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"acknowledged\": {\n      \"@id\": \"vertiv:acknowledged\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"deviceId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceName\": {\n   \
  \   \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"siteName\": {\n      \"@id\": \"vertiv:siteName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groupPath\": {\n      \"@id\": \"vertiv:groupPath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sensorId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sensorName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sensorType\": {\n      \"@id\": \"vertiv:sensorType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"schema:value\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"unit\": {\n      \"@id\": \"schema:unitText\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"vertiv:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastUpdated\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"timestamp\": {\n      \"@id\"\
  : \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"message\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rackId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rackName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"circuitId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"circuitName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currentAmps\": {\n      \"@id\": \"vertiv:currentAmps\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"voltageVolts\": {\n      \"@id\": \"vertiv:voltageVolts\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"powerWatts\": {\n      \"@id\": \"vertiv:powerWatts\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"assetId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetName\"\
  : {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetType\": {\n      \"@id\": \"vertiv:assetType\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/vertiv/refs/heads/main/json-ld/vertiv-context.jsonld
tags:
- Critical Infrastructure
- Data Center
- DCIM
- Infrastructure Monitoring
- Power Management
- UPS
- JSON-LD
- Linked Data
- Semantic Web
---
