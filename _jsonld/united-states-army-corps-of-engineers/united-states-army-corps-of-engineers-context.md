---
api_specs:
- filename: cwms-data-api-openapi.yml
  format: yaml
  label: CWMS Data API
  slug: cwms-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-states-army-corps-of-engineers/refs/heads/main/openapi/cwms-data-api-openapi.yml
class_count: 4
classes:
- name
- description
- url
- identifier
context_file: json-ld/united-states-army-corps-of-engineers-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/united-states-army-corps-of-engineers/refs/heads/main/json-ld/united-states-army-corps-of-engineers-context.jsonld
description: JSON-LD context defining the semantic vocabulary for United States Army Corps Of Engineers from United States Army Corps of Engineers.
layout: jsonld
name: United States Army Corps Of Engineers Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: dct
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: qudt
  uri: http://qudt.org/schema/qudt/
- prefix: geo
  uri: http://www.opengis.net/ont/geosparql#
- prefix: cwms
  uri: https://cwms-data.usace.army.mil/vocab#
- prefix: sosa
  uri: http://www.w3.org/ns/sosa/
- prefix: ssn
  uri: http://www.w3.org/ns/ssn/
properties:
- container: ''
  name: USACE
  type: reference
- container: ''
  name: location
  type: reference
- container: ''
  name: timeSeries
  type: reference
- container: ''
  name: observation
  type: reference
- container: ''
  name: observedProperty
  type: reference
- container: ''
  name: result
  type: ''
- container: ''
  name: resultTime
  type: dateTime
- container: ''
  name: phenomenonTime
  type: dateTime
- container: ''
  name: unit
  type: reference
- container: ''
  name: datum
  type: reference
- container: ''
  name: office
  type: reference
- container: ''
  name: qualityCode
  type: integer
- container: ''
  name: interval
  type: integer
- container: ''
  name: basin
  type: reference
- container: ''
  name: reservoir
  type: reference
- container: ''
  name: project
  type: reference
- container: ''
  name: rating
  type: reference
- container: ''
  name: forecast
  type: reference
- container: ''
  name: level
  type: reference
- container: ''
  name: stage
  type: ''
- container: ''
  name: flow
  type: ''
- container: ''
  name: elevation
  type: ''
- container: ''
  name: latitude
  type: double
- container: ''
  name: longitude
  type: double
property_count: 24
provider_name: United States Army Corps of Engineers
provider_slug: united-states-army-corps-of-engineers
slug: united-states-army-corps-of-engineers-context
source_filename: united-states-army-corps-of-engineers-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"dct\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"qudt\": \"http://qudt.org/schema/qudt/\",\n    \"geo\": \"http://www.opengis.net/ont/geosparql#\",\n    \"cwms\": \"https://cwms-data.usace.army.mil/vocab#\",\n    \"sosa\": \"http://www.w3.org/ns/sosa/\",\n    \"ssn\": \"http://www.w3.org/ns/ssn/\",\n\n    \"USACE\": {\n      \"@id\": \"schema:GovernmentOrganization\",\n      \"@type\": \"@id\"\n    },\n    \"location\": {\n      \"@id\": \"sosa:FeatureOfInterest\",\n      \"@type\": \"@id\"\n    },\n    \"timeSeries\": {\n      \"@id\": \"cwms:TimeSeries\",\n      \"@type\": \"@id\"\n    },\n    \"observation\": {\n      \"@id\": \"sosa:Observation\",\n      \"@type\": \"@id\"\n    },\n    \"observedProperty\": {\n      \"@id\": \"sosa:observedProperty\",\n      \"@type\": \"@id\"\n    },\n    \"result\": {\n      \"@id\": \"sosa:hasSimpleResult\"\
  \n    },\n    \"resultTime\": {\n      \"@id\": \"sosa:resultTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"phenomenonTime\": {\n      \"@id\": \"sosa:phenomenonTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"unit\": {\n      \"@id\": \"qudt:unit\",\n      \"@type\": \"@id\"\n    },\n    \"datum\": {\n      \"@id\": \"cwms:datum\",\n      \"@type\": \"@id\"\n    },\n    \"office\": {\n      \"@id\": \"cwms:office\",\n      \"@type\": \"@id\"\n    },\n    \"qualityCode\": {\n      \"@id\": \"cwms:qualityCode\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"interval\": {\n      \"@id\": \"cwms:interval\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"basin\": {\n      \"@id\": \"cwms:basin\",\n      \"@type\": \"@id\"\n    },\n    \"reservoir\": {\n      \"@id\": \"cwms:reservoir\",\n      \"@type\": \"@id\"\n    },\n    \"project\": {\n      \"@id\": \"cwms:project\",\n      \"@type\": \"@id\"\n    },\n    \"rating\": {\n      \"@id\": \"cwms:rating\",\n     \
  \ \"@type\": \"@id\"\n    },\n    \"forecast\": {\n      \"@id\": \"cwms:forecast\",\n      \"@type\": \"@id\"\n    },\n    \"level\": {\n      \"@id\": \"cwms:level\",\n      \"@type\": \"@id\"\n    },\n    \"stage\": {\n      \"@id\": \"cwms:stage\"\n    },\n    \"flow\": {\n      \"@id\": \"cwms:flow\"\n    },\n    \"elevation\": {\n      \"@id\": \"cwms:elevation\"\n    },\n    \"latitude\": {\n      \"@id\": \"schema:latitude\",\n      \"@type\": \"xsd:double\"\n    },\n    \"longitude\": {\n      \"@id\": \"schema:longitude\",\n      \"@type\": \"xsd:double\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"identifier\": \"schema:identifier\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/united-states-army-corps-of-engineers/refs/heads/main/json-ld/united-states-army-corps-of-engineers-context.jsonld
tags:
- Engineering
- Federal Government
- Water Resources
- Hydrology
- Civil Engineering
- JSON-LD
- Linked Data
- Semantic Web
---
