---
api_specs:
- filename: swagger.json
  format: json
  label: CloudGuard CNAPP REST API
  slug: cloudguard-cnapp-api
  spec_type: OpenAPI
  url: https://api.dome9.com/v2/swagger.json
class_count: 0
classes: []
context_file: json-ld/cloudguard-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cloudguard/refs/heads/main/json-ld/cloudguard-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cloudguard from CloudGuard.
layout: jsonld
name: Cloudguard Context
namespaces:
- prefix: cg
  uri: https://checkpoint.com/cloudguard/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: CloudAccount
  type: ''
- container: ''
  name: Ruleset
  type: ''
- container: ''
  name: Finding
  type: ''
- container: ''
  name: Assessment
  type: ''
- container: ''
  name: Alert
  type: ''
property_count: 5
provider_name: CloudGuard
provider_slug: cloudguard
slug: cloudguard-context
source_filename: cloudguard-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cg\": \"https://checkpoint.com/cloudguard/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"CloudAccount\": {\n      \"@id\": \"cg:CloudAccount\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"vendor\": \"cg:cloudVendor\",\n        \"externalAccountNumber\": \"cg:externalAccountNumber\",\n        \"organizationalUnitId\": \"cg:organizationalUnitId\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Ruleset\": {\n      \"@id\": \"cg:Ruleset\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"cloudVendor\": \"cg:cloudVendor\",\n        \"rulesCount\": \"\
  cg:rulesCount\",\n        \"language\": \"cg:language\"\n      }\n    },\n\n    \"Finding\": {\n      \"@id\": \"cg:Finding\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"severity\": \"cg:severity\",\n        \"ruleId\": \"cg:ruleId\",\n        \"ruleName\": \"schema:name\",\n        \"entityType\": \"cg:entityType\",\n        \"entityId\": \"cg:entityId\",\n        \"cloudAccountId\": \"cg:cloudAccountId\",\n        \"createdTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Assessment\": {\n      \"@id\": \"cg:Assessment\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"rulesetId\": \"cg:rulesetId\",\n        \"cloudAccountId\": \"cg:cloudAccountId\",\n        \"score\": \"cg:score\",\n        \"passed\": \"cg:passed\",\n        \"failed\": \"cg:failed\",\n        \"createdTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\
  \n        }\n      }\n    },\n\n    \"Alert\": {\n      \"@id\": \"cg:Alert\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"severity\": \"cg:severity\",\n        \"type\": \"cg:alertType\",\n        \"status\": \"cg:status\",\n        \"cloudAccountId\": \"cg:cloudAccountId\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cloudguard/refs/heads/main/json-ld/cloudguard-context.jsonld
tags:
- Check Point
- CNAPP
- Cloud Security
- Compliance
- CSPM
- CWPP
- Posture Management
- JSON-LD
- Linked Data
- Semantic Web
---
