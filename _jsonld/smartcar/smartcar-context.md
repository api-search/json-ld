---
api_specs:
- filename: smartcar-vehicles-openapi.yml
  format: yaml
  label: Smartcar Vehicles API
  slug: vehicles-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/smartcar/refs/heads/main/openapi/smartcar-vehicles-openapi.yml
class_count: 13
classes:
- name
- description
- Vehicle
- make
- manufacturer
- model
- modelDate
- vin
- location
- latitude
- longitude
- Connection
- Permission
context_file: json-ld/smartcar-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/smartcar/refs/heads/main/json-ld/smartcar-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Smartcar from Smartcar.
layout: jsonld
name: Smartcar Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: smartcar
  uri: https://api-evangelist.github.io/smartcar/vocab#
- prefix: auto
  uri: http://schema.org/auto/
properties:
- container: ''
  name: url
  type: reference
- container: ''
  name: vehicleId
  type: string
- container: ''
  name: batteryLevel
  type: decimal
- container: ''
  name: range
  type: schema:QuantitativeValue
- container: ''
  name: isPluggedIn
  type: boolean
- container: ''
  name: chargingState
  type: string
- container: ''
  name: isLocked
  type: boolean
- container: ''
  name: odometer
  type: schema:QuantitativeValue
- container: ''
  name: fuelLevel
  type: decimal
- container: ''
  name: percentRemaining
  type: decimal
- container: ''
  name: distance
  type: schema:QuantitativeValue
property_count: 11
provider_name: Smartcar
provider_slug: smartcar
slug: smartcar-context
source_filename: smartcar-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"smartcar\": \"https://api-evangelist.github.io/smartcar/vocab#\",\n    \"auto\": \"http://schema.org/auto/\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n\n    \"Vehicle\": \"schema:Vehicle\",\n    \"vehicleId\": {\n      \"@id\": \"smartcar:vehicleId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"make\": \"schema:vehicleIdentificationNumber\",\n    \"manufacturer\": \"schema:manufacturer\",\n    \"model\": \"schema:model\",\n    \"modelDate\": \"schema:modelDate\",\n    \"vin\": \"schema:vehicleIdentificationNumber\",\n\n    \"batteryLevel\": {\n      \"@id\": \"smartcar:batteryLevel\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"range\": {\n      \"@id\": \"schema:fuelCapacity\",\n      \"@type\": \"schema:QuantitativeValue\"\
  \n    },\n    \"isPluggedIn\": {\n      \"@id\": \"smartcar:isPluggedIn\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"chargingState\": {\n      \"@id\": \"smartcar:chargingState\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"isLocked\": {\n      \"@id\": \"smartcar:isLocked\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"location\": \"schema:GeoCoordinates\",\n    \"latitude\": \"schema:latitude\",\n    \"longitude\": \"schema:longitude\",\n\n    \"odometer\": {\n      \"@id\": \"smartcar:odometer\",\n      \"@type\": \"schema:QuantitativeValue\"\n    },\n    \"fuelLevel\": {\n      \"@id\": \"smartcar:fuelLevel\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"Connection\": \"schema:EntryPoint\",\n    \"Permission\": \"schema:DefinedTerm\",\n\n    \"percentRemaining\": {\n      \"@id\": \"smartcar:percentRemaining\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"distance\": {\n      \"@id\": \"schema:distance\",\n      \"@type\": \"schema:QuantitativeValue\"\n \
  \   }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/smartcar/refs/heads/main/json-ld/smartcar-context.jsonld
tags:
- Automotive
- Connected Vehicles
- IoT
- Mobility
- Fleet Management
- EV Management
- Telematics
- JSON-LD
- Linked Data
- Semantic Web
---
