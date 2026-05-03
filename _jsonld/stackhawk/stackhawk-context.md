---
api_specs:
- filename: stackhawk-openapi.json
  format: json
  label: StackHawk API
  slug: stackhawk-api
  spec_type: OpenAPI
  url: https://download.stackhawk.com/openapi/stackhawk-openapi.json
class_count: 9
classes:
- scanId
- findingId
- appId
- envId
- orgId
- severity
- name
- description
- status
context_file: json-ld/stackhawk-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/stackhawk/refs/heads/main/json-ld/stackhawk-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Stackhawk from StackHawk.
layout: jsonld
name: Stackhawk Context
namespaces:
- prefix: stackhawk
  uri: https://api.stackhawk.com/schema/
properties:
- container: ''
  name: Scan
  type: reference
- container: ''
  name: Finding
  type: reference
- container: ''
  name: Application
  type: reference
- container: ''
  name: ScanPolicy
  type: reference
property_count: 4
provider_name: StackHawk
provider_slug: stackhawk
slug: stackhawk-context
source_filename: stackhawk-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"stackhawk\": \"https://api.stackhawk.com/schema/\",\n    \"scanId\": \"stackhawk:scanIdentifier\",\n    \"findingId\": \"stackhawk:findingIdentifier\",\n    \"appId\": \"stackhawk:applicationIdentifier\",\n    \"envId\": \"stackhawk:environmentIdentifier\",\n    \"orgId\": \"stackhawk:organizationIdentifier\",\n    \"severity\": \"stackhawk:severity\",\n    \"Scan\": {\n      \"@id\": \"stackhawk:Scan\",\n      \"@type\": \"@id\"\n    },\n    \"Finding\": {\n      \"@id\": \"stackhawk:SecurityFinding\",\n      \"@type\": \"@id\"\n    },\n    \"Application\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"@type\": \"@id\"\n    },\n    \"ScanPolicy\": {\n      \"@id\": \"stackhawk:SecurityPolicy\",\n      \"@type\": \"@id\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"status\": \"stackhawk:status\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/stackhawk/refs/heads/main/json-ld/stackhawk-context.jsonld
tags:
- API Security
- Application Security
- DAST
- Security Testing
- Vulnerability Management
- JSON-LD
- Linked Data
- Semantic Web
---
