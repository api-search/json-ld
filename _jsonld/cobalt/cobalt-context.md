---
class_count: 0
classes: []
context_file: json-ld/cobalt-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cobalt/refs/heads/main/json-ld/cobalt-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cobalt from Cobalt.
layout: jsonld
name: Cobalt Context
namespaces:
- prefix: cobalt
  uri: https://api.gocobalt.io/api/v2/
properties:
- container: ''
  name: LinkedAccount
  type: ''
- container: ''
  name: Application
  type: ''
- container: ''
  name: Config
  type: ''
- container: ''
  name: Webhook
  type: ''
- container: ''
  name: Execution
  type: ''
- container: ''
  name: Workflow
  type: ''
- container: ''
  name: Datastore
  type: ''
property_count: 7
provider_name: Cobalt
provider_slug: cobalt
slug: cobalt-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"cobalt\": \"https://api.gocobalt.io/api/v2/\",\n    \"LinkedAccount\": {\n      \"@id\": \"cobalt:LinkedAccount\",\n      \"@context\": {\n        \"_id\": \"schema:identifier\",\n        \"linked_account_id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"your_app\": \"schema:additionalProperty\",\n        \"created_at\": \"schema:dateCreated\",\n        \"updated_at\": \"schema:dateModified\"\n      }\n    },\n    \"Application\": {\n      \"@id\": \"cobalt:Application\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"slug\": \"schema:identifier\",\n        \"icon\": \"schema:image\",\n        \"description\": \"schema:description\",\n        \"auth_type\": \"schema:additionalProperty\",\n        \"connected\": \"schema:status\"\n      }\n    },\n    \"Config\": {\n      \"@id\": \"cobalt:Config\",\n      \"@context\": {\n        \"_id\": \"schema:identifier\"\
  ,\n        \"slug\": \"schema:identifier\",\n        \"linked_account_id\": \"schema:identifier\",\n        \"fields\": \"schema:additionalProperty\",\n        \"workflows\": \"schema:hasPart\",\n        \"created_at\": \"schema:dateCreated\",\n        \"updated_at\": \"schema:dateModified\"\n      }\n    },\n    \"Webhook\": {\n      \"@id\": \"cobalt:Webhook\",\n      \"@context\": {\n        \"_id\": \"schema:identifier\",\n        \"webhook_url\": \"schema:url\",\n        \"webhook_events\": \"schema:additionalProperty\",\n        \"linked_account_id\": \"schema:identifier\"\n      }\n    },\n    \"Execution\": {\n      \"@id\": \"cobalt:Execution\",\n      \"@context\": {\n        \"_id\": \"schema:identifier\",\n        \"workflow_id\": \"schema:identifier\",\n        \"linked_account_id\": \"schema:identifier\",\n        \"status\": \"schema:status\",\n        \"started_at\": \"schema:startDate\",\n        \"completed_at\": \"schema:endDate\",\n        \"logs\": \"schema:additionalProperty\"\
  \n      }\n    },\n    \"Workflow\": {\n      \"@id\": \"cobalt:Workflow\",\n      \"@context\": {\n        \"_id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"nodes\": \"schema:hasPart\",\n        \"created_at\": \"schema:dateCreated\",\n        \"updated_at\": \"schema:dateModified\"\n      }\n    },\n    \"Datastore\": {\n      \"@id\": \"cobalt:Datastore\",\n      \"@context\": {\n        \"_id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"slug\": \"schema:identifier\",\n        \"config_id\": \"schema:identifier\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cobalt/refs/heads/main/json-ld/cobalt-context.jsonld
tags:
- Automation
- Embedded iPaaS
- Integrations
- JSON-LD
- Linked Data
- Semantic Web
---
