---
api_specs:
- filename: appsmith-openapi.yaml
  format: yaml
  label: Appsmith API
  slug: appsmith-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/appsmith/refs/heads/main/openapi/appsmith-openapi.yaml
class_count: 10
classes:
- applicationId
- name
- description
- workspaceId
- isPublic
- createdAt
- modifiedAt
- pages
- datasourceId
- type
context_file: json-ld/appsmith-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/appsmith/refs/heads/main/json-ld/appsmith-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Appsmith from Appsmith.
layout: jsonld
name: Appsmith Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: appsmith
  uri: https://www.appsmith.com/vocab#
properties: []
property_count: 0
provider_name: Appsmith
provider_slug: appsmith
slug: appsmith-context
source_filename: appsmith-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"appsmith\": \"https://www.appsmith.com/vocab#\",\n    \"applicationId\": \"schema:identifier\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"workspaceId\": \"schema:identifier\",\n    \"isPublic\": \"schema:isAccessibleForFree\",\n    \"createdAt\": \"schema:dateCreated\",\n    \"modifiedAt\": \"schema:dateModified\",\n    \"pages\": \"appsmith:pages\",\n    \"datasourceId\": \"schema:identifier\",\n    \"type\": \"schema:category\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/appsmith/refs/heads/main/json-ld/appsmith-context.jsonld
tags:
- Low-Code
- Open Source
- Internal Tools
- Workflow Automation
- Developer Tools
- JSON-LD
- Linked Data
- Semantic Web
---
