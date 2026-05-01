---
api_specs:
- filename: amazon-deadline-cloud-openapi.yml
  format: yaml
  label: Amazon Deadline Cloud API
  slug: amazon-deadline-cloud-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-deadline-cloud/refs/heads/main/openapi/amazon-deadline-cloud-openapi.yml
class_count: 0
classes: []
context_file: json-ld/amazon-deadline-cloud-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-deadline-cloud/refs/heads/main/json-ld/amazon-deadline-cloud-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Deadline Cloud from Amazon Deadline Cloud.
layout: jsonld
name: Amazon Deadline Cloud Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/deadline-cloud/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Farm
  type: ''
- container: ''
  name: Queue
  type: ''
- container: ''
  name: Fleet
  type: ''
- container: ''
  name: Job
  type: ''
- container: ''
  name: Worker
  type: ''
- container: ''
  name: farmId
  type: string
- container: ''
  name: queueId
  type: string
- container: ''
  name: fleetId
  type: string
- container: ''
  name: jobId
  type: string
- container: ''
  name: workerId
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: lifecycleStatus
  type: string
- container: ''
  name: taskRunStatus
  type: string
- container: ''
  name: priority
  type: integer
- container: ''
  name: workerCount
  type: integer
- container: ''
  name: kmsKeyArn
  type: string
- container: ''
  name: roleArn
  type: string
- container: ''
  name: configuration
  type: ''
- container: ''
  name: taskRunStatusCounts
  type: ''
- container: ''
  name: defaultBudgetAction
  type: string
- container: ''
  name: jobAttachmentSettings
  type: ''
- container: set
  name: farms
  type: ''
- container: set
  name: queues
  type: ''
- container: set
  name: fleets
  type: ''
- container: set
  name: jobs
  type: ''
- container: set
  name: workers
  type: ''
- container: ''
  name: nextToken
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: message
  type: string
- container: ''
  name: code
  type: string
property_count: 33
provider_name: Amazon Deadline Cloud
provider_slug: amazon-deadline-cloud
slug: amazon-deadline-cloud-context
source_filename: amazon-deadline-cloud-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/deadline-cloud/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Farm\": {\"@id\": \"aws:Farm\"},\n    \"Queue\": {\"@id\": \"aws:Queue\"},\n    \"Fleet\": {\"@id\": \"aws:Fleet\"},\n    \"Job\": {\"@id\": \"aws:RenderJob\"},\n    \"Worker\": {\"@id\": \"aws:Worker\"},\n\n    \"farmId\": {\"@id\": \"aws:farmId\", \"@type\": \"xsd:string\"},\n    \"queueId\": {\"@id\": \"aws:queueId\", \"@type\": \"xsd:string\"},\n    \"fleetId\": {\"@id\": \"aws:fleetId\", \"@type\": \"xsd:string\"},\n    \"jobId\": {\"@id\": \"aws:jobId\", \"@type\": \"xsd:string\"},\n    \"workerId\": {\"@id\": \"aws:workerId\", \"@type\": \"xsd:string\"},\n    \"displayName\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n    \"description\": {\"@id\": \"schema:description\", \"@type\": \"xsd:string\"},\n    \"status\": {\"@id\": \"aws:status\", \"@type\"\
  : \"xsd:string\"},\n    \"lifecycleStatus\": {\"@id\": \"aws:lifecycleStatus\", \"@type\": \"xsd:string\"},\n    \"taskRunStatus\": {\"@id\": \"aws:taskRunStatus\", \"@type\": \"xsd:string\"},\n    \"priority\": {\"@id\": \"aws:priority\", \"@type\": \"xsd:integer\"},\n    \"workerCount\": {\"@id\": \"aws:workerCount\", \"@type\": \"xsd:integer\"},\n    \"kmsKeyArn\": {\"@id\": \"aws:kmsKeyArn\", \"@type\": \"xsd:string\"},\n    \"roleArn\": {\"@id\": \"aws:roleArn\", \"@type\": \"xsd:string\"},\n    \"configuration\": {\"@id\": \"aws:configuration\"},\n    \"taskRunStatusCounts\": {\"@id\": \"aws:taskRunStatusCounts\"},\n    \"defaultBudgetAction\": {\"@id\": \"aws:defaultBudgetAction\", \"@type\": \"xsd:string\"},\n    \"jobAttachmentSettings\": {\"@id\": \"aws:jobAttachmentSettings\"},\n\n    \"farms\": {\"@id\": \"aws:farms\", \"@container\": \"@set\"},\n    \"queues\": {\"@id\": \"aws:queues\", \"@container\": \"@set\"},\n    \"fleets\": {\"@id\": \"aws:fleets\", \"@container\": \"\
  @set\"},\n    \"jobs\": {\"@id\": \"aws:jobs\", \"@container\": \"@set\"},\n    \"workers\": {\"@id\": \"aws:workers\", \"@container\": \"@set\"},\n    \"nextToken\": {\"@id\": \"aws:nextToken\", \"@type\": \"xsd:string\"},\n\n    \"createdAt\": {\"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\"},\n    \"updatedAt\": {\"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\"},\n\n    \"message\": {\"@id\": \"schema:description\", \"@type\": \"xsd:string\"},\n    \"code\": {\"@id\": \"aws:errorCode\", \"@type\": \"xsd:string\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-deadline-cloud/refs/heads/main/json-ld/amazon-deadline-cloud-context.jsonld
tags:
- Compute
- Media
- Rendering
- Visual Effects
- JSON-LD
- Linked Data
- Semantic Web
---
