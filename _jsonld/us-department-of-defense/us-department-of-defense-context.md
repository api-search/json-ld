---
api_specs:
- filename: usace-cwms-data-api-openapi.yml
  format: yaml
  label: USACE Corps Water Management System Data API
  slug: cwms-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-department-of-defense/refs/heads/main/openapi/usace-cwms-data-api-openapi.yml
class_count: 22
classes:
- WaterTimeSeries
- MonitoringLocation
- WaterProject
- ReservoirPool
- FieldMeasurement
- RatingCurve
- id
- type
- name
- description
- office-id
- units
- interval
- time-zone
- values
- latitude
- longitude
- elevation
- horizontal-datum
- vertical-datum
- active
- public-name
context_file: json-ld/us-department-of-defense-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/us-department-of-defense/refs/heads/main/json-ld/us-department-of-defense-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Us Department Of Defense from US Department of Defense.
layout: jsonld
name: Us Department Of Defense Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: dod
  uri: https://data.defense.gov/ns/
- prefix: usace
  uri: https://water.usace.army.mil/ns/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
- prefix: qudt
  uri: http://qudt.org/schema/qudt/
properties:
- container: ''
  name: Department
  type: ''
- container: ''
  name: USACE
  type: ''
property_count: 2
provider_name: US Department of Defense
provider_slug: us-department-of-defense
slug: us-department-of-defense-context
source_filename: us-department-of-defense-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"dod\": \"https://data.defense.gov/ns/\",\n    \"usace\": \"https://water.usace.army.mil/ns/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"qudt\": \"http://qudt.org/schema/qudt/\",\n\n    \"WaterTimeSeries\": \"usace:WaterTimeSeries\",\n    \"MonitoringLocation\": \"schema:Place\",\n    \"WaterProject\": \"schema:GovernmentBuilding\",\n    \"ReservoirPool\": \"usace:ReservoirPool\",\n    \"FieldMeasurement\": \"usace:FieldMeasurement\",\n    \"RatingCurve\": \"usace:RatingCurve\",\n\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"office-id\": \"usace:officeId\",\n    \"units\": \"qudt:unit\",\n    \"interval\": \"usace:measurementInterval\",\n    \"time-zone\": \"usace:timezone\",\n    \"values\": \"usace:observations\",\n\
  \n    \"latitude\": \"geo:lat\",\n    \"longitude\": \"geo:long\",\n    \"elevation\": \"usace:elevation\",\n    \"horizontal-datum\": \"usace:horizontalDatum\",\n    \"vertical-datum\": \"usace:verticalDatum\",\n    \"active\": \"schema:availableOnDevice\",\n    \"public-name\": \"schema:alternateName\",\n\n    \"Department\": {\n      \"@id\": \"schema:GovernmentOrganization\",\n      \"name\": \"US Department of Defense\",\n      \"url\": \"https://www.defense.gov\",\n      \"sameAs\": [\n        \"https://www.wikidata.org/wiki/Q11226\",\n        \"https://dbpedia.org/resource/United_States_Department_of_Defense\"\n      ]\n    },\n\n    \"USACE\": {\n      \"@id\": \"schema:GovernmentOrganization\",\n      \"name\": \"US Army Corps of Engineers\",\n      \"url\": \"https://www.usace.army.mil\",\n      \"sameAs\": \"https://www.wikidata.org/wiki/Q1049371\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/us-department-of-defense/refs/heads/main/json-ld/us-department-of-defense-context.jsonld
tags:
- Federal Government
- Defense
- Military
- Water Management
- Waterways
- Open Data
- JSON-LD
- Linked Data
- Semantic Web
---
