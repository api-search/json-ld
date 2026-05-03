---
api_specs:
- filename: usace-cwms-data-openapi.yml
  format: yaml
  label: USACE CWMS Data API
  slug: usace-cwms-data
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-army-corps-of-engineers/refs/heads/main/openapi/usace-cwms-data-openapi.yml
class_count: 30
classes:
- GovernmentOrganization
- Place
- name
- description
- officeId
- units
- values
- latitude
- longitude
- elevation
- verticalDatum
- horizontalDatum
- publicName
- longName
- kind
- timeZoneName
- countyName
- stateInitial
- active
- Timeseries
- Location
- StreamLocation
- Reservoir
- RatingTable
- LocationLevel
- Office
- WaterManagementData
- FloodStage
- ConservationPool
- FloodControl
context_file: json-ld/us-army-corps-of-engineers-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/us-army-corps-of-engineers/refs/heads/main/json-ld/us-army-corps-of-engineers-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Us Army Corps Of Engineers from US Army Corps of Engineers.
layout: jsonld
name: Us Army Corps Of Engineers Context
namespaces:
- prefix: dct
  uri: http://purl.org/dc/terms/
- prefix: hydro
  uri: http://www.opengeospatial.org/standards/waterml
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: usace
  uri: https://www.usace.army.mil/vocab/
- prefix: Dataset
  uri: http://www.w3.org/ns/dcat#Dataset
properties:
- container: ''
  name: begin
  type: dateTime
- container: ''
  name: end
  type: dateTime
- container: ''
  name: USACE
  type: GovernmentOrganization
property_count: 3
provider_name: US Army Corps of Engineers
provider_slug: us-army-corps-of-engineers
slug: us-army-corps-of-engineers-context
source_filename: us-army-corps-of-engineers-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"dct\": \"http://purl.org/dc/terms/\",\n    \"hydro\": \"http://www.opengeospatial.org/standards/waterml\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"usace\": \"https://www.usace.army.mil/vocab/\",\n\n    \"GovernmentOrganization\": \"GovernmentOrganization\",\n    \"Dataset\": \"http://www.w3.org/ns/dcat#Dataset\",\n    \"Place\": \"Place\",\n\n    \"name\": \"name\",\n    \"description\": \"description\",\n    \"officeId\": \"usace:officeId\",\n    \"units\": \"usace:units\",\n    \"begin\": {\n      \"@id\": \"dct:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"end\": {\n      \"@id\": \"dct:modified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"values\": \"usace:timeseriesValues\",\n    \"latitude\": \"geo:lat\",\n    \"longitude\": \"geo:long\",\n    \"elevation\": \"geo:alt\",\n    \"verticalDatum\": \"\
  usace:verticalDatum\",\n    \"horizontalDatum\": \"usace:horizontalDatum\",\n    \"publicName\": \"name\",\n    \"longName\": \"description\",\n    \"kind\": \"usace:locationKind\",\n    \"timeZoneName\": \"usace:timeZone\",\n    \"countyName\": \"usace:county\",\n    \"stateInitial\": \"usace:state\",\n    \"active\": \"usace:isActive\",\n\n    \"Timeseries\": \"usace:Timeseries\",\n    \"Location\": \"usace:Location\",\n    \"StreamLocation\": \"usace:StreamLocation\",\n    \"Reservoir\": \"usace:Reservoir\",\n    \"RatingTable\": \"usace:RatingTable\",\n    \"LocationLevel\": \"usace:LocationLevel\",\n    \"Office\": \"usace:Office\",\n    \"WaterManagementData\": \"usace:WaterManagementData\",\n\n    \"USACE\": {\n      \"@id\": \"usace:USACE\",\n      \"@type\": \"GovernmentOrganization\"\n    },\n\n    \"FloodStage\": \"usace:FloodStageLevel\",\n    \"ConservationPool\": \"usace:ConservationPoolLevel\",\n    \"FloodControl\": \"usace:FloodControlPool\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/us-army-corps-of-engineers/refs/heads/main/json-ld/us-army-corps-of-engineers-context.jsonld
tags:
- Water Resources
- Federal Government
- Military Engineering
- Infrastructure
- Open Data
- Geospatial Data
- JSON-LD
- Linked Data
- Semantic Web
---
