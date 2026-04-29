---
class_count: 2
classes:
- CreateConnectorRequest
- name
context_file: json-ld/apache-kafka-kafka-connect-create-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-kafka/refs/heads/main/json-ld/apache-kafka-kafka-connect-create-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Kafka Kafka Connect Create from Apache Kafka.
layout: jsonld
name: Apache Kafka Kafka Connect Create Context
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
  name: config
  type: reference
property_count: 1
provider_name: Apache Kafka
provider_slug: apache-kafka
slug: apache-kafka-kafka-connect-create-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"kafka\": \"https://apache-kafka.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CreateConnectorRequest\": \"kafka:CreateConnectorRequest\",\n    \"name\": \"schema:name\",\n    \"config\": {\n      \"@id\": \"kafka:config\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-kafka/refs/heads/main/json-ld/apache-kafka-kafka-connect-create-context.jsonld
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
