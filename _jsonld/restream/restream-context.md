---
api_specs:
- filename: restream-openapi.yml
  format: yaml
  label: Restream API
  slug: restream-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/restream/refs/heads/main/openapi/restream-openapi.yml
class_count: 19
classes:
- Channel
- Platform
- Event
- UserProfile
- StreamKey
- id
- name
- description
- url
- displayName
- active
- title
- status
- streamKey
- srtUrl
- image
- identifier
- email
- username
context_file: json-ld/restream-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/restream/refs/heads/main/json-ld/restream-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Restream from Restream.
layout: jsonld
name: Restream Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: restream
  uri: https://api.restream.io/v2/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: startedAt
  type: dateTime
- container: ''
  name: endedAt
  type: dateTime
- container: ''
  name: streamingPlatformId
  type: integer
- container: ''
  name: embedUrl
  type: reference
- container: list
  name: channels
  type: ''
- container: ''
  name: createdAt
  type: dateTime
property_count: 6
provider_name: Restream
provider_slug: restream
slug: restream-context
source_filename: restream-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"restream\": \"https://api.restream.io/v2/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Channel\": \"schema:BroadcastChannel\",\n    \"Platform\": \"schema:BroadcastService\",\n    \"Event\": \"schema:BroadcastEvent\",\n    \"UserProfile\": \"schema:Person\",\n    \"StreamKey\": \"restream:StreamKey\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"displayName\": \"schema:alternateName\",\n    \"active\": \"schema:active\",\n    \"title\": \"schema:headline\",\n    \"status\": \"schema:eventStatus\",\n    \"startedAt\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"endedAt\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"streamingPlatformId\": {\n      \"@id\": \"restream:streamingPlatformId\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"embedUrl\": {\n      \"@id\": \"schema:embedUrl\",\n      \"@type\": \"@id\"\n    },\n    \"streamKey\": \"restream:streamKey\",\n    \"srtUrl\": \"restream:srtUrl\",\n    \"channels\": {\n      \"@id\": \"restream:channels\",\n      \"@container\": \"@list\"\n    },\n    \"image\": \"schema:image\",\n    \"identifier\": \"schema:identifier\",\n    \"email\": \"schema:email\",\n    \"username\": \"schema:alternateName\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/restream/refs/heads/main/json-ld/restream-context.jsonld
tags:
- Broadcast
- Chat
- Content Delivery
- Live Streaming
- Multistreaming
- Video Streaming
- JSON-LD
- Linked Data
- Semantic Web
---
