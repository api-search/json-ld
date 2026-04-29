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
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"puls\": \"https://pulsar.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ClusterData\": \"puls:ClusterData\",\n    \"TenantInfo\": \"puls:TenantInfo\",\n    \"Policies\": \"puls:Policies\",\n    \"RetentionPolicies\": \"puls:RetentionPolicies\",\n    \"TopicStats\": \"puls:TopicStats\",\n    \"FunctionConfig\": \"puls:FunctionConfig\",\n    \"PulsarMessage\": \"puls:PulsarMessage\",\n    \"serviceUrl\": {\n      \"@id\": \"puls:serviceUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceUrlTls\": {\n      \"@id\": \"puls:serviceUrlTls\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brokerServiceUrl\": {\n      \"@id\": \"puls:brokerServiceUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brokerServiceUrlTls\": {\n      \"@id\": \"puls:brokerServiceUrlTls\",\n      \"@type\": \"xsd:string\"\n    },\n    \"peerClusterNames\": {\n   \
  \   \"@id\": \"puls:peerClusterNames\",\n      \"@container\": \"@set\"\n    },\n    \"adminRoles\": {\n      \"@id\": \"puls:adminRoles\",\n      \"@container\": \"@set\"\n    },\n    \"allowedClusters\": {\n      \"@id\": \"puls:allowedClusters\",\n      \"@container\": \"@set\"\n    },\n    \"replication_clusters\": {\n      \"@id\": \"puls:replication_clusters\",\n      \"@container\": \"@set\"\n    },\n    \"bundles\": {\n      \"@id\": \"puls:bundles\",\n      \"@type\": \"xsd:string\"\n    },\n    \"retention_policies\": {\n      \"@id\": \"puls:retention_policies\",\n      \"@type\": \"xsd:string\"\n    },\n    \"schema_auto_update_compatibility_strategy\": {\n      \"@id\": \"puls:schema_auto_update_compatibility_strategy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message_ttl_in_seconds\": {\n      \"@id\": \"puls:message_ttl_in_seconds\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"max_producers_per_topic\": {\n      \"@id\": \"puls:max_producers_per_topic\",\n \
  \     \"@type\": \"xsd:integer\"\n    },\n    \"max_consumers_per_topic\": {\n      \"@id\": \"puls:max_consumers_per_topic\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"max_consumers_per_subscription\": {\n      \"@id\": \"puls:max_consumers_per_subscription\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"backlog_quota_map\": {\n      \"@id\": \"puls:backlog_quota_map\",\n      \"@type\": \"xsd:string\"\n    },\n    \"retentionTimeInMinutes\": {\n      \"@id\": \"puls:retentionTimeInMinutes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"retentionSizeInMB\": {\n      \"@id\": \"puls:retentionSizeInMB\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"msgRateIn\": {\n      \"@id\": \"puls:msgRateIn\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"msgRateOut\": {\n      \"@id\": \"puls:msgRateOut\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"msgThroughputIn\": {\n      \"@id\": \"puls:msgThroughputIn\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"msgThroughputOut\"\
  : {\n      \"@id\": \"puls:msgThroughputOut\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"averageMsgSize\": {\n      \"@id\": \"puls:averageMsgSize\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"storageSize\": {\n      \"@id\": \"puls:storageSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"backlogSize\": {\n      \"@id\": \"puls:backlogSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"publishers\": {\n      \"@id\": \"puls:publishers\",\n      \"@container\": \"@set\"\n    },\n    \"subscriptions\": {\n      \"@id\": \"puls:subscriptions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tenant\": {\n      \"@id\": \"puls:tenant\",\n      \"@type\": \"xsd:string\"\n    },\n    \"namespace\": {\n      \"@id\": \"puls:namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"puls:name\",\n      \"@type\": \"schema:name\"\n    },\n    \"className\": {\n      \"@id\": \"puls:className\",\n      \"@type\": \"xsd:string\"\n    },\n   \
  \ \"inputs\": {\n      \"@id\": \"puls:inputs\",\n      \"@container\": \"@set\"\n    },\n    \"output\": {\n      \"@id\": \"puls:output\",\n      \"@type\": \"xsd:string\"\n    },\n    \"logTopic\": {\n      \"@id\": \"puls:logTopic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"processingGuarantees\": {\n      \"@id\": \"puls:processingGuarantees\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parallelism\": {\n      \"@id\": \"puls:parallelism\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"runtime\": {\n      \"@id\": \"puls:runtime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"autoAck\": {\n      \"@id\": \"puls:autoAck\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"userConfig\": {\n      \"@id\": \"puls:userConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"messageId\": {\n      \"@id\": \"puls:messageId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payload\": {\n      \"@id\": \"puls:payload\",\n      \"@type\": \"xsd:string\"\n    },\n    \"key\"\
  : {\n      \"@id\": \"puls:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orderingKey\": {\n      \"@id\": \"puls:orderingKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"properties\": {\n      \"@id\": \"puls:properties\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publishTime\": {\n      \"@id\": \"puls:publishTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventTime\": {\n      \"@id\": \"puls:eventTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sequenceId\": {\n      \"@id\": \"puls:sequenceId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"producerName\": {\n      \"@id\": \"puls:producerName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"redeliveryCount\": {\n      \"@id\": \"puls:redeliveryCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"schemaVersion\": {\n      \"@id\": \"puls:schemaVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"topic\": {\n      \"@id\": \"puls:topic\",\n      \"@type\": \"xsd:string\"\n    }\n \
  \ }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-pulsar/refs/heads/main/json-ld/apache-pulsar-context.jsonld
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
