---
api_specs:
- filename: tesla-openapi-original.yml
  format: yaml
  label: Tesla Fleet API
  slug: fleet-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tesla/refs/heads/main/openapi/tesla-openapi-original.yml
- filename: tesla-openapi-original.yml
  format: yaml
  label: Tesla Owner API
  slug: owner-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tesla/refs/heads/main/openapi/tesla-openapi-original.yml
class_count: 30
classes:
- Vehicle
- ChargeState
- ClimateState
- DriveState
- VehicleState
- EnergySite
- vehicleId
- vin
- displayName
- batteryLevel
- batteryRange
- chargingState
- chargeLimit
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
- valetMode
- softwareVersion
- Car
- identifier
- manufacturer
- model
context_file: json-ld/tesla-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tesla/refs/heads/main/json-ld/tesla-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tesla from Tesla.
layout: jsonld
name: Tesla Context
namespaces:
- prefix: tesla
  uri: https://www.tesla.com/vocab#
properties: []
property_count: 0
provider_name: Tesla
provider_slug: tesla
slug: tesla-context
source_filename: tesla-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"tesla\": \"https://www.tesla.com/vocab#\",\n    \"Vehicle\": \"tesla:Vehicle\",\n    \"ChargeState\": \"tesla:ChargeState\",\n    \"ClimateState\": \"tesla:ClimateState\",\n    \"DriveState\": \"tesla:DriveState\",\n    \"VehicleState\": \"tesla:VehicleState\",\n    \"EnergySite\": \"tesla:EnergySite\",\n    \"vehicleId\": \"tesla:vehicleId\",\n    \"vin\": \"tesla:vin\",\n    \"displayName\": \"schema:name\",\n    \"batteryLevel\": \"tesla:batteryLevel\",\n    \"batteryRange\": \"tesla:batteryRange\",\n    \"chargingState\": \"tesla:chargingState\",\n    \"chargeLimit\": \"tesla:chargeLimit\",\n    \"minutesToFullCharge\": \"tesla:minutesToFullCharge\",\n    \"insideTemp\": \"tesla:insideTemp\",\n    \"outsideTemp\": \"tesla:outsideTemp\",\n    \"isClimateOn\": \"tesla:isClimateOn\",\n    \"latitude\": \"schema:latitude\",\n    \"longitude\": \"schema:longitude\",\n    \"heading\": \"tesla:heading\",\n \
  \   \"speed\": \"schema:speed\",\n    \"odometer\": \"tesla:odometer\",\n    \"isLocked\": \"tesla:isLocked\",\n    \"sentryMode\": \"tesla:sentryMode\",\n    \"valetMode\": \"tesla:valetMode\",\n    \"softwareVersion\": \"schema:softwareVersion\",\n    \"Car\": \"schema:Car\",\n    \"identifier\": \"schema:identifier\",\n    \"manufacturer\": \"schema:manufacturer\",\n    \"model\": \"schema:model\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tesla/refs/heads/main/json-ld/tesla-context.jsonld
tags:
- Automobiles
- Cars
- Vehicles
- Electric Vehicles
- Energy
- Clean Energy
- IoT
- JSON-LD
- Linked Data
- Semantic Web
---
