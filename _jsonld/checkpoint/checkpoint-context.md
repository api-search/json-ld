---
api_specs:
- filename: checkpoint-management-api-openapi.yml
  format: yaml
  label: Check Point Management API
  slug: management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/checkpoint/refs/heads/main/openapi/checkpoint-management-api-openapi.yml
- filename: checkpoint-gaia-api-openapi.yml
  format: yaml
  label: Check Point Gaia API
  slug: gaia-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/checkpoint/refs/heads/main/openapi/checkpoint-gaia-api-openapi.yml
- filename: checkpoint-cloudguard-api-openapi.yml
  format: yaml
  label: Check Point CloudGuard API
  slug: cloudguard-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/checkpoint/refs/heads/main/openapi/checkpoint-cloudguard-api-openapi.yml
- filename: checkpoint-identity-awareness-api-openapi.yml
  format: yaml
  label: Check Point Identity Awareness API
  slug: identity-awareness-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/checkpoint/refs/heads/main/openapi/checkpoint-identity-awareness-api-openapi.yml
- filename: checkpoint-harmony-email-api-openapi.yml
  format: yaml
  label: Check Point Harmony Email API
  slug: harmony-email-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/checkpoint/refs/heads/main/openapi/checkpoint-harmony-email-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/checkpoint-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/checkpoint/refs/heads/main/json-ld/checkpoint-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Checkpoint from Check Point.
layout: jsonld
name: Checkpoint Context
namespaces:
- prefix: checkpoint
  uri: https://www.checkpoint.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Host
  type: ''
- container: ''
  name: AccessRule
  type: ''
- container: ''
  name: PolicyPackage
  type: ''
- container: ''
  name: CloudAccount
  type: ''
- container: ''
  name: ComplianceFinding
  type: ''
- container: ''
  name: IdentitySession
  type: ''
property_count: 6
provider_name: Check Point
provider_slug: checkpoint
slug: checkpoint-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"checkpoint\": \"https://www.checkpoint.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Host\": {\n      \"@id\": \"checkpoint:Host\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"ipAddress\": \"checkpoint:ipAddress\",\n        \"comments\": \"schema:description\"\n      }\n    },\n\n    \"AccessRule\": {\n      \"@id\": \"checkpoint:AccessRule\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"source\": \"checkpoint:source\",\n        \"destination\": \"checkpoint:destination\",\n        \"service\": \"checkpoint:service\",\n        \"action\": \"checkpoint:action\",\n        \"enabled\": {\n          \"@id\": \"checkpoint:enabled\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"PolicyPackage\": {\n      \"@id\": \"checkpoint:PolicyPackage\"\
  ,\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"uid\": \"checkpoint:uid\",\n        \"type\": \"checkpoint:type\"\n      }\n    },\n\n    \"CloudAccount\": {\n      \"@id\": \"checkpoint:CloudAccount\",\n      \"@context\": {\n        \"id\": \"checkpoint:id\",\n        \"name\": \"schema:name\",\n        \"vendor\": \"checkpoint:vendor\",\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ComplianceFinding\": {\n      \"@id\": \"checkpoint:ComplianceFinding\",\n      \"@context\": {\n        \"id\": \"checkpoint:findingId\",\n        \"severity\": \"checkpoint:severity\",\n        \"ruleName\": \"checkpoint:ruleName\",\n        \"status\": \"checkpoint:status\"\n      }\n    },\n\n    \"IdentitySession\": {\n      \"@id\": \"checkpoint:IdentitySession\",\n      \"@context\": {\n        \"ipAddress\": \"checkpoint:ipAddress\",\n        \"user\": \"schema:identifier\",\n\
  \        \"machine\": \"checkpoint:machine\",\n        \"sessionTimeout\": {\n          \"@id\": \"checkpoint:sessionTimeout\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/checkpoint/refs/heads/main/json-ld/checkpoint-context.jsonld
tags:
- Cloud Security
- Cybersecurity
- Endpoint Security
- Firewall
- Identity Awareness
- Mobile Security
- Network Security
- Security
- Threat Prevention
- WAF
- JSON-LD
- Linked Data
- Semantic Web
---
