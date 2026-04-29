---
api_specs:
- filename: actor-model.json
  format: json
  label: Actor Model API
  slug: actor-model-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/actor-model/refs/heads/main/openapi/actor-model.json
class_count: 53
classes:
- Actor
- ActorList
- ActorMessage
- MailboxInspection
- Supervisor
- ClusterMember
- Shard
- SystemHealth
- id
- path
- behavior
- status
- mailboxSize
- supervisorId
- messageCount
- restartCount
- actors
- total
- cursor
- type
- payload
- replyTo
- correlationId
- priority
- actorId
- pendingCount
- messages
- oldestMessageAge
- strategy
- maxRestarts
- restartWindow
- childCount
- supervisors
- nodeId
- address
- roles
- actorCount
- members
- leader
- totalActors
- shardId
- region
- entityCount
- shards
- totalShards
- totalEntities
- activeActors
- messagesPerSecond
- errorRate
- deadLetters
- clusterSize
- uptime
- initialState
context_file: json-ld/actor-model-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/actor-model/refs/heads/main/json-ld/actor-model-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Actor Model from Actor Model.
layout: jsonld
name: Actor Model Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: actor
  uri: https://vocab.api-evangelist.com/actor-model/
properties:
- container: ''
  name: spawnedAt
  type: dateTime
- container: ''
  name: lastMessageAt
  type: dateTime
- container: ''
  name: upSince
  type: dateTime
property_count: 3
provider_name: Actor Model
provider_slug: actor-model
slug: actor-model-context
source_filename: actor-model-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"actor\": \"https://vocab.api-evangelist.com/actor-model/\",\n\n    \"Actor\": \"actor:Actor\",\n    \"ActorList\": \"actor:ActorList\",\n    \"ActorMessage\": \"actor:ActorMessage\",\n    \"MailboxInspection\": \"actor:MailboxInspection\",\n    \"Supervisor\": \"actor:Supervisor\",\n    \"ClusterMember\": \"actor:ClusterMember\",\n    \"Shard\": \"actor:Shard\",\n    \"SystemHealth\": \"actor:SystemHealth\",\n\n    \"id\": \"@id\",\n    \"path\": \"actor:path\",\n    \"behavior\": \"actor:behavior\",\n    \"status\": \"actor:status\",\n    \"mailboxSize\": \"actor:mailboxSize\",\n    \"supervisorId\": \"actor:supervisorId\",\n    \"spawnedAt\": {\"@id\": \"actor:spawnedAt\", \"@type\": \"xsd:dateTime\"},\n    \"lastMessageAt\": {\"@id\": \"actor:lastMessageAt\", \"@type\": \"xsd:dateTime\"},\n    \"messageCount\": \"actor:messageCount\"\
  ,\n    \"restartCount\": \"actor:restartCount\",\n    \"actors\": \"actor:actors\",\n    \"total\": \"actor:total\",\n    \"cursor\": \"actor:cursor\",\n    \"type\": \"actor:type\",\n    \"payload\": \"actor:payload\",\n    \"replyTo\": \"actor:replyTo\",\n    \"correlationId\": \"actor:correlationId\",\n    \"priority\": \"actor:priority\",\n    \"actorId\": \"actor:actorId\",\n    \"pendingCount\": \"actor:pendingCount\",\n    \"messages\": \"actor:messages\",\n    \"oldestMessageAge\": \"actor:oldestMessageAge\",\n    \"strategy\": \"actor:strategy\",\n    \"maxRestarts\": \"actor:maxRestarts\",\n    \"restartWindow\": \"actor:restartWindow\",\n    \"childCount\": \"actor:childCount\",\n    \"supervisors\": \"actor:supervisors\",\n    \"nodeId\": \"actor:nodeId\",\n    \"address\": \"actor:address\",\n    \"roles\": \"actor:roles\",\n    \"upSince\": {\"@id\": \"actor:upSince\", \"@type\": \"xsd:dateTime\"},\n    \"actorCount\": \"actor:actorCount\",\n    \"members\": \"actor:members\"\
  ,\n    \"leader\": \"actor:leader\",\n    \"totalActors\": \"actor:totalActors\",\n    \"shardId\": \"actor:shardId\",\n    \"region\": \"actor:region\",\n    \"entityCount\": \"actor:entityCount\",\n    \"shards\": \"actor:shards\",\n    \"totalShards\": \"actor:totalShards\",\n    \"totalEntities\": \"actor:totalEntities\",\n    \"activeActors\": \"actor:activeActors\",\n    \"messagesPerSecond\": \"actor:messagesPerSecond\",\n    \"errorRate\": \"actor:errorRate\",\n    \"deadLetters\": \"actor:deadLetters\",\n    \"clusterSize\": \"actor:clusterSize\",\n    \"uptime\": \"actor:uptime\",\n    \"initialState\": \"actor:initialState\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/actor-model/refs/heads/main/json-ld/actor-model-context.jsonld
tags:
- Actor Model
- Concurrency
- Distributed Systems
- JSON-LD
- Linked Data
- Semantic Web
---
