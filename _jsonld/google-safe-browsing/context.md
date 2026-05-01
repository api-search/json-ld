---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google Safe Browsing API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-safe-browsing/refs/heads/main/openapi/openapi.yml
class_count: 9
classes:
- WebPage
- url
- name
- description
- potentialAction
- ActionStatusType
- threatType
- platformType
- threatEntryType
context_file: json-ld/context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-safe-browsing/refs/heads/main/json-ld/context.jsonld
description: JSON-LD context defining the semantic vocabulary for context from Google Safe Browsing.
layout: jsonld
name: context Context
namespaces:
- prefix: sb
  uri: https://safebrowsing.googleapis.com/v4/
properties:
- container: ''
  name: SecurityThreat
  type: reference
property_count: 1
provider_name: Google Safe Browsing
provider_slug: google-safe-browsing
slug: context
source_filename: context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"sb\": \"https://safebrowsing.googleapis.com/v4/\",\n    \"WebPage\": \"schema:WebPage\",\n    \"url\": \"schema:url\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"potentialAction\": \"schema:potentialAction\",\n    \"ActionStatusType\": \"schema:ActionStatusType\",\n    \"SecurityThreat\": {\n      \"@id\": \"sb:ThreatMatch\",\n      \"@type\": \"@id\"\n    },\n    \"threatType\": \"sb:threatType\",\n    \"platformType\": \"sb:platformType\",\n    \"threatEntryType\": \"sb:threatEntryType\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-safe-browsing/refs/heads/main/json-ld/context.jsonld
tags:
- Google
- Malware
- Safe Browsing
- Security
- Threats
- URLs
- JSON-LD
- Linked Data
- Semantic Web
---
