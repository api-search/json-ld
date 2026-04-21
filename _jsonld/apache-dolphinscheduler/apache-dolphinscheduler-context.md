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
