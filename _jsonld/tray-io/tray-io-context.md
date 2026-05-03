---
api_specs:
- filename: tray-io-platform-api-openapi.yml
  format: yaml
  label: Tray.io Platform API
  slug: tray-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tray-io/refs/heads/main/openapi/tray-io-platform-api-openapi.yml
class_count: 30
classes:
- id
- type
- Connector
- ConnectorVersion
- Operation
- Authentication
- Trigger
- Subscription
- User
- Workspace
- Project
- name
- title
- description
- email
- icon
- version
- createdAt
- role
- status
- connectorName
- connectorVersion
- triggerName
- authId
- serviceEnvironmentId
- inputSchema
- outputSchema
- scopes
- operations
- isLatest
context_file: json-ld/tray-io-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tray-io/refs/heads/main/json-ld/tray-io-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tray Io from Tray.io.
layout: jsonld
name: Tray Io Context
namespaces:
- prefix: trayio
  uri: https://tray.io/ns/
properties: []
property_count: 0
provider_name: Tray.io
provider_slug: tray-io
slug: tray-io-context
source_filename: tray-io-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"trayio\": \"https://tray.io/ns/\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"Connector\": \"trayio:Connector\",\n    \"ConnectorVersion\": \"trayio:ConnectorVersion\",\n    \"Operation\": \"trayio:Operation\",\n    \"Authentication\": \"trayio:Authentication\",\n    \"Trigger\": \"trayio:Trigger\",\n    \"Subscription\": \"trayio:Subscription\",\n    \"User\": \"trayio:User\",\n    \"Workspace\": \"trayio:Workspace\",\n    \"Project\": \"trayio:Project\",\n    \"name\": \"schema:name\",\n    \"title\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"email\": \"schema:email\",\n    \"icon\": \"schema:image\",\n    \"version\": \"schema:version\",\n    \"createdAt\": \"schema:dateCreated\",\n    \"role\": \"trayio:role\",\n    \"status\": \"trayio:status\",\n    \"connectorName\": \"trayio:connectorName\",\n    \"connectorVersion\": \"trayio:connectorVersion\",\n    \"triggerName\"\
  : \"trayio:triggerName\",\n    \"authId\": \"trayio:authId\",\n    \"serviceEnvironmentId\": \"trayio:serviceEnvironmentId\",\n    \"inputSchema\": \"trayio:inputSchema\",\n    \"outputSchema\": \"trayio:outputSchema\",\n    \"scopes\": \"trayio:scopes\",\n    \"operations\": \"trayio:operations\",\n    \"isLatest\": \"trayio:isLatest\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tray-io/refs/heads/main/json-ld/tray-io-context.jsonld
tags:
- AI Agents
- API Aggregation
- Automation
- Connectors
- Integration
- iPaaS
- Workflow Automation
- JSON-LD
- Linked Data
- Semantic Web
---
