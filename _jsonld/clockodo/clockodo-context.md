---
class_count: 7
classes:
- id
- name
- email
- users_id
- customers_id
- projects_id
- services_id
context_file: json-ld/clockodo-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/clockodo/refs/heads/main/json-ld/clockodo-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Clockodo from Clockodo.
layout: jsonld
name: Clockodo Context
namespaces:
- prefix: clockodo
  uri: https://my.clockodo.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Entry
  type: schema:Action
- container: ''
  name: Customer
  type: schema:Organization
- container: ''
  name: Project
  type: schema:Project
- container: ''
  name: Service
  type: schema:Service
- container: ''
  name: User
  type: schema:Person
- container: ''
  name: Absence
  type: schema:Event
- container: ''
  name: time_since
  type: dateTime
- container: ''
  name: time_until
  type: dateTime
- container: ''
  name: duration
  type: duration
- container: ''
  name: billable
  type: boolean
property_count: 10
provider_name: Clockodo
provider_slug: clockodo
slug: clockodo-context
tags:
- Absence Management
- Billing
- Project Management
- Stop Clock
- Time Tracking
- Timesheets
- JSON-LD
- Linked Data
- Semantic Web
---
