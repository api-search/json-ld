---
class_count: 6
classes:
- Device
- name
- description
- identifier
- dateCreated
- dateModified
context_file: json-ld/scada-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/scada/refs/heads/main/json-ld/scada-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Scada from SCADA.
layout: jsonld
name: Scada Context
namespaces:
- prefix: scada
  uri: https://schema.scada.example.com/ontology#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: ssn
  uri: http://www.w3.org/ns/ssn/
- prefix: sosa
  uri: http://www.w3.org/ns/sosa/
- prefix: iot
  uri: http://iotschema.org/
properties:
- container: ''
  name: ScadaSystem
  type: reference
- container: ''
  name: PLCDevice
  type: reference
- container: ''
  name: Tag
  type: reference
- container: ''
  name: Alarm
  type: reference
- container: ''
  name: Historian
  type: reference
- container: ''
  name: ProcessArea
  type: reference
- container: ''
  name: HMI
  type: reference
- container: ''
  name: RTU
  type: reference
- container: ''
  name: Sensor
  type: reference
- container: ''
  name: Observation
  type: reference
- container: ''
  name: tagName
  type: string
- container: ''
  name: tagValue
  type: ''
- container: ''
  name: tagDataType
  type: string
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: quality
  type: string
- container: ''
  name: alarmState
  type: string
- container: ''
  name: alarmPriority
  type: integer
- container: ''
  name: alarmMessage
  type: string
- container: ''
  name: engineeringUnits
  type: string
- container: ''
  name: highHighLimit
  type: decimal
- container: ''
  name: highLimit
  type: decimal
- container: ''
  name: lowLimit
  type: decimal
- container: ''
  name: lowLowLimit
  type: decimal
property_count: 23
provider_name: SCADA
provider_slug: scada
slug: scada-context
source_filename: scada-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"scada\": \"https://schema.scada.example.com/ontology#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ssn\": \"http://www.w3.org/ns/ssn/\",\n    \"sosa\": \"http://www.w3.org/ns/sosa/\",\n    \"iot\": \"http://iotschema.org/\",\n\n    \"ScadaSystem\": {\n      \"@id\": \"scada:ScadaSystem\",\n      \"@type\": \"@id\",\n      \"comment\": \"A Supervisory Control and Data Acquisition system\"\n    },\n    \"PLCDevice\": {\n      \"@id\": \"scada:PLCDevice\",\n      \"@type\": \"@id\",\n      \"comment\": \"A Programmable Logic Controller (PLC) connected to the SCADA network\"\n    },\n    \"Tag\": {\n      \"@id\": \"scada:Tag\",\n      \"@type\": \"@id\",\n      \"comment\": \"A SCADA data point representing a sensor, setpoint, or control variable\"\n    },\n    \"Alarm\": {\n      \"@id\": \"scada:Alarm\",\n      \"@type\": \"@id\",\n      \"comment\": \"A SCADA alarm\
  \ triggered when a tag value crosses a threshold\"\n    },\n    \"Historian\": {\n      \"@id\": \"scada:Historian\",\n      \"@type\": \"@id\",\n      \"comment\": \"A time-series database that stores historical process data from SCADA\"\n    },\n    \"ProcessArea\": {\n      \"@id\": \"scada:ProcessArea\",\n      \"@type\": \"@id\",\n      \"comment\": \"A logical grouping of equipment within a SCADA system\"\n    },\n    \"HMI\": {\n      \"@id\": \"scada:HMI\",\n      \"@type\": \"@id\",\n      \"comment\": \"Human-Machine Interface for operator visualization and control\"\n    },\n    \"RTU\": {\n      \"@id\": \"scada:RTU\",\n      \"@type\": \"@id\",\n      \"comment\": \"Remote Terminal Unit - a field device that collects data from sensors\"\n    },\n    \"Sensor\": {\n      \"@id\": \"sosa:Sensor\",\n      \"@type\": \"@id\",\n      \"comment\": \"A physical device measuring an industrial process variable\"\n    },\n    \"Observation\": {\n      \"@id\": \"sosa:Observation\",\n\
  \      \"@type\": \"@id\",\n      \"comment\": \"A measurement reading from a sensor at a specific time\"\n    },\n\n    \"tagName\": {\n      \"@id\": \"scada:tagName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tagValue\": {\n      \"@id\": \"scada:tagValue\"\n    },\n    \"tagDataType\": {\n      \"@id\": \"scada:tagDataType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"scada:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"quality\": {\n      \"@id\": \"scada:quality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alarmState\": {\n      \"@id\": \"scada:alarmState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alarmPriority\": {\n      \"@id\": \"scada:alarmPriority\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"alarmMessage\": {\n      \"@id\": \"scada:alarmMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"engineeringUnits\": {\n      \"@id\": \"scada:engineeringUnits\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"highHighLimit\": {\n      \"@id\": \"scada:highHighLimit\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"highLimit\": {\n      \"@id\": \"scada:highLimit\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"lowLimit\": {\n      \"@id\": \"scada:lowLimit\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"lowLowLimit\": {\n      \"@id\": \"scada:lowLowLimit\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"Device\": \"schema:Device\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"identifier\": \"schema:identifier\",\n    \"dateCreated\": \"schema:dateCreated\",\n    \"dateModified\": \"schema:dateModified\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/scada/refs/heads/main/json-ld/scada-context.jsonld
tags:
- Critical Infrastructure
- ICS
- Industrial Automation
- Industrial IoT
- OT Security
- SCADA
- JSON-LD
- Linked Data
- Semantic Web
---
