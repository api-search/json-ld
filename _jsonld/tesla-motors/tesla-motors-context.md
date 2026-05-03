---
api_specs:
- filename: tesla-motors-owner-openapi.yml
  format: yaml
  label: Tesla Owner API
  slug: owner-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tesla-motors/refs/heads/main/openapi/tesla-motors-owner-openapi.yml
class_count: 32
classes:
- Vehicle
- ChargeState
- ClimateState
- DriveState
- VehicleState
- vehicleId
- vin
- displayName
- optionCodes
- vehicleState
- batteryLevel
- batteryRange
- chargingState
- chargeLimit
- chargerPower
- minutesToFullCharge
- insideTemp
- outsideTemp
- isClimateOn
- latitude
- longitude
- heading
- speed
- odometer
- isLocked
- sentryMode
- softwareVersion
- Car
- identifier
- manufacturer
- model
- color
context_file: json-ld/tesla-motors-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tesla-motors/refs/heads/main/json-ld/tesla-motors-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tesla Motors from Tesla Motors.
layout: jsonld
name: Tesla Motors Context
namespaces:
- prefix: tesla
  uri: https://www.tesla.com/vocab#
properties: []
property_count: 0
provider_name: Tesla Motors
provider_slug: tesla-motors
slug: tesla-motors-context
source_filename: tesla-motors-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"tesla\": \"https://www.tesla.com/vocab#\",\n    \"Vehicle\": \"tesla:Vehicle\",\n    \"ChargeState\": \"tesla:ChargeState\",\n    \"ClimateState\": \"tesla:ClimateState\",\n    \"DriveState\": \"tesla:DriveState\",\n    \"VehicleState\": \"tesla:VehicleState\",\n    \"vehicleId\": \"tesla:vehicleId\",\n    \"vin\": \"tesla:vin\",\n    \"displayName\": \"schema:name\",\n    \"optionCodes\": \"tesla:optionCodes\",\n    \"vehicleState\": \"tesla:vehicleState\",\n    \"batteryLevel\": \"tesla:batteryLevel\",\n    \"batteryRange\": \"tesla:batteryRange\",\n    \"chargingState\": \"tesla:chargingState\",\n    \"chargeLimit\": \"tesla:chargeLimit\",\n    \"chargerPower\": \"tesla:chargerPower\",\n    \"minutesToFullCharge\": \"tesla:minutesToFullCharge\",\n    \"insideTemp\": \"tesla:insideTemp\",\n    \"outsideTemp\": \"tesla:outsideTemp\",\n    \"isClimateOn\": \"tesla:isClimateOn\",\n    \"latitude\": \"schema:latitude\"\
  ,\n    \"longitude\": \"schema:longitude\",\n    \"heading\": \"tesla:heading\",\n    \"speed\": \"schema:speed\",\n    \"odometer\": \"tesla:odometer\",\n    \"isLocked\": \"tesla:isLocked\",\n    \"sentryMode\": \"tesla:sentryMode\",\n    \"softwareVersion\": \"schema:softwareVersion\",\n    \"Car\": \"schema:Car\",\n    \"identifier\": \"schema:identifier\",\n    \"manufacturer\": \"schema:manufacturer\",\n    \"model\": \"schema:model\",\n    \"color\": \"schema:color\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tesla-motors/refs/heads/main/json-ld/tesla-motors-context.jsonld
tags:
- Automobiles
- Electric Vehicles
- Cars
- Smart Vehicles
- IoT
- JSON-LD
- Linked Data
- Semantic Web
---
