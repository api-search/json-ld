---
api_specs:
- filename: siemens-mindsphere-asset-management-openapi.yml
  format: yaml
  label: Siemens MindSphere Asset Management API
  slug: asset-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/siemens-mindsphere/refs/heads/main/openapi/siemens-mindsphere-asset-management-openapi.yml
- filename: siemens-mindsphere-iot-timeseries-openapi.yml
  format: yaml
  label: Siemens MindSphere IoT Time Series API
  slug: iot-timeseries-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/siemens-mindsphere/refs/heads/main/openapi/siemens-mindsphere-iot-timeseries-openapi.yml
class_count: 23
classes:
- Asset
- AssetType
- AspectType
- TimeSeriesDataPoint
- Location
- VariableDefinition
- assetId
- name
- description
- externalId
- timezone
- twinType
- tenantId
- etag
- country
- locality
- region
- postalCode
- streetAddress
- variables
- dataType
- unit
- value
context_file: json-ld/siemens-mindsphere-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/siemens-mindsphere/refs/heads/main/json-ld/siemens-mindsphere-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Siemens Mindsphere from Siemens MindSphere.
layout: jsonld
name: Siemens Mindsphere Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: mindsphere
  uri: https://gateway.eu1.mindsphere.io/vocab/
- prefix: sosa
  uri: http://www.w3.org/ns/sosa/
- prefix: ssn
  uri: http://www.w3.org/ns/ssn/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
properties:
- container: ''
  name: typeId
  type: reference
- container: ''
  name: parentId
  type: reference
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: location
  type: schema:Place
- container: ''
  name: latitude
  type: double
- container: ''
  name: longitude
  type: double
- container: ''
  name: altitude
  type: double
- container: ''
  name: aspects
  type: reference
- container: ''
  name: aspectTypeId
  type: reference
- container: ''
  name: _time
  type: dateTime
property_count: 11
provider_name: Siemens MindSphere
provider_slug: siemens-mindsphere
slug: siemens-mindsphere-context
source_filename: siemens-mindsphere-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"mindsphere\": \"https://gateway.eu1.mindsphere.io/vocab/\",\n    \"sosa\": \"http://www.w3.org/ns/sosa/\",\n    \"ssn\": \"http://www.w3.org/ns/ssn/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n\n    \"Asset\": \"schema:Thing\",\n    \"AssetType\": \"schema:Class\",\n    \"AspectType\": \"sosa:ObservableProperty\",\n    \"TimeSeriesDataPoint\": \"sosa:Observation\",\n    \"Location\": \"schema:Place\",\n    \"VariableDefinition\": \"sosa:ObservableProperty\",\n\n    \"assetId\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"externalId\": \"schema:identifier\",\n    \"typeId\": {\n      \"@id\": \"schema:additionalType\",\n      \"@type\": \"@id\"\n    },\n    \"parentId\": {\n      \"@id\": \"schema:isPartOf\",\n      \"@type\": \"@id\"\n    },\n    \"timezone\":\
  \ \"schema:temporalCoverage\",\n    \"twinType\": \"mindsphere:twinType\",\n    \"tenantId\": \"mindsphere:tenantId\",\n    \"etag\": \"mindsphere:etag\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"location\": {\n      \"@id\": \"schema:location\",\n      \"@type\": \"schema:Place\"\n    },\n    \"latitude\": {\n      \"@id\": \"geo:lat\",\n      \"@type\": \"xsd:double\"\n    },\n    \"longitude\": {\n      \"@id\": \"geo:long\",\n      \"@type\": \"xsd:double\"\n    },\n    \"altitude\": {\n      \"@id\": \"geo:alt\",\n      \"@type\": \"xsd:double\"\n    },\n    \"country\": \"schema:addressCountry\",\n    \"locality\": \"schema:addressLocality\",\n    \"region\": \"schema:addressRegion\",\n    \"postalCode\": \"schema:postalCode\",\n    \"streetAddress\": \"schema:streetAddress\",\n\n    \"aspects\": {\n   \
  \   \"@id\": \"sosa:observes\",\n      \"@type\": \"@id\"\n    },\n    \"variables\": \"sosa:hasResult\",\n    \"aspectTypeId\": {\n      \"@id\": \"sosa:observedProperty\",\n      \"@type\": \"@id\"\n    },\n\n    \"_time\": {\n      \"@id\": \"sosa:resultTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"dataType\": \"schema:dataType\",\n    \"unit\": \"schema:unitCode\",\n    \"value\": \"sosa:hasSimpleResult\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/siemens-mindsphere/refs/heads/main/json-ld/siemens-mindsphere-context.jsonld
tags:
- IoT
- Industrial
- Digital Twin
- Time Series
- Asset Management
- Industrial IoT
- Insights Hub
- JSON-LD
- Linked Data
- Semantic Web
---
