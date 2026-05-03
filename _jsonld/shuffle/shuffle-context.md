---
api_specs:
- filename: shuffle-openapi.yml
  format: yaml
  label: Shuffle API
  slug: shuffle-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/shuffle/refs/heads/main/openapi/shuffle-openapi.yml
class_count: 13
classes:
- Workflow
- Execution
- Action
- Trigger
- App
- Organization
- User
- id
- name
- description
- email
- url
- username
context_file: json-ld/shuffle-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/shuffle/refs/heads/main/json-ld/shuffle-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Shuffle from Shuffle.
layout: jsonld
name: Shuffle Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: shuffle
  uri: https://shuffler.io/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: status
  type: '@vocab'
- container: ''
  name: org_id
  type: string
- container: ''
  name: workflow_id
  type: string
- container: ''
  name: execution_id
  type: string
- container: ''
  name: created
  type: long
- container: ''
  name: edited
  type: long
- container: ''
  name: started_at
  type: long
- container: ''
  name: completed_at
  type: long
- container: list
  name: actions
  type: ''
- container: list
  name: triggers
  type: ''
- container: set
  name: tags
  type: ''
- container: ''
  name: app_name
  type: string
- container: ''
  name: app_version
  type: string
- container: ''
  name: execution_argument
  type: string
- container: ''
  name: result
  type: string
- container: list
  name: results
  type: ''
- container: ''
  name: authorization
  type: string
- container: ''
  name: role
  type: '@vocab'
property_count: 18
provider_name: Shuffle
provider_slug: shuffle
slug: shuffle-context
source_filename: shuffle-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"shuffle\": \"https://shuffler.io/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Workflow\": \"shuffle:Workflow\",\n    \"Execution\": \"shuffle:Execution\",\n    \"Action\": \"shuffle:Action\",\n    \"Trigger\": \"shuffle:Trigger\",\n    \"App\": \"shuffle:App\",\n    \"Organization\": \"schema:Organization\",\n    \"User\": \"schema:Person\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"email\": \"schema:email\",\n    \"url\": \"schema:url\",\n\n    \"status\": {\n      \"@id\": \"shuffle:status\",\n      \"@type\": \"@vocab\"\n    },\n    \"org_id\": {\n      \"@id\": \"shuffle:organizationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"workflow_id\": {\n      \"@id\": \"shuffle:workflowId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"execution_id\": {\n      \"@id\": \"shuffle:executionId\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"created\": {\n      \"@id\": \"shuffle:created\",\n      \"@type\": \"xsd:long\"\n    },\n    \"edited\": {\n      \"@id\": \"shuffle:edited\",\n      \"@type\": \"xsd:long\"\n    },\n    \"started_at\": {\n      \"@id\": \"shuffle:startedAt\",\n      \"@type\": \"xsd:long\"\n    },\n    \"completed_at\": {\n      \"@id\": \"shuffle:completedAt\",\n      \"@type\": \"xsd:long\"\n    },\n    \"actions\": {\n      \"@id\": \"shuffle:actions\",\n      \"@container\": \"@list\"\n    },\n    \"triggers\": {\n      \"@id\": \"shuffle:triggers\",\n      \"@container\": \"@list\"\n    },\n    \"tags\": {\n      \"@id\": \"shuffle:tags\",\n      \"@container\": \"@set\"\n    },\n    \"app_name\": {\n      \"@id\": \"shuffle:appName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"app_version\": {\n      \"@id\": \"shuffle:appVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"execution_argument\": {\n      \"@id\": \"shuffle:executionArgument\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"result\": {\n      \"@id\": \"shuffle:result\",\n      \"@type\": \"xsd:string\"\n    },\n    \"results\": {\n      \"@id\": \"shuffle:results\",\n      \"@container\": \"@list\"\n    },\n    \"authorization\": {\n      \"@id\": \"shuffle:authorization\",\n      \"@type\": \"xsd:string\"\n    },\n    \"role\": {\n      \"@id\": \"shuffle:role\",\n      \"@type\": \"@vocab\"\n    },\n    \"username\": \"schema:name\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/shuffle/refs/heads/main/json-ld/shuffle-context.jsonld
tags:
- Security
- Workflows
- Automation
- SOAR
- Orchestration
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
