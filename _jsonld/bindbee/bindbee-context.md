---
class_count: 10
classes:
- id
- first_name
- last_name
- email
- department
- start_date
- name
- status
- end_date
- created_at
context_file: json-ld/bindbee-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/bindbee/refs/heads/main/json-ld/bindbee-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Bindbee from Bindbee.
layout: jsonld
name: Bindbee Context
namespaces:
- prefix: bb
  uri: https://bindbee.dev/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: job_title
  type: string
- container: ''
  name: employment_status
  type: string
- container: ''
  name: data
  type: string
- container: ''
  name: next_cursor
  type: string
- container: ''
  name: has_more
  type: boolean
- container: ''
  name: parent_id
  type: string
- container: ''
  name: employee_id
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: job_id
  type: string
- container: ''
  name: stage
  type: string
property_count: 12
provider_name: Bindbee
provider_slug: bindbee
slug: bindbee-context
tags:
- ATS
- HR Integration
- HRIS
- Workforce
- JSON-LD
- Linked Data
- Semantic Web
---
