---
class_count: 26
classes:
- id
- type
- Organization
- Project
- Component
- API
- Build
- Deployment
- Environment
- Application
- Subscription
- name
- description
- handle
- branch
- commitHash
- buildpackId
- version
- context
- visibility
- status
- severity
- businessPlan
- throttlingPolicy
- authType
- isDefault
context_file: json-ld/choreo-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/choreo/refs/heads/main/json-ld/choreo-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Choreo from Choreo.
layout: jsonld
name: Choreo Context
namespaces:
- prefix: choreo
  uri: https://wso2.com/choreo/ns#
properties:
- container: ''
  name: orgId
  type: reference
- container: ''
  name: projectId
  type: reference
- container: ''
  name: componentId
  type: reference
- container: ''
  name: buildId
  type: reference
- container: ''
  name: environmentId
  type: reference
- container: ''
  name: applicationId
  type: reference
- container: ''
  name: apiId
  type: reference
- container: ''
  name: repoUrl
  type: reference
- container: ''
  name: endpointUrl
  type: reference
- container: ''
  name: createdAt
  type: schema:DateTime
- container: ''
  name: completedAt
  type: schema:DateTime
- container: ''
  name: triggeredAt
  type: schema:DateTime
- container: ''
  name: resolvedAt
  type: schema:DateTime
property_count: 13
provider_name: Choreo
provider_slug: choreo
slug: choreo-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"choreo\": \"https://wso2.com/choreo/ns#\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"Organization\": \"choreo:Organization\",\n    \"Project\": \"choreo:Project\",\n    \"Component\": \"choreo:Component\",\n    \"API\": \"choreo:API\",\n    \"Build\": \"choreo:Build\",\n    \"Deployment\": \"choreo:Deployment\",\n    \"Environment\": \"choreo:Environment\",\n    \"Application\": \"choreo:Application\",\n    \"Subscription\": \"choreo:Subscription\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"handle\": \"choreo:handle\",\n    \"orgId\": {\n      \"@id\": \"choreo:orgId\",\n      \"@type\": \"@id\"\n    },\n    \"projectId\": {\n      \"@id\": \"choreo:projectId\",\n      \"@type\": \"@id\"\n    },\n    \"componentId\": {\n      \"@id\": \"choreo:componentId\",\n      \"@type\": \"@id\"\n    },\n    \"buildId\": {\n      \"@id\": \"choreo:buildId\",\n \
  \     \"@type\": \"@id\"\n    },\n    \"environmentId\": {\n      \"@id\": \"choreo:environmentId\",\n      \"@type\": \"@id\"\n    },\n    \"applicationId\": {\n      \"@id\": \"choreo:applicationId\",\n      \"@type\": \"@id\"\n    },\n    \"apiId\": {\n      \"@id\": \"choreo:apiId\",\n      \"@type\": \"@id\"\n    },\n    \"repoUrl\": {\n      \"@id\": \"schema:codeRepository\",\n      \"@type\": \"@id\"\n    },\n    \"branch\": \"choreo:branch\",\n    \"commitHash\": \"choreo:commitHash\",\n    \"buildpackId\": \"choreo:buildpackId\",\n    \"version\": \"schema:version\",\n    \"context\": \"choreo:contextPath\",\n    \"visibility\": \"choreo:visibility\",\n    \"status\": \"choreo:status\",\n    \"severity\": \"choreo:severity\",\n    \"businessPlan\": \"choreo:businessPlan\",\n    \"throttlingPolicy\": \"choreo:throttlingPolicy\",\n    \"endpointUrl\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"authType\": \"choreo:authType\",\n    \"isDefault\":\
  \ \"choreo:isDefault\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"completedAt\": {\n      \"@id\": \"choreo:dateCompleted\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"triggeredAt\": {\n      \"@id\": \"choreo:dateTriggered\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"resolvedAt\": {\n      \"@id\": \"choreo:dateResolved\",\n      \"@type\": \"schema:DateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/choreo/refs/heads/main/json-ld/choreo-context.jsonld
tags:
- AI Apps
- API Management
- CI/CD
- Cloud Native
- DevOps
- Developer Portal
- FinOps
- IDE
- Internal Developer Platform
- Kubernetes
- Lifecycle
- Observability
- Orchestration
- Platform Engineering
- Pro-Code API Composition
- Unified
- WSO2
- Workflows
- JSON-LD
- Linked Data
- Semantic Web
---
