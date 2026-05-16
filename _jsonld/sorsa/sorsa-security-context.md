---
api_specs:
- filename: sorsa-openapi.yml
  format: yaml
  label: Sorsa API v3
  slug: sorsa-api-v3
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sorsa/refs/heads/main/openapi/sorsa-openapi.yml
class_count: 8
classes:
- ApiKey
- in
- header
- RateLimit
- requestsPerSecond
- monthlyQuota
- remaining
- expires_at
context_file: json-ld/sorsa-security-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sorsa/refs/heads/main/json-ld/sorsa-security-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sorsa Security from Sorsa.
layout: jsonld
name: Sorsa Security Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: sorsa
  uri: https://api.sorsa.io/v3/vocab#
properties: []
property_count: 0
provider_name: Sorsa
provider_slug: sorsa
slug: sorsa-security-context
source_filename: sorsa-security-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"sorsa\": \"https://api.sorsa.io/v3/vocab#\",\n    \"ApiKey\": \"sorsa:ApiKeyAuth\",\n    \"in\": \"sorsa:credentialLocation\",\n    \"header\": \"sorsa:HttpHeader\",\n    \"RateLimit\": \"sorsa:RateLimit\",\n    \"requestsPerSecond\": \"sorsa:requestsPerSecond\",\n    \"monthlyQuota\": \"sorsa:monthlyQuota\",\n    \"remaining\": \"sorsa:quotaRemaining\",\n    \"expires_at\": \"schema:expires\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sorsa/refs/heads/main/json-ld/sorsa-security-context.jsonld
tags:
- Twitter
- X
- Social Media
- Data Extraction
- Real-Time
- JSON-LD
- Linked Data
- Semantic Web
---
