---
class_count: 29
classes:
- id
- type
- Project
- Api
- Endpoint
- Schema
- Connector
- Deployment
- Test
- TestRun
- User
- Token
- name
- description
- url
- version
- status
- environment
- method
- path
- generationSource
- prompt
- requestSchema
- responseSchema
- region
- replicas
- scopes
- email
- organization
context_file: json-ld/apigen-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apigen/refs/heads/main/json-ld/apigen-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apigen from APIGen.
layout: jsonld
name: Apigen Context
namespaces:
- prefix: apigen
  uri: https://api.apigen.com/vocab#
properties:
- container: ''
  name: projectId
  type: reference
- container: ''
  name: apiId
  type: reference
- container: ''
  name: endpointId
  type: reference
- container: ''
  name: connectorId
  type: reference
- container: ''
  name: ownerId
  type: reference
- container: ''
  name: deployedBy
  type: reference
- container: ''
  name: specUrl
  type: reference
- container: ''
  name: createdAt
  type: DateTime
- container: ''
  name: updatedAt
  type: DateTime
- container: ''
  name: expiresAt
  type: DateTime
property_count: 10
provider_name: APIGen
provider_slug: apigen
slug: apigen-context
tags:
- Code
- Documentation
- Generation
- Open Source
- PHP
- JSON-LD
- Linked Data
- Semantic Web
---
