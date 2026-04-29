---
class_count: 0
classes: []
context_file: json-ld/cloudhealth-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cloudhealth/refs/heads/main/json-ld/cloudhealth-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cloudhealth from CloudHealth.
layout: jsonld
name: Cloudhealth Context
namespaces:
- prefix: ch
  uri: https://cloudhealthtech.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Account
  type: ''
- container: ''
  name: Asset
  type: ''
- container: ''
  name: Perspective
  type: ''
- container: ''
  name: Report
  type: ''
- container: ''
  name: Policy
  type: ''
property_count: 5
provider_name: CloudHealth
provider_slug: cloudhealth
slug: cloudhealth-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ch\": \"https://cloudhealthtech.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Account\": {\n      \"@id\": \"ch:Account\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"vendor\": \"ch:cloudVendor\",\n        \"ownerId\": \"ch:ownerId\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Asset\": {\n      \"@id\": \"ch:Asset\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"type\": \"ch:assetType\",\n        \"accountId\": \"ch:accountId\",\n        \"region\": \"ch:region\",\n        \"tags\": \"ch:tags\"\n      }\n    },\n\n    \"Perspective\": {\n      \"@id\": \"ch:Perspective\",\n      \"\
  @context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"active\": \"ch:active\",\n        \"groups\": \"ch:groups\",\n        \"rules\": \"ch:rules\"\n      }\n    },\n\n    \"Report\": {\n      \"@id\": \"ch:Report\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"type\": \"ch:reportType\",\n        \"interval\": \"ch:interval\",\n        \"dimensions\": \"ch:dimensions\",\n        \"measures\": \"ch:measures\"\n      }\n    },\n\n    \"Policy\": {\n      \"@id\": \"ch:Policy\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"ruleType\": \"ch:ruleType\",\n        \"active\": \"ch:active\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cloudhealth/refs/heads/main/json-ld/cloudhealth-context.jsonld
tags:
- Cloud Cost
- Cloud Governance
- Cloud Management
- Cost Optimization
- FinOps
- Multi-Cloud
- JSON-LD
- Linked Data
- Semantic Web
---
