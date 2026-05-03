---
api_specs:
- filename: strimzi-kafka-bridge-openapi.yml
  format: yaml
  label: Strimzi Kafka Bridge REST API
  slug: strimzi-kafka-bridge-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/strimzi/refs/heads/main/openapi/strimzi-kafka-bridge-openapi.yml
class_count: 0
classes: []
context_file: json-ld/strimzi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/strimzi/refs/heads/main/json-ld/strimzi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Strimzi from Strimzi.
layout: jsonld
name: Strimzi Context
namespaces:
- prefix: strimzi
  uri: https://strimzi.io/vocab/
- prefix: kafka
  uri: https://kafka.apache.org/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: k8s
  uri: https://kubernetes.io/api/
properties:
- container: ''
  name: KafkaCluster
  type: ''
- container: ''
  name: KafkaTopic
  type: ''
- container: ''
  name: KafkaUser
  type: ''
- container: ''
  name: Message
  type: ''
property_count: 4
provider_name: Strimzi
provider_slug: strimzi
slug: strimzi-context
source_filename: strimzi-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"strimzi\": \"https://strimzi.io/vocab/\",\n    \"kafka\": \"https://kafka.apache.org/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"k8s\": \"https://kubernetes.io/api/\",\n\n    \"KafkaCluster\": {\n      \"@id\": \"strimzi:KafkaCluster\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"namespace\": \"k8s:namespace\",\n        \"replicas\": {\n          \"@id\": \"strimzi:replicas\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"version\": {\n          \"@id\": \"strimzi:kafkaVersion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"bootstrapServers\": {\n          \"@id\": \"kafka:bootstrapServers\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"KafkaTopic\": {\n      \"@id\": \"kafka:Topic\",\n      \"@context\": {\n        \"name\"\
  : \"schema:name\",\n        \"partitions\": {\n          \"@id\": \"kafka:partitions\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"replicas\": {\n          \"@id\": \"kafka:replicationFactor\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"config\": \"kafka:topicConfig\"\n      }\n    },\n\n    \"KafkaUser\": {\n      \"@id\": \"strimzi:KafkaUser\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"authentication\": \"strimzi:authentication\",\n        \"authorization\": \"strimzi:authorization\"\n      }\n    },\n\n    \"Message\": {\n      \"@id\": \"kafka:Message\",\n      \"@context\": {\n        \"topic\": \"kafka:topic\",\n        \"partition\": {\n          \"@id\": \"kafka:partition\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"offset\": {\n          \"@id\": \"kafka:offset\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"key\": \"kafka:messageKey\",\n        \"value\": \"kafka:messageValue\"\
  ,\n        \"timestamp\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/strimzi/refs/heads/main/json-ld/strimzi-context.jsonld
tags:
- Kafka
- Kubernetes
- Messaging
- Operator
- Streaming
- JSON-LD
- Linked Data
- Semantic Web
---
