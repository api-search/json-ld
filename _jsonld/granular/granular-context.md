---
api_specs:
- filename: granular-farm-management-openapi.yml
  format: yaml
  label: Granular Farm Management API
  slug: granular-farm-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/granular/refs/heads/main/openapi/granular-farm-management-openapi.yml
class_count: 9
classes:
- id
- name
- irrigated
- county
- state
- crop
- variety
- activityType
- notes
context_file: json-ld/granular-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/granular/refs/heads/main/json-ld/granular-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Granular from Granular (Corteva Agriscience).
layout: jsonld
name: Granular Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
- prefix: agro
  uri: http://agroportal.lirmm.fr/ontologies/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dct
  uri: http://purl.org/dc/terms/
- prefix: geosparql
  uri: http://www.opengis.net/ont/geosparql#
properties:
- container: ''
  name: Farm
  type: reference
- container: ''
  name: Field
  type: reference
- container: ''
  name: CropPlan
  type: reference
- container: ''
  name: Activity
  type: reference
- container: ''
  name: farmId
  type: reference
- container: ''
  name: acres
  type: decimal
- container: ''
  name: boundary
  type: reference
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: season
  type: integer
- container: ''
  name: plannedAcres
  type: decimal
- container: ''
  name: targetYield
  type: decimal
- container: ''
  name: date
  type: date
- container: ''
  name: totalRevenue
  type: decimal
- container: ''
  name: totalExpenses
  type: decimal
- container: ''
  name: netIncome
  type: decimal
property_count: 16
provider_name: Granular (Corteva Agriscience)
provider_slug: granular
slug: granular-context
source_filename: granular-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"agro\": \"http://agroportal.lirmm.fr/ontologies/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dct\": \"http://purl.org/dc/terms/\",\n    \"geosparql\": \"http://www.opengis.net/ont/geosparql#\",\n\n    \"Farm\": {\n      \"@id\": \"schema:LocalBusiness\",\n      \"@type\": \"@id\"\n    },\n    \"Field\": {\n      \"@id\": \"schema:Place\",\n      \"@type\": \"@id\"\n    },\n    \"CropPlan\": {\n      \"@id\": \"schema:PlanAction\",\n      \"@type\": \"@id\"\n    },\n    \"Activity\": {\n      \"@id\": \"schema:Action\",\n      \"@type\": \"@id\"\n    },\n\n    \"id\": \"schema:identifier\",\n    \"name\": \"schema:name\",\n    \"farmId\": {\n      \"@id\": \"schema:containedInPlace\",\n      \"@type\": \"@id\"\n    },\n    \"acres\": {\n      \"@id\": \"schema:floorSize\",\n      \"@type\": \"xsd:decimal\"\
  \n    },\n    \"boundary\": {\n      \"@id\": \"geosparql:hasGeometry\",\n      \"@type\": \"@id\"\n    },\n    \"irrigated\": \"schema:amenityFeature\",\n    \"county\": \"schema:addressRegion\",\n    \"state\": \"schema:addressRegion\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"crop\": \"schema:name\",\n    \"variety\": \"schema:additionalType\",\n    \"season\": {\n      \"@id\": \"schema:temporalCoverage\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"plannedAcres\": {\n      \"@id\": \"schema:floorSize\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"targetYield\": {\n      \"@id\": \"schema:expectedArrivalFrom\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"activityType\": \"schema:actionStatus\",\n    \"date\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n\
  \    \"notes\": \"schema:description\",\n\n    \"totalRevenue\": {\n      \"@id\": \"schema:revenue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"totalExpenses\": {\n      \"@id\": \"schema:cost\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"netIncome\": {\n      \"@id\": \"schema:profitMargin\",\n      \"@type\": \"xsd:decimal\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/granular/refs/heads/main/json-ld/granular-context.jsonld
tags:
- Agriculture
- Farm Management
- Financial
- Crop Planning
- Agronomy
- JSON-LD
- Linked Data
- Semantic Web
---
