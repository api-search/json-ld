---
api_specs:
- filename: trigger-dev-management-openapi.yml
  format: yaml
  label: Trigger.dev Management API
  slug: trigger-dev-management
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trigger-dev/refs/heads/main/openapi/trigger-dev-management-openapi.yml
class_count: 6
classes:
- Run
- Schedule
- Deployment
- Queue
- Batch
- WaitpointToken
context_file: json-ld/trigger-dev-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/trigger-dev/refs/heads/main/json-ld/trigger-dev-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Trigger Dev from Trigger.dev.
layout: jsonld
name: Trigger Dev Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: tdev
  uri: https://trigger.dev/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: ''
- container: ''
  name: status
  type: string
- container: ''
  name: taskIdentifier
  type: string
- container: ''
  name: version
  type: string
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
  name: finishedAt
  type: dateTime
- container: ''
  name: isTest
  type: boolean
- container: ''
  name: payload
  type: ''
- container: ''
  name: output
  type: ''
- container: set
  name: tags
  type: ''
- container: ''
  name: metadata
  type: ''
- container: ''
  name: relatedRuns
  type: ''
- container: list
  name: attempts
  type: ''
- container: ''
  name: task
  type: string
- container: ''
  name: cron
  type: string
- container: ''
  name: timezone
  type: string
- container: ''
  name: nextRun
  type: dateTime
- container: ''
  name: active
  type: boolean
- container: ''
  name: deduplicationKey
  type: string
- container: ''
  name: externalId
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: paused
  type: boolean
- container: ''
  name: concurrencyLimit
  type: integer
- container: ''
  name: depth
  type: integer
- container: ''
  name: idempotencyKey
  type: string
- container: ''
  name: ttl
  type: string
- container: ''
  name: expiresAt
  type: dateTime
property_count: 29
provider_name: Trigger.dev
provider_slug: trigger-dev
slug: trigger-dev-context
source_filename: trigger-dev-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"tdev\": \"https://trigger.dev/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Run\": \"tdev:Run\",\n    \"Schedule\": \"tdev:Schedule\",\n    \"Deployment\": \"tdev:Deployment\",\n    \"Queue\": \"tdev:Queue\",\n    \"Batch\": \"tdev:Batch\",\n    \"WaitpointToken\": \"tdev:WaitpointToken\",\n\n    \"id\": {\n      \"@id\": \"@id\"\n    },\n    \"status\": {\n      \"@id\": \"tdev:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskIdentifier\": {\n      \"@id\": \"tdev:taskIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"startedAt\"\
  : {\n      \"@id\": \"tdev:startedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"finishedAt\": {\n      \"@id\": \"tdev:finishedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"isTest\": {\n      \"@id\": \"tdev:isTest\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"payload\": {\n      \"@id\": \"tdev:payload\"\n    },\n    \"output\": {\n      \"@id\": \"tdev:output\"\n    },\n    \"tags\": {\n      \"@id\": \"schema:keywords\",\n      \"@container\": \"@set\"\n    },\n    \"metadata\": {\n      \"@id\": \"schema:additionalProperty\"\n    },\n    \"relatedRuns\": {\n      \"@id\": \"tdev:relatedRuns\"\n    },\n    \"attempts\": {\n      \"@id\": \"tdev:attempts\",\n      \"@container\": \"@list\"\n    },\n\n    \"task\": {\n      \"@id\": \"tdev:task\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cron\": {\n      \"@id\": \"tdev:cronExpression\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timezone\": {\n      \"@id\": \"tdev:timezone\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"nextRun\": {\n      \"@id\": \"tdev:nextRun\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"active\": {\n      \"@id\": \"tdev:active\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"deduplicationKey\": {\n      \"@id\": \"tdev:deduplicationKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"externalId\": {\n      \"@id\": \"tdev:externalId\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paused\": {\n      \"@id\": \"tdev:paused\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"concurrencyLimit\": {\n      \"@id\": \"tdev:concurrencyLimit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"depth\": {\n      \"@id\": \"tdev:depth\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"idempotencyKey\": {\n      \"@id\": \"tdev:idempotencyKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ttl\": {\n      \"@id\": \"tdev:ttl\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"expiresAt\": {\n      \"@id\": \"tdev:expiresAt\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/trigger-dev/refs/heads/main/json-ld/trigger-dev-context.jsonld
tags:
- Developer-First
- Workflow Automation
- Background Jobs
- TypeScript
- AI Agents
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
