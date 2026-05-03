---
api_specs:
- filename: tray-ai-embedded-api-openapi.yml
  format: yaml
  label: Tray.ai Embedded API
  slug: embedded-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tray-ai/refs/heads/main/openapi/tray-ai-embedded-api-openapi.yml
- filename: tray-ai-platform-api-openapi.yml
  format: yaml
  label: Tray.ai Platform API
  slug: platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tray-ai/refs/heads/main/openapi/tray-ai-platform-api-openapi.yml
class_count: 51
classes:
- id
- type
- Connector
- ConnectorVersion
- Operation
- Authentication
- Solution
- SolutionInstance
- User
- Workspace
- Subscription
- Trigger
- Project
- name
- description
- title
- email
- icon
- version
- createdAt
- created
- enabled
- owner
- externalUserId
- isTestUser
- role
- status
- connectorName
- connectorVersion
- triggerName
- triggerUrl
- authId
- serviceEnvironmentId
- solutionId
- inputSchema
- outputSchema
- scopes
- authValues
- configValues
- configSlots
- authSlots
- tags
- workflows
- operations
- service
- serviceEnvironment
- solutionVersionFlags
- hasNewerVersion
- externalId
- accessToken
- userId
context_file: json-ld/tray-ai-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tray-ai/refs/heads/main/json-ld/tray-ai-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tray Ai from Tray.ai.
layout: jsonld
name: Tray Ai Context
namespaces:
- prefix: tray
  uri: https://tray.ai/ns/
properties: []
property_count: 0
provider_name: Tray.ai
provider_slug: tray-ai
slug: tray-ai-context
source_filename: tray-ai-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"tray\": \"https://tray.ai/ns/\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"Connector\": \"tray:Connector\",\n    \"ConnectorVersion\": \"tray:ConnectorVersion\",\n    \"Operation\": \"tray:Operation\",\n    \"Authentication\": \"tray:Authentication\",\n    \"Solution\": \"tray:Solution\",\n    \"SolutionInstance\": \"tray:SolutionInstance\",\n    \"User\": \"tray:User\",\n    \"Workspace\": \"tray:Workspace\",\n    \"Subscription\": \"tray:Subscription\",\n    \"Trigger\": \"tray:Trigger\",\n    \"Project\": \"tray:Project\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"title\": \"schema:name\",\n    \"email\": \"schema:email\",\n    \"icon\": \"schema:image\",\n    \"version\": \"schema:version\",\n    \"createdAt\": \"schema:dateCreated\",\n    \"created\": \"schema:dateCreated\",\n    \"enabled\": \"tray:enabled\",\n    \"owner\": \"tray:owner\",\n \
  \   \"externalUserId\": \"tray:externalUserId\",\n    \"isTestUser\": \"tray:isTestUser\",\n    \"role\": \"tray:role\",\n    \"status\": \"tray:status\",\n    \"connectorName\": \"tray:connectorName\",\n    \"connectorVersion\": \"tray:connectorVersion\",\n    \"triggerName\": \"tray:triggerName\",\n    \"triggerUrl\": \"tray:triggerUrl\",\n    \"authId\": \"tray:authId\",\n    \"serviceEnvironmentId\": \"tray:serviceEnvironmentId\",\n    \"solutionId\": \"tray:solutionId\",\n    \"inputSchema\": \"tray:inputSchema\",\n    \"outputSchema\": \"tray:outputSchema\",\n    \"scopes\": \"tray:scopes\",\n    \"authValues\": \"tray:authValues\",\n    \"configValues\": \"tray:configValues\",\n    \"configSlots\": \"tray:configSlots\",\n    \"authSlots\": \"tray:authSlots\",\n    \"tags\": \"schema:keywords\",\n    \"workflows\": \"tray:workflows\",\n    \"operations\": \"tray:operations\",\n    \"service\": \"tray:service\",\n    \"serviceEnvironment\": \"tray:serviceEnvironment\",\n    \"solutionVersionFlags\"\
  : \"tray:solutionVersionFlags\",\n    \"hasNewerVersion\": \"tray:hasNewerVersion\",\n    \"externalId\": \"tray:externalId\",\n    \"accessToken\": \"tray:accessToken\",\n    \"userId\": \"tray:userId\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tray-ai/refs/heads/main/json-ld/tray-ai-context.jsonld
tags:
- Automation
- Integration
- iPaaS
- JSON-LD
- Linked Data
- Semantic Web
---
