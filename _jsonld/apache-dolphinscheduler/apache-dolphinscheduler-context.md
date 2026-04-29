---
class_count: 6
classes:
- WorkflowDefinition
- WorkflowInstance
- TaskDefinition
- Schedule
- description
- name
context_file: json-ld/apache-dolphinscheduler-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/json-ld/apache-dolphinscheduler-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Dolphinscheduler from Apache DolphinScheduler.
layout: jsonld
name: Apache Dolphinscheduler Context
namespaces:
- prefix: ds
  uri: https://dolphinscheduler.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: code
  type: integer
- container: ''
  name: commandType
  type: string
- container: ''
  name: createTime
  type: dateTime
- container: ''
  name: crontab
  type: string
- container: ''
  name: duration
  type: string
- container: ''
  name: endTime
  type: dateTime
- container: ''
  name: failureStrategy
  type: string
- container: ''
  name: flag
  type: string
- container: ''
  name: globalParams
  type: string
- container: ''
  name: host
  type: string
- container: ''
  name: id
  type: integer
- container: ''
  name: processDefinitionCode
  type: integer
- container: ''
  name: projectCode
  type: integer
- container: ''
  name: releaseState
  type: string
- container: ''
  name: retryInterval
  type: integer
- container: ''
  name: retryTimes
  type: integer
- container: ''
  name: runTimes
  type: integer
- container: ''
  name: startTime
  type: dateTime
- container: ''
  name: state
  type: string
- container: ''
  name: taskParams
  type: reference
- container: ''
  name: taskPriority
  type: string
- container: ''
  name: taskType
  type: string
- container: ''
  name: tenantCode
  type: string
- container: ''
  name: timeout
  type: integer
- container: ''
  name: timezoneId
  type: string
- container: ''
  name: updateTime
  type: dateTime
- container: ''
  name: version
  type: integer
- container: ''
  name: warningType
  type: string
- container: ''
  name: workerGroup
  type: string
property_count: 29
provider_name: Apache DolphinScheduler
provider_slug: apache-dolphinscheduler
slug: apache-dolphinscheduler-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ds\": \"https://dolphinscheduler.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"WorkflowDefinition\": \"ds:WorkflowDefinition\",\n    \"WorkflowInstance\": \"ds:WorkflowInstance\",\n    \"TaskDefinition\": \"ds:TaskDefinition\",\n    \"Schedule\": \"ds:Schedule\",\n    \"code\": {\n      \"@id\": \"ds:code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"commandType\": {\n      \"@id\": \"ds:commandType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createTime\": {\n      \"@id\": \"ds:createTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"crontab\": {\n      \"@id\": \"ds:crontab\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"duration\": {\n      \"@id\": \"ds:duration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endTime\": {\n      \"@id\": \"ds:endTime\",\n      \"@type\":\
  \ \"xsd:dateTime\"\n    },\n    \"failureStrategy\": {\n      \"@id\": \"ds:failureStrategy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flag\": {\n      \"@id\": \"ds:flag\",\n      \"@type\": \"xsd:string\"\n    },\n    \"globalParams\": {\n      \"@id\": \"ds:globalParams\",\n      \"@type\": \"xsd:string\"\n    },\n    \"host\": {\n      \"@id\": \"ds:host\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"ds:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": \"schema:name\",\n    \"processDefinitionCode\": {\n      \"@id\": \"ds:processDefinitionCode\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"projectCode\": {\n      \"@id\": \"ds:projectCode\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"releaseState\": {\n      \"@id\": \"ds:releaseState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"retryInterval\": {\n      \"@id\": \"ds:retryInterval\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"retryTimes\": {\n      \"@id\"\
  : \"ds:retryTimes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"runTimes\": {\n      \"@id\": \"ds:runTimes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"startTime\": {\n      \"@id\": \"ds:startTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"state\": {\n      \"@id\": \"ds:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskParams\": {\n      \"@id\": \"ds:taskParams\",\n      \"@type\": \"@id\"\n    },\n    \"taskPriority\": {\n      \"@id\": \"ds:taskPriority\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskType\": {\n      \"@id\": \"ds:taskType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tenantCode\": {\n      \"@id\": \"ds:tenantCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeout\": {\n      \"@id\": \"ds:timeout\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"timezoneId\": {\n      \"@id\": \"ds:timezoneId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updateTime\": {\n      \"@id\": \"ds:updateTime\",\n      \"@type\"\
  : \"xsd:dateTime\"\n    },\n    \"version\": {\n      \"@id\": \"ds:version\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"warningType\": {\n      \"@id\": \"ds:warningType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"workerGroup\": {\n      \"@id\": \"ds:workerGroup\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/json-ld/apache-dolphinscheduler-context.jsonld
tags:
- Apache
- DAG
- Data Pipeline
- Open Source
- Orchestration
- Python
- Scheduling
- Workflow
- JSON-LD
- Linked Data
- Semantic Web
---
