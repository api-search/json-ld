---
class_count: 3
classes:
- name
- description
- email
context_file: json-ld/cflow-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cflow/refs/heads/main/json-ld/cflow-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cflow from Cflow.
layout: jsonld
name: Cflow Context
namespaces:
- prefix: cflow
  uri: https://us.cflowapps.com/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: workflowId
  type: string
- container: ''
  name: stageId
  type: string
- container: ''
  name: requestId
  type: string
- container: ''
  name: currentStage
  type: string
- container: ''
  name: submittedBy
  type: string
- container: ''
  name: fields
  type: '@json'
- container: ''
  name: stages
  type: '@json'
- container: ''
  name: reviewers
  type: '@json'
- container: ''
  name: order
  type: integer
- container: ''
  name: status
  type: string
- container: ''
  name: role
  type: string
- container: ''
  name: permissions
  type: '@json'
- container: ''
  name: username
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
property_count: 15
provider_name: Cflow
provider_slug: cflow
slug: cflow-context
tags:
- Automations
- Business Process Automation
- Integrations
- No-Code
- Platform
- Protocols
- Rules
- Workflows
- JSON-LD
- Linked Data
- Semantic Web
---
