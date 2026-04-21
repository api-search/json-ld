---
class_count: 6
classes:
- Integration
- Workflow
- Connector
- Analytics
- name
- description
context_file: json-ld/apifuse-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apifuse/refs/heads/main/json-ld/apifuse-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apifuse from Apifuse.
layout: jsonld
name: Apifuse Context
namespaces:
- prefix: apifuse
  uri: https://apifuse.io/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: triggerType
  type: string
- container: ''
  name: authType
  type: string
- container: ''
  name: totalTasks
  type: integer
- container: ''
  name: activeIntegrations
  type: integer
- container: ''
  name: activeUsers
  type: integer
property_count: 8
provider_name: Apifuse
provider_slug: apifuse
slug: apifuse-context
tags:
- Embedded Integrations
- Integration Platform
- Integrations
- iPaaS
- Marketplace
- SaaS
- Workflow Automation
- JSON-LD
- Linked Data
- Semantic Web
---
