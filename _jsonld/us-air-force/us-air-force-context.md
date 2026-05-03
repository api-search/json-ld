---
class_count: 32
classes:
- GovernmentOrganization
- Dataset
- DataCatalog
- DataDownload
- id
- title
- description
- publisher
- keyword
- theme
- accrualPeriodicity
- accessLevel
- license
- distribution
- downloadURL
- mediaType
- format
- spatial
- temporal
- contactPoint
- AirForceProgram
- MilitaryInstallation
- AirForceBase
- AirForcePersonnel
- AircraftFleet
- MilitaryUnit
- ResearchProgram
- name
- url
- email
- fn
- hasEmail
context_file: json-ld/us-air-force-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/us-air-force/refs/heads/main/json-ld/us-air-force-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Us Air Force from US Air Force.
layout: jsonld
name: Us Air Force Context
namespaces:
- prefix: dcat
  uri: http://www.w3.org/ns/dcat#
- prefix: dct
  uri: http://purl.org/dc/terms/
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
- prefix: gov
  uri: https://www.w3.org/ns/gov#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: usaf
  uri: https://www.af.mil/vocab/
properties:
- container: ''
  name: modified
  type: dateTime
- container: ''
  name: issued
  type: date
property_count: 2
provider_name: US Air Force
provider_slug: us-air-force
slug: us-air-force-context
source_filename: us-air-force-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"dcat\": \"http://www.w3.org/ns/dcat#\",\n    \"dct\": \"http://purl.org/dc/terms/\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"gov\": \"https://www.w3.org/ns/gov#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"usaf\": \"https://www.af.mil/vocab/\",\n\n    \"GovernmentOrganization\": \"GovernmentOrganization\",\n    \"Dataset\": \"dcat:Dataset\",\n    \"DataCatalog\": \"DataCatalog\",\n    \"DataDownload\": \"DataDownload\",\n\n    \"id\": \"@id\",\n    \"title\": \"dct:title\",\n    \"description\": \"dct:description\",\n    \"publisher\": \"dct:publisher\",\n    \"keyword\": \"dcat:keyword\",\n    \"theme\": \"dcat:theme\",\n    \"modified\": {\n      \"@id\": \"dct:modified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"issued\": {\n      \"@id\": \"dct:issued\",\n      \"@type\": \"xsd:date\"\n    },\n    \"accrualPeriodicity\": \"dct:accrualPeriodicity\",\n    \"accessLevel\"\
  : \"dct:accessRights\",\n    \"license\": \"dct:license\",\n    \"distribution\": \"dcat:distribution\",\n    \"downloadURL\": \"dcat:downloadURL\",\n    \"mediaType\": \"dcat:mediaType\",\n    \"format\": \"dct:format\",\n    \"spatial\": \"dct:spatial\",\n    \"temporal\": \"dct:temporal\",\n    \"contactPoint\": \"dcat:contactPoint\",\n\n    \"AirForceProgram\": \"usaf:AirForceProgram\",\n    \"MilitaryInstallation\": \"usaf:MilitaryInstallation\",\n    \"AirForceBase\": \"usaf:AirForceBase\",\n    \"AirForcePersonnel\": \"usaf:AirForcePersonnel\",\n    \"AircraftFleet\": \"usaf:AircraftFleet\",\n    \"MilitaryUnit\": \"usaf:MilitaryUnit\",\n    \"ResearchProgram\": \"usaf:ResearchProgram\",\n\n    \"name\": \"name\",\n    \"url\": \"url\",\n    \"email\": \"email\",\n    \"fn\": \"foaf:name\",\n    \"hasEmail\": \"foaf:mbox\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/us-air-force/refs/heads/main/json-ld/us-air-force-context.jsonld
tags:
- Air Force
- Federal Government
- Military
- Defense
- Open Data
- Government API
- JSON-LD
- Linked Data
- Semantic Web
---
