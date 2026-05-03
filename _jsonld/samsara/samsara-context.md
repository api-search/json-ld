---
api_specs:
- filename: samsara-openapi.yml
  format: yaml
  label: Samsara API
  slug: samsara
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/samsara/refs/heads/main/openapi/samsara-openapi.yml
class_count: 44
classes:
- Vehicle
- Driver
- Route
- Address
- Tag
- SafetyEvent
- Asset
- Webhook
- id
- name
- description
- vin
- make
- model
- year
- licensePlate
- staticAssignedDriver
- eldSettings
- eldExempt
- phone
- username
- licenseNumber
- licenseState
- timezone
- driverActivationStatus
- currentVehicle
- hosRulesets
- formattedAddress
- geofence
- eventType
- speedMilesPerHour
- severity
- coachingState
- time
- stops
- scheduledArrivalTime
- scheduledDepartureTime
- externalIds
- tags
- notes
- createdAtTime
- updatedAtTime
- endCursor
- hasNextPage
context_file: json-ld/samsara-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/samsara/refs/heads/main/json-ld/samsara-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Samsara from Samsara.
layout: jsonld
name: Samsara Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: geo
  uri: https://www.w3.org/2003/01/geo/wgs84_pos#
- prefix: samsara
  uri: https://www.samsara.com/api/vocabulary#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: odometerMeters
  type: integer
- container: ''
  name: engineHours
  type: decimal
- container: ''
  name: latitude
  type: decimal
- container: ''
  name: longitude
  type: decimal
property_count: 4
provider_name: Samsara
provider_slug: samsara
slug: samsara-context
source_filename: samsara-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"geo\": \"https://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"samsara\": \"https://www.samsara.com/api/vocabulary#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Vehicle\": \"schema:Vehicle\",\n    \"Driver\": \"schema:Person\",\n    \"Route\": \"schema:TripPlan\",\n    \"Address\": \"schema:Place\",\n    \"Tag\": \"schema:DefinedTerm\",\n    \"SafetyEvent\": \"schema:Event\",\n    \"Asset\": \"schema:Product\",\n    \"Webhook\": \"schema:Action\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n\n    \"vin\": \"schema:vehicleIdentificationNumber\",\n    \"make\": \"schema:brand\",\n    \"model\": \"schema:model\",\n    \"year\": \"schema:vehicleModelDate\",\n    \"licensePlate\": \"schema:vehiclePlate\",\n    \"odometerMeters\": {\n      \"@id\": \"samsara:odometerMeters\",\n      \"@type\": \"xsd:integer\"\n\
  \    },\n    \"engineHours\": {\n      \"@id\": \"samsara:engineHours\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"staticAssignedDriver\": \"schema:driver\",\n    \"eldSettings\": \"samsara:eldSettings\",\n    \"eldExempt\": \"samsara:eldExempt\",\n\n    \"phone\": \"schema:telephone\",\n    \"username\": \"schema:identifier\",\n    \"licenseNumber\": \"schema:licenseNumber\",\n    \"licenseState\": \"schema:addressRegion\",\n    \"timezone\": \"schema:timezone\",\n    \"driverActivationStatus\": \"schema:status\",\n    \"currentVehicle\": \"schema:vehicle\",\n    \"hosRulesets\": \"samsara:hosRulesets\",\n\n    \"latitude\": {\n      \"@id\": \"geo:lat\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"longitude\": {\n      \"@id\": \"geo:long\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"formattedAddress\": \"schema:address\",\n    \"geofence\": \"samsara:geofence\",\n\n    \"eventType\": \"samsara:eventType\",\n    \"speedMilesPerHour\": \"samsara:speedMilesPerHour\",\n\
  \    \"severity\": \"samsara:severity\",\n    \"coachingState\": \"samsara:coachingState\",\n    \"time\": \"schema:startTime\",\n\n    \"stops\": \"schema:itemListElement\",\n    \"scheduledArrivalTime\": \"schema:arrivalTime\",\n    \"scheduledDepartureTime\": \"schema:departureTime\",\n\n    \"externalIds\": \"samsara:externalIds\",\n    \"tags\": \"schema:subjectOf\",\n    \"notes\": \"schema:description\",\n\n    \"createdAtTime\": \"schema:dateCreated\",\n    \"updatedAtTime\": \"schema:dateModified\",\n\n    \"endCursor\": \"samsara:endCursor\",\n    \"hasNextPage\": \"samsara:hasNextPage\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/samsara/refs/heads/main/json-ld/samsara-context.jsonld
tags:
- Asset Tracking
- Connected Operations
- ELD
- Fleet Management
- GPS Tracking
- IoT
- Logistics
- Safety
- Telematics
- Transportation
- JSON-LD
- Linked Data
- Semantic Web
---
