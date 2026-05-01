---
api_specs:
- filename: apache-oozie-openapi.yaml
  format: yaml
  label: Apache Oozie REST API
  slug: apache-oozie-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-oozie/refs/heads/main/openapi/apache-oozie-openapi.yaml
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
source_filename: apache-oozie-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"oozie\": \"https://oozie.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"BuildVersion\": \"oozie:BuildVersion\",\n    \"JobAction\": \"oozie:JobAction\",\n    \"JobId\": \"oozie:JobId\",\n    \"JobInfo\": \"oozie:JobInfo\",\n    \"JobList\": \"oozie:JobList\",\n    \"SystemMetrics\": \"oozie:SystemMetrics\",\n    \"SystemStatus\": \"oozie:SystemStatus\",\n    \"ValidationResult\": \"oozie:ValidationResult\",\n    \"actions\": {\n      \"@id\": \"oozie:actions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"appName\": {\n      \"@id\": \"oozie:appName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"appPath\": {\n      \"@id\": \"oozie:appPath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"buildVersion\": {\n      \"@id\": \"oozie:buildVersion\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"bundlejobs\": {\n      \"@id\": \"oozie:bundlejobs\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"coordinatorjobs\": {\n      \"@id\": \"oozie:coordinatorjobs\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"counters\": {\n      \"@id\": \"oozie:counters\",\n      \"@type\": \"@id\"\n    },\n    \"createdTime\": {\n      \"@id\": \"oozie:createdTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"endTime\": {\n      \"@id\": \"oozie:endTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"errorCode\": {\n      \"@id\": \"oozie:errorCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorMessage\": {\n      \"@id\": \"oozie:errorMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gauges\": {\n      \"@id\": \"oozie:gauges\",\n      \"@type\": \"@id\"\n    },\n    \"group\": {\n      \"@id\": \"oozie:group\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n\
  \      \"@id\": \"oozie:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastModTime\": {\n      \"@id\": \"oozie:lastModTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"len\": {\n      \"@id\": \"oozie:len\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": \"schema:name\",\n    \"offset\": {\n      \"@id\": \"oozie:offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"run\": {\n      \"@id\": \"oozie:run\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"startTime\": {\n      \"@id\": \"oozie:startTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"status\": {\n      \"@id\": \"oozie:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"systemMode\": {\n      \"@id\": \"oozie:systemMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timers\": {\n      \"@id\": \"oozie:timers\",\n      \"@type\": \"@id\"\n    },\n    \"total\": {\n      \"@id\": \"oozie:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"type\": {\n      \"@id\": \"oozie:type\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"user\": {\n      \"@id\": \"oozie:user\",\n      \"@type\": \"xsd:string\"\n    },\n    \"validate\": {\n      \"@id\": \"oozie:validate\",\n      \"@type\": \"@id\"\n    },\n    \"workflows\": {\n      \"@id\": \"oozie:workflows\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-oozie/refs/heads/main/json-ld/apache-oozie-context.jsonld
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
