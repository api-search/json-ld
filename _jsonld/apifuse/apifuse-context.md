---
api_specs:
- filename: apifuse-api.yaml
  format: yaml
  label: Apifuse API
  slug: apifuse-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apifuse/refs/heads/main/openapi/apifuse-api.yaml
class_count: 6
classes:
- Integration
- Workflow
- Connector
- Analytics
- name
- description
context_file: json-ld/apifuse-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apifuse/refs/heads/main/json-ld/apifuse-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apifuse from Apifuse.
layout: jsonld
name: Apifuse Context
namespaces:
- prefix: apifuse
  uri: https://apifuse.io/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: triggerType
  type: string
- container: ''
  name: authType
  type: string
- container: ''
  name: totalTasks
  type: integer
- container: ''
  name: activeIntegrations
  type: integer
- container: ''
  name: activeUsers
  type: integer
property_count: 8
provider_name: Apifuse
provider_slug: apifuse
slug: apifuse-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"apifuse\": \"https://apifuse.io/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Integration\": \"apifuse:Integration\",\n    \"Workflow\": \"apifuse:Workflow\",\n    \"Connector\": \"apifuse:Connector\",\n    \"Analytics\": \"apifuse:Analytics\",\n    \"id\": {\n      \"@id\": \"dcterms:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"status\": {\n      \"@id\": \"apifuse:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"apifuse:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"triggerType\": {\n      \"@id\": \"apifuse:triggerType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authType\": {\n      \"@id\": \"apifuse:authType\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"totalTasks\": {\n      \"@id\": \"apifuse:totalTasks\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"activeIntegrations\": {\n      \"@id\": \"apifuse:activeIntegrations\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"activeUsers\": {\n      \"@id\": \"apifuse:activeUsers\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apifuse/refs/heads/main/json-ld/apifuse-context.jsonld
tags:
- Embedded Integrations
- Integration Platform
- Integrations
- iPaaS
- Marketplace
- SaaS
- Workflow Automation
- JSON-LD
- Linked Data
- Semantic Web
---
