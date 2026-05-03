---
api_specs:
- filename: stellar-cyber-openapi.yml
  format: yaml
  label: Stellar Cyber Open XDR API
  slug: stellar-cyber
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stellar-cyber/refs/heads/main/openapi/stellar-cyber-openapi.yml
class_count: 23
classes:
- id
- name
- description
- status
- priority
- severity
- assignee
- tenant_id
- created_at
- updated_at
- alert_count
- source
- tags
- entries
- trigger
- actions
- enabled
- ip_address
- version
- last_seen
- checkpoint
- type
- config
context_file: json-ld/stellar-cyber-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/stellar-cyber/refs/heads/main/json-ld/stellar-cyber-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Stellar Cyber from Stellar Cyber.
layout: jsonld
name: Stellar Cyber Context
namespaces:
- prefix: xdr
  uri: https://stellarcyber.ai/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: security
  uri: https://w3c.github.io/security-vocab#
properties:
- container: ''
  name: Case
  type: reference
- container: ''
  name: Alert
  type: reference
- container: ''
  name: Sensor
  type: reference
- container: ''
  name: Tenant
  type: reference
- container: ''
  name: Connector
  type: reference
- container: ''
  name: Watchlist
  type: reference
- container: ''
  name: Playbook
  type: reference
property_count: 7
provider_name: Stellar Cyber
provider_slug: stellar-cyber
slug: stellar-cyber-context
source_filename: stellar-cyber-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xdr\": \"https://stellarcyber.ai/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"security\": \"https://w3c.github.io/security-vocab#\",\n    \"Case\": {\n      \"@id\": \"xdr:Case\",\n      \"@type\": \"@id\"\n    },\n    \"Alert\": {\n      \"@id\": \"xdr:Alert\",\n      \"@type\": \"@id\"\n    },\n    \"Sensor\": {\n      \"@id\": \"xdr:Sensor\",\n      \"@type\": \"@id\"\n    },\n    \"Tenant\": {\n      \"@id\": \"xdr:Tenant\",\n      \"@type\": \"@id\"\n    },\n    \"Connector\": {\n      \"@id\": \"xdr:Connector\",\n      \"@type\": \"@id\"\n    },\n    \"Watchlist\": {\n      \"@id\": \"xdr:Watchlist\",\n      \"@type\": \"@id\"\n    },\n    \"Playbook\": {\n      \"@id\": \"xdr:Playbook\",\n      \"@type\": \"@id\"\n    },\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"status\": \"xdr:status\",\n    \"priority\": \"xdr:priority\",\n    \"severity\"\
  : \"xdr:severity\",\n    \"assignee\": \"xdr:assignee\",\n    \"tenant_id\": \"xdr:tenantId\",\n    \"created_at\": \"schema:dateCreated\",\n    \"updated_at\": \"schema:dateModified\",\n    \"alert_count\": \"xdr:alertCount\",\n    \"source\": \"xdr:source\",\n    \"tags\": \"schema:keywords\",\n    \"entries\": \"xdr:entries\",\n    \"trigger\": \"xdr:trigger\",\n    \"actions\": \"xdr:actions\",\n    \"enabled\": \"schema:enabled\",\n    \"ip_address\": \"schema:ipAddress\",\n    \"version\": \"schema:softwareVersion\",\n    \"last_seen\": \"xdr:lastSeen\",\n    \"checkpoint\": \"xdr:checkpoint\",\n    \"type\": \"schema:additionalType\",\n    \"config\": \"xdr:config\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/stellar-cyber/refs/heads/main/json-ld/stellar-cyber-context.jsonld
tags:
- Cybersecurity
- Security
- XDR
- SIEM
- SOAR
- AI
- JSON-LD
- Linked Data
- Semantic Web
---
