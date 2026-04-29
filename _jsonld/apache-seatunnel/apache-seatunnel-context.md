---
api_specs:
- filename: apache-seatunnel-rest-api.yaml
  format: yaml
  label: Apache SeaTunnel REST API
  slug: apache-seatunnel-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-seatunnel/refs/heads/main/openapi/apache-seatunnel-rest-api.yaml
class_count: 10
classes:
- JobList
- JobInfo
- JobSubmitRequest
- JobSubmitResult
- JobDetail
- JobMetrics
- JobStopRequest
- JobStopResult
- SystemInfo
- ClusterOverview
context_file: json-ld/apache-seatunnel-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-seatunnel/refs/heads/main/json-ld/apache-seatunnel-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Seatunnel from Apache SeaTunnel.
layout: jsonld
name: Apache Seatunnel Context
namespaces:
- prefix: seat
  uri: https://seatunnel.apache.org/schema/
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
  name: jobName
  type: string
- container: ''
  name: jobStatus
  type: string
- container: ''
  name: createTime
  type: string
- container: ''
  name: finishTime
  type: string
- container: ''
  name: jobContent
  type: string
- container: ''
  name: isStartWithSavePoint
  type: boolean
- container: ''
  name: jobDag
  type: string
- container: ''
  name: metrics
  type: string
- container: ''
  name: errorMsg
  type: string
- container: ''
  name: sourceReceivedCount
  type: integer
- container: ''
  name: sinkWriteCount
  type: integer
- container: ''
  name: sourceReceivedQPS
  type: decimal
- container: ''
  name: sinkWriteQPS
  type: decimal
- container: ''
  name: isStopWithSavePoint
  type: boolean
- container: ''
  name: status
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: processors
  type: integer
- container: ''
  name: physicalMemory
  type: integer
- container: ''
  name: freePhysicalMemory
  type: integer
- container: ''
  name: totalHeapMemory
  type: integer
- container: ''
  name: freeHeapMemory
  type: integer
- container: ''
  name: usedHeapMemory
  type: integer
- container: ''
  name: workers
  type: integer
- container: ''
  name: runningJobs
  type: integer
- container: ''
  name: finishedJobs
  type: integer
- container: ''
  name: failedJobs
  type: integer
- container: ''
  name: canceledJobs
  type: integer
- container: ''
  name: totalSlot
  type: integer
- container: ''
  name: usedSlot
  type: integer
property_count: 32
provider_name: Apache SeaTunnel
provider_slug: apache-seatunnel
slug: apache-seatunnel-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"seat\": \"https://seatunnel.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"JobList\": \"seat:JobList\",\n    \"JobInfo\": \"seat:JobInfo\",\n    \"JobSubmitRequest\": \"seat:JobSubmitRequest\",\n    \"JobSubmitResult\": \"seat:JobSubmitResult\",\n    \"JobDetail\": \"seat:JobDetail\",\n    \"JobMetrics\": \"seat:JobMetrics\",\n    \"JobStopRequest\": \"seat:JobStopRequest\",\n    \"JobStopResult\": \"seat:JobStopResult\",\n    \"SystemInfo\": \"seat:SystemInfo\",\n    \"ClusterOverview\": \"seat:ClusterOverview\",\n    \"jobs\": {\n      \"@id\": \"seat:jobs\",\n      \"@container\": \"@set\"\n    },\n    \"total\": {\n      \"@id\": \"seat:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"jobId\": {\n      \"@id\": \"seat:jobId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobName\": {\n      \"@id\": \"seat:jobName\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"jobStatus\": {\n      \"@id\": \"seat:jobStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createTime\": {\n      \"@id\": \"seat:createTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"finishTime\": {\n      \"@id\": \"seat:finishTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobContent\": {\n      \"@id\": \"seat:jobContent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isStartWithSavePoint\": {\n      \"@id\": \"seat:isStartWithSavePoint\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"jobDag\": {\n      \"@id\": \"seat:jobDag\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metrics\": {\n      \"@id\": \"seat:metrics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorMsg\": {\n      \"@id\": \"seat:errorMsg\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceReceivedCount\": {\n      \"@id\": \"seat:sourceReceivedCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sinkWriteCount\": {\n      \"@id\": \"\
  seat:sinkWriteCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sourceReceivedQPS\": {\n      \"@id\": \"seat:sourceReceivedQPS\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"sinkWriteQPS\": {\n      \"@id\": \"seat:sinkWriteQPS\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"isStopWithSavePoint\": {\n      \"@id\": \"seat:isStopWithSavePoint\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"status\": {\n      \"@id\": \"seat:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"seat:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"processors\": {\n      \"@id\": \"seat:processors\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"physicalMemory\": {\n      \"@id\": \"seat:physicalMemory\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"freePhysicalMemory\": {\n      \"@id\": \"seat:freePhysicalMemory\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalHeapMemory\": {\n      \"@id\": \"seat:totalHeapMemory\",\n   \
  \   \"@type\": \"xsd:integer\"\n    },\n    \"freeHeapMemory\": {\n      \"@id\": \"seat:freeHeapMemory\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"usedHeapMemory\": {\n      \"@id\": \"seat:usedHeapMemory\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"workers\": {\n      \"@id\": \"seat:workers\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"runningJobs\": {\n      \"@id\": \"seat:runningJobs\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"finishedJobs\": {\n      \"@id\": \"seat:finishedJobs\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"failedJobs\": {\n      \"@id\": \"seat:failedJobs\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"canceledJobs\": {\n      \"@id\": \"seat:canceledJobs\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalSlot\": {\n      \"@id\": \"seat:totalSlot\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"usedSlot\": {\n      \"@id\": \"seat:usedSlot\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-seatunnel/refs/heads/main/json-ld/apache-seatunnel-context.jsonld
tags:
- Data Integration
- ETL
- ELT
- Batch
- Streaming
- Apache
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
