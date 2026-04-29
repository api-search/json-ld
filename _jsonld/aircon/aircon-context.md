---
class_count: 6
classes:
- Thermostat
- HvacSchedule
- SensorReading
- EnergyReport
- name
- description
context_file: json-ld/aircon-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aircon/refs/heads/main/json-ld/aircon-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aircon from Aircon.
layout: jsonld
name: Aircon Context
namespaces:
- prefix: aircon
  uri: https://aircon.api-evangelist.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: currentTemperature
  type: decimal
- container: ''
  name: targetTemperature
  type: decimal
- container: ''
  name: hvacMode
  type: string
- container: ''
  name: hvacStatus
  type: string
- container: ''
  name: fanMode
  type: string
- container: ''
  name: humidity
  type: decimal
- container: ''
  name: targetHumidity
  type: decimal
- container: ''
  name: isOnline
  type: boolean
- container: ''
  name: heatSetpoint
  type: decimal
- container: ''
  name: coolSetpoint
  type: decimal
- container: ''
  name: startTime
  type: string
- container: ''
  name: endTime
  type: string
- container: ''
  name: sensorType
  type: string
- container: ''
  name: inUse
  type: boolean
- container: ''
  name: heatingRuntimeMinutes
  type: integer
- container: ''
  name: coolingRuntimeMinutes
  type: integer
- container: ''
  name: fanRuntimeMinutes
  type: integer
- container: ''
  name: estimatedKwh
  type: decimal
- container: ''
  name: averageIndoorTemp
  type: decimal
- container: ''
  name: averageOutdoorTemp
  type: decimal
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: lastUpdated
  type: dateTime
property_count: 22
provider_name: Aircon
provider_slug: aircon
slug: aircon-context
source_filename: aircon-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aircon\": \"https://aircon.api-evangelist.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Thermostat\": \"aircon:Thermostat\",\n    \"HvacSchedule\": \"aircon:HvacSchedule\",\n    \"SensorReading\": \"aircon:SensorReading\",\n    \"EnergyReport\": \"aircon:EnergyReport\",\n    \"currentTemperature\": {\n      \"@id\": \"aircon:current_temperature\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"targetTemperature\": {\n      \"@id\": \"aircon:target_temperature\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"hvacMode\": {\n      \"@id\": \"aircon:hvac_mode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hvacStatus\": {\n      \"@id\": \"aircon:hvac_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fanMode\": {\n      \"@id\": \"aircon:fan_mode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"humidity\": {\n      \"@id\": \"aircon:humidity\"\
  ,\n      \"@type\": \"xsd:decimal\"\n    },\n    \"targetHumidity\": {\n      \"@id\": \"aircon:target_humidity\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"isOnline\": {\n      \"@id\": \"aircon:is_online\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"heatSetpoint\": {\n      \"@id\": \"aircon:heat_setpoint\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"coolSetpoint\": {\n      \"@id\": \"aircon:cool_setpoint\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"startTime\": {\n      \"@id\": \"aircon:start_time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endTime\": {\n      \"@id\": \"aircon:end_time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sensorType\": {\n      \"@id\": \"aircon:sensor_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inUse\": {\n      \"@id\": \"aircon:in_use\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"heatingRuntimeMinutes\": {\n      \"@id\": \"aircon:heating_runtime_minutes\",\n      \"@type\": \"xsd:integer\"\n   \
  \ },\n    \"coolingRuntimeMinutes\": {\n      \"@id\": \"aircon:cooling_runtime_minutes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"fanRuntimeMinutes\": {\n      \"@id\": \"aircon:fan_runtime_minutes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"estimatedKwh\": {\n      \"@id\": \"aircon:estimated_kwh\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"averageIndoorTemp\": {\n      \"@id\": \"aircon:average_indoor_temp\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"averageOutdoorTemp\": {\n      \"@id\": \"aircon:average_outdoor_temp\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"timestamp\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastUpdated\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aircon/refs/heads/main/json-ld/aircon-context.jsonld
tags:
- Air Conditioning
- HVAC
- Climate Control
- IoT
- Smart Home
- Thermostat
- Building Automation
- Energy Management
- JSON-LD
- Linked Data
- Semantic Web
---
