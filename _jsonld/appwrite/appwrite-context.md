---
api_specs:
- filename: appwrite-openapi.yaml
  format: yaml
  label: Appwrite API
  slug: appwrite-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/appwrite/refs/heads/main/openapi/appwrite-openapi.yaml
class_count: 10
classes:
- $id
- name
- email
- phone
- emailVerification
- phoneVerification
- status
- createdAt
- updatedAt
- labels
context_file: json-ld/appwrite-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/appwrite/refs/heads/main/json-ld/appwrite-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Appwrite from Appwrite.
layout: jsonld
name: Appwrite Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: appwrite
  uri: https://appwrite.io/vocab#
properties: []
property_count: 0
provider_name: Appwrite
provider_slug: appwrite
slug: appwrite-context
source_filename: appwrite-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"appwrite\": \"https://appwrite.io/vocab#\",\n    \"$id\": \"schema:identifier\",\n    \"name\": \"schema:name\",\n    \"email\": \"schema:email\",\n    \"phone\": \"schema:telephone\",\n    \"emailVerification\": \"appwrite:emailVerification\",\n    \"phoneVerification\": \"appwrite:phoneVerification\",\n    \"status\": \"appwrite:status\",\n    \"createdAt\": \"schema:dateCreated\",\n    \"updatedAt\": \"schema:dateModified\",\n    \"labels\": \"appwrite:labels\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/appwrite/refs/heads/main/json-ld/appwrite-context.jsonld
tags:
- Applications
- Backends
- Mobile
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
