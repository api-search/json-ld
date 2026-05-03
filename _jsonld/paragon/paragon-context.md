---
api_specs:
- filename: paragon-proxy-api-openapi.yml
  format: yaml
  label: Proxy API
  slug: proxy-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/paragon/refs/heads/main/openapi/paragon-proxy-api-openapi.yml
- filename: paragon-users-api-openapi.yml
  format: yaml
  label: Users API
  slug: users-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/paragon/refs/heads/main/openapi/paragon-users-api-openapi.yml
- filename: paragon-task-history-api-openapi.yml
  format: yaml
  label: Task History API
  slug: task-history-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/paragon/refs/heads/main/openapi/paragon-task-history-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/paragon-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/paragon/refs/heads/main/json-ld/paragon-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Paragon from Paragon.
layout: jsonld
name: Paragon Context
namespaces:
- prefix: paragon
  uri: https://docs.useparagon.com/apis/
properties:
- container: ''
  name: User
  type: ''
- container: ''
  name: UserIntegration
  type: ''
- container: ''
  name: Integration
  type: ''
- container: ''
  name: Credential
  type: ''
- container: ''
  name: WorkflowExecution
  type: ''
- container: ''
  name: ProxyRequest
  type: ''
property_count: 6
provider_name: Paragon
provider_slug: paragon
slug: paragon-context
source_filename: paragon-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"paragon\": \"https://docs.useparagon.com/apis/\",\n    \"User\": {\n      \"@id\": \"paragon:users\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"meta\": \"https://schema.org/additionalProperty\",\n        \"authenticated\": \"https://schema.org/actionStatus\",\n        \"integrations\": \"https://schema.org/hasPart\"\n      }\n    },\n    \"UserIntegration\": {\n      \"@id\": \"paragon:users#integration\",\n      \"@context\": {\n        \"enabled\": \"https://schema.org/actionStatus\",\n        \"credentialStatus\": \"https://schema.org/status\",\n        \"providerId\": \"https://schema.org/identifier\"\n      }\n    },\n    \"Integration\": {\n      \"@id\": \"paragon:users#integrations\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"type\": \"https://schema.org/category\"\
  ,\n        \"enabled\": \"https://schema.org/actionStatus\",\n        \"icon\": \"https://schema.org/image\"\n      }\n    },\n    \"Credential\": {\n      \"@id\": \"paragon:users#credentials\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"integrationId\": {\n          \"@id\": \"paragon:users#integrations\",\n          \"@type\": \"@id\"\n        },\n        \"status\": \"https://schema.org/status\"\n      }\n    },\n    \"WorkflowExecution\": {\n      \"@id\": \"paragon:task-history\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"userId\": {\n          \"@id\": \"paragon:users\",\n          \"@type\": \"@id\"\n        },\n        \"workflowId\": \"https://schema.org/identifier\",\n        \"status\": \"https://schema.org/status\",\n        \"taskCount\": \"https://schema.org/size\",\n        \"runDuration\": \"https://schema.org/duration\",\n        \"dateStarted\": \"https://schema.org/startDate\",\n\
  \        \"dateEnded\": \"https://schema.org/endDate\"\n      }\n    },\n    \"ProxyRequest\": {\n      \"@id\": \"paragon:making-api-requests\",\n      \"@context\": {\n        \"projectId\": \"https://schema.org/identifier\",\n        \"integrationType\": \"https://schema.org/category\",\n        \"integrationId\": \"https://schema.org/identifier\",\n        \"apiPath\": \"https://schema.org/urlTemplate\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/paragon/refs/heads/main/json-ld/paragon-context.jsonld
tags:
- Embedded iPaaS
- Integrations
- JSON-LD
- Linked Data
- Semantic Web
---
