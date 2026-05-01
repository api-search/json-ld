---
api_specs:
- filename: earth-engine.yml
  format: yaml
  label: Google Earth Engine REST API v1
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-earth-engine/refs/heads/main/openapi/earth-engine.yml
class_count: 12
classes:
- EarthEngineAsset
- ImageCollection
- name
- id
- title
- description
- type
- geometry
- sizeBytes
- bands
- crsCode
- properties
context_file: json-ld/earth-engine.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-earth-engine/refs/heads/main/json-ld/earth-engine.jsonld
description: JSON-LD context defining the semantic vocabulary for Earth Engine from Google Earth Engine REST.
layout: jsonld
name: Earth Engine Context
namespaces:
- prefix: gee
  uri: https://earthengine.googleapis.com/v1/
properties:
- container: ''
  name: updateTime
  type: schema:DateTime
- container: ''
  name: startTime
  type: schema:DateTime
- container: ''
  name: endTime
  type: schema:DateTime
property_count: 3
provider_name: Google Earth Engine REST
provider_slug: google-earth-engine
slug: earth-engine
source_filename: earth-engine.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gee\": \"https://earthengine.googleapis.com/v1/\",\n    \"EarthEngineAsset\": \"schema:Dataset\",\n    \"ImageCollection\": \"schema:DataCatalog\",\n    \"name\": \"schema:name\",\n    \"id\": \"schema:identifier\",\n    \"title\": \"schema:headline\",\n    \"description\": \"schema:description\",\n    \"type\": \"schema:additionalType\",\n    \"updateTime\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"startTime\": {\n      \"@id\": \"schema:temporalCoverage\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"endTime\": {\n      \"@id\": \"schema:expires\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"geometry\": \"schema:spatialCoverage\",\n    \"sizeBytes\": \"schema:contentSize\",\n    \"bands\": \"schema:variableMeasured\",\n    \"crsCode\": \"schema:variableMeasured\",\n    \"properties\": \"schema:additionalProperty\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-earth-engine/refs/heads/main/json-ld/earth-engine.jsonld
tags:
- Climate
- Earth Observation
- Environmental
- Geospatial
- GIS
- Google
- Remote Sensing
- Satellite Imagery
- JSON-LD
- Linked Data
- Semantic Web
---
