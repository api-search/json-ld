---
api_specs:
- filename: rest_api_swagger.json
  format: json
  label: IBM MQ REST API
  slug: ''
  spec_type: OpenAPI
  url: https://www.ibm.com/docs/en/SSFKSJ_9.3.0/com.ibm.mq.dev.doc/rest_api_swagger.json
- filename: messaging_rest_api_swagger.json
  format: json
  label: IBM MQ Messaging REST API
  slug: ''
  spec_type: OpenAPI
  url: https://www.ibm.com/docs/en/SSFKSJ_9.3.0/com.ibm.mq.dev.doc/messaging_rest_api_swagger.json
- filename: ibm-mq-messaging-asyncapi.yml
  format: yaml
  label: IBM MQ JMS API
  slug: ''
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/ibm-mq/refs/heads/main/asyncapi/ibm-mq-messaging-asyncapi.yml
class_count: 0
classes: []
context_file: json-ld/ibm-mq-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ibm-mq/refs/heads/main/json-ld/ibm-mq-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ibm Mq from IBM MQ.
layout: jsonld
name: Ibm Mq Context
namespaces:
- prefix: ibmmq
  uri: https://www.ibm.com/schemas/ibm-mq/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: QueueManager
  type: ''
- container: ''
  name: Queue
  type: ''
- container: ''
  name: Topic
  type: ''
- container: ''
  name: Channel
  type: ''
- container: ''
  name: Subscription
  type: ''
- container: ''
  name: Message
  type: ''
- container: ''
  name: Installation
  type: ''
property_count: 7
provider_name: IBM MQ
provider_slug: ibm-mq
slug: ibm-mq-context
source_filename: ibm-mq-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ibmmq\": \"https://www.ibm.com/schemas/ibm-mq/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"QueueManager\": {\n      \"@id\": \"ibmmq:QueueManager\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"state\": \"ibmmq:state\",\n        \"platform\": \"ibmmq:platform\",\n        \"commandLevel\": {\n          \"@id\": \"ibmmq:commandLevel\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"maximumMessageLength\": {\n          \"@id\": \"ibmmq:maximumMessageLength\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"deadLetterQueue\": \"ibmmq:deadLetterQueue\",\n        \"defaultTransmissionQueue\": \"ibmmq:defaultTransmissionQueue\",\n        \"connectionCount\": {\n          \"@id\": \"ibmmq:connectionCount\",\n          \"\
  @type\": \"xsd:integer\"\n        },\n        \"started\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Queue\": {\n      \"@id\": \"ibmmq:Queue\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"type\": \"ibmmq:queueType\",\n        \"maximumDepth\": {\n          \"@id\": \"ibmmq:maximumDepth\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"maximumMessageLength\": {\n          \"@id\": \"ibmmq:maximumMessageLength\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"currentDepth\": {\n          \"@id\": \"ibmmq:currentDepth\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"inhibitPut\": {\n          \"@id\": \"ibmmq:inhibitPut\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"inhibitGet\": {\n          \"@id\": \"ibmmq:inhibitGet\",\n          \"@type\": \"xsd:boolean\"\n        },\n    \
  \    \"defaultPersistence\": \"ibmmq:defaultPersistence\"\n      }\n    },\n\n    \"Topic\": {\n      \"@id\": \"ibmmq:Topic\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"topicString\": \"ibmmq:topicString\",\n        \"durableSubscriptions\": \"ibmmq:durableSubscriptions\"\n      }\n    },\n\n    \"Channel\": {\n      \"@id\": \"ibmmq:Channel\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"type\": \"ibmmq:channelType\",\n        \"connectionName\": \"ibmmq:connectionName\",\n        \"transmissionQueue\": \"ibmmq:transmissionQueue\",\n        \"state\": \"ibmmq:channelState\",\n        \"messagesTransferred\": {\n          \"@id\": \"ibmmq:messagesTransferred\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"bytesTransferred\": {\n          \"@id\": \"ibmmq:bytesTransferred\",\n          \"@type\": \"xsd:integer\"\n     \
  \   }\n      }\n    },\n\n    \"Subscription\": {\n      \"@id\": \"ibmmq:Subscription\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"topicString\": \"ibmmq:topicString\",\n        \"destination\": \"ibmmq:destination\",\n        \"durability\": \"ibmmq:durability\"\n      }\n    },\n\n    \"Message\": {\n      \"@id\": \"ibmmq:Message\",\n      \"@context\": {\n        \"messageId\": \"ibmmq:messageId\",\n        \"correlationId\": \"ibmmq:correlationId\",\n        \"persistence\": \"ibmmq:persistence\",\n        \"priority\": {\n          \"@id\": \"ibmmq:priority\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"expiry\": {\n          \"@id\": \"ibmmq:expiry\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"replyTo\": \"ibmmq:replyTo\",\n        \"format\": \"ibmmq:format\",\n        \"timestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n\
  \        }\n      }\n    },\n\n    \"Installation\": {\n      \"@id\": \"ibmmq:Installation\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"version\": \"schema:softwareVersion\",\n        \"path\": \"ibmmq:installationPath\",\n        \"platform\": \"ibmmq:platform\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ibm-mq/refs/heads/main/json-ld/ibm-mq-context.jsonld
tags:
- Async
- Enterprise
- Integration
- Messaging
- Middleware
- Queue
- JSON-LD
- Linked Data
- Semantic Web
---
