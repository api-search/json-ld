---
api_specs:
- filename: usgs-earthquake-catalog-openapi.yml
  format: yaml
  label: USGS Earthquake Catalog API
  slug: earthquake-catalog-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-geological-survey/refs/heads/main/openapi/usgs-earthquake-catalog-openapi.yml
- filename: openapi
  format: yaml
  label: USGS Water Data OGC API
  slug: water-data-api
  spec_type: OpenAPI
  url: https://api.waterdata.usgs.gov/ogcapi/v0/openapi?f=json
class_count: 22
classes:
- EarthquakeEvent
- SeismicMagnitude
- WaterMonitoringLocation
- WaterObservation
- WaterTimeSeries
- id
- type
- mag
- magType
- place
- depth
- latitude
- longitude
- alert
- tsunami
- felt
- sig
- status
- monitoringLocationIdentifier
- parameterCode
- values
- units
context_file: json-ld/us-geological-survey-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/us-geological-survey/refs/heads/main/json-ld/us-geological-survey-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Us Geological Survey from US Geological Survey.
layout: jsonld
name: Us Geological Survey Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: usgs
  uri: https://www.usgs.gov/ns/
- prefix: qudt
  uri: http://qudt.org/schema/qudt/
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: geosparql
  uri: http://www.opengis.net/ont/geosparql#
- prefix: ssn
  uri: http://www.w3.org/ns/ssn/
- prefix: sosa
  uri: http://www.w3.org/ns/sosa/
properties:
- container: ''
  name: time
  type: dateTime
- container: ''
  name: updated
  type: dateTime
- container: ''
  name: url
  type: reference
- container: ''
  name: Organization
  type: ''
- container: ''
  name: MMI
  type: ''
- container: ''
  name: PAGER
  type: ''
property_count: 6
provider_name: US Geological Survey
provider_slug: us-geological-survey
slug: us-geological-survey-context
source_filename: us-geological-survey-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"usgs\": \"https://www.usgs.gov/ns/\",\n    \"qudt\": \"http://qudt.org/schema/qudt/\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"geosparql\": \"http://www.opengis.net/ont/geosparql#\",\n    \"ssn\": \"http://www.w3.org/ns/ssn/\",\n    \"sosa\": \"http://www.w3.org/ns/sosa/\",\n\n    \"EarthquakeEvent\": \"schema:Event\",\n    \"SeismicMagnitude\": \"usgs:SeismicMagnitude\",\n    \"WaterMonitoringLocation\": \"sosa:FeatureOfInterest\",\n    \"WaterObservation\": \"sosa:Observation\",\n    \"WaterTimeSeries\": \"usgs:WaterTimeSeries\",\n\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n\n    \"mag\": \"usgs:magnitude\",\n    \"magType\": \"usgs:magnitudeType\",\n    \"place\": \"schema:location\",\n    \"time\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updated\"\
  : {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"depth\": \"usgs:depthKm\",\n    \"latitude\": \"geo:lat\",\n    \"longitude\": \"geo:long\",\n    \"alert\": \"usgs:pagarAlertLevel\",\n    \"tsunami\": \"usgs:tsunamiFlag\",\n    \"felt\": \"usgs:dyfiCount\",\n    \"sig\": \"usgs:significanceScore\",\n    \"status\": \"schema:eventStatus\",\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n\n    \"monitoringLocationIdentifier\": \"sosa:hasFeatureOfInterest\",\n    \"parameterCode\": \"sosa:observedProperty\",\n    \"values\": \"sosa:hasResult\",\n    \"units\": \"qudt:unit\",\n\n    \"Organization\": {\n      \"@id\": \"schema:GovernmentOrganization\",\n      \"name\": \"US Geological Survey\",\n      \"url\": \"https://www.usgs.gov\",\n      \"sameAs\": [\n        \"https://www.wikidata.org/wiki/Q193755\",\n        \"https://dbpedia.org/resource/United_States_Geological_Survey\"\n      ]\n    },\n\n    \"MMI\"\
  : {\n      \"@id\": \"usgs:ModifiedMercalliIntensity\",\n      \"description\": \"The Modified Mercalli Intensity scale for measuring earthquake shaking intensity\"\n    },\n\n    \"PAGER\": {\n      \"@id\": \"usgs:PAGER\",\n      \"description\": \"Prompt Assessment of Global Earthquakes for Response - rapid impact assessment system\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/us-geological-survey/refs/heads/main/json-ld/us-geological-survey-context.jsonld
tags:
- Federal Government
- Earth Science
- Earthquakes
- Water Data
- Geospatial
- Hazards
- Environment
- JSON-LD
- Linked Data
- Semantic Web
---
