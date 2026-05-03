---
api_specs:
- filename: zuplo-openapi.yml
  format: yaml
  label: Zuplo Developer API
  slug: zuplo
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zuplo/refs/heads/main/openapi/zuplo-openapi.yml
class_count: 27
classes:
- ApiKey
- Consumer
- Bucket
- Tunnel
- Deployment
- AuditLog
- Meter
- Plan
- Feature
- Variable
- id
- name
- description
- createdOn
- updatedOn
- expiresOn
- tags
- status
- url
- accountName
- bucketName
- consumerId
- projectName
- branchName
- token
- key
- sub
context_file: json-ld/zuplo-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/zuplo/refs/heads/main/json-ld/zuplo-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Zuplo from Zuplo.
layout: jsonld
name: Zuplo Context
namespaces:
- prefix: zuplo
  uri: https://zuplo.com/ontology/
properties: []
property_count: 0
provider_name: Zuplo
provider_slug: zuplo
slug: zuplo-context
source_filename: zuplo-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"zuplo\": \"https://zuplo.com/ontology/\",\n    \"ApiKey\": \"zuplo:ApiKey\",\n    \"Consumer\": \"zuplo:Consumer\",\n    \"Bucket\": \"zuplo:Bucket\",\n    \"Tunnel\": \"zuplo:Tunnel\",\n    \"Deployment\": \"zuplo:Deployment\",\n    \"AuditLog\": \"zuplo:AuditLog\",\n    \"Meter\": \"zuplo:Meter\",\n    \"Plan\": \"zuplo:Plan\",\n    \"Feature\": \"zuplo:Feature\",\n    \"Variable\": \"zuplo:Variable\",\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"createdOn\": \"schema:dateCreated\",\n    \"updatedOn\": \"schema:dateModified\",\n    \"expiresOn\": \"schema:expires\",\n    \"tags\": \"schema:keywords\",\n    \"status\": \"zuplo:status\",\n    \"url\": \"schema:url\",\n    \"accountName\": \"zuplo:accountName\",\n    \"bucketName\": \"zuplo:bucketName\",\n    \"consumerId\": \"zuplo:consumerId\",\n    \"projectName\": \"zuplo:projectName\",\n  \
  \  \"branchName\": \"zuplo:branchName\",\n    \"token\": \"zuplo:token\",\n    \"key\": \"zuplo:key\",\n    \"sub\": \"zuplo:sub\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/zuplo/refs/heads/main/json-ld/zuplo-context.jsonld
tags:
- AI Gateway
- API Management
- Gateways
- Platform
- JSON-LD
- Linked Data
- Semantic Web
---
