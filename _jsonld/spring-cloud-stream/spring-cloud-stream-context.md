---
class_count: 7
classes:
- StreamBinding
- MessageChannel
- ConsumerGroup
- KafkaBinder
- RabbitMQBinder
- SoftwareApplication
- url
context_file: json-ld/spring-cloud-stream-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/spring-cloud-stream/refs/heads/main/json-ld/spring-cloud-stream-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Spring Cloud Stream from Spring Cloud Stream.
layout: jsonld
name: Spring Cloud Stream Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: spring
  uri: https://spring.io/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: destination
  type: string
- container: ''
  name: group
  type: string
- container: ''
  name: contentType
  type: ''
- container: ''
  name: binder
  type: string
- container: ''
  name: concurrency
  type: integer
- container: ''
  name: partitioned
  type: boolean
- container: ''
  name: partitionCount
  type: integer
- container: ''
  name: name
  type: ''
- container: ''
  name: description
  type: ''
property_count: 9
provider_name: Spring Cloud Stream
provider_slug: spring-cloud-stream
slug: spring-cloud-stream-context
source_filename: spring-cloud-stream-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"spring\": \"https://spring.io/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"StreamBinding\": \"spring:StreamBinding\",\n    \"MessageChannel\": \"spring:MessageChannel\",\n    \"ConsumerGroup\": \"spring:ConsumerGroup\",\n    \"KafkaBinder\": \"spring:KafkaBinder\",\n    \"RabbitMQBinder\": \"spring:RabbitMQBinder\",\n\n    \"destination\": {\n      \"@id\": \"spring:destination\",\n      \"@type\": \"xsd:string\"\n    },\n    \"group\": {\n      \"@id\": \"spring:group\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contentType\": {\n      \"@id\": \"schema:encodingFormat\"\n    },\n    \"binder\": {\n      \"@id\": \"spring:binder\",\n      \"@type\": \"xsd:string\"\n    },\n    \"concurrency\": {\n      \"@id\": \"spring:concurrency\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"partitioned\": {\n      \"@id\": \"spring:partitioned\",\n      \"\
  @type\": \"xsd:boolean\"\n    },\n    \"partitionCount\": {\n      \"@id\": \"spring:partitionCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"url\": \"schema:url\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/spring-cloud-stream/refs/heads/main/json-ld/spring-cloud-stream-context.jsonld
tags:
- Apache Kafka
- AsyncAPI
- Event-Driven
- Java
- Messaging
- Microservices
- RabbitMQ
- Spring Framework
- Stream Processing
- JSON-LD
- Linked Data
- Semantic Web
---
