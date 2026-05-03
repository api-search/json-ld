---
api_specs:
- filename: spring-integration-http-openapi.yml
  format: yaml
  label: Spring Integration HTTP Adapter API
  slug: spring-integration-http
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spring-integration/refs/heads/main/openapi/spring-integration-http-openapi.yml
- filename: spring-integration-management-openapi.yml
  format: yaml
  label: Spring Integration Management API
  slug: spring-integration-management
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spring-integration/refs/heads/main/openapi/spring-integration-management-openapi.yml
class_count: 3
classes:
- name
- description
- url
context_file: json-ld/spring-integration-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/spring-integration/refs/heads/main/json-ld/spring-integration-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Spring Integration from Spring Integration.
layout: jsonld
name: Spring Integration Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: eip
  uri: https://www.enterpriseintegrationpatterns.com/vocab/
- prefix: springint
  uri: https://spring.io/projects/spring-integration/vocab/
properties:
- container: ''
  name: MessageChannel
  type: reference
- container: ''
  name: MessageHandler
  type: reference
- container: ''
  name: MessageEndpoint
  type: reference
- container: ''
  name: Message
  type: reference
- container: ''
  name: MessageRouter
  type: reference
- container: ''
  name: MessageFilter
  type: reference
- container: ''
  name: MessageTranslator
  type: reference
- container: ''
  name: ServiceActivator
  type: reference
- container: ''
  name: Aggregator
  type: reference
- container: ''
  name: Splitter
  type: reference
- container: ''
  name: payload
  type: ''
- container: ''
  name: headers
  type: ''
- container: ''
  name: correlationId
  type: ''
- container: ''
  name: replyChannel
  type: ''
- container: ''
  name: errorChannel
  type: ''
- container: ''
  name: sequenceNumber
  type: ''
- container: ''
  name: sequenceSize
  type: ''
- container: ''
  name: channelType
  type: ''
- container: ''
  name: handlerType
  type: ''
- container: ''
  name: sendCount
  type: ''
- container: ''
  name: handleCount
  type: ''
property_count: 21
provider_name: Spring Integration
provider_slug: spring-integration
slug: spring-integration-context
source_filename: spring-integration-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"eip\": \"https://www.enterpriseintegrationpatterns.com/vocab/\",\n    \"springint\": \"https://spring.io/projects/spring-integration/vocab/\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n\n    \"MessageChannel\": {\n      \"@id\": \"eip:MessageChannel\",\n      \"@type\": \"@id\"\n    },\n    \"MessageHandler\": {\n      \"@id\": \"eip:MessageHandler\",\n      \"@type\": \"@id\"\n    },\n    \"MessageEndpoint\": {\n      \"@id\": \"eip:MessageEndpoint\",\n      \"@type\": \"@id\"\n    },\n    \"Message\": {\n      \"@id\": \"eip:Message\",\n      \"@type\": \"@id\"\n    },\n    \"MessageRouter\": {\n      \"@id\": \"eip:MessageRouter\",\n      \"@type\": \"@id\"\n    },\n    \"MessageFilter\": {\n      \"@id\": \"eip:MessageFilter\",\n      \"@type\": \"@id\"\n    },\n    \"MessageTranslator\": {\n      \"@id\": \"\
  eip:MessageTranslator\",\n      \"@type\": \"@id\"\n    },\n    \"ServiceActivator\": {\n      \"@id\": \"eip:ServiceActivator\",\n      \"@type\": \"@id\"\n    },\n    \"Aggregator\": {\n      \"@id\": \"eip:Aggregator\",\n      \"@type\": \"@id\"\n    },\n    \"Splitter\": {\n      \"@id\": \"eip:Splitter\",\n      \"@type\": \"@id\"\n    },\n\n    \"payload\": { \"@id\": \"eip:payload\" },\n    \"headers\": { \"@id\": \"eip:headers\" },\n    \"correlationId\": { \"@id\": \"eip:correlationId\" },\n    \"replyChannel\": { \"@id\": \"eip:replyChannel\" },\n    \"errorChannel\": { \"@id\": \"eip:errorChannel\" },\n    \"sequenceNumber\": { \"@id\": \"eip:sequenceNumber\" },\n    \"sequenceSize\": { \"@id\": \"eip:sequenceSize\" },\n\n    \"channelType\": { \"@id\": \"springint:channelType\" },\n    \"handlerType\": { \"@id\": \"springint:handlerType\" },\n    \"sendCount\": { \"@id\": \"springint:sendCount\" },\n    \"handleCount\": { \"@id\": \"springint:handleCount\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/spring-integration/refs/heads/main/json-ld/spring-integration-context.jsonld
tags:
- AMQP
- Enterprise Integration
- Event-Driven
- Integration Patterns
- Java
- Messaging
- Spring
- JSON-LD
- Linked Data
- Semantic Web
---
