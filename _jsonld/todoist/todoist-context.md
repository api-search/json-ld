---
api_specs:
- filename: todoist-openapi.yml
  format: yaml
  label: Todoist API
  slug: todoist-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/todoist/refs/heads/main/openapi/todoist-openapi.yml
class_count: 21
classes:
- Task
- Project
- Section
- Label
- Comment
- Workspace
- id
- content
- description
- labels
- priority
- is_completed
- comment_count
- name
- color
- is_favorite
- is_shared
- view_style
- email
- full_name
- timezone
context_file: json-ld/todoist-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/todoist/refs/heads/main/json-ld/todoist-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Todoist from Todoist.
layout: jsonld
name: Todoist Context
namespaces:
- prefix: todoist
  uri: https://developer.todoist.com/api/v1/#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: project_id
  type: reference
- container: ''
  name: created_at
  type: dateTime
- container: ''
  name: due
  type: reference
- container: ''
  name: due_date
  type: date
- container: ''
  name: assignee_id
  type: reference
- container: ''
  name: creator_id
  type: reference
- container: ''
  name: url
  type: reference
property_count: 7
provider_name: Todoist
provider_slug: todoist
slug: todoist-context
source_filename: todoist-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"todoist\": \"https://developer.todoist.com/api/v1/#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Task\": \"todoist:Task\",\n    \"Project\": \"todoist:Project\",\n    \"Section\": \"todoist:Section\",\n    \"Label\": \"todoist:Label\",\n    \"Comment\": \"todoist:Comment\",\n    \"Workspace\": \"todoist:Workspace\",\n    \"id\": \"@id\",\n    \"content\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"project_id\": {\n      \"@id\": \"schema:isPartOf\",\n      \"@type\": \"@id\"\n    },\n    \"labels\": \"schema:keywords\",\n    \"priority\": \"schema:priority\",\n    \"is_completed\": \"schema:actionStatus\",\n    \"created_at\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"due\": {\n      \"@id\": \"schema:scheduledTime\",\n      \"@type\": \"@id\"\n    },\n    \"due_date\": {\n      \"@id\": \"schema:scheduledTime\"\
  ,\n      \"@type\": \"xsd:date\"\n    },\n    \"assignee_id\": {\n      \"@id\": \"schema:agent\",\n      \"@type\": \"@id\"\n    },\n    \"creator_id\": {\n      \"@id\": \"schema:author\",\n      \"@type\": \"@id\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"comment_count\": \"schema:commentCount\",\n    \"name\": \"schema:name\",\n    \"color\": \"schema:color\",\n    \"is_favorite\": \"todoist:isFavorite\",\n    \"is_shared\": \"todoist:isShared\",\n    \"view_style\": \"todoist:viewStyle\",\n    \"email\": \"schema:email\",\n    \"full_name\": \"schema:name\",\n    \"timezone\": \"schema:containedInPlace\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/todoist/refs/heads/main/json-ld/todoist-context.jsonld
tags:
- Productivity
- Tasks
- To-Do
- Task Management
- Collaboration
- JSON-LD
- Linked Data
- Semantic Web
---
