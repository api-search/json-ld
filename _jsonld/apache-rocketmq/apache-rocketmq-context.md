---
api_specs:
- filename: apache-rocketmq-rest-api.yaml
  format: yaml
  label: Apache RocketMQ
  slug: apache-rocketmq
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-rocketmq/refs/heads/main/openapi/apache-rocketmq-rest-api.yaml
class_count: 14
classes:
- TopicList
- Topic
- TopicRequest
- MessageRequest
- SendResult
- ReceiveRequest
- ReceiveResult
- Message
- AckRequest
- ConsumerGroupList
- ConsumerGroup
- ConsumerGroupRequest
- BrokerList
- Broker
context_file: json-ld/apache-rocketmq-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-rocketmq/refs/heads/main/json-ld/apache-rocketmq-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Rocketmq from Apache RocketMQ.
layout: jsonld
name: Apache Rocketmq Context
namespaces:
- prefix: rock
  uri: https://rocketmq.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: topics
  type: ''
- container: ''
  name: total
  type: integer
- container: ''
  name: name
  type: schema:name
- container: ''
  name: clusterName
  type: string
- container: ''
  name: queueNum
  type: integer
- container: ''
  name: perm
  type: integer
- container: ''
  name: topicFilterType
  type: string
- container: ''
  name: topic
  type: string
- container: ''
  name: body
  type: string
- container: ''
  name: tag
  type: string
- container: set
  name: keys
  type: ''
- container: ''
  name: properties
  type: string
- container: ''
  name: delayLevel
  type: integer
- container: ''
  name: msgId
  type: string
- container: ''
  name: offsetMsgId
  type: string
- container: ''
  name: queueOffset
  type: integer
- container: ''
  name: queueId
  type: integer
- container: ''
  name: sendStatus
  type: string
- container: ''
  name: consumerGroup
  type: string
- container: ''
  name: maxMessages
  type: integer
- container: ''
  name: invisibleDuration
  type: integer
- container: set
  name: messages
  type: ''
- container: ''
  name: bornTimestamp
  type: integer
- container: ''
  name: receiptHandle
  type: string
- container: set
  name: groups
  type: ''
- container: ''
  name: consumeFromWhere
  type: string
- container: ''
  name: consumeType
  type: string
- container: ''
  name: messageModel
  type: string
- container: set
  name: brokers
  type: ''
- container: ''
  name: brokerName
  type: string
- container: ''
  name: clusterId
  type: string
- container: ''
  name: brokerId
  type: integer
- container: ''
  name: brokerAddr
  type: string
- container: ''
  name: version
  type: string
property_count: 34
provider_name: Apache RocketMQ
provider_slug: apache-rocketmq
slug: apache-rocketmq-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"rock\": \"https://rocketmq.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"TopicList\": \"rock:TopicList\",\n    \"Topic\": \"rock:Topic\",\n    \"TopicRequest\": \"rock:TopicRequest\",\n    \"MessageRequest\": \"rock:MessageRequest\",\n    \"SendResult\": \"rock:SendResult\",\n    \"ReceiveRequest\": \"rock:ReceiveRequest\",\n    \"ReceiveResult\": \"rock:ReceiveResult\",\n    \"Message\": \"rock:Message\",\n    \"AckRequest\": \"rock:AckRequest\",\n    \"ConsumerGroupList\": \"rock:ConsumerGroupList\",\n    \"ConsumerGroup\": \"rock:ConsumerGroup\",\n    \"ConsumerGroupRequest\": \"rock:ConsumerGroupRequest\",\n    \"BrokerList\": \"rock:BrokerList\",\n    \"Broker\": \"rock:Broker\",\n    \"topics\": {\n      \"@id\": \"rock:topics\",\n      \"@container\": \"@set\"\n    },\n    \"total\": {\n      \"@id\": \"rock:total\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"name\": {\n      \"@id\": \"rock:name\",\n      \"@type\": \"schema:name\"\n    },\n    \"clusterName\": {\n      \"@id\": \"rock:clusterName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queueNum\": {\n      \"@id\": \"rock:queueNum\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"perm\": {\n      \"@id\": \"rock:perm\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"topicFilterType\": {\n      \"@id\": \"rock:topicFilterType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"topic\": {\n      \"@id\": \"rock:topic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"body\": {\n      \"@id\": \"rock:body\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tag\": {\n      \"@id\": \"rock:tag\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keys\": {\n      \"@id\": \"rock:keys\",\n      \"@container\": \"@set\"\n    },\n    \"properties\": {\n      \"@id\": \"rock:properties\",\n      \"@type\": \"xsd:string\"\n    },\n    \"delayLevel\": {\n      \"@id\": \"rock:delayLevel\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"msgId\": {\n      \"@id\": \"rock:msgId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"offsetMsgId\": {\n      \"@id\": \"rock:offsetMsgId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queueOffset\": {\n      \"@id\": \"rock:queueOffset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"queueId\": {\n      \"@id\": \"rock:queueId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sendStatus\": {\n      \"@id\": \"rock:sendStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"consumerGroup\": {\n      \"@id\": \"rock:consumerGroup\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxMessages\": {\n      \"@id\": \"rock:maxMessages\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"invisibleDuration\": {\n      \"@id\": \"rock:invisibleDuration\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"messages\": {\n      \"@id\": \"rock:messages\",\n      \"@container\": \"@set\"\n    },\n    \"bornTimestamp\": {\n      \"@id\"\
  : \"rock:bornTimestamp\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"receiptHandle\": {\n      \"@id\": \"rock:receiptHandle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groups\": {\n      \"@id\": \"rock:groups\",\n      \"@container\": \"@set\"\n    },\n    \"consumeFromWhere\": {\n      \"@id\": \"rock:consumeFromWhere\",\n      \"@type\": \"xsd:string\"\n    },\n    \"consumeType\": {\n      \"@id\": \"rock:consumeType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"messageModel\": {\n      \"@id\": \"rock:messageModel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brokers\": {\n      \"@id\": \"rock:brokers\",\n      \"@container\": \"@set\"\n    },\n    \"brokerName\": {\n      \"@id\": \"rock:brokerName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clusterId\": {\n      \"@id\": \"rock:clusterId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brokerId\": {\n      \"@id\": \"rock:brokerId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"brokerAddr\"\
  : {\n      \"@id\": \"rock:brokerAddr\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"rock:version\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-rocketmq/refs/heads/main/json-ld/apache-rocketmq-context.jsonld
tags:
- Cloud Native
- Messaging
- Message Queue
- Pub-Sub
- Streaming
- Apache
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
