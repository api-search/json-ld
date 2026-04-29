---
api_specs:
- filename: appomni-openapi.yaml
  format: yaml
  label: AppOmni API
  slug: appomni-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/appomni/refs/heads/main/openapi/appomni-openapi.yaml
class_count: 15
classes:
- eventId
- severity
- type
- application
- description
- detectedAt
- status
- userId
- policyId
- name
- enabled
- reportId
- framework
- period
- generatedAt
context_file: json-ld/appomni-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/appomni/refs/heads/main/json-ld/appomni-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Appomni from AppOmni.
layout: jsonld
name: Appomni Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: appomni
  uri: https://www.appomni.com/vocab#
properties: []
property_count: 0
provider_name: AppOmni
provider_slug: appomni
slug: appomni-context
source_filename: appomni-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"appomni\": \"https://www.appomni.com/vocab#\",\n    \"eventId\": \"schema:identifier\",\n    \"severity\": \"appomni:severity\",\n    \"type\": \"schema:category\",\n    \"application\": \"schema:applicationCategory\",\n    \"description\": \"schema:description\",\n    \"detectedAt\": \"schema:dateCreated\",\n    \"status\": \"appomni:status\",\n    \"userId\": \"schema:identifier\",\n    \"policyId\": \"schema:identifier\",\n    \"name\": \"schema:name\",\n    \"enabled\": \"appomni:enabled\",\n    \"reportId\": \"schema:identifier\",\n    \"framework\": \"appomni:framework\",\n    \"period\": \"appomni:period\",\n    \"generatedAt\": \"schema:dateCreated\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/appomni/refs/heads/main/json-ld/appomni-context.jsonld
tags:
- SaaS Security
- Compliance
- Threat Detection
- CASB
- Zero Trust
- JSON-LD
- Linked Data
- Semantic Web
---
