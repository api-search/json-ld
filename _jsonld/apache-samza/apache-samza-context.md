---
class_count: 8
classes:
- JobList
- Job
- JobStatus
- TaskList
- Task
- Partition
- CheckpointList
- Checkpoint
context_file: json-ld/apache-samza-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-samza/refs/heads/main/json-ld/apache-samza-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Samza from Apache Samza.
layout: jsonld
name: Apache Samza Context
namespaces:
- prefix: samz
  uri: https://samza.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: jobs
  type: ''
- container: ''
  name: jobName
  type: string
- container: ''
  name: jobId
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: containersCount
  type: integer
- container: ''
  name: taskCount
  type: integer
- container: ''
  name: message
  type: string
- container: set
  name: tasks
  type: ''
- container: ''
  name: taskName
  type: string
- container: ''
  name: containerId
  type: string
- container: set
  name: partitions
  type: ''
- container: ''
  name: systemName
  type: string
- container: ''
  name: stream
  type: string
- container: ''
  name: partitionId
  type: integer
- container: set
  name: checkpoints
  type: ''
- container: ''
  name: systemStreamPartition
  type: string
- container: ''
  name: offset
  type: string
property_count: 17
provider_name: Apache Samza
provider_slug: apache-samza
slug: apache-samza-context
tags:
- Big Data
- Hadoop
- Kafka
- Stream Processing
- Streaming
- Apache
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
