---
api_specs:
- filename: bindbee-api.yaml
  format: yaml
  label: Bindbee API
  slug: bindbee-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bindbee/refs/heads/main/openapi/bindbee-api.yaml
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
source_filename: bindbee-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"bb\": \"https://bindbee.dev/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"id\": \"schema:identifier\",\n    \"first_name\": \"schema:givenName\",\n    \"last_name\": \"schema:familyName\",\n    \"email\": \"schema:email\",\n    \"job_title\": {\n      \"@id\": \"bb:job_title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"department\": \"schema:department\",\n    \"employment_status\": {\n      \"@id\": \"bb:employment_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"start_date\": \"schema:startDate\",\n    \"data\": {\n      \"@id\": \"bb:data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"next_cursor\": {\n      \"@id\": \"bb:next_cursor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"has_more\": {\n      \"@id\": \"bb:has_more\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"name\": \"schema:name\",\n    \"parent_id\": {\n      \"@id\"\
  : \"bb:parent_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"employee_id\": {\n      \"@id\": \"bb:employee_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"bb:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": \"schema:status\",\n    \"end_date\": \"schema:endDate\",\n    \"title\": {\n      \"@id\": \"bb:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"bb:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"created_at\": \"schema:dateCreated\",\n    \"job_id\": {\n      \"@id\": \"bb:job_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stage\": {\n      \"@id\": \"bb:stage\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/bindbee/refs/heads/main/json-ld/bindbee-context.jsonld
tags:
- ATS
- HR Integration
- HRIS
- Workforce
- JSON-LD
- Linked Data
- Semantic Web
---
