---
class_count: 2
classes:
- id
- name
context_file: json-ld/climate-fieldview-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/climate-fieldview/refs/heads/main/json-ld/climate-fieldview-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Climate Fieldview from Climate FieldView.
layout: jsonld
name: Climate Fieldview Context
namespaces:
- prefix: fieldview
  uri: https://api.climate.com/api/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
- prefix: geojson
  uri: https://purl.org/geojson/vocab#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Field
  type: schema:Place
- container: ''
  name: PlantingLayer
  type: schema:Dataset
- container: ''
  name: HarvestLayer
  type: schema:Dataset
- container: ''
  name: SoilSample
  type: schema:Observation
- container: ''
  name: growerName
  type: schema:Person
- container: ''
  name: farmName
  type: ''
- container: ''
  name: acreage
  type: schema:QuantitativeValue
- container: ''
  name: boundary
  type: ''
- container: ''
  name: centroid
  type: ''
- container: ''
  name: latitude
  type: double
- container: ''
  name: longitude
  type: double
- container: ''
  name: state
  type: ''
- container: ''
  name: county
  type: ''
- container: ''
  name: crop
  type: ''
- container: ''
  name: seedVariety
  type: ''
- container: ''
  name: seedingRate
  type: ''
- container: ''
  name: yieldAverage
  type: schema:QuantitativeValue
- container: ''
  name: moistureAverage
  type: ''
- container: set
  name: fieldIds
  type: ''
- container: ''
  name: occurredOn
  type: dateTime
- container: ''
  name: sampledOn
  type: date
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
property_count: 23
provider_name: Climate FieldView
provider_slug: climate-fieldview
slug: climate-fieldview-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"fieldview\": \"https://api.climate.com/api/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"geojson\": \"https://purl.org/geojson/vocab#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Field\": {\n      \"@id\": \"fieldview:Field\",\n      \"@type\": \"schema:Place\"\n    },\n    \"PlantingLayer\": {\n      \"@id\": \"fieldview:PlantingLayer\",\n      \"@type\": \"schema:Dataset\"\n    },\n    \"HarvestLayer\": {\n      \"@id\": \"fieldview:HarvestLayer\",\n      \"@type\": \"schema:Dataset\"\n    },\n    \"SoilSample\": {\n      \"@id\": \"fieldview:SoilSample\",\n      \"@type\": \"schema:Observation\"\n    },\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"growerName\": {\n      \"@id\": \"schema:provider\",\n      \"@type\": \"schema:Person\"\n    },\n    \"farmName\"\
  : {\n      \"@id\": \"schema:containedInPlace\"\n    },\n    \"acreage\": {\n      \"@id\": \"schema:floorSize\",\n      \"@type\": \"schema:QuantitativeValue\"\n    },\n    \"boundary\": {\n      \"@id\": \"geojson:geometry\"\n    },\n    \"centroid\": {\n      \"@id\": \"geo:Point\"\n    },\n    \"latitude\": {\n      \"@id\": \"geo:lat\",\n      \"@type\": \"xsd:double\"\n    },\n    \"longitude\": {\n      \"@id\": \"geo:long\",\n      \"@type\": \"xsd:double\"\n    },\n    \"state\": {\n      \"@id\": \"schema:addressRegion\"\n    },\n    \"county\": {\n      \"@id\": \"schema:addressLocality\"\n    },\n    \"crop\": {\n      \"@id\": \"schema:material\"\n    },\n    \"seedVariety\": {\n      \"@id\": \"fieldview:seedVariety\"\n    },\n    \"seedingRate\": {\n      \"@id\": \"fieldview:seedingRate\"\n    },\n    \"yieldAverage\": {\n      \"@id\": \"schema:yield\",\n      \"@type\": \"schema:QuantitativeValue\"\n    },\n    \"moistureAverage\": {\n      \"@id\": \"fieldview:moistureContent\"\
  \n    },\n    \"fieldIds\": {\n      \"@id\": \"fieldview:relatedField\",\n      \"@container\": \"@set\"\n    },\n    \"occurredOn\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"sampledOn\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:date\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/climate-fieldview/refs/heads/main/json-ld/climate-fieldview-context.jsonld
tags:
- Agriculture
- Bayer
- Crop Data
- Field Boundaries
- Harvest
- OAuth2
- Planting
- Precision Ag
- JSON-LD
- Linked Data
- Semantic Web
---
