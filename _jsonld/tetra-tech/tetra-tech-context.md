---
class_count: 19
classes:
- id
- name
- description
- tags
- type
- status
- analytics
- stationId
- stationName
- collectedBy
- labId
- projectId
- latitude
- longitude
- datum
- value
- unit
- method
- qualifier
context_file: json-ld/tetra-tech-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tetra-tech/refs/heads/main/json-ld/tetra-tech-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tetra Tech from Tetra Tech.
layout: jsonld
name: Tetra Tech Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
- prefix: envo
  uri: http://purl.obolibrary.org/obo/ENVO_
- prefix: tt
  uri: https://raw.githubusercontent.com/api-evangelist/tetra-tech/main/vocabulary/tetra-tech-vocabulary.yml#
properties:
- container: ''
  name: Project
  type: reference
- container: ''
  name: WaterQualitySample
  type: reference
- container: ''
  name: MonitoringStation
  type: reference
- container: ''
  name: WaterQualityParameter
  type: reference
- container: ''
  name: created
  type: dateTime
- container: ''
  name: modified
  type: date
- container: ''
  name: client
  type: reference
- container: ''
  name: location
  type: reference
- container: set
  name: dataCollections
  type: ''
- container: ''
  name: collectionDate
  type: dateTime
- container: set
  name: parameters
  type: ''
property_count: 11
provider_name: Tetra Tech
provider_slug: tetra-tech
slug: tetra-tech-context
source_filename: tetra-tech-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"envo\": \"http://purl.obolibrary.org/obo/ENVO_\",\n    \"tt\": \"https://raw.githubusercontent.com/api-evangelist/tetra-tech/main/vocabulary/tetra-tech-vocabulary.yml#\",\n\n    \"Project\": {\n      \"@id\": \"schema:Project\",\n      \"@type\": \"@id\"\n    },\n    \"WaterQualitySample\": {\n      \"@id\": \"tt:WaterQualitySample\",\n      \"@type\": \"@id\"\n    },\n    \"MonitoringStation\": {\n      \"@id\": \"tt:MonitoringStation\",\n      \"@type\": \"@id\"\n    },\n    \"WaterQualityParameter\": {\n      \"@id\": \"tt:WaterQualityParameter\",\n      \"@type\": \"@id\"\n    },\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"created\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\" },\n  \
  \  \"modified\": { \"@id\": \"schema:dateModified\", \"@type\": \"xsd:date\" },\n    \"tags\": \"schema:keywords\",\n\n    \"type\": \"tt:projectType\",\n    \"status\": \"tt:projectStatus\",\n    \"client\": { \"@id\": \"schema:client\", \"@type\": \"@id\" },\n    \"location\": { \"@id\": \"schema:location\", \"@type\": \"@id\" },\n    \"dataCollections\": { \"@id\": \"tt:dataCollections\", \"@container\": \"@set\" },\n    \"analytics\": \"tt:analytics\",\n\n    \"stationId\": \"tt:stationId\",\n    \"stationName\": \"schema:name\",\n    \"collectionDate\": { \"@id\": \"tt:collectionDate\", \"@type\": \"xsd:dateTime\" },\n    \"collectedBy\": \"tt:collectedBy\",\n    \"parameters\": { \"@id\": \"tt:parameters\", \"@container\": \"@set\" },\n    \"labId\": \"tt:labId\",\n    \"projectId\": \"tt:projectId\",\n\n    \"latitude\": \"geo:lat\",\n    \"longitude\": \"geo:long\",\n    \"datum\": \"tt:geodeticDatum\",\n\n    \"value\": \"schema:value\",\n    \"unit\": \"schema:unitCode\",\n \
  \   \"method\": \"tt:analyticalMethod\",\n    \"qualifier\": \"tt:dataQualifier\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tetra-tech/refs/heads/main/json-ld/tetra-tech-context.jsonld
tags:
- Analytics
- Consulting
- Data Management
- Engineering
- Environment
- Infrastructure
- Water
- JSON-LD
- Linked Data
- Semantic Web
---
