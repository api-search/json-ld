---
api_specs:
- filename: theneo-api-openapi.yml
  format: yaml
  label: Theneo
  slug: theneo
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/theneo/refs/heads/main/openapi/theneo-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/theneo-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/theneo/refs/heads/main/json-ld/theneo-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Theneo from Theneo.
layout: jsonld
name: Theneo Context
namespaces:
- prefix: theneo
  uri: https://www.theneo.io/docs/
properties:
- container: ''
  name: Project
  type: ''
- container: ''
  name: Workspace
  type: ''
- container: ''
  name: ProjectUser
  type: ''
property_count: 3
provider_name: Theneo
provider_slug: theneo
slug: theneo-context
source_filename: theneo-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"theneo\": \"https://www.theneo.io/docs/\",\n    \"Project\": {\n      \"@id\": \"theneo:project\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"slug\": \"https://schema.org/alternateName\",\n        \"workspaceId\": {\n          \"@id\": \"theneo:workspace\",\n          \"@type\": \"@id\"\n        },\n        \"description\": \"https://schema.org/description\",\n        \"published\": \"https://schema.org/status\",\n        \"createdAt\": \"https://schema.org/dateCreated\",\n        \"updatedAt\": \"https://schema.org/dateModified\"\n      }\n    },\n    \"Workspace\": {\n      \"@id\": \"theneo:workspace\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"slug\": \"https://schema.org/alternateName\"\n      }\n    },\n    \"ProjectUser\"\
  : {\n      \"@id\": \"theneo:project-user\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"email\": \"https://schema.org/email\",\n        \"role\": \"https://schema.org/roleName\",\n        \"name\": \"https://schema.org/name\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/theneo/refs/heads/main/json-ld/theneo-context.jsonld
tags:
- API Documentation
- Developer Tools
- Documentation Platform
- AI
- Platform
- JSON-LD
- Linked Data
- Semantic Web
---
