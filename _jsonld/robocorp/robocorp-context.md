---
api_specs:
- filename: openapi.json
  format: json
  label: Robocorp Control Room API
  slug: control-room-api
  spec_type: OpenAPI
  url: https://robocorp.com/api/openapi.json
class_count: 34
classes:
- Workspace
- id
- name
- Worker
- status
- worker_group_id
- last_seen
- created_at
- WorkerGroup
- description
- worker_count
- Process
- steps
- schedules
- ProcessRun
- state
- started_at
- completed_at
- WorkItem
- process_id
- payload
- Asset
- content_type
- size
- Secret
- Webhook
- url
- events
- TaskPackage
- source_type
- source_url
- branch
- Assistant
- Automation
context_file: json-ld/robocorp-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/robocorp/refs/heads/main/json-ld/robocorp-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Robocorp from Robocorp.
layout: jsonld
name: Robocorp Context
namespaces:
- prefix: robocorp
  uri: https://api-evangelist.github.io/robocorp/vocab#
properties: []
property_count: 0
provider_name: Robocorp
provider_slug: robocorp
slug: robocorp-context
source_filename: robocorp-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"robocorp\": \"https://api-evangelist.github.io/robocorp/vocab#\",\n    \"Workspace\": \"robocorp:Workspace\",\n    \"id\": \"schema:identifier\",\n    \"name\": \"schema:name\",\n    \"Worker\": \"robocorp:Worker\",\n    \"status\": \"schema:actionStatus\",\n    \"worker_group_id\": \"robocorp:workerGroupId\",\n    \"last_seen\": \"schema:dateModified\",\n    \"created_at\": \"schema:dateCreated\",\n    \"WorkerGroup\": \"schema:Offer\",\n    \"description\": \"schema:description\",\n    \"worker_count\": \"robocorp:workerCount\",\n    \"Process\": \"schema:Action\",\n    \"steps\": \"schema:step\",\n    \"schedules\": \"schema:schedule\",\n    \"ProcessRun\": \"schema:CreateAction\",\n    \"state\": \"schema:actionStatus\",\n    \"started_at\": \"schema:startTime\",\n    \"completed_at\": \"schema:endTime\",\n    \"WorkItem\": \"robocorp:WorkItem\",\n    \"process_id\": \"robocorp:processId\",\n    \"payload\"\
  : \"schema:object\",\n    \"Asset\": \"schema:DigitalDocument\",\n    \"content_type\": \"schema:encodingFormat\",\n    \"size\": \"schema:contentSize\",\n    \"Secret\": \"robocorp:Secret\",\n    \"Webhook\": \"schema:WebhookAction\",\n    \"url\": \"schema:url\",\n    \"events\": \"schema:event\",\n    \"TaskPackage\": \"schema:SoftwareApplication\",\n    \"source_type\": \"robocorp:sourceType\",\n    \"source_url\": \"schema:url\",\n    \"branch\": \"robocorp:branch\",\n    \"Assistant\": \"schema:SoftwareApplication\",\n    \"Automation\": \"schema:Action\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/robocorp/refs/heads/main/json-ld/robocorp-context.jsonld
tags:
- RPA
- Workflow Automation
- Python
- Open Source
- Automation
- JSON-LD
- Linked Data
- Semantic Web
---
