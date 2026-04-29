---
class_count: 0
classes: []
context_file: json-ld/carrier-global-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/carrier-global/refs/heads/main/json-ld/carrier-global-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Carrier Global from Carrier Global.
layout: jsonld
name: Carrier Global Context
namespaces:
- prefix: carrier
  uri: https://carrier.com/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: geo
  uri: http://www.opengis.net/ont/geosparql#
properties:
- container: ''
  name: Asset
  type: ''
- container: ''
  name: TRU
  type: ''
- container: ''
  name: Compartment
  type: ''
- container: ''
  name: Alarm
  type: ''
- container: ''
  name: Trip
  type: ''
- container: ''
  name: Geofence
  type: ''
- container: ''
  name: Command
  type: ''
- container: ''
  name: Building
  type: ''
- container: ''
  name: Space
  type: ''
- container: ''
  name: EquipmentUnit
  type: ''
property_count: 10
provider_name: Carrier Global
provider_slug: carrier-global
slug: carrier-global-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"carrier\": \"https://carrier.com/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"geo\": \"http://www.opengis.net/ont/geosparql#\",\n\n    \"Asset\": {\n      \"@id\": \"carrier:Asset\",\n      \"@context\": {\n        \"assetId\": \"schema:identifier\",\n        \"vin\": \"carrier:vin\",\n        \"make\": \"schema:brand\",\n        \"model\": \"schema:model\",\n        \"tru\": {\n          \"@id\": \"carrier:tru\",\n          \"@type\": \"@id\"\n        },\n        \"location\": {\n          \"@id\": \"schema:geo\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"TRU\": {\n      \"@id\": \"carrier:TRU\",\n      \"@context\": {\n        \"truId\": \"schema:identifier\",\n        \"serialNumber\": \"schema:serialNumber\",\n        \"fuelType\": \"carrier:fuelType\",\n        \"compartments\": {\n          \"@id\": \"carrier:compartments\",\n\
  \          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"Compartment\": {\n      \"@id\": \"carrier:Compartment\",\n      \"@context\": {\n        \"compartmentId\": \"schema:identifier\",\n        \"setpointC\": {\n          \"@id\": \"carrier:setpointC\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"returnAirC\": {\n          \"@id\": \"carrier:returnAirC\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"supplyAirC\": {\n          \"@id\": \"carrier:supplyAirC\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"Alarm\": {\n      \"@id\": \"carrier:Alarm\",\n      \"@context\": {\n        \"alarmId\": \"schema:identifier\",\n        \"code\": \"carrier:alarmCode\",\n        \"severity\": \"carrier:severity\",\n        \"raisedAt\": {\n          \"@id\": \"carrier:raisedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"clearedAt\": {\n          \"@id\": \"carrier:clearedAt\",\n          \"@type\"\
  : \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Trip\": {\n      \"@id\": \"carrier:Trip\",\n      \"@context\": {\n        \"tripId\": \"schema:identifier\",\n        \"startedAt\": {\n          \"@id\": \"schema:startTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endedAt\": {\n          \"@id\": \"schema:endTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"route\": \"schema:itinerary\"\n      }\n    },\n\n    \"Geofence\": {\n      \"@id\": \"carrier:Geofence\",\n      \"@context\": {\n        \"geofenceId\": \"schema:identifier\",\n        \"shape\": \"schema:geo\",\n        \"name\": \"schema:name\"\n      }\n    },\n\n    \"Command\": {\n      \"@id\": \"carrier:Command\",\n      \"@context\": {\n        \"commandId\": \"schema:identifier\",\n        \"action\": \"carrier:action\",\n        \"issuedAt\": {\n          \"@id\": \"carrier:issuedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"status\": \"carrier:commandStatus\"\
  \n      }\n    },\n\n    \"Building\": {\n      \"@id\": \"carrier:Building\",\n      \"@context\": {\n        \"buildingId\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"address\": \"schema:address\",\n        \"squareFeet\": {\n          \"@id\": \"schema:floorSize\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"Space\": {\n      \"@id\": \"carrier:Space\",\n      \"@context\": {\n        \"spaceId\": \"schema:identifier\",\n        \"building\": {\n          \"@id\": \"carrier:building\",\n          \"@type\": \"@id\"\n        },\n        \"iaqScore\": {\n          \"@id\": \"carrier:iaqScore\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"co2Ppm\": {\n          \"@id\": \"carrier:co2Ppm\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"occupancy\": {\n          \"@id\": \"carrier:occupancy\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"EquipmentUnit\": {\n      \"@id\"\
  : \"carrier:EquipmentUnit\",\n      \"@context\": {\n        \"equipmentId\": \"schema:identifier\",\n        \"equipmentType\": \"carrier:equipmentType\",\n        \"status\": \"carrier:equipmentStatus\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/carrier-global/refs/heads/main/json-ld/carrier-global-context.jsonld
tags:
- HVAC
- Cold Chain
- Telematics
- Building Automation
- IoT
- Refrigeration
- Fortune 500
- JSON-LD
- Linked Data
- Semantic Web
---
