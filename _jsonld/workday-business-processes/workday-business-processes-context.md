---
api_specs:
- filename: Business_Process_Service.yaml
  format: yaml
  label: Workday Business Process API
  slug: ''
  spec_type: OpenAPI
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Business_Process_Service/v41.1/Business_Process_Service.yaml
class_count: 31
classes:
- BusinessProcessDefinition
- ProcessInstance
- InitiateProcessRequest
- ProcessStep
- InboxItem
- ApprovalRequest
- DenialRequest
- id
- name
- description
- status
- type
- stepId
- stepName
- stepType
- assignedGroup
- assignedTo
- definitionId
- processType
- initiatorId
- transactionId
- processData
- currentStep
- cancelReason
- processInstanceId
- subject
- actionTaken
- priority
- comment
- approverId
- denierId
context_file: json-ld/workday-business-processes-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/workday-business-processes/refs/heads/main/json-ld/workday-business-processes-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Workday Business Processes from Workday Business Processes.
layout: jsonld
name: Workday Business Processes Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: wdbp
  uri: https://community.workday.com/sites/default/files/file-hosting/productionapi/Business_Process_Service/v41.1/schema/
properties:
- container: ''
  name: version
  type: integer
- container: list
  name: steps
  type: ''
- container: ''
  name: order
  type: integer
- container: ''
  name: completionPercent
  type: integer
- container: ''
  name: startDate
  type: dateTime
- container: ''
  name: endDate
  type: dateTime
- container: ''
  name: dueDate
  type: date
- container: ''
  name: createdDate
  type: dateTime
- container: ''
  name: completedDate
  type: dateTime
- container: ''
  name: total
  type: integer
- container: list
  name: data
  type: ''
property_count: 11
provider_name: Workday Business Processes
provider_slug: workday-business-processes
slug: workday-business-processes-context
source_filename: workday-business-processes-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"wdbp\": \"https://community.workday.com/sites/default/files/file-hosting/productionapi/Business_Process_Service/v41.1/schema/\",\n\n    \"BusinessProcessDefinition\": \"wdbp:BusinessProcessDefinition\",\n    \"ProcessInstance\": \"wdbp:ProcessInstance\",\n    \"InitiateProcessRequest\": \"wdbp:InitiateProcessRequest\",\n    \"ProcessStep\": \"wdbp:ProcessStep\",\n    \"InboxItem\": \"wdbp:InboxItem\",\n    \"ApprovalRequest\": \"wdbp:ApprovalRequest\",\n    \"DenialRequest\": \"wdbp:DenialRequest\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"status\": \"wdbp:status\",\n    \"type\": \"schema:additionalType\",\n    \"version\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"steps\": {\n      \"@id\": \"wdbp:steps\",\n      \"\
  @container\": \"@list\"\n    },\n    \"stepId\": \"schema:identifier\",\n    \"stepName\": \"schema:name\",\n    \"stepType\": \"wdbp:stepType\",\n    \"assignedGroup\": \"schema:memberOf\",\n    \"assignedTo\": \"schema:assignee\",\n    \"order\": {\n      \"@id\": \"schema:position\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"definitionId\": \"wdbp:definitionId\",\n    \"processType\": \"wdbp:processType\",\n    \"initiatorId\": \"wdbp:initiatorId\",\n    \"transactionId\": \"schema:identifier\",\n    \"processData\": \"wdbp:processData\",\n    \"currentStep\": \"wdbp:currentStep\",\n    \"cancelReason\": \"wdbp:cancelReason\",\n    \"completionPercent\": {\n      \"@id\": \"wdbp:completionPercent\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"startDate\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"endDate\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"dueDate\": {\n      \"@id\"\
  : \"schema:expires\",\n      \"@type\": \"xsd:date\"\n    },\n    \"createdDate\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"completedDate\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"processInstanceId\": \"wdbp:processInstanceId\",\n    \"subject\": \"schema:name\",\n    \"actionTaken\": \"wdbp:actionTaken\",\n    \"priority\": \"wdbp:priority\",\n\n    \"comment\": \"schema:comment\",\n    \"approverId\": \"wdbp:approverId\",\n    \"denierId\": \"wdbp:denierId\",\n\n    \"total\": {\n      \"@id\": \"wdbp:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"data\": {\n      \"@id\": \"wdbp:data\",\n      \"@container\": \"@list\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/workday-business-processes/refs/heads/main/json-ld/workday-business-processes-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
