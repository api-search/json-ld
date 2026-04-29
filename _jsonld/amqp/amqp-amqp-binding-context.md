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
- AMQP Binding
context_file: json-ld/amqp-amqp-binding-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amqp/refs/heads/main/json-ld/amqp-amqp-binding-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amqp Amqp Binding from AMQP.
layout: jsonld
name: Amqp Amqp Binding Context
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
  name: source
  type: string
- container: ''
  name: destination
  type: string
- container: ''
  name: destinationType
  type: string
- container: ''
  name: routingKey
  type: string
- container: ''
  name: arguments
  type: reference
property_count: 5
provider_name: AMQP
provider_slug: amqp
slug: amqp-amqp-binding-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amqp\": \"https://www.amqp.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AMQP Binding\": \"amqp:AMQP Binding\",\n    \"source\": {\n      \"@id\": \"amqp:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destination\": {\n      \"@id\": \"amqp:destination\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destinationType\": {\n      \"@id\": \"amqp:destinationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"routingKey\": {\n      \"@id\": \"amqp:routingKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arguments\": {\n      \"@id\": \"amqp:arguments\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amqp/refs/heads/main/json-ld/amqp-amqp-binding-context.jsonld
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
