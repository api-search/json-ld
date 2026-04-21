---
class_count: 9
classes:
- BuildVersion
- JobAction
- JobId
- JobInfo
- JobList
- SystemMetrics
- SystemStatus
- ValidationResult
- name
context_file: json-ld/apache-oozie-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-oozie/refs/heads/main/json-ld/apache-oozie-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Oozie from Apache Oozie.
layout: jsonld
name: Apache Oozie Context
namespaces:
- prefix: oozie
  uri: https://oozie.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: actions
  type: string
- container: ''
  name: appName
  type: string
- container: ''
  name: appPath
  type: string
- container: ''
  name: buildVersion
  type: string
- container: set
  name: bundlejobs
  type: string
- container: set
  name: coordinatorjobs
  type: string
- container: ''
  name: counters
  type: reference
- container: ''
  name: createdTime
  type: dateTime
- container: ''
  name: endTime
  type: dateTime
- container: ''
  name: errorCode
  type: string
- container: ''
  name: errorMessage
  type: string
- container: ''
  name: gauges
  type: reference
- container: ''
  name: group
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: lastModTime
  type: dateTime
- container: ''
  name: len
  type: integer
- container: ''
  name: offset
  type: integer
- container: ''
  name: run
  type: integer
- container: ''
  name: startTime
  type: dateTime
- container: ''
  name: status
  type: string
- container: ''
  name: systemMode
  type: string
- container: ''
  name: timers
  type: reference
- container: ''
  name: total
  type: integer
- container: ''
  name: type
  type: string
- container: ''
  name: user
  type: string
- container: ''
  name: validate
  type: reference
- container: set
  name: workflows
  type: string
property_count: 27
provider_name: Apache Oozie
provider_slug: apache-oozie
slug: apache-oozie-context
tags:
- Workflow
- Hadoop
- Orchestration
- Scheduling
- Big Data
- Apache
- Java
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
