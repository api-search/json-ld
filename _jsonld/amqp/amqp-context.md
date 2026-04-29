---
api_specs:
- filename: amqp-messaging.yml
  format: yaml
  label: AMQP Messaging API
  slug: ''
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/amqp/refs/heads/main/asyncapi/amqp-messaging.yml
class_count: 0
classes: []
context_file: json-ld/amqp-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amqp/refs/heads/main/json-ld/amqp-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amqp from AMQP.
layout: jsonld
name: Amqp Context
namespaces:
- prefix: amqp
  uri: https://www.amqp.org/specification/1.0#
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: rdf
  uri: http://www.w3.org/1999/02/22-rdf-syntax-ns#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Message
  type: ''
- container: ''
  name: Exchange
  type: ''
- container: ''
  name: Queue
  type: ''
- container: ''
  name: Binding
  type: ''
- container: ''
  name: Connection
  type: ''
- container: ''
  name: Channel
  type: ''
- container: ''
  name: PublishSubscribe
  type: ''
- container: ''
  name: PointToPoint
  type: ''
- container: ''
  name: RequestReply
  type: ''
property_count: 9
provider_name: AMQP
provider_slug: amqp
slug: amqp-context
source_filename: amqp-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amqp\": \"https://www.amqp.org/specification/1.0#\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"rdf\": \"http://www.w3.org/1999/02/22-rdf-syntax-ns#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Message\": {\n      \"@id\": \"amqp:Message\",\n      \"@context\": {\n        \"body\": {\n          \"@id\": \"amqp:body\",\n          \"rdfs:comment\": \"The payload content of the AMQP message\"\n        },\n        \"messageId\": {\n          \"@id\": \"amqp:message-id\",\n          \"@type\": \"xsd:string\",\n          \"rdfs:comment\": \"Unique identifier for the message\"\n        },\n        \"correlationId\": {\n          \"@id\": \"amqp:correlation-id\",\n          \"@type\": \"xsd:string\",\n          \"rdfs:comment\": \"Identifier used to correlate request and reply messages\"\n        },\n\
  \        \"contentType\": {\n          \"@id\": \"amqp:content-type\",\n          \"@type\": \"xsd:string\",\n          \"schema:sameAs\": \"dcterms:format\"\n        },\n        \"contentEncoding\": {\n          \"@id\": \"amqp:content-encoding\",\n          \"@type\": \"xsd:string\"\n        },\n        \"replyTo\": {\n          \"@id\": \"amqp:reply-to\",\n          \"@type\": \"xsd:string\",\n          \"rdfs:comment\": \"Address for reply messages in the request/reply pattern\"\n        },\n        \"timestamp\": {\n          \"@id\": \"amqp:creation-time\",\n          \"@type\": \"xsd:dateTime\",\n          \"schema:sameAs\": \"dcterms:created\"\n        },\n        \"expiration\": {\n          \"@id\": \"amqp:absolute-expiry-time\",\n          \"@type\": \"xsd:string\"\n        },\n        \"priority\": {\n          \"@id\": \"amqp:priority\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"deliveryMode\": {\n          \"@id\": \"amqp:durable\",\n          \"@type\"\
  : \"xsd:integer\",\n          \"rdfs:comment\": \"1 = non-persistent, 2 = persistent\"\n        },\n        \"userId\": {\n          \"@id\": \"amqp:user-id\",\n          \"@type\": \"xsd:string\",\n          \"schema:sameAs\": \"schema:identifier\"\n        },\n        \"appId\": {\n          \"@id\": \"amqp:group-id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"amqp:subject\",\n          \"@type\": \"xsd:string\",\n          \"schema:sameAs\": \"dcterms:type\"\n        }\n      }\n    },\n\n    \"Exchange\": {\n      \"@id\": \"amqp:Exchange\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"exchangeType\": {\n          \"@id\": \"amqp:exchange-type\",\n          \"@type\": \"xsd:string\",\n          \"rdfs:comment\": \"One of: direct, topic, fanout, headers\"\n        },\n        \"durable\": {\n          \"@id\": \"amqp:durable\",\n         \
  \ \"@type\": \"xsd:boolean\"\n        },\n        \"autoDelete\": {\n          \"@id\": \"amqp:auto-delete\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"internal\": {\n          \"@id\": \"amqp:internal\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Queue\": {\n      \"@id\": \"amqp:Queue\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"durable\": {\n          \"@id\": \"amqp:durable\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"exclusive\": {\n          \"@id\": \"amqp:exclusive\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"autoDelete\": {\n          \"@id\": \"amqp:auto-delete\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"messageCount\": {\n          \"@id\": \"amqp:message-count\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"consumerCount\": {\n          \"@id\": \"amqp:consumer-count\"\
  ,\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Binding\": {\n      \"@id\": \"amqp:Binding\",\n      \"@context\": {\n        \"source\": {\n          \"@id\": \"amqp:source\",\n          \"@type\": \"@id\",\n          \"rdfs:comment\": \"The exchange from which messages are routed\"\n        },\n        \"destination\": {\n          \"@id\": \"amqp:destination\",\n          \"@type\": \"@id\",\n          \"rdfs:comment\": \"The queue or exchange receiving routed messages\"\n        },\n        \"routingKey\": {\n          \"@id\": \"amqp:routing-key\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Connection\": {\n      \"@id\": \"amqp:Connection\",\n      \"schema:sameAs\": \"schema:WebSocket\",\n      \"@context\": {\n        \"host\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"xsd:string\"\n        },\n        \"port\": {\n          \"@id\": \"amqp:port\",\n          \"@type\": \"xsd:integer\"\n        },\n\
  \        \"virtualHost\": {\n          \"@id\": \"amqp:virtual-host\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Channel\": {\n      \"@id\": \"amqp:Channel\",\n      \"@context\": {\n        \"channelNumber\": {\n          \"@id\": \"amqp:channel-number\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"prefetchCount\": {\n          \"@id\": \"amqp:prefetch-count\",\n          \"@type\": \"xsd:integer\",\n          \"rdfs:comment\": \"Maximum number of unacknowledged messages the consumer will receive\"\n        }\n      }\n    },\n\n    \"PublishSubscribe\": {\n      \"@id\": \"amqp:PublishSubscribe\",\n      \"rdfs:subClassOf\": \"schema:Action\",\n      \"rdfs:comment\": \"The publish/subscribe messaging pattern where messages are broadcast to all subscribers via a fanout or topic exchange\"\n    },\n\n    \"PointToPoint\": {\n      \"@id\": \"amqp:PointToPoint\",\n      \"rdfs:subClassOf\": \"schema:Action\",\n      \"rdfs:comment\": \"\
  The point-to-point messaging pattern where each message is consumed by exactly one consumer from a queue\"\n    },\n\n    \"RequestReply\": {\n      \"@id\": \"amqp:RequestReply\",\n      \"rdfs:subClassOf\": \"schema:Action\",\n      \"rdfs:comment\": \"The request/reply messaging pattern using correlation IDs and reply-to queues for synchronous-style communication over asynchronous transport\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amqp/refs/heads/main/json-ld/amqp-context.jsonld
tags:
- AMQP
- Asynchronous
- Message Queue
- Messaging
- Middleware
- Open Standard
- Publish Subscribe
- JSON-LD
- Linked Data
- Semantic Web
---
