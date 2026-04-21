---
class_count: 7
classes:
- JobList
- Job
- JobRequest
- JobLogs
- ScriptRequest
- ValidationResult
- ValidationError
context_file: json-ld/apache-pig-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-pig/refs/heads/main/json-ld/apache-pig-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Pig from Apache Pig.
layout: jsonld
name: Apache Pig Context
namespaces:
- prefix: pig
  uri: https://pig.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: jobs
  type: ''
- container: ''
  name: total
  type: integer
- container: ''
  name: jobId
  type: string
- container: ''
  name: name
  type: schema:name
- container: ''
  name: status
  type: string
- container: ''
  name: submittedAt
  type: string
- container: ''
  name: startedAt
  type: string
- container: ''
  name: completedAt
  type: string
- container: ''
  name: executionEngine
  type: string
- container: ''
  name: progress
  type: decimal
- container: ''
  name: script
  type: string
- container: ''
  name: parameters
  type: string
- container: set
  name: logs
  type: ''
- container: ''
  name: valid
  type: boolean
- container: set
  name: errors
  type: ''
- container: ''
  name: line
  type: integer
- container: ''
  name: column
  type: integer
- container: ''
  name: message
  type: string
- container: ''
  name: severity
  type: string
property_count: 19
provider_name: Apache Pig
provider_slug: apache-pig
slug: apache-pig-context
tags:
- Big Data
- Data Analysis
- ETL
- Hadoop
- Scripting
- Apache
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
