---
api_specs:
- filename: openfema-fire-data-openapi.yml
  format: yaml
  label: OpenFEMA Fire Data API
  slug: openfema-fire-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-states-fire-administration/refs/heads/main/openapi/openfema-fire-data-openapi.yml
class_count: 3
classes:
- DisasterDeclaration
- FireIncident
- GovernmentOrganization
context_file: json-ld/united-states-fire-administration-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/united-states-fire-administration/refs/heads/main/json-ld/united-states-fire-administration-context.jsonld
description: JSON-LD context defining the semantic vocabulary for United States Fire Administration from United States Fire Administration.
layout: jsonld
name: United States Fire Administration Context
namespaces:
- prefix: fema
  uri: https://www.fema.gov/ontology/
- prefix: usfa
  uri: https://www.usfa.fema.gov/ontology/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: disasterNumber
  type: reference
- container: ''
  name: declarationType
  type: ''
- container: ''
  name: declarationTitle
  type: ''
- container: ''
  name: state
  type: ''
- container: ''
  name: declarationDate
  type: schema:Date
- container: ''
  name: incidentType
  type: ''
- container: ''
  name: incidentBeginDate
  type: schema:Date
- container: ''
  name: incidentEndDate
  type: schema:Date
- container: ''
  name: fdid
  type: ''
- container: ''
  name: incidentDate
  type: schema:Date
- container: ''
  name: propertyLoss
  type: schema:MonetaryAmount
- container: ''
  name: civilianDeaths
  type: schema:Integer
- container: ''
  name: firefighterDeaths
  type: schema:Integer
property_count: 13
provider_name: United States Fire Administration
provider_slug: united-states-fire-administration
slug: united-states-fire-administration-context
source_filename: united-states-fire-administration-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"fema\": \"https://www.fema.gov/ontology/\",\n    \"usfa\": \"https://www.usfa.fema.gov/ontology/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"DisasterDeclaration\": \"fema:DisasterDeclaration\",\n    \"FireIncident\": \"usfa:FireIncident\",\n    \"GovernmentOrganization\": \"GovernmentOrganization\",\n\n    \"disasterNumber\": {\n      \"@id\": \"fema:disasterNumber\",\n      \"@type\": \"@id\"\n    },\n    \"declarationType\": {\n      \"@id\": \"fema:declarationType\"\n    },\n    \"declarationTitle\": {\n      \"@id\": \"schema:name\"\n    },\n    \"state\": {\n      \"@id\": \"schema:addressRegion\"\n    },\n    \"declarationDate\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"schema:Date\"\n    },\n    \"incidentType\": {\n      \"@id\": \"fema:incidentType\"\n    },\n    \"incidentBeginDate\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"schema:Date\"\
  \n    },\n    \"incidentEndDate\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"schema:Date\"\n    },\n    \"fdid\": {\n      \"@id\": \"usfa:fireDepartmentId\"\n    },\n    \"incidentDate\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"schema:Date\"\n    },\n    \"propertyLoss\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"schema:MonetaryAmount\"\n    },\n    \"civilianDeaths\": {\n      \"@id\": \"usfa:civilianDeaths\",\n      \"@type\": \"schema:Integer\"\n    },\n    \"firefighterDeaths\": {\n      \"@id\": \"usfa:firefighterDeaths\",\n      \"@type\": \"schema:Integer\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/united-states-fire-administration/refs/heads/main/json-ld/united-states-fire-administration-context.jsonld
tags:
- Federal Government
- Fire Safety
- Emergency Management
- Public Safety
- FEMA
- JSON-LD
- Linked Data
- Semantic Web
---
