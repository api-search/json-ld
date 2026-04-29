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
- AMQP Exchange
context_file: json-ld/amqp-amqp-exchange-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amqp/refs/heads/main/json-ld/amqp-amqp-exchange-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amqp Amqp Exchange from AMQP.
layout: jsonld
name: Amqp Amqp Exchange Context
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
  name: name
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: durable
  type: boolean
- container: ''
  name: autoDelete
  type: boolean
- container: ''
  name: internal
  type: boolean
- container: ''
  name: arguments
  type: reference
property_count: 6
provider_name: AMQP
provider_slug: amqp
slug: amqp-amqp-exchange-context
source_filename: amqp-amqp-exchange-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amqp\": \"https://www.amqp.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AMQP Exchange\": \"amqp:AMQP Exchange\",\n    \"name\": {\n      \"@id\": \"amqp:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"amqp:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"durable\": {\n      \"@id\": \"amqp:durable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"autoDelete\": {\n      \"@id\": \"amqp:autoDelete\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"internal\": {\n      \"@id\": \"amqp:internal\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"arguments\": {\n      \"@id\": \"amqp:arguments\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amqp/refs/heads/main/json-ld/amqp-amqp-exchange-context.jsonld
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
