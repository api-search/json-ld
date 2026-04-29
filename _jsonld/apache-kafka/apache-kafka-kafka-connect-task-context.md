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
class_count: 2
classes:
- TaskInfo
- TaskStatus
context_file: json-ld/apache-kafka-kafka-connect-task-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-kafka/refs/heads/main/json-ld/apache-kafka-kafka-connect-task-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Kafka Kafka Connect Task from Apache Kafka.
layout: jsonld
name: Apache Kafka Kafka Connect Task Context
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
  name: id
  type: reference
- container: ''
  name: connector
  type: string
- container: ''
  name: task
  type: integer
- container: ''
  name: config
  type: reference
- container: ''
  name: state
  type: string
- container: ''
  name: workerId
  type: string
- container: ''
  name: trace
  type: string
property_count: 7
provider_name: Apache Kafka
provider_slug: apache-kafka
slug: apache-kafka-kafka-connect-task-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"kafka\": \"https://apache-kafka.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"TaskInfo\": \"kafka:TaskInfo\",\n    \"TaskStatus\": \"kafka:TaskStatus\",\n    \"id\": {\n      \"@id\": \"kafka:id\",\n      \"@type\": \"@id\"\n    },\n    \"connector\": {\n      \"@id\": \"kafka:connector\",\n      \"@type\": \"xsd:string\"\n    },\n    \"task\": {\n      \"@id\": \"kafka:task\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"config\": {\n      \"@id\": \"kafka:config\",\n      \"@type\": \"@id\"\n    },\n    \"state\": {\n      \"@id\": \"kafka:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"workerId\": {\n      \"@id\": \"kafka:worker_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trace\": {\n      \"@id\": \"kafka:trace\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-kafka/refs/heads/main/json-ld/apache-kafka-kafka-connect-task-context.jsonld
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
