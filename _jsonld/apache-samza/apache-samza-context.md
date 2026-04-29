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
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"samz\": \"https://samza.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"JobList\": \"samz:JobList\",\n    \"Job\": \"samz:Job\",\n    \"JobStatus\": \"samz:JobStatus\",\n    \"TaskList\": \"samz:TaskList\",\n    \"Task\": \"samz:Task\",\n    \"Partition\": \"samz:Partition\",\n    \"CheckpointList\": \"samz:CheckpointList\",\n    \"Checkpoint\": \"samz:Checkpoint\",\n    \"jobs\": {\n      \"@id\": \"samz:jobs\",\n      \"@container\": \"@set\"\n    },\n    \"jobName\": {\n      \"@id\": \"samz:jobName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobId\": {\n      \"@id\": \"samz:jobId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"samz:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"containersCount\": {\n      \"@id\": \"samz:containersCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"taskCount\"\
  : {\n      \"@id\": \"samz:taskCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"message\": {\n      \"@id\": \"samz:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tasks\": {\n      \"@id\": \"samz:tasks\",\n      \"@container\": \"@set\"\n    },\n    \"taskName\": {\n      \"@id\": \"samz:taskName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"containerId\": {\n      \"@id\": \"samz:containerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partitions\": {\n      \"@id\": \"samz:partitions\",\n      \"@container\": \"@set\"\n    },\n    \"systemName\": {\n      \"@id\": \"samz:systemName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stream\": {\n      \"@id\": \"samz:stream\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partitionId\": {\n      \"@id\": \"samz:partitionId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"checkpoints\": {\n      \"@id\": \"samz:checkpoints\",\n      \"@container\": \"@set\"\n    },\n    \"systemStreamPartition\": {\n\
  \      \"@id\": \"samz:systemStreamPartition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"offset\": {\n      \"@id\": \"samz:offset\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-samza/refs/heads/main/json-ld/apache-samza-context.jsonld
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
