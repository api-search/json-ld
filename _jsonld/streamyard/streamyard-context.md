---
api_specs:
- filename: streamyard-openapi.yml
  format: yaml
  label: StreamYard API
  slug: streamyard-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/streamyard/refs/heads/main/openapi/streamyard-openapi.yml
class_count: 0
classes: []
context_file: json-ld/streamyard-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/streamyard/refs/heads/main/json-ld/streamyard-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Streamyard from StreamYard.
layout: jsonld
name: Streamyard Context
namespaces:
- prefix: streamyard
  uri: https://streamyard.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Broadcast
  type: ''
- container: ''
  name: Destination
  type: ''
- container: ''
  name: Recording
  type: ''
property_count: 3
provider_name: StreamYard
provider_slug: streamyard
slug: streamyard-context
source_filename: streamyard-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"streamyard\": \"https://streamyard.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Broadcast\": {\n      \"@id\": \"schema:BroadcastEvent\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"title\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"status\": {\n          \"@id\": \"streamyard:broadcastStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"streamyard:broadcastType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"scheduledAt\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"startedAt\": {\n          \"@id\": \"streamyard:actualStartTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endedAt\": {\n          \"@id\": \"\
  streamyard:actualEndTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"studioUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"destinations\": {\n          \"@id\": \"streamyard:hasDestination\"\n        }\n      }\n    },\n\n    \"Destination\": {\n      \"@id\": \"streamyard:StreamingDestination\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"platform\": {\n          \"@id\": \"streamyard:platform\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": \"schema:name\",\n        \"accountName\": \"streamyard:accountName\",\n        \"isConnected\": {\n          \"@id\": \"streamyard:isConnected\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n \
  \   },\n\n    \"Recording\": {\n      \"@id\": \"schema:VideoObject\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"title\": \"schema:name\",\n        \"duration\": {\n          \"@id\": \"schema:duration\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"fileSize\": {\n          \"@id\": \"schema:contentSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"downloadUrl\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"@id\"\n        },\n        \"thumbnailUrl\": {\n          \"@id\": \"schema:thumbnailUrl\",\n          \"@type\": \"@id\"\n        },\n        \"status\": {\n          \"@id\": \"streamyard:recordingStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/streamyard/refs/heads/main/json-ld/streamyard-context.jsonld
tags:
- Broadcasting
- Live Streaming
- Multi-Streaming
- Recordings
- Video
- JSON-LD
- Linked Data
- Semantic Web
---
