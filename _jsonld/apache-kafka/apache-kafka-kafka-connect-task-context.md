---
class_count: 2
classes:
- TaskInfo
- TaskStatus
context_file: json-ld/apache-kafka-kafka-connect-task-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-kafka/refs/heads/main/json-ld/apache-kafka-kafka-connect-task-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Kafka Kafka Connect Task from Apache Kafka.
layout: jsonld
name: Apache Kafka Kafka Connect Task Context
namespaces:
- prefix: kafka
  uri: https://apache-kafka.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: reference
- container: ''
  name: connector
  type: string
- container: ''
  name: task
  type: integer
- container: ''
  name: config
  type: reference
- container: ''
  name: state
  type: string
- container: ''
  name: workerId
  type: string
- container: ''
  name: trace
  type: string
property_count: 7
provider_name: Apache Kafka
provider_slug: apache-kafka
slug: apache-kafka-kafka-connect-task-context
tags:
- Distributed Systems
- Event Streaming
- Messaging
- Open Source
- Pub-Sub
- JSON-LD
- Linked Data
- Semantic Web
---
