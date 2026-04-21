---
class_count: 2
classes:
- JolokiaResponse
- JolokiaError
context_file: json-ld/apache-activemq-rest-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-activemq/refs/heads/main/json-ld/apache-activemq-rest-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Activemq Rest from Apache ActiveMQ.
layout: jsonld
name: Apache Activemq Rest Context
namespaces:
- prefix: amq
  uri: https://activemq.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: request
  type: reference
- container: ''
  name: value
  type: string
- container: ''
  name: timestamp
  type: integer
- container: ''
  name: status
  type: integer
- container: ''
  name: errorType
  type: string
- container: ''
  name: error
  type: string
property_count: 6
provider_name: Apache ActiveMQ
provider_slug: apache-activemq
slug: apache-activemq-rest-context
tags:
- AMQP
- Apache
- Java
- JMS
- Message Broker
- Messaging
- MQTT
- Open Source
- STOMP
- JSON-LD
- Linked Data
- Semantic Web
---
