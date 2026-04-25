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
