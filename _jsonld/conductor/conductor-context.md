---
class_count: 7
classes:
- WorkflowDef
- TaskDef
- WorkflowExecution
- Task
- EventHandler
- EventHandlerAction
- WorkflowTask
context_file: json-ld/conductor-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/conductor/refs/heads/main/json-ld/conductor-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Conductor from Conductor.
layout: jsonld
name: Conductor Context
namespaces:
- prefix: conductor
  uri: https://conductor-oss.github.io/conductor/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: version
  type: integer
- container: ''
  name: status
  type: string
- container: ''
  name: workflowId
  type: string
- container: ''
  name: workflowName
  type: string
- container: ''
  name: workflowVersion
  type: integer
- container: ''
  name: correlationId
  type: string
- container: ''
  name: taskId
  type: string
- container: ''
  name: taskType
  type: string
- container: ''
  name: taskReferenceName
  type: string
- container: ''
  name: taskDefName
  type: string
- container: ''
  name: referenceTaskName
  type: string
- container: list
  name: tasks
  type: ''
- container: list
  name: actions
  type: ''
- container: ''
  name: inputParameters
  type: ''
- container: ''
  name: outputParameters
  type: ''
- container: ''
  name: input
  type: ''
- container: ''
  name: output
  type: ''
- container: ''
  name: inputData
  type: ''
- container: ''
  name: outputData
  type: ''
- container: ''
  name: ownerEmail
  type: string
- container: ''
  name: failureWorkflow
  type: string
- container: ''
  name: timeoutPolicy
  type: string
- container: ''
  name: timeoutSeconds
  type: integer
- container: ''
  name: retryCount
  type: integer
- container: ''
  name: retryLogic
  type: string
- container: ''
  name: retryDelaySeconds
  type: integer
- container: ''
  name: startTime
  type: integer
- container: ''
  name: endTime
  type: integer
- container: ''
  name: updateTime
  type: integer
- container: ''
  name: createTime
  type: integer
- container: ''
  name: priority
  type: integer
- container: ''
  name: event
  type: string
- container: ''
  name: condition
  type: string
- container: ''
  name: active
  type: boolean
- container: ''
  name: restartable
  type: boolean
- container: ''
  name: reasonForIncompletion
  type: string
- container: ''
  name: workerId
  type: string
- container: ''
  name: parentWorkflowId
  type: string
property_count: 40
provider_name: Conductor
provider_slug: conductor
slug: conductor-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://conductor-oss.github.io/conductor/schema/\",\n    \"conductor\": \"https://conductor-oss.github.io/conductor/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"WorkflowDef\": \"conductor:WorkflowDef\",\n    \"TaskDef\": \"conductor:TaskDef\",\n    \"WorkflowExecution\": \"conductor:WorkflowExecution\",\n    \"Task\": \"conductor:Task\",\n    \"EventHandler\": \"conductor:EventHandler\",\n    \"EventHandlerAction\": \"conductor:EventHandlerAction\",\n    \"WorkflowTask\": \"conductor:WorkflowTask\",\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"conductor:version\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"status\": {\n      \"@id\": \"conductor:status\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"workflowId\": {\n      \"@id\": \"conductor:workflowId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"workflowName\": {\n      \"@id\": \"conductor:workflowName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"workflowVersion\": {\n      \"@id\": \"conductor:workflowVersion\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"correlationId\": {\n      \"@id\": \"conductor:correlationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskId\": {\n      \"@id\": \"conductor:taskId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskType\": {\n      \"@id\": \"conductor:taskType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskReferenceName\": {\n      \"@id\": \"conductor:taskReferenceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskDefName\": {\n      \"@id\": \"conductor:taskDefName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"referenceTaskName\": {\n      \"@id\": \"conductor:referenceTaskName\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"tasks\": {\n      \"@id\": \"conductor:tasks\",\n      \"@container\": \"@list\"\n    },\n    \"actions\": {\n      \"@id\": \"conductor:actions\",\n      \"@container\": \"@list\"\n    },\n    \"inputParameters\": {\n      \"@id\": \"conductor:inputParameters\"\n    },\n    \"outputParameters\": {\n      \"@id\": \"conductor:outputParameters\"\n    },\n    \"input\": {\n      \"@id\": \"conductor:input\"\n    },\n    \"output\": {\n      \"@id\": \"conductor:output\"\n    },\n    \"inputData\": {\n      \"@id\": \"conductor:inputData\"\n    },\n    \"outputData\": {\n      \"@id\": \"conductor:outputData\"\n    },\n    \"ownerEmail\": {\n      \"@id\": \"conductor:ownerEmail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failureWorkflow\": {\n      \"@id\": \"conductor:failureWorkflow\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeoutPolicy\": {\n      \"@id\": \"conductor:timeoutPolicy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeoutSeconds\": {\n\
  \      \"@id\": \"conductor:timeoutSeconds\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"retryCount\": {\n      \"@id\": \"conductor:retryCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"retryLogic\": {\n      \"@id\": \"conductor:retryLogic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"retryDelaySeconds\": {\n      \"@id\": \"conductor:retryDelaySeconds\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"startTime\": {\n      \"@id\": \"conductor:startTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"endTime\": {\n      \"@id\": \"conductor:endTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"updateTime\": {\n      \"@id\": \"conductor:updateTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"createTime\": {\n      \"@id\": \"conductor:createTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"priority\": {\n      \"@id\": \"conductor:priority\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"event\": {\n      \"@id\": \"conductor:event\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"condition\": {\n      \"@id\": \"conductor:condition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"active\": {\n      \"@id\": \"conductor:active\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"restartable\": {\n      \"@id\": \"conductor:restartable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"reasonForIncompletion\": {\n      \"@id\": \"conductor:reasonForIncompletion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"workerId\": {\n      \"@id\": \"conductor:workerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parentWorkflowId\": {\n      \"@id\": \"conductor:parentWorkflowId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/conductor/refs/heads/main/json-ld/conductor-context.jsonld
tags:
- Automation
- Orchestration
- State
- Tasks
- Workflows
- JSON-LD
- Linked Data
- Semantic Web
---
