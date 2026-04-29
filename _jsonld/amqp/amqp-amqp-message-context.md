---
api_specs:
- filename: amqp-messaging.yml
  format: yaml
  label: AMQP Messaging API
  slug: ''
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/amqp/refs/heads/main/asyncapi/amqp-messaging.yml
class_count: 1
classes:
- AMQP Message
context_file: json-ld/amqp-amqp-message-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amqp/refs/heads/main/json-ld/amqp-amqp-message-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amqp Amqp Message from AMQP.
layout: jsonld
name: Amqp Amqp Message Context
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
  name: properties
  type: string
- container: ''
  name: headers
  type: reference
- container: ''
  name: body
  type: string
- container: ''
  name: exchange
  type: string
- container: ''
  name: routingKey
  type: string
- container: ''
  name: mandatory
  type: boolean
- container: ''
  name: immediate
  type: boolean
property_count: 7
provider_name: AMQP
provider_slug: amqp
slug: amqp-amqp-message-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amqp\": \"https://www.amqp.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AMQP Message\": \"amqp:AMQP Message\",\n    \"properties\": {\n      \"@id\": \"amqp:properties\",\n      \"@type\": \"xsd:string\"\n    },\n    \"headers\": {\n      \"@id\": \"amqp:headers\",\n      \"@type\": \"@id\"\n    },\n    \"body\": {\n      \"@id\": \"amqp:body\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exchange\": {\n      \"@id\": \"amqp:exchange\",\n      \"@type\": \"xsd:string\"\n    },\n    \"routingKey\": {\n      \"@id\": \"amqp:routingKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mandatory\": {\n      \"@id\": \"amqp:mandatory\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"immediate\": {\n      \"@id\": \"amqp:immediate\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amqp/refs/heads/main/json-ld/amqp-amqp-message-context.jsonld
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
