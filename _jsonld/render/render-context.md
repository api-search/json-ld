---
api_specs:
- filename: render-openapi.json
  format: json
  label: Render API
  slug: render-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/render/refs/heads/main/openapi/render-openapi.json
class_count: 31
classes:
- Service
- Deploy
- Project
- Environment
- Postgres
- KeyValue
- Blueprint
- EnvGroup
- Disk
- CronJob
- Workflow
- id
- name
- description
- type
- status
- plan
- region
- ownerId
- environmentId
- repo
- branch
- buildCommand
- startCommand
- slug
- url
- numInstances
- runtime
- autoscaling
- trigger
- commit
context_file: json-ld/render-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/render/refs/heads/main/json-ld/render-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Render from Render.
layout: jsonld
name: Render Context
namespaces:
- prefix: render
  uri: https://api.render.com/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: serviceTypes
  type: '@vocab'
- container: ''
  name: statusValues
  type: '@vocab'
property_count: 4
provider_name: Render
provider_slug: render
slug: render-context
source_filename: render-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"render\": \"https://api.render.com/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Service\": \"render:Service\",\n    \"Deploy\": \"render:Deploy\",\n    \"Project\": \"render:Project\",\n    \"Environment\": \"render:Environment\",\n    \"Postgres\": \"render:Postgres\",\n    \"KeyValue\": \"render:KeyValue\",\n    \"Blueprint\": \"render:Blueprint\",\n    \"EnvGroup\": \"render:EnvGroup\",\n    \"Disk\": \"render:Disk\",\n    \"CronJob\": \"render:CronJob\",\n    \"Workflow\": \"render:Workflow\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"type\": \"render:serviceType\",\n    \"status\"\
  : \"render:status\",\n    \"plan\": \"render:plan\",\n    \"region\": \"render:region\",\n    \"ownerId\": \"render:ownerId\",\n    \"environmentId\": \"render:environmentId\",\n    \"repo\": \"schema:codeRepository\",\n    \"branch\": \"render:branch\",\n    \"buildCommand\": \"render:buildCommand\",\n    \"startCommand\": \"render:startCommand\",\n    \"slug\": \"schema:identifier\",\n    \"url\": \"schema:url\",\n    \"numInstances\": \"render:numInstances\",\n    \"runtime\": \"render:runtime\",\n\n    \"autoscaling\": \"render:autoscaling\",\n    \"trigger\": \"render:trigger\",\n    \"commit\": \"render:commit\",\n\n    \"serviceTypes\": {\n      \"@id\": \"render:serviceTypes\",\n      \"@type\": \"@vocab\",\n      \"@context\": {\n        \"web_service\": \"render:WebService\",\n        \"static_site\": \"render:StaticSite\",\n        \"background_worker\": \"render:BackgroundWorker\",\n        \"cron_job\": \"render:CronJob\",\n        \"private_service\": \"render:PrivateService\"\
  \n      }\n    },\n\n    \"statusValues\": {\n      \"@id\": \"render:statusValues\",\n      \"@type\": \"@vocab\",\n      \"@context\": {\n        \"live\": \"render:Live\",\n        \"suspended\": \"render:Suspended\",\n        \"deactivated\": \"render:Deactivated\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/render/refs/heads/main/json-ld/render-context.jsonld
tags:
- Cloud
- Platform
- Deployment
- Infrastructure
- DevOps
- Web Services
- Databases
- Hosting
- JSON-LD
- Linked Data
- Semantic Web
---
