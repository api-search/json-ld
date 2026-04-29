---
class_count: 3
classes:
- MachineLocation
- Telemetry
- Machine
context_file: json-ld/agco-telematics-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/agco/refs/heads/main/json-ld/agco-telematics-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Agco Telematics from agco.
layout: jsonld
name: Agco Telematics Context
namespaces:
- prefix: agco
  uri: https://agcocorp.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: machineId
  type: string
- container: ''
  name: latitude
  type: decimal
- container: ''
  name: longitude
  type: decimal
- container: ''
  name: altitude
  type: decimal
- container: ''
  name: heading
  type: decimal
- container: ''
  name: groundSpeed
  type: decimal
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: engineSpeed
  type: decimal
- container: ''
  name: engineLoad
  type: decimal
- container: ''
  name: engineHours
  type: decimal
- container: ''
  name: fuelLevel
  type: decimal
- container: ''
  name: fuelConsumptionRate
  type: decimal
- container: ''
  name: coolantTemperature
  type: decimal
- container: set
  name: faultCodes
  type: string
- container: ''
  name: operatingMode
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: serialNumber
  type: string
- container: ''
  name: model
  type: string
- container: ''
  name: brand
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
property_count: 24
provider_name: agco
provider_slug: agco
slug: agco-telematics-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"agco\": \"https://agcocorp.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"MachineLocation\": \"agco:MachineLocation\",\n    \"machineId\": {\n      \"@id\": \"agco:machine_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"latitude\": {\n      \"@id\": \"agco:latitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"longitude\": {\n      \"@id\": \"agco:longitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"altitude\": {\n      \"@id\": \"agco:altitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"heading\": {\n      \"@id\": \"agco:heading\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"groundSpeed\": {\n      \"@id\": \"agco:ground_speed\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"timestamp\": {\n      \"@id\": \"agco:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\
  \    \"Telemetry\": \"agco:Telemetry\",\n    \"engineSpeed\": {\n      \"@id\": \"agco:engine_speed\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"engineLoad\": {\n      \"@id\": \"agco:engine_load\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"engineHours\": {\n      \"@id\": \"agco:engine_hours\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"fuelLevel\": {\n      \"@id\": \"agco:fuel_level\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"fuelConsumptionRate\": {\n      \"@id\": \"agco:fuel_consumption_rate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"coolantTemperature\": {\n      \"@id\": \"agco:coolant_temperature\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"faultCodes\": {\n      \"@id\": \"agco:fault_codes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operatingMode\": {\n      \"@id\": \"agco:operating_mode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Machine\": \"agco:Machine\",\n    \"id\": {\n      \"@id\"\
  : \"agco:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serialNumber\": {\n      \"@id\": \"agco:serial_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"model\": {\n      \"@id\": \"agco:model\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brand\": {\n      \"@id\": \"agco:brand\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"agco:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"agco:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"agco:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"agco:created_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"agco:updated_at\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/agco/refs/heads/main/json-ld/agco-telematics-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
