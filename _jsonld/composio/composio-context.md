---
api_specs:
- filename: composio-openapi-original.yml
  format: yaml
  label: Composio Tool Router API
  slug: tool-router-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/composio/refs/heads/main/openapi/composio-openapi-original.yml
- filename: composio-openapi-original.yml
  format: yaml
  label: Composio Tools API
  slug: tools-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/composio/refs/heads/main/openapi/composio-openapi-original.yml
- filename: composio-openapi-original.yml
  format: yaml
  label: Composio Connected Accounts API
  slug: connected-accounts-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/composio/refs/heads/main/openapi/composio-openapi-original.yml
- filename: composio-openapi-original.yml
  format: yaml
  label: Composio Auth Configs API
  slug: auth-configs-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/composio/refs/heads/main/openapi/composio-openapi-original.yml
- filename: composio-openapi-original.yml
  format: yaml
  label: Composio Triggers API
  slug: triggers-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/composio/refs/heads/main/openapi/composio-openapi-original.yml
- filename: composio-openapi-original.yml
  format: yaml
  label: Composio Toolkits API
  slug: toolkits-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/composio/refs/heads/main/openapi/composio-openapi-original.yml
class_count: 0
classes: []
context_file: json-ld/composio-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/composio/refs/heads/main/json-ld/composio-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Composio from Composio.
layout: jsonld
name: Composio Context
namespaces:
- prefix: composio
  uri: https://composio.dev/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Tool
  type: ''
- container: ''
  name: Toolkit
  type: ''
- container: ''
  name: ConnectedAccount
  type: ''
- container: ''
  name: AuthConfig
  type: ''
- container: ''
  name: Trigger
  type: ''
- container: ''
  name: Session
  type: ''
- container: ''
  name: ExecutionResult
  type: ''
property_count: 7
provider_name: Composio
provider_slug: composio
slug: composio-context
source_filename: composio-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"composio\": \"https://composio.dev/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Tool\": {\n      \"@id\": \"composio:Tool\",\n      \"@context\": {\n        \"id\": \"composio:toolId\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"toolkit\": \"composio:toolkit\",\n        \"parameters\": \"composio:parameters\",\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Toolkit\": {\n      \"@id\": \"composio:Toolkit\",\n      \"@context\": {\n        \"slug\": \"composio:slug\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"logo\": {\n          \"@id\": \"schema:logo\",\n          \"@type\": \"@id\"\n        },\n        \"categories\"\
  : {\n          \"@id\": \"schema:category\",\n          \"@container\": \"@set\"\n        },\n        \"authSchemes\": {\n          \"@id\": \"composio:authSchemes\",\n          \"@container\": \"@set\"\n        },\n        \"toolCount\": \"composio:toolCount\"\n      }\n    },\n\n    \"ConnectedAccount\": {\n      \"@id\": \"composio:ConnectedAccount\",\n      \"@context\": {\n        \"id\": \"composio:connectedAccountId\",\n        \"toolkit\": \"composio:toolkit\",\n        \"status\": \"composio:status\",\n        \"entityId\": \"composio:entityId\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"AuthConfig\": {\n      \"@id\": \"composio:AuthConfig\",\n      \"@context\": {\n        \"id\": \"composio:authConfigId\",\n        \"toolkit\": \"composio:toolkit\",\n        \"authScheme\": \"composio:authScheme\",\n        \"scopes\": {\n          \"@id\": \"composio:scopes\",\n          \"\
  @container\": \"@set\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Trigger\": {\n      \"@id\": \"composio:Trigger\",\n      \"@context\": {\n        \"id\": \"composio:triggerId\",\n        \"connectedAccountId\": \"composio:connectedAccountId\",\n        \"triggerName\": \"composio:triggerName\",\n        \"webhookUrl\": {\n          \"@id\": \"composio:webhookUrl\",\n          \"@type\": \"@id\"\n        },\n        \"status\": \"composio:status\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Session\": {\n      \"@id\": \"composio:Session\",\n      \"@context\": {\n        \"sessionId\": \"composio:sessionId\",\n        \"connectedAccountId\": \"composio:connectedAccountId\",\n        \"status\": \"composio:status\"\n      }\n    },\n\n    \"ExecutionResult\": {\n      \"@id\"\
  : \"composio:ExecutionResult\",\n      \"@context\": {\n        \"success\": \"composio:success\",\n        \"output\": \"composio:output\",\n        \"error\": \"composio:error\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/composio/refs/heads/main/json-ld/composio-context.jsonld
tags:
- AI Agents
- Authentication
- Integrations
- OAuth
- Tools
- Unified_API
- JSON-LD
- Linked Data
- Semantic Web
---
