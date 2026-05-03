---
api_specs:
- filename: sybase-ase-rest-api-openapi.yml
  format: yaml
  label: Sybase ASE REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sybase/refs/heads/main/openapi/sybase-ase-rest-api-openapi.yml
- filename: openapi.json
  format: json
  label: Sybase IQ REST API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sybase.example.com/iq/v1/openapi.json
class_count: 18
classes:
- Server
- Database
- Login
- Device
- Backup
- ConfigParameter
- id
- name
- version
- status
- host
- port
- owner
- physicalName
- deviceNumber
- databaseName
- type
- requiresRestart
context_file: json-ld/sybase-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sybase/refs/heads/main/json-ld/sybase-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sybase from Sybase.
layout: jsonld
name: Sybase Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: sybase
  uri: https://www.sap.com/vocab/sybase#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: startTime
  type: dateTime
- container: ''
  name: sizeMB
  type: decimal
- container: ''
  name: dataUsedMB
  type: decimal
- container: ''
  name: logUsedMB
  type: decimal
- container: ''
  name: cpuUtilization
  type: decimal
- container: ''
  name: uptime
  type: integer
property_count: 6
provider_name: Sybase
provider_slug: sybase
slug: sybase-context
source_filename: sybase-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"sybase\": \"https://www.sap.com/vocab/sybase#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Server\": \"sybase:ASEServer\",\n    \"Database\": \"sybase:ASEDatabase\",\n    \"Login\": \"sybase:ASELogin\",\n    \"Device\": \"sybase:ASEDevice\",\n    \"Backup\": \"sybase:ASEBackup\",\n    \"ConfigParameter\": \"sybase:ConfigParameter\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"version\": \"schema:softwareVersion\",\n    \"status\": \"schema:additionalType\",\n    \"host\": \"schema:serverAddress\",\n    \"port\": \"schema:serverPort\",\n    \"startTime\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"owner\": \"schema:accountablePerson\",\n    \"sizeMB\": {\n      \"@id\": \"sybase:sizeInMegabytes\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"dataUsedMB\": {\n      \"@id\": \"sybase:dataUsedMegabytes\"\
  ,\n      \"@type\": \"xsd:decimal\"\n    },\n    \"logUsedMB\": {\n      \"@id\": \"sybase:logUsedMegabytes\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"cpuUtilization\": {\n      \"@id\": \"sybase:cpuUtilization\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"uptime\": {\n      \"@id\": \"sybase:uptimeSeconds\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"physicalName\": \"sybase:physicalPath\",\n    \"deviceNumber\": \"sybase:deviceNumber\",\n    \"databaseName\": \"sybase:databaseName\",\n    \"type\": \"schema:additionalType\",\n    \"requiresRestart\": \"sybase:requiresRestart\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sybase/refs/heads/main/json-ld/sybase-context.jsonld
tags:
- Database
- Enterprise
- SAP
- SQL
- JSON-LD
- Linked Data
- Semantic Web
---
