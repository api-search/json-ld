---
class_count: 10
classes:
- Partition
- ProduceRequest
- CreateTopicRequest
- ProduceResponse
- Acl
- Topic
- Broker
- CreateAclRequest
- ConsumerGroup
- Cluster
context_file: json-ld/apache-kafka-kafka-rest-proxy-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-kafka/refs/heads/main/json-ld/apache-kafka-kafka-rest-proxy-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Kafka Kafka Rest Proxy from Apache Kafka.
layout: jsonld
name: Apache Kafka Kafka Rest Proxy Context
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
  name: kind
  type: string
- container: ''
  name: metadata
  type: reference
- container: ''
  name: clusterId
  type: string
- container: ''
  name: topicName
  type: string
- container: ''
  name: partitionId
  type: integer
- container: ''
  name: leader
  type: reference
- container: set
  name: replicas
  type: reference
- container: set
  name: headers
  type: reference
- container: ''
  name: key
  type: reference
- container: ''
  name: type
  type: string
- container: ''
  name: data
  type: string
- container: ''
  name: value
  type: reference
- container: ''
  name: partitionsCount
  type: integer
- container: ''
  name: replicationFactor
  type: integer
- container: set
  name: configs
  type: reference
- container: ''
  name: errorCode
  type: integer
- container: ''
  name: offset
  type: integer
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: resourceType
  type: string
- container: ''
  name: resourceName
  type: string
- container: ''
  name: patternType
  type: string
- container: ''
  name: principal
  type: string
- container: ''
  name: host
  type: string
- container: ''
  name: operation
  type: string
- container: ''
  name: permission
  type: string
- container: ''
  name: isInternal
  type: boolean
- container: ''
  name: partitions
  type: reference
- container: ''
  name: related
  type: string
- container: ''
  name: brokerId
  type: integer
- container: ''
  name: port
  type: integer
- container: ''
  name: consumerGroupId
  type: string
- container: ''
  name: isSimple
  type: boolean
- container: ''
  name: partitionAssignor
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: coordinator
  type: reference
- container: ''
  name: consumers
  type: reference
- container: ''
  name: lagSummary
  type: reference
- container: ''
  name: self
  type: string
- container: ''
  name: controller
  type: reference
- container: ''
  name: brokers
  type: reference
- container: ''
  name: topics
  type: reference
property_count: 41
provider_name: Apache Kafka
provider_slug: apache-kafka
slug: apache-kafka-kafka-rest-proxy-context
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
