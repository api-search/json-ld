---
api_specs:
- filename: spanning-google-workspace-api-openapi.yml
  format: yaml
  label: Spanning Backup for Google Workspace API
  slug: spanning-google-workspace-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spanning/refs/heads/main/openapi/spanning-google-workspace-api-openapi.yml
class_count: 10
classes:
- User
- Export
- SharedDrive
- userKey
- email
- displayName
- exportId
- status
- driveId
- name
context_file: json-ld/spanning-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/spanning/refs/heads/main/json-ld/spanning-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Spanning from Spanning.
layout: jsonld
name: Spanning Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: spanning
  uri: https://spanning.com/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: assigned
  type: boolean
- container: ''
  name: backupStatus
  type: ''
- container: ''
  name: lastBackup
  type: dateTime
- container: ''
  name: isAdmin
  type: boolean
- container: ''
  name: isSuspended
  type: boolean
- container: ''
  name: initiatedAt
  type: dateTime
- container: ''
  name: completedAt
  type: dateTime
- container: ''
  name: downloadUrl
  type: reference
- container: ''
  name: expiresAt
  type: dateTime
- container: ''
  name: sizeBytes
  type: integer
- container: ''
  name: backupEnabled
  type: boolean
property_count: 11
provider_name: Spanning
provider_slug: spanning
slug: spanning-context
source_filename: spanning-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"spanning\": \"https://spanning.com/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"User\": \"schema:Person\",\n    \"Export\": \"spanning:Export\",\n    \"SharedDrive\": \"spanning:SharedDrive\",\n\n    \"userKey\": \"@id\",\n    \"email\": \"schema:email\",\n    \"displayName\": \"schema:name\",\n    \"assigned\": {\n      \"@id\": \"spanning:licenseAssigned\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"backupStatus\": {\n      \"@id\": \"spanning:backupStatus\"\n    },\n    \"lastBackup\": {\n      \"@id\": \"spanning:lastBackup\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"isAdmin\": {\n      \"@id\": \"spanning:isAdmin\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isSuspended\": {\n      \"@id\": \"spanning:isSuspended\",\n      \"@type\": \"xsd:boolean\"\n    },\n\n    \"exportId\": \"@id\",\n    \"status\": \"spanning:status\",\n   \
  \ \"initiatedAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"completedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"downloadUrl\": {\n      \"@id\": \"schema:contentUrl\",\n      \"@type\": \"@id\"\n    },\n    \"expiresAt\": {\n      \"@id\": \"schema:expires\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"sizeBytes\": {\n      \"@id\": \"schema:contentSize\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"driveId\": \"@id\",\n    \"name\": \"schema:name\",\n    \"backupEnabled\": {\n      \"@id\": \"spanning:backupEnabled\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/spanning/refs/heads/main/json-ld/spanning-context.jsonld
tags:
- Data Protection
- SaaS Backup
- Cloud Backup
- Microsoft 365
- Google Workspace
- Salesforce
- JSON-LD
- Linked Data
- Semantic Web
---
