---
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
