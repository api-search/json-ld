---
api_specs:
- filename: codehooks-database-rest-api-openapi.yml
  format: yaml
  label: Codehooks Database REST API
  slug: codehooks-database-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/codehooks/refs/heads/main/openapi/codehooks-database-rest-api-openapi.yml
- filename: codehooks-events-asyncapi.yml
  format: yaml
  label: Codehooks Events (AsyncAPI)
  slug: codehooks-events
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/codehooks/refs/heads/main/asyncapi/codehooks-events-asyncapi.yml
class_count: 3
classes:
- Document
- KeyValueEntry
- QueueJob
context_file: json-ld/codehooks-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/codehooks/refs/heads/main/json-ld/codehooks-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Codehooks from Codehooks.
layout: jsonld
name: Codehooks Context
namespaces:
- prefix: codehooks
  uri: https://codehooks.io/ns/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: collection
  type: reference
- container: ''
  name: _id
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: value
  type: ''
- container: ''
  name: ttl
  type: integer
- container: ''
  name: topic
  type: string
- container: ''
  name: payload
  type: ''
- container: ''
  name: status
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: completedAt
  type: dateTime
- container: ''
  name: _createdOn
  type: dateTime
- container: ''
  name: _updatedOn
  type: dateTime
property_count: 12
provider_name: Codehooks
provider_slug: codehooks
slug: codehooks-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"codehooks\": \"https://codehooks.io/ns/\",\n    \"Document\": \"codehooks:Document\",\n    \"KeyValueEntry\": \"codehooks:KeyValueEntry\",\n    \"QueueJob\": \"codehooks:QueueJob\",\n    \"collection\": {\n      \"@id\": \"codehooks:collection\",\n      \"@type\": \"@id\"\n    },\n    \"_id\": {\n      \"@id\": \"codehooks:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"key\": {\n      \"@id\": \"codehooks:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"codehooks:value\"\n    },\n    \"ttl\": {\n      \"@id\": \"codehooks:timeToLive\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"topic\": {\n      \"@id\": \"codehooks:topic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payload\": {\n      \"@id\": \"codehooks:payload\"\n    },\n    \"status\": {\n      \"@id\": \"codehooks:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n\
  \      \"@id\": \"codehooks:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"completedAt\": {\n      \"@id\": \"codehooks:completedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"_createdOn\": {\n      \"@id\": \"codehooks:createdOn\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"_updatedOn\": {\n      \"@id\": \"codehooks:updatedOn\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/codehooks/refs/heads/main/json-ld/codehooks-context.jsonld
tags:
- Backend
- Database
- Events
- Hooks
- JavaScript
- NoSQL
- Queues
- Serverless
- Webhooks
- Workers
- Workflows
- JSON-LD
- Linked Data
- Semantic Web
---
