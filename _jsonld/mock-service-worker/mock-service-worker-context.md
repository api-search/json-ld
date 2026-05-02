---
class_count: 4
classes:
- name
- description
- url
- status
context_file: json-ld/mock-service-worker-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/mock-service-worker/refs/heads/main/json-ld/mock-service-worker-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Mock Service Worker from Mock Service Worker.
layout: jsonld
name: Mock Service Worker Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: Handler
  uri: https://mswjs.io/vocab#Handler
- prefix: RestHandler
  uri: https://mswjs.io/vocab#RestHandler
- prefix: GraphQLHandler
  uri: https://mswjs.io/vocab#GraphQLHandler
- prefix: WebSocketHandler
  uri: https://mswjs.io/vocab#WebSocketHandler
- prefix: SSEHandler
  uri: https://mswjs.io/vocab#SSEHandler
- prefix: method
  uri: https://mswjs.io/vocab#method
- prefix: path
  uri: https://mswjs.io/vocab#path
- prefix: operationName
  uri: https://mswjs.io/vocab#operationName
- prefix: response
  uri: https://mswjs.io/vocab#response
- prefix: delay
  uri: https://mswjs.io/vocab#delay
properties: []
property_count: 0
provider_name: Mock Service Worker
provider_slug: mock-service-worker
slug: mock-service-worker-context
source_filename: mock-service-worker-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://mswjs.io/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"Handler\": \"https://mswjs.io/vocab#Handler\",\n    \"RestHandler\": \"https://mswjs.io/vocab#RestHandler\",\n    \"GraphQLHandler\": \"https://mswjs.io/vocab#GraphQLHandler\",\n    \"WebSocketHandler\": \"https://mswjs.io/vocab#WebSocketHandler\",\n    \"SSEHandler\": \"https://mswjs.io/vocab#SSEHandler\",\n    \"method\": \"https://mswjs.io/vocab#method\",\n    \"path\": \"https://mswjs.io/vocab#path\",\n    \"operationName\": \"https://mswjs.io/vocab#operationName\",\n    \"response\": \"https://mswjs.io/vocab#response\",\n    \"delay\": \"https://mswjs.io/vocab#delay\",\n    \"status\": \"schema:HttpStatusCode\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/mock-service-worker/refs/heads/main/json-ld/mock-service-worker-context.jsonld
tags:
- API Mocking
- GraphQL
- HTTP
- Mock Server
- Mocking
- Service Worker
- Testing
- WebSocket
- JSON-LD
- Linked Data
- Semantic Web
---
