---
class_count: 7
classes:
- ClusterData
- TenantInfo
- Policies
- RetentionPolicies
- TopicStats
- FunctionConfig
- PulsarMessage
context_file: json-ld/apache-pulsar-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-pulsar/refs/heads/main/json-ld/apache-pulsar-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Pulsar from Apache Pulsar.
layout: jsonld
name: Apache Pulsar Context
namespaces:
- prefix: puls
  uri: https://pulsar.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: serviceUrl
  type: string
- container: ''
  name: serviceUrlTls
  type: string
- container: ''
  name: brokerServiceUrl
  type: string
- container: ''
  name: brokerServiceUrlTls
  type: string
- container: set
  name: peerClusterNames
  type: ''
- container: set
  name: adminRoles
  type: ''
- container: set
  name: allowedClusters
  type: ''
- container: set
  name: replication_clusters
  type: ''
- container: ''
  name: bundles
  type: string
- container: ''
  name: retention_policies
  type: string
- container: ''
  name: schema_auto_update_compatibility_strategy
  type: string
- container: ''
  name: message_ttl_in_seconds
  type: integer
- container: ''
  name: max_producers_per_topic
  type: integer
- container: ''
  name: max_consumers_per_topic
  type: integer
- container: ''
  name: max_consumers_per_subscription
  type: integer
- container: ''
  name: backlog_quota_map
  type: string
- container: ''
  name: retentionTimeInMinutes
  type: integer
- container: ''
  name: retentionSizeInMB
  type: integer
- container: ''
  name: msgRateIn
  type: decimal
- container: ''
  name: msgRateOut
  type: decimal
- container: ''
  name: msgThroughputIn
  type: decimal
- container: ''
  name: msgThroughputOut
  type: decimal
- container: ''
  name: averageMsgSize
  type: decimal
- container: ''
  name: storageSize
  type: integer
- container: ''
  name: backlogSize
  type: integer
- container: set
  name: publishers
  type: ''
- container: ''
  name: subscriptions
  type: string
- container: ''
  name: tenant
  type: string
- container: ''
  name: namespace
  type: string
- container: ''
  name: name
  type: schema:name
- container: ''
  name: className
  type: string
- container: set
  name: inputs
  type: ''
- container: ''
  name: output
  type: string
- container: ''
  name: logTopic
  type: string
- container: ''
  name: processingGuarantees
  type: string
- container: ''
  name: parallelism
  type: integer
- container: ''
  name: runtime
  type: string
- container: ''
  name: autoAck
  type: boolean
- container: ''
  name: userConfig
  type: string
- container: ''
  name: messageId
  type: string
- container: ''
  name: payload
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: orderingKey
  type: string
- container: ''
  name: properties
  type: string
- container: ''
  name: publishTime
  type: string
- container: ''
  name: eventTime
  type: string
- container: ''
  name: sequenceId
  type: integer
- container: ''
  name: producerName
  type: string
- container: ''
  name: redeliveryCount
  type: integer
- container: ''
  name: schemaVersion
  type: string
- container: ''
  name: topic
  type: string
property_count: 51
provider_name: Apache Pulsar
provider_slug: apache-pulsar
slug: apache-pulsar-context
tags:
- Cloud Native
- Messaging
- Multi-Tenant
- Pub-Sub
- Streaming
- Apache
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
