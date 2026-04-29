---
class_count: 1
classes:
- AMQP Message Properties
context_file: json-ld/amqp-amqp-message-properties-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amqp/refs/heads/main/json-ld/amqp-amqp-message-properties-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amqp Amqp Message Properties from AMQP.
layout: jsonld
name: Amqp Amqp Message Properties Context
namespaces:
- prefix: amqp
  uri: https://www.amqp.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: contentType
  type: string
- container: ''
  name: contentEncoding
  type: string
- container: ''
  name: headers
  type: reference
- container: ''
  name: deliveryMode
  type: integer
- container: ''
  name: priority
  type: integer
- container: ''
  name: correlationId
  type: string
- container: ''
  name: replyTo
  type: string
- container: ''
  name: expiration
  type: string
- container: ''
  name: messageId
  type: string
- container: ''
  name: timestamp
  type: integer
- container: ''
  name: type
  type: string
- container: ''
  name: userId
  type: string
- container: ''
  name: appId
  type: string
- container: ''
  name: clusterId
  type: string
property_count: 14
provider_name: AMQP
provider_slug: amqp
slug: amqp-amqp-message-properties-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amqp\": \"https://www.amqp.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AMQP Message Properties\": \"amqp:AMQP Message Properties\",\n    \"contentType\": {\n      \"@id\": \"amqp:contentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contentEncoding\": {\n      \"@id\": \"amqp:contentEncoding\",\n      \"@type\": \"xsd:string\"\n    },\n    \"headers\": {\n      \"@id\": \"amqp:headers\",\n      \"@type\": \"@id\"\n    },\n    \"deliveryMode\": {\n      \"@id\": \"amqp:deliveryMode\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"priority\": {\n      \"@id\": \"amqp:priority\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"correlationId\": {\n      \"@id\": \"amqp:correlationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"replyTo\": {\n      \"@id\": \"amqp:replyTo\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"expiration\": {\n      \"@id\": \"amqp:expiration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"messageId\": {\n      \"@id\": \"amqp:messageId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"amqp:timestamp\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"type\": {\n      \"@id\": \"amqp:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userId\": {\n      \"@id\": \"amqp:userId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"appId\": {\n      \"@id\": \"amqp:appId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clusterId\": {\n      \"@id\": \"amqp:clusterId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amqp/refs/heads/main/json-ld/amqp-amqp-message-properties-context.jsonld
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
