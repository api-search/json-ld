---
api_specs:
- filename: openapi.json
  format: json
  label: Workday Extend REST API
  slug: ''
  spec_type: OpenAPI
  url: https://api.workday.com/extend/openapi.json
- filename: workday-extend-orchestration-openapi.yml
  format: yaml
  label: Workday Orchestration API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday-extend/refs/heads/main/openapi/workday-extend-orchestration-openapi.yml
- filename: workday-extend-custom-objects-openapi.yml
  format: yaml
  label: Workday Custom Objects API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday-extend/refs/heads/main/openapi/workday-extend-custom-objects-openapi.yml
- filename: workday-extend-graph-api-openapi.yml
  format: yaml
  label: Workday Graph API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday-extend/refs/heads/main/openapi/workday-extend-graph-api-openapi.yml
class_count: 29
classes:
- App
- Orchestration
- OrchestrationExecution
- CustomObjectDefinition
- AppVersion
- AppDeployment
- id
- descriptor
- name
- description
- status
- category
- createdOn
- lastModified
- href
- versionNumber
- changelog
- environment
- triggerType
- steps
- inputData
- parentObjectType
- instanceType
- fields
- dataType
- configurations
- key
- value
- isSecret
context_file: json-ld/workday-extend-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/workday-extend/refs/heads/main/json-ld/workday-extend-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Workday Extend from Workday Extend.
layout: jsonld
name: Workday Extend Context
namespaces:
- prefix: wd
  uri: https://www.workday.com/ontology/extend/
- prefix: extend
  uri: https://raw.githubusercontent.com/api-evangelist/workday-extend/main/json-ld/
properties:
- container: ''
  name: owner
  type: reference
- container: ''
  name: currentVersion
  type: reference
property_count: 2
provider_name: Workday Extend
provider_slug: workday-extend
slug: workday-extend-context
source_filename: workday-extend-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"wd\": \"https://www.workday.com/ontology/extend/\",\n    \"extend\": \"https://raw.githubusercontent.com/api-evangelist/workday-extend/main/json-ld/\",\n\n    \"App\": \"wd:App\",\n    \"Orchestration\": \"wd:Orchestration\",\n    \"OrchestrationExecution\": \"wd:OrchestrationExecution\",\n    \"CustomObjectDefinition\": \"wd:CustomObjectDefinition\",\n    \"AppVersion\": \"wd:AppVersion\",\n    \"AppDeployment\": \"wd:AppDeployment\",\n\n    \"id\": \"@id\",\n    \"descriptor\": \"schema:name\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"status\": \"wd:status\",\n    \"category\": \"schema:category\",\n    \"owner\": {\n      \"@id\": \"schema:author\",\n      \"@type\": \"@id\"\n    },\n    \"currentVersion\": {\n      \"@id\": \"wd:currentVersion\",\n      \"@type\": \"@id\"\n    },\n    \"createdOn\": \"schema:dateCreated\",\n    \"lastModified\": \"schema:dateModified\"\
  ,\n    \"href\": \"schema:url\",\n    \"versionNumber\": \"wd:versionNumber\",\n    \"changelog\": \"wd:changelog\",\n    \"environment\": \"wd:environment\",\n    \"triggerType\": \"wd:triggerType\",\n    \"steps\": \"wd:steps\",\n    \"inputData\": \"wd:inputData\",\n    \"parentObjectType\": \"wd:parentObjectType\",\n    \"instanceType\": \"wd:instanceType\",\n    \"fields\": \"wd:fields\",\n    \"dataType\": \"wd:dataType\",\n    \"configurations\": \"wd:configurations\",\n    \"key\": \"wd:key\",\n    \"value\": \"schema:value\",\n    \"isSecret\": \"wd:isSecret\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/workday-extend/refs/heads/main/json-ld/workday-extend-context.jsonld
tags:
- Automation
- Custom Applications
- Enterprise
- Extensions
- HCM
- Human Capital Management
- Integration
- Orchestration
- PaaS
- JSON-LD
- Linked Data
- Semantic Web
---
