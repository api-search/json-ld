---
api_specs:
- filename: cursor-admin-api-openapi.yml
  format: yaml
  label: Cursor Admin API
  slug: admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cursor/refs/heads/main/openapi/cursor-admin-api-openapi.yml
class_count: 25
classes:
- Member
- Team
- BillingGroup
- AuditEvent
- DailyUsage
- UserSpend
- RepoBlocklist
- id
- type
- email
- name
- role
- isRemoved
- date
- timestamp
- eventType
- userId
- userEmail
- linesAdded
- linesDeleted
- completions
- chatRequests
- modelUsage
- spendCents
- hardLimit
context_file: json-ld/cursor-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cursor/refs/heads/main/json-ld/cursor-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cursor from Cursor.
layout: jsonld
name: Cursor Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: cursor
  uri: https://raw.githubusercontent.com/api-evangelist/cursor/refs/heads/main/vocabulary/cursor-vocabulary.yml#
properties: []
property_count: 0
provider_name: Cursor
provider_slug: cursor
slug: cursor-context
source_filename: cursor-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://raw.githubusercontent.com/api-evangelist/cursor/refs/heads/main/vocabulary/cursor-vocabulary.yml#\",\n    \"schema\": \"https://schema.org/\",\n    \"cursor\": \"https://raw.githubusercontent.com/api-evangelist/cursor/refs/heads/main/vocabulary/cursor-vocabulary.yml#\",\n    \"Member\": \"cursor:Member\",\n    \"Team\": \"cursor:Team\",\n    \"BillingGroup\": \"cursor:BillingGroup\",\n    \"AuditEvent\": \"cursor:AuditEvent\",\n    \"DailyUsage\": \"cursor:DailyUsage\",\n    \"UserSpend\": \"cursor:UserSpend\",\n    \"RepoBlocklist\": \"cursor:RepoBlocklist\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"email\": \"schema:email\",\n    \"name\": \"schema:name\",\n    \"role\": \"cursor:role\",\n    \"isRemoved\": \"cursor:isRemoved\",\n    \"date\": \"schema:dateCreated\",\n    \"timestamp\": \"schema:dateCreated\",\n    \"eventType\": \"cursor:eventType\",\n    \"userId\": \"cursor:userId\",\n\
  \    \"userEmail\": \"schema:email\",\n    \"linesAdded\": \"cursor:linesAdded\",\n    \"linesDeleted\": \"cursor:linesDeleted\",\n    \"completions\": \"cursor:completions\",\n    \"chatRequests\": \"cursor:chatRequests\",\n    \"modelUsage\": \"cursor:modelUsage\",\n    \"spendCents\": \"cursor:spendCents\",\n    \"hardLimit\": \"cursor:hardLimit\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cursor/refs/heads/main/json-ld/cursor-context.jsonld
tags:
- AI
- AI Editor
- Code Generation
- Coding Assistant
- Copilot
- Developer Tools
- LLM
- Productivity
- VSCode Fork
- JSON-LD
- Linked Data
- Semantic Web
---
