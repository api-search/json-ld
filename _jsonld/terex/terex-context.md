---
class_count: 6
classes:
- Product
- Organization
- Vehicle
- name
- description
- url
context_file: json-ld/terex-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/terex/refs/heads/main/json-ld/terex-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Terex from Terex.
layout: jsonld
name: Terex Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: terex
  uri: https://www.terex.com/#
- prefix: owl
  uri: http://www.w3.org/2002/07/owl#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: ConstructionEquipment
  type: reference
- container: ''
  name: FleetAsset
  type: reference
- container: ''
  name: TelematicsReading
  type: reference
- container: ''
  name: MaintenanceAlert
  type: reference
- container: ''
  name: serialNumber
  type: string
- container: ''
  name: model
  type: string
- container: ''
  name: manufacturer
  type: reference
- container: ''
  name: location
  type: reference
- container: ''
  name: latitude
  type: decimal
- container: ''
  name: longitude
  type: decimal
- container: ''
  name: engineHours
  type: decimal
- container: ''
  name: fuelLevel
  type: decimal
- container: ''
  name: operatingStatus
  type: '@vocab'
- container: ''
  name: alertType
  type: string
- container: ''
  name: alertSeverity
  type: '@vocab'
- container: ''
  name: timestamp
  type: dateTime
property_count: 16
provider_name: Terex
provider_slug: terex
slug: terex-context
source_filename: terex-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"terex\": \"https://www.terex.com/#\",\n    \"owl\": \"http://www.w3.org/2002/07/owl#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"ConstructionEquipment\": {\n      \"@id\": \"terex:ConstructionEquipment\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"A piece of construction or industrial equipment\"\n    },\n    \"FleetAsset\": {\n      \"@id\": \"terex:FleetAsset\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"A tracked fleet asset with telematics data\"\n    },\n    \"TelematicsReading\": {\n      \"@id\": \"terex:TelematicsReading\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"A telematics data reading from a connected machine\"\n    },\n    \"MaintenanceAlert\": {\n      \"@id\": \"terex:MaintenanceAlert\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"A predictive\
  \ maintenance alert for a machine\"\n    },\n\n    \"Product\": \"schema:Product\",\n    \"Organization\": \"schema:Organization\",\n    \"Vehicle\": \"schema:Vehicle\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"serialNumber\": {\n      \"@id\": \"schema:serialNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"model\": {\n      \"@id\": \"schema:model\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manufacturer\": {\n      \"@id\": \"schema:manufacturer\",\n      \"@type\": \"@id\"\n    },\n    \"location\": {\n      \"@id\": \"schema:location\",\n      \"@type\": \"@id\"\n    },\n    \"latitude\": {\n      \"@id\": \"schema:latitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"longitude\": {\n      \"@id\": \"schema:longitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"engineHours\": {\n      \"@id\": \"terex:engineHours\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"fuelLevel\": {\n\
  \      \"@id\": \"terex:fuelLevel\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"operatingStatus\": {\n      \"@id\": \"terex:operatingStatus\",\n      \"@type\": \"@vocab\",\n      \"@context\": {\n        \"operating\": \"terex:Operating\",\n        \"idle\": \"terex:Idle\",\n        \"offline\": \"terex:Offline\",\n        \"maintenance\": \"terex:InMaintenance\"\n      }\n    },\n    \"alertType\": {\n      \"@id\": \"terex:alertType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alertSeverity\": {\n      \"@id\": \"terex:alertSeverity\",\n      \"@type\": \"@vocab\",\n      \"@context\": {\n        \"info\": \"terex:Info\",\n        \"warning\": \"terex:Warning\",\n        \"critical\": \"terex:Critical\"\n      }\n    },\n    \"timestamp\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/terex/refs/heads/main/json-ld/terex-context.jsonld
tags:
- Aerial Work Platforms
- Construction Equipment
- Fleet Management
- Manufacturing
- Materials Processing
- Telematics
- JSON-LD
- Linked Data
- Semantic Web
---
