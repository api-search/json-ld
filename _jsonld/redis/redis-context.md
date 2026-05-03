---
class_count: 0
classes: []
context_file: json-ld/redis-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/redis/refs/heads/main/json-ld/redis-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Redis from Redis.
layout: jsonld
name: Redis Context
namespaces:
- prefix: redis
  uri: https://redis.io/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: KeyValueEntry
  type: ''
- container: ''
  name: ServerInfo
  type: ''
- container: ''
  name: Command
  type: ''
property_count: 3
provider_name: Redis
provider_slug: redis
slug: redis-context
source_filename: redis-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"redis\": \"https://redis.io/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"KeyValueEntry\": {\n      \"@id\": \"redis:KeyValueEntry\",\n      \"@context\": {\n        \"key\": \"redis:key\",\n        \"type\": \"redis:dataType\",\n        \"value\": \"redis:value\",\n        \"ttl\": {\n          \"@id\": \"redis:ttl\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"encoding\": \"redis:encoding\"\n      }\n    },\n\n    \"ServerInfo\": {\n      \"@id\": \"redis:ServerInfo\",\n      \"@context\": {\n        \"redis_version\": \"redis:version\",\n        \"redis_mode\": \"redis:mode\",\n        \"uptime_in_seconds\": {\n          \"@id\": \"redis:uptimeSeconds\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"connected_clients\": {\n          \"@id\": \"redis:connectedClients\",\n     \
  \     \"@type\": \"xsd:integer\"\n        },\n        \"used_memory\": {\n          \"@id\": \"redis:usedMemoryBytes\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"maxmemory\": {\n          \"@id\": \"redis:maxMemoryBytes\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"maxmemory_policy\": \"redis:maxMemoryPolicy\",\n        \"role\": \"redis:replicationRole\",\n        \"connected_slaves\": {\n          \"@id\": \"redis:connectedReplicas\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"keyspace_hits\": {\n          \"@id\": \"redis:keyspaceHits\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"keyspace_misses\": {\n          \"@id\": \"redis:keyspaceMisses\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Command\": {\n      \"@id\": \"redis:Command\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"arity\": \"redis:arity\",\n        \"flags\": {\n          \"@id\": \"redis:flags\"\
  ,\n          \"@container\": \"@set\"\n        },\n        \"complexity\": \"redis:complexity\",\n        \"acl_categories\": {\n          \"@id\": \"redis:aclCategories\",\n          \"@container\": \"@set\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/redis/refs/heads/main/json-ld/redis-context.jsonld
tags:
- Cache
- Database
- In-Memory
- Key-Value Store
- NoSQL
- Open Source
- Streaming
- JSON-LD
- Linked Data
- Semantic Web
---
