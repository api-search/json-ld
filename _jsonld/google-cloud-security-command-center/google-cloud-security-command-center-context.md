---
api_specs:
- filename: security-command-center-api-openapi.yml
  format: yaml
  label: Security Command Center API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-security-command-center/refs/heads/main/openapi/security-command-center-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/google-cloud-security-command-center-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-security-command-center/refs/heads/main/json-ld/google-cloud-security-command-center-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Cloud Security Command Center from Google Cloud Security Command Center.
layout: jsonld
name: Google Cloud Security Command Center Context
namespaces:
- prefix: scc
  uri: https://cloud.google.com/security-command-center/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Finding
  type: ''
- container: ''
  name: Source
  type: ''
- container: ''
  name: Asset
  type: ''
- container: ''
  name: NotificationConfig
  type: ''
property_count: 4
provider_name: Google Cloud Security Command Center
provider_slug: google-cloud-security-command-center
slug: google-cloud-security-command-center-context
source_filename: google-cloud-security-command-center-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"scc\": \"https://cloud.google.com/security-command-center/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Finding\": {\n      \"@id\": \"scc:Finding\",\n      \"@context\": {\n        \"name\": \"scc:findingName\",\n        \"parent\": \"scc:parent\",\n        \"state\": \"scc:state\",\n        \"category\": \"scc:category\",\n        \"resourceName\": \"scc:resourceName\",\n        \"severity\": \"scc:severity\",\n        \"externalUri\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"eventTime\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Source\": {\n      \"@id\": \"scc:Source\"\
  ,\n      \"@context\": {\n        \"name\": \"scc:sourceName\",\n        \"displayName\": \"schema:name\",\n        \"description\": \"schema:description\"\n      }\n    },\n\n    \"Asset\": {\n      \"@id\": \"scc:Asset\",\n      \"@context\": {\n        \"name\": \"scc:assetName\",\n        \"resourceProperties\": \"scc:resourceProperties\",\n        \"securityCenterProperties\": \"scc:securityCenterProperties\",\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"NotificationConfig\": {\n      \"@id\": \"scc:NotificationConfig\",\n      \"@context\": {\n        \"name\": \"scc:configName\",\n        \"description\": \"schema:description\",\n        \"pubsubTopic\": \"scc:pubsubTopic\",\n        \"streamingConfig\": \"scc:streamingConfig\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-security-command-center/refs/heads/main/json-ld/google-cloud-security-command-center-context.jsonld
tags:
- Cloud Security
- Compliance
- Risk Management
- Security
- Threat Detection
- Vulnerability Management
- JSON-LD
- Linked Data
- Semantic Web
---
