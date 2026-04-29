---
api_specs:
- filename: acceldata-adoc-api.yaml
  format: yaml
  label: Acceldata Data Observability Cloud API
  slug: adoc-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/acceldata/refs/heads/main/openapi/acceldata-adoc-api.yaml
class_count: 55
classes:
- schema
- Alert
- DataQualityRule
- Dataset
- LineageNode
- LineageGraph
- PipelineJob
- User
- Role
- id
- name
- description
- severity
- status
- message
- datasetId
- ruleId
- ruleType
- columnName
- threshold
- enabled
- databaseName
- schemaName
- dataSourceType
- rowCount
- columnCount
- qualityScore
- type
- platform
- database
- nodes
- edges
- rootNodeId
- sourceId
- targetId
- transformationType
- durationSeconds
- recordsProcessed
- username
- email
- firstName
- lastName
- active
- permissions
- total
- page
- pageSize
- alerts
- rules
- datasets
- jobs
- users
- roles
- code
- details
context_file: json-ld/acceldata-adoc-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/acceldata/refs/heads/main/json-ld/acceldata-adoc-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Acceldata Adoc Api from Acceldata.
layout: jsonld
name: Acceldata Adoc Api Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: adoc
  uri: https://acceldata.io/vocab/
properties:
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: lastProfiledAt
  type: dateTime
- container: ''
  name: startTime
  type: dateTime
- container: ''
  name: endTime
  type: dateTime
property_count: 5
provider_name: Acceldata
provider_slug: acceldata
slug: acceldata-adoc-api-context
source_filename: acceldata-adoc-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"adoc\": \"https://acceldata.io/vocab/\",\n\n    \"Alert\": \"adoc:Alert\",\n    \"DataQualityRule\": \"adoc:DataQualityRule\",\n    \"Dataset\": \"adoc:Dataset\",\n    \"LineageNode\": \"adoc:LineageNode\",\n    \"LineageGraph\": \"adoc:LineageGraph\",\n    \"PipelineJob\": \"adoc:PipelineJob\",\n    \"User\": \"schema:Person\",\n    \"Role\": \"adoc:Role\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"severity\": \"adoc:severity\",\n    \"status\": \"adoc:status\",\n    \"message\": \"schema:description\",\n    \"datasetId\": \"adoc:dataset\",\n    \"ruleId\"\
  : \"adoc:rule\",\n\n    \"ruleType\": \"adoc:ruleType\",\n    \"columnName\": \"adoc:columnName\",\n    \"threshold\": \"adoc:threshold\",\n    \"enabled\": \"adoc:enabled\",\n\n    \"databaseName\": \"adoc:databaseName\",\n    \"schemaName\": \"adoc:schemaName\",\n    \"dataSourceType\": \"adoc:dataSourceType\",\n    \"rowCount\": \"adoc:rowCount\",\n    \"columnCount\": \"adoc:columnCount\",\n    \"qualityScore\": \"adoc:qualityScore\",\n    \"lastProfiledAt\": {\n      \"@id\": \"adoc:lastProfiledAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"type\": \"@type\",\n    \"platform\": \"adoc:platform\",\n    \"database\": \"adoc:database\",\n    \"schema\": \"adoc:schema\",\n    \"nodes\": \"adoc:nodes\",\n    \"edges\": \"adoc:edges\",\n    \"rootNodeId\": \"adoc:rootNodeId\",\n    \"sourceId\": \"adoc:sourceId\",\n    \"targetId\": \"adoc:targetId\",\n    \"transformationType\": \"adoc:transformationType\",\n\n    \"startTime\": {\n      \"@id\": \"schema:startTime\",\n    \
  \  \"@type\": \"xsd:dateTime\"\n    },\n    \"endTime\": {\n      \"@id\": \"schema:endTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"durationSeconds\": \"adoc:durationSeconds\",\n    \"recordsProcessed\": \"adoc:recordsProcessed\",\n\n    \"username\": \"schema:identifier\",\n    \"email\": \"schema:email\",\n    \"firstName\": \"schema:givenName\",\n    \"lastName\": \"schema:familyName\",\n    \"active\": \"adoc:active\",\n\n    \"permissions\": \"adoc:permissions\",\n\n    \"total\": \"adoc:total\",\n    \"page\": \"adoc:page\",\n    \"pageSize\": \"adoc:pageSize\",\n    \"alerts\": \"adoc:alerts\",\n    \"rules\": \"adoc:rules\",\n    \"datasets\": \"adoc:datasets\",\n    \"jobs\": \"adoc:jobs\",\n    \"users\": \"adoc:users\",\n    \"roles\": \"adoc:roles\",\n\n    \"code\": \"adoc:errorCode\",\n    \"details\": \"schema:description\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/acceldata/refs/heads/main/json-ld/acceldata-adoc-api-context.jsonld
tags:
- AI Agents
- Data Management
- Data Observability
- Data Pipeline
- Data Quality
- Intelligence
- Observability
- JSON-LD
- Linked Data
- Semantic Web
---
