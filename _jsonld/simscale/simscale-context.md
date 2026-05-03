---
api_specs:
- filename: simscale-openapi.yml
  format: yaml
  label: SimScale REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/simscale/refs/heads/main/openapi/simscale-openapi.yml
class_count: 25
classes:
- Project
- Geometry
- Simulation
- MeshOperation
- SimulationRun
- SimulationResults
- projectId
- simulationId
- geometryId
- meshOperationId
- runId
- name
- description
- status
- measurementSystem
- geometryCount
- simulationCount
- format
- numberOfSolids
- numberOfSurfaces
- type
- model
- progress
- outputs
- downloadUrl
context_file: json-ld/simscale-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/simscale/refs/heads/main/json-ld/simscale-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Simscale from SimScale.
layout: jsonld
name: Simscale Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: simscale
  uri: https://api.simscale.com/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: created
  type: dateTime
- container: ''
  name: modified
  type: dateTime
- container: ''
  name: startTime
  type: dateTime
- container: ''
  name: finishedTime
  type: dateTime
property_count: 4
provider_name: SimScale
provider_slug: simscale
slug: simscale-context
source_filename: simscale-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"simscale\": \"https://api.simscale.com/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Project\": \"schema:Project\",\n    \"Geometry\": \"simscale:Geometry\",\n    \"Simulation\": \"simscale:Simulation\",\n    \"MeshOperation\": \"simscale:MeshOperation\",\n    \"SimulationRun\": \"simscale:SimulationRun\",\n    \"SimulationResults\": \"simscale:SimulationResults\",\n\n    \"projectId\": \"@id\",\n    \"simulationId\": \"@id\",\n    \"geometryId\": \"@id\",\n    \"meshOperationId\": \"@id\",\n    \"runId\": \"@id\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"created\": {\"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\"},\n    \"modified\": {\"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\"},\n    \"status\": \"schema:status\",\n\n    \"measurementSystem\": \"simscale:measurementSystem\",\n \
  \   \"geometryCount\": \"simscale:geometryCount\",\n    \"simulationCount\": \"simscale:simulationCount\",\n\n    \"format\": \"simscale:fileFormat\",\n    \"numberOfSolids\": \"simscale:solidCount\",\n    \"numberOfSurfaces\": \"simscale:surfaceCount\",\n\n    \"type\": \"schema:additionalType\",\n    \"model\": \"simscale:physicsModel\",\n\n    \"progress\": \"simscale:completionPercentage\",\n    \"startTime\": {\"@id\": \"schema:startDate\", \"@type\": \"xsd:dateTime\"},\n    \"finishedTime\": {\"@id\": \"schema:endDate\", \"@type\": \"xsd:dateTime\"},\n\n    \"outputs\": \"simscale:resultOutputs\",\n    \"downloadUrl\": \"schema:url\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/simscale/refs/heads/main/json-ld/simscale-context.jsonld
tags:
- CAE
- CFD
- FEA
- Simulation
- Engineering
- JSON-LD
- Linked Data
- Semantic Web
---
