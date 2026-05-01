---
class_count: 0
classes: []
context_file: json-ld/google-nest.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-nest/refs/heads/main/json-ld/google-nest.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Nest from Google Nest Smart Device Management.
layout: jsonld
name: Google Nest Context
namespaces:
- prefix: sdm
  uri: https://developers.google.com/nest/device-access/api#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Device
  type: ''
- container: ''
  name: Structure
  type: ''
- container: ''
  name: Room
  type: ''
- container: ''
  name: deviceType
  type: string
- container: ''
  name: traits
  type: '@json'
- container: list
  name: parentRelations
  type: ''
- container: ''
  name: command
  type: string
- container: ''
  name: params
  type: '@json'
- container: ''
  name: displayName
  type: string
property_count: 9
provider_name: Google Nest Smart Device Management
provider_slug: google-nest
slug: google-nest
source_filename: google-nest.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"sdm\": \"https://developers.google.com/nest/device-access/api#\",\n    \"Device\": {\n      \"@id\": \"sdm:Device\"\n    },\n    \"Structure\": {\n      \"@id\": \"sdm:Structure\"\n    },\n    \"Room\": {\n      \"@id\": \"sdm:Room\"\n    },\n    \"deviceType\": {\n      \"@id\": \"sdm:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"traits\": {\n      \"@id\": \"sdm:traits\",\n      \"@type\": \"@json\"\n    },\n    \"parentRelations\": {\n      \"@id\": \"sdm:parentRelations\",\n      \"@container\": \"@list\"\n    },\n    \"command\": {\n      \"@id\": \"sdm:command\",\n      \"@type\": \"xsd:string\"\n    },\n    \"params\": {\n      \"@id\": \"sdm:params\",\n      \"@type\": \"@json\"\n    },\n    \"displayName\": {\n      \"@id\": \"https://schema.org/name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-nest/refs/heads/main/json-ld/google-nest.jsonld
tags:
- Camera
- Device Management
- Doorbell
- Google Nest
- IoT
- Smart Home
- Thermostat
- JSON-LD
- Linked Data
- Semantic Web
---
