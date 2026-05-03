---
api_specs:
- filename: vks-api-openapi.yml
  format: yaml
  label: VKS API
  slug: vks-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vks-integrations/refs/heads/main/openapi/vks-api-openapi.yml
class_count: 8
classes:
- WorkOrder
- Guidebook
- Operation
- ProductionRecord
- SmartForm
- Organization
- HowTo
- HowToStep
context_file: json-ld/vks-integrations-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/vks-integrations/refs/heads/main/json-ld/vks-integrations-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Vks Integrations from VKS Integrations.
layout: jsonld
name: Vks Integrations Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: vks
  uri: https://vksapp.com/vocabulary#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: ''
- container: ''
  name: work_order_number
  type: string
- container: ''
  name: guidebook_id
  type: string
- container: ''
  name: guidebook_name
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: part_number
  type: string
- container: ''
  name: expected_quantity
  type: integer
- container: ''
  name: actual_quantity
  type: integer
- container: ''
  name: assigned_worker
  type: string
- container: ''
  name: step_number
  type: integer
- container: ''
  name: worker_id
  type: string
- container: ''
  name: smart_form_data
  type: ''
- container: ''
  name: completion_time_seconds
  type: integer
- container: ''
  name: name
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: version
  type: ''
- container: ''
  name: step_count
  type: integer
- container: ''
  name: started_at
  type: dateTime
- container: ''
  name: completed_at
  type: dateTime
- container: ''
  name: recorded_at
  type: dateTime
- container: ''
  name: created_at
  type: dateTime
- container: ''
  name: updated_at
  type: dateTime
property_count: 22
provider_name: VKS Integrations
provider_slug: vks-integrations
slug: vks-integrations-context
source_filename: vks-integrations-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"vks\": \"https://vksapp.com/vocabulary#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"WorkOrder\": \"vks:WorkOrder\",\n    \"Guidebook\": \"vks:Guidebook\",\n    \"Operation\": \"vks:Operation\",\n    \"ProductionRecord\": \"vks:ProductionRecord\",\n    \"SmartForm\": \"vks:SmartForm\",\n\n    \"id\": {\"@id\": \"@id\"},\n    \"work_order_number\": {\"@id\": \"vks:workOrderNumber\", \"@type\": \"xsd:string\"},\n    \"guidebook_id\": {\"@id\": \"vks:guidebookId\", \"@type\": \"xsd:string\"},\n    \"guidebook_name\": {\"@id\": \"vks:guidebookName\", \"@type\": \"xsd:string\"},\n    \"status\": {\"@id\": \"vks:status\", \"@type\": \"xsd:string\"},\n    \"part_number\": {\"@id\": \"vks:partNumber\", \"@type\": \"xsd:string\"},\n    \"expected_quantity\": {\"@id\": \"vks:expectedQuantity\", \"@type\": \"xsd:integer\"},\n    \"actual_quantity\": {\"@id\": \"vks:actualQuantity\"\
  , \"@type\": \"xsd:integer\"},\n    \"assigned_worker\": {\"@id\": \"vks:assignedWorker\", \"@type\": \"xsd:string\"},\n\n    \"step_number\": {\"@id\": \"vks:stepNumber\", \"@type\": \"xsd:integer\"},\n    \"worker_id\": {\"@id\": \"vks:workerId\", \"@type\": \"xsd:string\"},\n    \"smart_form_data\": {\"@id\": \"vks:smartFormData\"},\n    \"completion_time_seconds\": {\"@id\": \"vks:completionTimeSeconds\", \"@type\": \"xsd:integer\"},\n\n    \"name\": {\"@id\": \"schema:name\"},\n    \"description\": {\"@id\": \"schema:description\"},\n    \"version\": {\"@id\": \"schema:version\"},\n    \"step_count\": {\"@id\": \"vks:stepCount\", \"@type\": \"xsd:integer\"},\n\n    \"started_at\": {\"@id\": \"vks:startedAt\", \"@type\": \"xsd:dateTime\"},\n    \"completed_at\": {\"@id\": \"vks:completedAt\", \"@type\": \"xsd:dateTime\"},\n    \"recorded_at\": {\"@id\": \"vks:recordedAt\", \"@type\": \"xsd:dateTime\"},\n    \"created_at\": {\"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\"\
  },\n    \"updated_at\": {\"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\"},\n\n    \"Organization\": \"schema:Organization\",\n    \"HowTo\": \"schema:HowTo\",\n    \"HowToStep\": \"schema:HowToStep\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/vks-integrations/refs/heads/main/json-ld/vks-integrations-context.jsonld
tags:
- ERP Integration
- Manufacturing
- MES
- Operations Management
- Quality Management
- Work Instructions
- Work Orders
- JSON-LD
- Linked Data
- Semantic Web
---
