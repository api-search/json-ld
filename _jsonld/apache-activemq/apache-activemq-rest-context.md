---
api_specs:
- filename: apache-activemq-rest-openapi.yaml
  format: yaml
  label: Apache ActiveMQ REST API
  slug: apache-activemq-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-activemq/refs/heads/main/openapi/apache-activemq-rest-openapi.yaml
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
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amq\": \"https://activemq.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"JolokiaResponse\": \"amq:JolokiaResponse\",\n    \"request\": {\n      \"@id\": \"amq:request\",\n      \"@type\": \"@id\"\n    },\n    \"value\": {\n      \"@id\": \"amq:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"amq:timestamp\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"status\": {\n      \"@id\": \"amq:status\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"JolokiaError\": \"amq:JolokiaError\",\n    \"errorType\": {\n      \"@id\": \"amq:error_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"error\": {\n      \"@id\": \"amq:error\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-activemq/refs/heads/main/json-ld/apache-activemq-rest-context.jsonld
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
