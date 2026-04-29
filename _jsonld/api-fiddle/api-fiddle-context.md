---
class_count: 13
classes:
- Project
- Specification
- Workspace
- name
- description
- visibility
- format
- content
- version
- status
- members
- role
- tags
context_file: json-ld/api-fiddle-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/api-fiddle/refs/heads/main/json-ld/api-fiddle-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Api Fiddle from API-Fiddle.
layout: jsonld
name: Api Fiddle Context
namespaces:
- prefix: apifiddle
  uri: https://api-fiddle.com/schemas/
properties:
- container: ''
  name: projectId
  type: reference
- container: ''
  name: workspaceId
  type: reference
- container: ''
  name: specificationId
  type: reference
- container: ''
  name: ownerId
  type: reference
- container: ''
  name: createdAt
  type: schema:DateTime
- container: ''
  name: updatedAt
  type: schema:DateTime
property_count: 6
provider_name: API-Fiddle
provider_slug: api-fiddle
slug: api-fiddle-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"apifiddle\": \"https://api-fiddle.com/schemas/\",\n    \"Project\": \"apifiddle:Project\",\n    \"Specification\": \"apifiddle:Specification\",\n    \"Workspace\": \"apifiddle:Workspace\",\n    \"projectId\": {\n      \"@id\": \"apifiddle:projectId\",\n      \"@type\": \"@id\"\n    },\n    \"workspaceId\": {\n      \"@id\": \"apifiddle:workspaceId\",\n      \"@type\": \"@id\"\n    },\n    \"specificationId\": {\n      \"@id\": \"apifiddle:specificationId\",\n      \"@type\": \"@id\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"visibility\": \"apifiddle:visibility\",\n    \"format\": \"schema:encodingFormat\",\n    \"content\": \"schema:text\",\n    \"version\": \"schema:version\",\n    \"status\": \"apifiddle:status\",\n    \"ownerId\": {\n      \"@id\": \"apifiddle:ownerId\",\n      \"@type\": \"@id\"\n    },\n    \"members\": \"apifiddle:members\",\n    \"\
  role\": \"apifiddle:role\",\n    \"tags\": \"schema:keywords\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"schema:DateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/api-fiddle/refs/heads/main/json-ld/api-fiddle-context.jsonld
tags:
- API Design
- OpenAPI
- Collaboration
- Documentation
- Platform
- JSON-LD
- Linked Data
- Semantic Web
---
