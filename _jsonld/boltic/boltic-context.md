---
class_count: 36
classes:
- id
- type
- Workflow
- Table
- Pipe
- Route
- StreamEvent
- Service
- Plugin
- Consumer
- Execution
- SyncRun
- StreamSource
- name
- description
- status
- trigger
- nodes
- columns
- source
- destination
- schedule
- paths
- methods
- tags
- email
- userId
- anonymousId
- executionCount
- rowsSynced
- rowCount
- duration
- config
- properties
- frequency
- cronExpression
context_file: json-ld/boltic-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/boltic/refs/heads/main/json-ld/boltic-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Boltic from Boltic.
layout: jsonld
name: Boltic Context
namespaces:
- prefix: boltic
  uri: https://www.boltic.io/ns/
properties:
- container: ''
  name: createdAt
  type: schema:DateTime
- container: ''
  name: updatedAt
  type: schema:DateTime
- container: ''
  name: serviceId
  type: reference
- container: ''
  name: workflowId
  type: reference
- container: ''
  name: pipeId
  type: reference
- container: ''
  name: sourceId
  type: reference
- container: ''
  name: integrationId
  type: reference
- container: ''
  name: url
  type: reference
- container: ''
  name: timestamp
  type: schema:DateTime
property_count: 9
provider_name: Boltic
provider_slug: boltic
slug: boltic-context
tags:
- Automation
- DataSync
- Gateways
- NoCode
- Streaming
- Workflows
- JSON-LD
- Linked Data
- Semantic Web
---
