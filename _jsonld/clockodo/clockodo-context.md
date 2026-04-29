---
api_specs:
- filename: clockodo-openapi.yml
  format: yaml
  label: Clockodo API
  slug: clockodo-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/clockodo/refs/heads/main/openapi/clockodo-openapi.yml
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
source_filename: clockodo-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"clockodo\": \"https://my.clockodo.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Entry\": {\n      \"@id\": \"clockodo:Entry\",\n      \"@type\": \"schema:Action\"\n    },\n    \"Customer\": {\n      \"@id\": \"clockodo:Customer\",\n      \"@type\": \"schema:Organization\"\n    },\n    \"Project\": {\n      \"@id\": \"clockodo:Project\",\n      \"@type\": \"schema:Project\"\n    },\n    \"Service\": {\n      \"@id\": \"clockodo:Service\",\n      \"@type\": \"schema:Service\"\n    },\n    \"User\": {\n      \"@id\": \"clockodo:User\",\n      \"@type\": \"schema:Person\"\n    },\n    \"Absence\": {\n      \"@id\": \"clockodo:Absence\",\n      \"@type\": \"schema:Event\"\n    },\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"email\": \"schema:email\",\n    \"time_since\": {\n      \"@id\": \"schema:startTime\",\n      \"@type\": \"xsd:dateTime\"\
  \n    },\n    \"time_until\": {\n      \"@id\": \"schema:endTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"duration\": {\n      \"@id\": \"schema:duration\",\n      \"@type\": \"xsd:duration\"\n    },\n    \"billable\": {\n      \"@id\": \"clockodo:billable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"users_id\": \"clockodo:userId\",\n    \"customers_id\": \"clockodo:customerId\",\n    \"projects_id\": \"clockodo:projectId\",\n    \"services_id\": \"clockodo:serviceId\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/clockodo/refs/heads/main/json-ld/clockodo-context.jsonld
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
