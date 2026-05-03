---
class_count: 33
classes:
- Organization
- name
- description
- Vehicle
- CommercialVehicle
- vehicleId
- vehicleType
- vin
- Fleet
- fleetId
- fleetName
- vehicleCount
- TelematicsDevice
- deviceId
- deviceType
- firmwareVersion
- DiagnosticEvent
- eventId
- eventType
- faultCode
- severity
- BrakingSystem
- AbsBraking
- ElectronicBraking
- StabilityControl
- AirSuspension
- TransmissionAutomation
- Location
- latitude
- longitude
- altitude
- speed
- heading
context_file: json-ld/wabco-holdings-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/wabco-holdings/refs/heads/main/json-ld/wabco-holdings-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Wabco Holdings from WABCO Holdings.
layout: jsonld
name: Wabco Holdings Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: auto
  uri: https://schema.org/
- prefix: wabco
  uri: https://www.wabco-holdings.com/vocab/
properties:
- container: ''
  name: url
  type: reference
- container: ''
  name: timestamp
  type: dateTime
property_count: 2
provider_name: WABCO Holdings
provider_slug: wabco-holdings
slug: wabco-holdings-context
source_filename: wabco-holdings-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"auto\": \"https://schema.org/\",\n    \"wabco\": \"https://www.wabco-holdings.com/vocab/\",\n\n    \"Organization\": \"schema:Organization\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n\n    \"Vehicle\": \"schema:Vehicle\",\n    \"CommercialVehicle\": \"auto:BusOrCoach\",\n    \"vehicleId\": \"@id\",\n    \"vehicleType\": \"auto:vehicleModelDate\",\n    \"vin\": \"auto:vehicleIdentificationNumber\",\n\n    \"Fleet\": \"wabco:Fleet\",\n    \"fleetId\": \"@id\",\n    \"fleetName\": \"schema:name\",\n    \"vehicleCount\": \"schema:numberOfEmployees\",\n\n    \"TelematicsDevice\": \"wabco:TelematicsDevice\",\n    \"deviceId\": \"@id\",\n    \"deviceType\": \"schema:additionalType\",\n    \"firmwareVersion\": \"schema:version\"\
  ,\n\n    \"DiagnosticEvent\": \"wabco:DiagnosticEvent\",\n    \"eventId\": \"@id\",\n    \"eventType\": \"schema:additionalType\",\n    \"timestamp\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"faultCode\": \"wabco:faultCode\",\n    \"severity\": \"wabco:severity\",\n\n    \"BrakingSystem\": \"wabco:BrakingSystem\",\n    \"AbsBraking\": \"wabco:AbsBraking\",\n    \"ElectronicBraking\": \"wabco:ElectronicBraking\",\n    \"StabilityControl\": \"wabco:StabilityControl\",\n\n    \"AirSuspension\": \"wabco:AirSuspension\",\n    \"TransmissionAutomation\": \"wabco:TransmissionAutomation\",\n\n    \"Location\": \"schema:GeoCoordinates\",\n    \"latitude\": \"schema:latitude\",\n    \"longitude\": \"schema:longitude\",\n    \"altitude\": \"schema:elevation\",\n    \"speed\": \"wabco:speed\",\n    \"heading\": \"wabco:heading\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/wabco-holdings/refs/heads/main/json-ld/wabco-holdings-context.jsonld
tags:
- Commercial Vehicles
- Fleet Management
- Telematics
- Safety Systems
- Transportation
- JSON-LD
- Linked Data
- Semantic Web
---
