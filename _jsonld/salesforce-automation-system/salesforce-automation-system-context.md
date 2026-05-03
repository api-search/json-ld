---
api_specs:
- filename: salesforce-automation-flow-openapi.yml
  format: yaml
  label: Salesforce Flow Automation API
  slug: salesforce-flow-automation-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-automation-system/refs/heads/main/openapi/salesforce-automation-flow-openapi.yml
class_count: 1
classes:
- Id
context_file: json-ld/salesforce-automation-system-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/salesforce-automation-system/refs/heads/main/json-ld/salesforce-automation-system-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Salesforce Automation System from Salesforce Automation System.
layout: jsonld
name: Salesforce Automation System Context
namespaces:
- prefix: sf
  uri: https://developer.salesforce.com/docs/automation/vocab#
properties:
- container: ''
  name: FlowDefinition
  type: reference
- container: ''
  name: FlowVersion
  type: ''
- container: ''
  name: ApprovalProcess
  type: ''
- container: ''
  name: ApprovalRequest
  type: ''
- container: ''
  name: ProcessInstance
  type: ''
- container: ''
  name: ApiName
  type: ''
- container: ''
  name: Label
  type: ''
- container: ''
  name: Description
  type: ''
- container: ''
  name: Status
  type: ''
- container: ''
  name: ProcessType
  type: ''
- container: ''
  name: TriggerType
  type: ''
- container: ''
  name: ActiveVersionId
  type: reference
- container: ''
  name: actionType
  type: ''
- container: ''
  name: contextActorId
  type: reference
- container: ''
  name: contextId
  type: reference
- container: ''
  name: comments
  type: ''
- container: ''
  name: success
  type: boolean
- container: ''
  name: instanceStatus
  type: ''
- container: ''
  name: CreatedDate
  type: dateTime
- container: ''
  name: LastModifiedDate
  type: dateTime
property_count: 20
provider_name: Salesforce Automation System
provider_slug: salesforce-automation-system
slug: salesforce-automation-system-context
source_filename: salesforce-automation-system-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"sf\": \"https://developer.salesforce.com/docs/automation/vocab#\",\n    \"FlowDefinition\": {\n      \"@id\": \"sf:FlowDefinition\",\n      \"@type\": \"@id\"\n    },\n    \"FlowVersion\": {\n      \"@id\": \"sf:FlowVersion\"\n    },\n    \"ApprovalProcess\": {\n      \"@id\": \"sf:ApprovalProcess\"\n    },\n    \"ApprovalRequest\": {\n      \"@id\": \"sf:ApprovalRequest\"\n    },\n    \"ProcessInstance\": {\n      \"@id\": \"sf:ProcessInstance\"\n    },\n    \"Id\": \"@id\",\n    \"ApiName\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"Label\": {\n      \"@id\": \"schema:name\"\n    },\n    \"Description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"Status\": {\n      \"@id\": \"schema:status\"\n    },\n    \"ProcessType\": {\n      \"@id\": \"sf:processType\"\n    },\n    \"TriggerType\": {\n      \"@id\": \"sf:triggerType\"\n    },\n    \"ActiveVersionId\": {\n      \"@id\": \"\
  sf:activeVersionId\",\n      \"@type\": \"@id\"\n    },\n    \"actionType\": {\n      \"@id\": \"sf:actionType\"\n    },\n    \"contextActorId\": {\n      \"@id\": \"sf:actorId\",\n      \"@type\": \"@id\"\n    },\n    \"contextId\": {\n      \"@id\": \"sf:targetId\",\n      \"@type\": \"@id\"\n    },\n    \"comments\": {\n      \"@id\": \"schema:comment\"\n    },\n    \"success\": {\n      \"@id\": \"sf:success\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"instanceStatus\": {\n      \"@id\": \"sf:instanceStatus\"\n    },\n    \"CreatedDate\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"LastModifiedDate\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/salesforce-automation-system/refs/heads/main/json-ld/salesforce-automation-system-context.jsonld
tags:
- Approval Process
- Automation
- CRM
- Flow
- Process Builder
- Salesforce
- Workflow
- JSON-LD
- Linked Data
- Semantic Web
---
