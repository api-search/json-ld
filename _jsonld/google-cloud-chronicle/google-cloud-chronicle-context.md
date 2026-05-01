---
api_specs:
- filename: chronicle-api-openapi.yml
  format: yaml
  label: Chronicle API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-chronicle/refs/heads/main/openapi/chronicle-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/google-cloud-chronicle-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-chronicle/refs/heads/main/json-ld/google-cloud-chronicle-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Cloud Chronicle from Google Cloud Chronicle.
layout: jsonld
name: Google Cloud Chronicle Context
namespaces:
- prefix: chronicle
  uri: https://cloud.google.com/chronicle/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: UDMEvent
  type: ''
- container: ''
  name: Rule
  type: ''
- container: ''
  name: Alert
  type: ''
- container: ''
  name: Feed
  type: ''
property_count: 4
provider_name: Google Cloud Chronicle
provider_slug: google-cloud-chronicle
slug: google-cloud-chronicle-context
source_filename: google-cloud-chronicle-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"chronicle\": \"https://cloud.google.com/chronicle/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"UDMEvent\": {\n      \"@id\": \"chronicle:UDMEvent\",\n      \"@context\": {\n        \"metadata\": \"chronicle:metadata\",\n        \"principal\": \"chronicle:principal\",\n        \"target\": \"chronicle:target\",\n        \"src\": \"chronicle:src\",\n        \"observer\": \"chronicle:observer\",\n        \"securityResult\": \"chronicle:securityResult\",\n        \"network\": \"chronicle:network\"\n      }\n    },\n\n    \"Rule\": {\n      \"@id\": \"chronicle:Rule\",\n      \"@context\": {\n        \"name\": \"chronicle:ruleName\",\n        \"displayName\": \"schema:name\",\n        \"text\": \"chronicle:ruleText\",\n        \"severity\": \"chronicle:severity\",\n        \"enabled\": \"chronicle:enabled\",\n     \
  \   \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Alert\": {\n      \"@id\": \"chronicle:Alert\",\n      \"@context\": {\n        \"name\": \"chronicle:alertName\",\n        \"ruleName\": \"chronicle:ruleName\",\n        \"severity\": \"chronicle:severity\",\n        \"state\": \"chronicle:alertState\",\n        \"feedback\": \"chronicle:feedback\",\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Feed\": {\n      \"@id\": \"chronicle:Feed\",\n      \"@context\": {\n        \"name\": \"chronicle:feedName\",\n        \"displayName\": \"schema:name\",\n        \"sourceType\": \"chronicle:sourceType\",\n        \"logType\": \"chronicle:logType\",\n        \"state\": \"chronicle:feedState\"\n\
  \      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-chronicle/refs/heads/main/json-ld/google-cloud-chronicle-context.jsonld
tags:
- Incident Response
- Log Management
- Security Analytics
- Security Operations
- SIEM
- Threat Detection
- JSON-LD
- Linked Data
- Semantic Web
---
