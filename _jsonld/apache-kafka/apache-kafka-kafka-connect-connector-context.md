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
class_count: 5
classes:
- ConnectorStatus
- ConnectorPlugin
- ConnectorInfo
- name
- version
context_file: json-ld/apache-kafka-kafka-connect-connector-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-kafka/refs/heads/main/json-ld/apache-kafka-kafka-connect-connector-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Kafka Kafka Connect Connector from Apache Kafka.
layout: jsonld
name: Apache Kafka Kafka Connect Connector Context
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
  name: connector
  type: reference
- container: ''
  name: state
  type: string
- container: ''
  name: workerId
  type: string
- container: set
  name: tasks
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: class
  type: string
- container: ''
  name: config
  type: reference
property_count: 7
provider_name: Apache Kafka
provider_slug: apache-kafka
slug: apache-kafka-kafka-connect-connector-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"kafka\": \"https://apache-kafka.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ConnectorStatus\": \"kafka:ConnectorStatus\",\n    \"ConnectorPlugin\": \"kafka:ConnectorPlugin\",\n    \"ConnectorInfo\": \"kafka:ConnectorInfo\",\n    \"name\": \"schema:name\",\n    \"connector\": {\n      \"@id\": \"kafka:connector\",\n      \"@type\": \"@id\"\n    },\n    \"state\": {\n      \"@id\": \"kafka:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"workerId\": {\n      \"@id\": \"kafka:worker_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tasks\": {\n      \"@id\": \"kafka:tasks\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"kafka:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"class\": {\n      \"@id\": \"kafka:class\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"version\": \"schema:version\",\n    \"config\": {\n      \"@id\": \"kafka:config\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-kafka/refs/heads/main/json-ld/apache-kafka-kafka-connect-connector-context.jsonld
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
