---
api_specs:
- filename: talend-orchestration-openapi.yml
  format: yaml
  label: Talend Cloud Orchestration API
  slug: talend-orchestration-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/talend/refs/heads/main/openapi/talend-orchestration-openapi.yml
- filename: talend-processing-openapi.yml
  format: yaml
  label: Talend Cloud Processing API
  slug: talend-processing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/talend/refs/heads/main/openapi/talend-processing-openapi.yml
class_count: 10
classes:
- Task
- Plan
- Workspace
- Environment
- Connection
- RemoteEngine
- TaskExecution
- PlanExecution
- Artifact
- RunProfile
context_file: json-ld/talend-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/talend/refs/heads/main/json-ld/talend-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Talend from Talend.
layout: jsonld
name: Talend Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: talend
  uri: https://talend.qlik.dev/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: ''
- container: ''
  name: name
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: created
  type: dateTime
- container: ''
  name: updated
  type: dateTime
- container: ''
  name: owner
  type: ''
- container: ''
  name: status
  type: string
- container: ''
  name: workspaceId
  type: reference
- container: ''
  name: environmentId
  type: reference
- container: ''
  name: artifactId
  type: reference
- container: ''
  name: artifactVersion
  type: string
- container: ''
  name: executionId
  type: string
- container: ''
  name: taskId
  type: reference
- container: ''
  name: planId
  type: reference
- container: ''
  name: startTime
  type: dateTime
- container: ''
  name: endTime
  type: dateTime
- container: ''
  name: duration
  type: integer
- container: ''
  name: engineId
  type: reference
- container: ''
  name: logUrl
  type: reference
- container: list
  name: steps
  type: ''
- container: ''
  name: runConfig
  type: ''
- container: ''
  name: cronExpression
  type: ''
- container: ''
  name: timezone
  type: ''
- container: ''
  name: rowsProcessed
  type: integer
property_count: 24
provider_name: Talend
provider_slug: talend
slug: talend-context
source_filename: talend-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"talend\": \"https://talend.qlik.dev/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Task\": \"talend:Task\",\n    \"Plan\": \"talend:Plan\",\n    \"Workspace\": \"talend:Workspace\",\n    \"Environment\": \"talend:Environment\",\n    \"Connection\": \"talend:Connection\",\n    \"RemoteEngine\": \"talend:RemoteEngine\",\n    \"TaskExecution\": \"talend:TaskExecution\",\n    \"PlanExecution\": \"talend:PlanExecution\",\n    \"Artifact\": \"talend:Artifact\",\n    \"RunProfile\": \"talend:RunProfile\",\n\n    \"id\": { \"@id\": \"@id\" },\n    \"name\": { \"@id\": \"schema:name\" },\n    \"description\": { \"@id\": \"schema:description\" },\n    \"created\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\" },\n    \"updated\": { \"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\" },\n    \"owner\": { \"@id\": \"schema:creator\" },\n    \"\
  status\": { \"@id\": \"talend:status\", \"@type\": \"xsd:string\" },\n    \"workspaceId\": { \"@id\": \"talend:workspace\", \"@type\": \"@id\" },\n    \"environmentId\": { \"@id\": \"talend:environment\", \"@type\": \"@id\" },\n    \"artifactId\": { \"@id\": \"talend:artifact\", \"@type\": \"@id\" },\n    \"artifactVersion\": { \"@id\": \"talend:artifactVersion\", \"@type\": \"xsd:string\" },\n    \"executionId\": { \"@id\": \"talend:executionId\", \"@type\": \"xsd:string\" },\n    \"taskId\": { \"@id\": \"talend:task\", \"@type\": \"@id\" },\n    \"planId\": { \"@id\": \"talend:plan\", \"@type\": \"@id\" },\n    \"startTime\": { \"@id\": \"schema:startDate\", \"@type\": \"xsd:dateTime\" },\n    \"endTime\": { \"@id\": \"schema:endDate\", \"@type\": \"xsd:dateTime\" },\n    \"duration\": { \"@id\": \"schema:duration\", \"@type\": \"xsd:integer\" },\n    \"engineId\": { \"@id\": \"talend:remoteEngine\", \"@type\": \"@id\" },\n    \"logUrl\": { \"@id\": \"talend:logUrl\", \"@type\": \"@id\"\
  \ },\n    \"steps\": { \"@id\": \"talend:steps\", \"@container\": \"@list\" },\n    \"runConfig\": { \"@id\": \"talend:runConfig\" },\n    \"cronExpression\": { \"@id\": \"talend:cronExpression\" },\n    \"timezone\": { \"@id\": \"talend:timezone\" },\n    \"rowsProcessed\": { \"@id\": \"talend:rowsProcessed\", \"@type\": \"xsd:integer\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/talend/refs/heads/main/json-ld/talend-context.jsonld
tags:
- API Management
- Data Integration
- Data Quality
- ETL
- Orchestration
- Pipelines
- JSON-LD
- Linked Data
- Semantic Web
---
