---
api_specs:
- filename: terrain-openapi.yml
  format: yaml
  label: Terrain API
  slug: terrain-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/terrain-discovery-environment-api/refs/heads/main/openapi/terrain-openapi.yml
class_count: 29
classes:
- Analysis
- App
- FileSystemObject
- Collection
- AVU
- Notification
- PermanentIdRequest
- iRODSPath
- fileSize
- permission
- systemId
- appId
- resultFolderPath
- avu
- attr
- unit
- analysisStatus
- appType
- name
- description
- dateCreated
- dateModified
- startDate
- endDate
- username
- email
- Dataset
- DOI
- identifier
context_file: json-ld/terrain-discovery-environment-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/terrain-discovery-environment-api/refs/heads/main/json-ld/terrain-discovery-environment-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Terrain Discovery Environment Api from Terrain Discovery Environment API.
layout: jsonld
name: Terrain Discovery Environment Api Context
namespaces:
- prefix: cyverse
  uri: https://cyverse.org/vocab#
- prefix: irods
  uri: https://irods.org/vocab#
- prefix: terrain
  uri: https://de.cyverse.org/vocab#
properties: []
property_count: 0
provider_name: Terrain Discovery Environment API
provider_slug: terrain-discovery-environment-api
slug: terrain-discovery-environment-api-context
source_filename: terrain-discovery-environment-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"cyverse\": \"https://cyverse.org/vocab#\",\n    \"irods\": \"https://irods.org/vocab#\",\n    \"terrain\": \"https://de.cyverse.org/vocab#\",\n    \"Analysis\": \"terrain:Analysis\",\n    \"App\": \"terrain:App\",\n    \"FileSystemObject\": \"irods:DataObject\",\n    \"Collection\": \"irods:Collection\",\n    \"AVU\": \"irods:AVU\",\n    \"Notification\": \"terrain:Notification\",\n    \"PermanentIdRequest\": \"terrain:PermanentIdRequest\",\n    \"iRODSPath\": \"irods:logicalPath\",\n    \"fileSize\": \"schema:fileSize\",\n    \"permission\": \"terrain:permission\",\n    \"systemId\": \"terrain:systemId\",\n    \"appId\": \"terrain:appId\",\n    \"resultFolderPath\": \"terrain:resultFolderPath\",\n    \"avu\": \"irods:avu\",\n    \"attr\": \"irods:attribute\",\n    \"unit\": \"irods:unit\",\n    \"analysisStatus\": \"terrain:analysisStatus\",\n    \"appType\": \"terrain:appType\",\n    \"name\": \"schema:name\"\
  ,\n    \"description\": \"schema:description\",\n    \"dateCreated\": \"schema:dateCreated\",\n    \"dateModified\": \"schema:dateModified\",\n    \"startDate\": \"schema:startDate\",\n    \"endDate\": \"schema:endDate\",\n    \"username\": \"schema:identifier\",\n    \"email\": \"schema:email\",\n    \"Dataset\": \"schema:Dataset\",\n    \"DOI\": \"schema:identifier\",\n    \"identifier\": \"schema:identifier\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/terrain-discovery-environment-api/refs/heads/main/json-ld/terrain-discovery-environment-api-context.jsonld
tags:
- Bioinformatics
- Data Science
- Life Sciences
- Filesystem
- Cloud Computing
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
