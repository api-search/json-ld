---
api_specs:
- filename: cloudally-openapi.yml
  format: yaml
  label: CloudAlly API
  slug: cloudally-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cloudally/refs/heads/main/openapi/cloudally-openapi.yml
class_count: 4
classes:
- id
- name
- type
- status
context_file: json-ld/cloudally-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cloudally/refs/heads/main/json-ld/cloudally-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cloudally from CloudAlly.
layout: jsonld
name: Cloudally Context
namespaces:
- prefix: cloudally
  uri: https://api.cloudally.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: BackupTask
  type: schema:Action
- container: ''
  name: RestoreJob
  type: schema:Action
- container: ''
  name: Partner
  type: schema:Organization
- container: ''
  name: Reseller
  type: schema:Organization
- container: ''
  name: User
  type: schema:Person
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: lastBackup
  type: dateTime
- container: ''
  name: size
  type: integer
property_count: 8
provider_name: CloudAlly
provider_slug: cloudally
slug: cloudally-context
source_filename: cloudally-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cloudally\": \"https://api.cloudally.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"BackupTask\": {\n      \"@id\": \"cloudally:BackupTask\",\n      \"@type\": \"schema:Action\"\n    },\n    \"RestoreJob\": {\n      \"@id\": \"cloudally:RestoreJob\",\n      \"@type\": \"schema:Action\"\n    },\n    \"Partner\": {\n      \"@id\": \"cloudally:Partner\",\n      \"@type\": \"schema:Organization\"\n    },\n    \"Reseller\": {\n      \"@id\": \"cloudally:Reseller\",\n      \"@type\": \"schema:Organization\"\n    },\n    \"User\": {\n      \"@id\": \"cloudally:User\",\n      \"@type\": \"schema:Person\"\n    },\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"type\": \"cloudally:taskType\",\n    \"status\": \"schema:actionStatus\",\n    \"createdAt\": {\"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\"},\n    \"lastBackup\": {\"@id\"\
  : \"cloudally:lastBackup\", \"@type\": \"xsd:dateTime\"},\n    \"size\": {\"@id\": \"schema:contentSize\", \"@type\": \"xsd:integer\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cloudally/refs/heads/main/json-ld/cloudally-context.jsonld
tags:
- Backup
- Box
- Data Protection
- Disaster Recovery
- Dropbox
- Google Workspace
- Microsoft 365
- OpenText
- SaaS Backup
- Salesforce
- JSON-LD
- Linked Data
- Semantic Web
---
