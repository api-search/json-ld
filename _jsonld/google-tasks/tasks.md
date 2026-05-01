---
api_specs:
- filename: tasks.yml
  format: yaml
  label: Google Tasks API v1
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-tasks/refs/heads/main/openapi/tasks.yml
class_count: 9
classes:
- Task
- TaskList
- id
- title
- notes
- status
- parent
- position
- links
context_file: json-ld/tasks.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-tasks/refs/heads/main/json-ld/tasks.jsonld
description: JSON-LD context defining the semantic vocabulary for Tasks from Google Tasks.
layout: jsonld
name: Tasks Context
namespaces:
- prefix: gtasks
  uri: https://tasks.googleapis.com/tasks/v1/
properties:
- container: ''
  name: due
  type: schema:DateTime
- container: ''
  name: completed
  type: schema:DateTime
- container: ''
  name: updated
  type: schema:DateTime
- container: ''
  name: selfLink
  type: reference
property_count: 4
provider_name: Google Tasks
provider_slug: google-tasks
slug: tasks
source_filename: tasks.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gtasks\": \"https://tasks.googleapis.com/tasks/v1/\",\n    \"Task\": \"schema:Action\",\n    \"TaskList\": \"schema:ItemList\",\n    \"id\": \"schema:identifier\",\n    \"title\": \"schema:name\",\n    \"notes\": \"schema:description\",\n    \"status\": \"schema:actionStatus\",\n    \"due\": {\n      \"@id\": \"schema:scheduledTime\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"completed\": {\n      \"@id\": \"schema:endTime\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"updated\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"selfLink\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"parent\": \"schema:isPartOf\",\n    \"position\": \"schema:position\",\n    \"links\": \"schema:relatedLink\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-tasks/refs/heads/main/json-ld/tasks.jsonld
tags:
- Google
- Productivity
- Task Management
- Tasks
- Todo
- Workspace
- JSON-LD
- Linked Data
- Semantic Web
---
