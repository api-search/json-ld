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
