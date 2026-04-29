---
api_specs:
- filename: kafka-rest-proxy.yml
  format: yaml
  label: Kafka REST Proxy API
  slug: kafka-rest-proxy-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-kafka/refs/heads/main/openapi/kafka-rest-proxy.yml
- filename: kafka-connect.yml
  format: yaml
  label: Kafka Connect REST API
  slug: kafka-connect-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-kafka/refs/heads/main/openapi/kafka-connect.yml
- filename: kafka-messaging.yml
  format: yaml
  label: Apache Kafka Messaging API
  slug: kafka-messaging-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-kafka/refs/heads/main/asyncapi/kafka-messaging.yml
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
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"kafka\": \"https://apache-kafka.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Partition\": \"kafka:Partition\",\n    \"ProduceRequest\": \"kafka:ProduceRequest\",\n    \"CreateTopicRequest\": \"kafka:CreateTopicRequest\",\n    \"ProduceResponse\": \"kafka:ProduceResponse\",\n    \"Acl\": \"kafka:Acl\",\n    \"Topic\": \"kafka:Topic\",\n    \"Broker\": \"kafka:Broker\",\n    \"CreateAclRequest\": \"kafka:CreateAclRequest\",\n    \"ConsumerGroup\": \"kafka:ConsumerGroup\",\n    \"Cluster\": \"kafka:Cluster\",\n    \"kind\": {\n      \"@id\": \"kafka:kind\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"kafka:metadata\",\n      \"@type\": \"@id\"\n    },\n    \"clusterId\": {\n      \"@id\": \"kafka:cluster_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"topicName\"\
  : {\n      \"@id\": \"kafka:topic_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partitionId\": {\n      \"@id\": \"kafka:partition_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"leader\": {\n      \"@id\": \"kafka:leader\",\n      \"@type\": \"@id\"\n    },\n    \"replicas\": {\n      \"@id\": \"kafka:replicas\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"headers\": {\n      \"@id\": \"kafka:headers\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"key\": {\n      \"@id\": \"kafka:key\",\n      \"@type\": \"@id\"\n    },\n    \"type\": {\n      \"@id\": \"kafka:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"kafka:data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"kafka:value\",\n      \"@type\": \"@id\"\n    },\n    \"partitionsCount\": {\n      \"@id\": \"kafka:partitions_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"replicationFactor\"\
  : {\n      \"@id\": \"kafka:replication_factor\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"configs\": {\n      \"@id\": \"kafka:configs\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"errorCode\": {\n      \"@id\": \"kafka:error_code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"offset\": {\n      \"@id\": \"kafka:offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"timestamp\": {\n      \"@id\": \"kafka:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"resourceType\": {\n      \"@id\": \"kafka:resource_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceName\": {\n      \"@id\": \"kafka:resource_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"patternType\": {\n      \"@id\": \"kafka:pattern_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"principal\": {\n      \"@id\": \"kafka:principal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"host\": {\n      \"@id\": \"kafka:host\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"operation\": {\n      \"@id\": \"kafka:operation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"permission\": {\n      \"@id\": \"kafka:permission\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isInternal\": {\n      \"@id\": \"kafka:is_internal\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"partitions\": {\n      \"@id\": \"kafka:partitions\",\n      \"@type\": \"@id\"\n    },\n    \"related\": {\n      \"@id\": \"kafka:related\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brokerId\": {\n      \"@id\": \"kafka:broker_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"port\": {\n      \"@id\": \"kafka:port\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"consumerGroupId\": {\n      \"@id\": \"kafka:consumer_group_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isSimple\": {\n      \"@id\": \"kafka:is_simple\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"partitionAssignor\": {\n      \"@id\": \"kafka:partition_assignor\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"kafka:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"coordinator\": {\n      \"@id\": \"kafka:coordinator\",\n      \"@type\": \"@id\"\n    },\n    \"consumers\": {\n      \"@id\": \"kafka:consumers\",\n      \"@type\": \"@id\"\n    },\n    \"lagSummary\": {\n      \"@id\": \"kafka:lag_summary\",\n      \"@type\": \"@id\"\n    },\n    \"self\": {\n      \"@id\": \"kafka:self\",\n      \"@type\": \"xsd:string\"\n    },\n    \"controller\": {\n      \"@id\": \"kafka:controller\",\n      \"@type\": \"@id\"\n    },\n    \"brokers\": {\n      \"@id\": \"kafka:brokers\",\n      \"@type\": \"@id\"\n    },\n    \"topics\": {\n      \"@id\": \"kafka:topics\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-kafka/refs/heads/main/json-ld/apache-kafka-kafka-rest-proxy-context.jsonld
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
