---
api_specs:
- filename: pandium-pandium-openapi.yml
  format: yaml
  label: Pandium
  slug: pandium
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/pandium/refs/heads/main/openapi/pandium-pandium-openapi.yml
class_count: 0
classes: []
context_file: json-ld/pandium-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/pandium/refs/heads/main/json-ld/pandium-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Pandium from Pandium.
layout: jsonld
name: Pandium Context
namespaces:
- prefix: pandium
  uri: https://docs.pandium.com/reference/
properties:
- container: ''
  name: Integration
  type: ''
- container: ''
  name: Tenant
  type: ''
- container: ''
  name: Run
  type: ''
- container: ''
  name: Release
  type: ''
property_count: 4
provider_name: Pandium
provider_slug: pandium
slug: pandium-context
source_filename: pandium-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"pandium\": \"https://docs.pandium.com/reference/\",\n    \"Integration\": {\n      \"@id\": \"pandium:pandium-api\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"archived\": \"https://schema.org/isAccessibleForFree\",\n        \"created_date\": \"https://schema.org/dateCreated\",\n        \"modified_date\": \"https://schema.org/dateModified\"\n      }\n    },\n    \"Tenant\": {\n      \"@id\": \"pandium:pandium-api\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"archived\": \"https://schema.org/isAccessibleForFree\",\n        \"integration_id\": {\n          \"@id\": \"pandium:pandium-api\",\n          \"@type\": \"@id\"\n        },\n        \"configs\": \"https://schema.org/propertyValue\",\n        \"created_date\": \"https://schema.org/dateCreated\"\
  ,\n        \"modified_date\": \"https://schema.org/dateModified\",\n        \"paused\": \"https://schema.org/status\",\n        \"user_schedule\": \"https://schema.org/repeatFrequency\",\n        \"schedule\": \"https://schema.org/repeatFrequency\",\n        \"source\": \"https://schema.org/source\",\n        \"integration_release_id\": {\n          \"@id\": \"pandium:pandium-api\",\n          \"@type\": \"@id\"\n        },\n        \"integration_release_channel\": \"https://schema.org/category\",\n        \"status\": \"https://schema.org/status\"\n      }\n    },\n    \"Run\": {\n      \"@id\": \"pandium:pandium-api\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"tenant_id\": {\n          \"@id\": \"pandium:pandium-api\",\n          \"@type\": \"@id\"\n        },\n        \"trigger_id\": \"https://schema.org/identifier\",\n        \"status\": \"https://schema.org/status\",\n        \"mode\": \"https://schema.org/category\",\n        \"created_date\"\
  : \"https://schema.org/dateCreated\",\n        \"modified_date\": \"https://schema.org/dateModified\",\n        \"started_date\": \"https://schema.org/startDate\",\n        \"completed_date\": \"https://schema.org/endDate\"\n      }\n    },\n    \"Release\": {\n      \"@id\": \"pandium:pandium-api\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"integration_id\": {\n          \"@id\": \"pandium:pandium-api\",\n          \"@type\": \"@id\"\n        },\n        \"version\": \"https://schema.org/softwareVersion\",\n        \"created_date\": \"https://schema.org/dateCreated\",\n        \"modified_date\": \"https://schema.org/dateModified\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/pandium/refs/heads/main/json-ld/pandium-context.jsonld
tags:
- B2B
- Hubs
- Integrations
- Workflows
- JSON-LD
- Linked Data
- Semantic Web
---
