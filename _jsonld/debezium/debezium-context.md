---
api_specs:
- filename: debezium-connect.yml
  format: yaml
  label: Debezium Kafka Connect REST API
  slug: debezium-kafka-connect-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/debezium/refs/heads/main/openapi/debezium-connect.yml
class_count: 4
classes:
- Connector
- Task
- ChangeEvent
- Source
context_file: json-ld/debezium-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/debezium/refs/heads/main/json-ld/debezium-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Debezium from Debezium.
layout: jsonld
name: Debezium Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: debezium
  uri: https://schema.debezium.io/
properties:
- container: ''
  name: name
  type: schema:Text
- container: ''
  name: config
  type: ''
- container: ''
  name: status
  type: schema:Text
- container: ''
  name: type
  type: schema:Text
- container: ''
  name: before
  type: ''
- container: ''
  name: after
  type: ''
- container: ''
  name: op
  type: schema:Text
- container: ''
  name: ts_ms
  type: schema:Integer
- container: ''
  name: topic
  type: schema:Text
property_count: 9
provider_name: Debezium
provider_slug: debezium
slug: debezium-context
source_filename: debezium-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.debezium.io/\",\n    \"schema\": \"https://schema.org/\",\n    \"debezium\": \"https://schema.debezium.io/\",\n    \"Connector\": \"debezium:Connector\",\n    \"Task\": \"debezium:Task\",\n    \"ChangeEvent\": \"debezium:ChangeEvent\",\n    \"Source\": \"debezium:Source\",\n    \"name\": {\"@id\": \"schema:name\", \"@type\": \"schema:Text\"},\n    \"config\": {\"@id\": \"debezium:config\"},\n    \"status\": {\"@id\": \"debezium:status\", \"@type\": \"schema:Text\"},\n    \"type\": {\"@id\": \"schema:additionalType\", \"@type\": \"schema:Text\"},\n    \"before\": {\"@id\": \"debezium:before\"},\n    \"after\": {\"@id\": \"debezium:after\"},\n    \"op\": {\"@id\": \"debezium:operation\", \"@type\": \"schema:Text\"},\n    \"ts_ms\": {\"@id\": \"debezium:tsMs\", \"@type\": \"schema:Integer\"},\n    \"topic\": {\"@id\": \"debezium:topic\", \"@type\": \"schema:Text\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/debezium/refs/heads/main/json-ld/debezium-context.jsonld
tags:
- Apache Kafka
- CDC
- Change Data Capture
- Databases
- Event Streaming
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
