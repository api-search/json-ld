---
api_specs:
- filename: spin-ai-openapi.yml
  format: yaml
  label: Spin.AI SpinOne API
  slug: spin-ai-spinone-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spin-ai/refs/heads/main/openapi/spin-ai-openapi.yml
class_count: 3
classes:
- Entity
- BackupEntity
- id
context_file: json-ld/spin-ai-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/spin-ai/refs/heads/main/json-ld/spin-ai-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Spin Ai from Spin.AI.
layout: jsonld
name: Spin Ai Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: spinai
  uri: https://spin.ai/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: external_id
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: platform
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: email
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: backup_enabled
  type: boolean
- container: ''
  name: last_backup_at
  type: dateTime
- container: ''
  name: created_at
  type: dateTime
- container: ''
  name: updated_at
  type: dateTime
property_count: 10
provider_name: Spin.AI
provider_slug: spin-ai
slug: spin-ai-context
source_filename: spin-ai-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"spinai\": \"https://spin.ai/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Entity\": \"spinai:Entity\",\n    \"BackupEntity\": \"spinai:BackupEntity\",\n\n    \"id\": \"@id\",\n    \"external_id\": {\n      \"@id\": \"spinai:externalId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"spinai:entityType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platform\": {\n      \"@id\": \"spinai:platform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"spinai:backupStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"backup_enabled\": {\n      \"@id\": \"spinai:backupEnabled\",\n      \"@type\": \"xsd:boolean\"\n   \
  \ },\n    \"last_backup_at\": {\n      \"@id\": \"spinai:lastBackupAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"created_at\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updated_at\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/spin-ai/refs/heads/main/json-ld/spin-ai-context.jsonld
tags:
- Backup
- Compliance
- Data Protection
- Ransomware
- SaaS Security
- JSON-LD
- Linked Data
- Semantic Web
---
