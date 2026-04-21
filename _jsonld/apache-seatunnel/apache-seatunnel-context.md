---
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
