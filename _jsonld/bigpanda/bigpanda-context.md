---
class_count: 6
classes:
- status
- description
- timestamp
- name
- id
- user
context_file: json-ld/bigpanda-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/bigpanda/refs/heads/main/json-ld/bigpanda-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Bigpanda from BigPanda.
layout: jsonld
name: Bigpanda Context
namespaces:
- prefix: bp
  uri: https://docs.bigpanda.io/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: app_key
  type: string
- container: ''
  name: host
  type: string
- container: ''
  name: check
  type: string
- container: ''
  name: _id
  type: string
- container: ''
  name: condition
  type: string
- container: ''
  name: environments
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: alerts_count
  type: integer
- container: ''
  name: started_at
  type: integer
- container: ''
  name: incidents
  type: string
- container: ''
  name: start
  type: integer
- container: ''
  name: end
  type: integer
- container: ''
  name: active
  type: boolean
- container: ''
  name: maintenance_plans
  type: string
- container: ''
  name: summary
  type: string
- container: ''
  name: identifier
  type: string
- container: ''
  name: hosts
  type: string
- container: ''
  name: action
  type: string
- container: ''
  name: logs
  type: string
property_count: 19
provider_name: BigPanda
provider_slug: bigpanda
slug: bigpanda-context
tags:
- Incidents
- Monitoring
- Platform
- JSON-LD
- Linked Data
- Semantic Web
---
