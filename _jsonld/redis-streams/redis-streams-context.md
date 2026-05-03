---
class_count: 0
classes: []
context_file: json-ld/redis-streams-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/redis-streams/refs/heads/main/json-ld/redis-streams-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Redis Streams from Redis Streams.
layout: jsonld
name: Redis Streams Context
namespaces:
- prefix: redis
  uri: https://redis.io/ns/streams/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: StreamEntry
  type: ''
- container: ''
  name: ConsumerGroup
  type: ''
- container: ''
  name: Consumer
  type: ''
- container: ''
  name: StreamInfo
  type: ''
property_count: 4
provider_name: Redis Streams
provider_slug: redis-streams
slug: redis-streams-context
source_filename: redis-streams-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"redis\": \"https://redis.io/ns/streams/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"StreamEntry\": {\n      \"@id\": \"redis:StreamEntry\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"redis:entryId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fields\": {\n          \"@id\": \"redis:fields\",\n          \"@container\": \"@index\"\n        }\n      }\n    },\n\n    \"ConsumerGroup\": {\n      \"@id\": \"redis:ConsumerGroup\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"stream\": {\n          \"@id\": \"redis:streamKey\",\n          \"@type\": \"xsd:string\"\n        },\n        \"last-delivered-id\": {\n          \"@id\": \"redis:lastDeliveredId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"entries-read\": {\n          \"@id\": \"redis:entriesRead\"\
  ,\n          \"@type\": \"xsd:integer\"\n        },\n        \"lag\": {\n          \"@id\": \"redis:lag\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"pel-count\": {\n          \"@id\": \"redis:pelCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"consumers\": {\n          \"@id\": \"redis:consumers\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Consumer\": {\n      \"@id\": \"redis:Consumer\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"pending\": {\n          \"@id\": \"redis:pendingCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"idle\": {\n          \"@id\": \"redis:idleMs\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"StreamInfo\": {\n      \"@id\": \"redis:StreamInfo\",\n      \"@context\": {\n        \"length\": {\n          \"@id\": \"redis:streamLength\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"last-generated-id\":\
  \ {\n          \"@id\": \"redis:lastGeneratedId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"entries-added\": {\n          \"@id\": \"redis:entriesAdded\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"groups\": {\n          \"@id\": \"redis:groupCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"first-entry\": {\n          \"@id\": \"redis:firstEntry\"\n        },\n        \"last-entry\": {\n          \"@id\": \"redis:lastEntry\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/redis-streams/refs/heads/main/json-ld/redis-streams-context.jsonld
tags:
- Consumer Groups
- Event-Driven
- In-Memory
- Messaging
- Redis
- Streaming
- JSON-LD
- Linked Data
- Semantic Web
---
