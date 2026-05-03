---
api_specs:
- filename: squillo-platform-openapi.yml
  format: yaml
  label: Squillo Platform API
  slug: squillo-platform
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/squillo/refs/heads/main/openapi/squillo-platform-openapi.yml
class_count: 17
classes:
- Workflow
- WorkflowStep
- Execution
- Connector
- Connection
- id
- name
- description
- status
- tags
- trigger
- triggeredBy
- action
- inputMapping
- outputMapping
- category
- logoUrl
context_file: json-ld/squillo-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/squillo/refs/heads/main/json-ld/squillo-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Squillo from Squillo.
layout: jsonld
name: Squillo Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: squillo
  uri: https://squillo.io/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: startedAt
  type: dateTime
- container: ''
  name: completedAt
  type: dateTime
- container: list
  name: steps
  type: ''
- container: ''
  name: connectorId
  type: reference
- container: ''
  name: workflowId
  type: reference
property_count: 7
provider_name: Squillo
provider_slug: squillo
slug: squillo-context
source_filename: squillo-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"squillo\": \"https://squillo.io/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Workflow\": \"schema:Action\",\n    \"WorkflowStep\": \"schema:Action\",\n    \"Execution\": \"schema:Action\",\n    \"Connector\": \"schema:SoftwareApplication\",\n    \"Connection\": \"schema:ListItem\",\n\n    \"id\": \"schema:identifier\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"status\": \"schema:status\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"startedAt\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"completedAt\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"tags\":\
  \ \"schema:keywords\",\n    \"steps\": {\n      \"@id\": \"squillo:hasStep\",\n      \"@container\": \"@list\"\n    },\n    \"trigger\": \"squillo:hasTrigger\",\n    \"triggeredBy\": \"squillo:triggeredBy\",\n    \"connectorId\": {\n      \"@id\": \"squillo:usesConnector\",\n      \"@type\": \"@id\"\n    },\n    \"action\": \"squillo:performs\",\n    \"inputMapping\": \"squillo:inputMapping\",\n    \"outputMapping\": \"squillo:outputMapping\",\n    \"workflowId\": {\n      \"@id\": \"squillo:fromWorkflow\",\n      \"@type\": \"@id\"\n    },\n    \"category\": \"schema:category\",\n    \"logoUrl\": \"schema:logo\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/squillo/refs/heads/main/json-ld/squillo-context.jsonld
tags:
- Integration Platform
- Automation
- Workflow
- No-Code
- IT Process Automation
- Software As A Utility
- JSON-LD
- Linked Data
- Semantic Web
---
