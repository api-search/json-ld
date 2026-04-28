---
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
