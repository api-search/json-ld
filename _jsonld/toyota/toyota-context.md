---
api_specs:
- filename: toyota-telematics-openapi.yml
  format: yaml
  label: Toyota Telematics API
  slug: toyota-telematics
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toyota/refs/heads/main/openapi/toyota-telematics-openapi.yml
- filename: toyota-connected-services-openapi.yml
  format: yaml
  label: Toyota Connected Services API
  slug: toyota-connected-services
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toyota/refs/heads/main/openapi/toyota-connected-services-openapi.yml
class_count: 58
classes:
- Vehicle
- vin
- alias
- make
- model
- year
- color
- trim
- isConnected
- lastConnectedAt
- VehicleStatus
- ignition
- doorsLocked
- doorStatus
- windowStatus
- lastUpdatedAt
- VehicleHealth
- overallStatus
- oilQuantity
- warningLights
- maintenanceRequired
- ElectricStatus
- batteryLevel
- batteryRange
- fuelLevel
- fuelRange
- totalRange
- chargingStatus
- pluggedIn
- estimatedChargeCompleteTime
- VehicleLocation
- latitude
- longitude
- heading
- speed
- isParked
- timestamp
- Trip
- startTime
- endTime
- distanceMiles
- durationMinutes
- startAddress
- endAddress
- route
- Notification
- title
- message
- isRead
- severity
- createdAt
- ServiceHistory
- category
- description
- serviceDate
- mileage
- dealerCode
- dealerName
context_file: json-ld/toyota-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/toyota/refs/heads/main/json-ld/toyota-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Toyota from Toyota.
layout: jsonld
name: Toyota Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: toyota
  uri: https://api.toyota.com/vocab#
- prefix: auto
  uri: https://auto.schema.org/
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties: []
property_count: 0
provider_name: Toyota
provider_slug: toyota
slug: toyota-context
source_filename: toyota-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"toyota\": \"https://api.toyota.com/vocab#\",\n    \"auto\": \"https://auto.schema.org/\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Vehicle\": \"schema:Vehicle\",\n    \"vin\": \"auto:vehicleIdentificationNumber\",\n    \"alias\": \"schema:name\",\n    \"make\": \"schema:brand\",\n    \"model\": \"schema:model\",\n    \"year\": \"auto:modelDate\",\n    \"color\": \"auto:color\",\n    \"trim\": \"auto:vehicleInteriorColor\",\n    \"isConnected\": \"toyota:isConnected\",\n    \"lastConnectedAt\": \"toyota:lastConnectedAt\",\n\n    \"VehicleStatus\": \"toyota:VehicleStatus\",\n    \"ignition\": \"toyota:ignitionState\",\n    \"doorsLocked\": \"toyota:doorsLocked\",\n    \"doorStatus\": \"toyota:doorStatus\",\n    \"windowStatus\": \"toyota:windowStatus\",\n    \"lastUpdatedAt\": \"schema:dateModified\",\n\n\
  \    \"VehicleHealth\": \"toyota:VehicleHealth\",\n    \"overallStatus\": \"toyota:healthStatus\",\n    \"oilQuantity\": \"toyota:oilLevel\",\n    \"warningLights\": \"toyota:warningLights\",\n    \"maintenanceRequired\": \"toyota:maintenanceRequired\",\n\n    \"ElectricStatus\": \"toyota:ElectricVehicleStatus\",\n    \"batteryLevel\": \"toyota:batteryStateOfCharge\",\n    \"batteryRange\": \"toyota:electricRange\",\n    \"fuelLevel\": \"toyota:fuelLevel\",\n    \"fuelRange\": \"toyota:fuelRange\",\n    \"totalRange\": \"toyota:totalRange\",\n    \"chargingStatus\": \"toyota:chargingStatus\",\n    \"pluggedIn\": \"toyota:isPluggedIn\",\n    \"estimatedChargeCompleteTime\": \"toyota:chargeCompleteTime\",\n\n    \"VehicleLocation\": \"geo:Point\",\n    \"latitude\": \"geo:lat\",\n    \"longitude\": \"geo:long\",\n    \"heading\": \"toyota:vehicleHeading\",\n    \"speed\": \"toyota:vehicleSpeed\",\n    \"isParked\": \"toyota:isParked\",\n    \"timestamp\": \"schema:dateModified\",\n\n   \
  \ \"Trip\": \"schema:Trip\",\n    \"startTime\": \"schema:startDate\",\n    \"endTime\": \"schema:endDate\",\n    \"distanceMiles\": \"auto:mileageFromOdometer\",\n    \"durationMinutes\": \"toyota:tripDuration\",\n    \"startAddress\": \"schema:departureStop\",\n    \"endAddress\": \"schema:arrivalStop\",\n    \"route\": \"schema:itinerary\",\n\n    \"Notification\": \"schema:Message\",\n    \"title\": \"schema:name\",\n    \"message\": \"schema:text\",\n    \"isRead\": \"toyota:isRead\",\n    \"severity\": \"toyota:alertSeverity\",\n    \"createdAt\": \"schema:dateCreated\",\n\n    \"ServiceHistory\": \"toyota:ServiceRecord\",\n    \"category\": \"schema:additionalType\",\n    \"description\": \"schema:description\",\n    \"serviceDate\": \"schema:startDate\",\n    \"mileage\": \"auto:mileageFromOdometer\",\n    \"dealerCode\": \"toyota:dealerCode\",\n    \"dealerName\": \"schema:provider\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/toyota/refs/heads/main/json-ld/toyota-context.jsonld
tags:
- Automobiles
- Cars
- Vehicles
- Connected Car
- Telematics
- Fleet Management
- Electric Vehicles
- JSON-LD
- Linked Data
- Semantic Web
---
