---
class_count: 3
classes:
- Broadcast
- name
- description
context_file: json-ld/ant-media-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ant-media/refs/heads/main/json-ld/ant-media-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ant Media from Ant Media.
layout: jsonld
name: Ant Media Context
namespaces:
- prefix: antmedia
  uri: https://api-evangelist.github.io/ant-media/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: streamId
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: publishType
  type: string
- container: ''
  name: streamUrl
  type: reference
- container: ''
  name: hlsViewerCount
  type: integer
- container: ''
  name: webRTCViewerCount
  type: integer
- container: ''
  name: rtmpViewerCount
  type: integer
- container: ''
  name: mp4Enabled
  type: integer
- container: ''
  name: duration
  type: integer
- container: ''
  name: startTime
  type: integer
- container: ''
  name: is360
  type: boolean
- container: ''
  name: latitude
  type: string
- container: ''
  name: longitude
  type: string
property_count: 14
provider_name: Ant Media
provider_slug: ant-media
slug: ant-media-context
source_filename: ant-media-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"antmedia\": \"https://api-evangelist.github.io/ant-media/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Broadcast\": \"antmedia:Broadcast\",\n    \"streamId\": {\"@id\": \"dcterms:identifier\", \"@type\": \"xsd:string\"},\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"status\": {\"@id\": \"antmedia:status\", \"@type\": \"xsd:string\"},\n    \"type\": {\"@id\": \"antmedia:type\", \"@type\": \"xsd:string\"},\n    \"publishType\": {\"@id\": \"antmedia:publish_type\", \"@type\": \"xsd:string\"},\n    \"streamUrl\": {\"@id\": \"schema:url\", \"@type\": \"@id\"},\n    \"hlsViewerCount\": {\"@id\": \"antmedia:hls_viewer_count\", \"@type\": \"xsd:integer\"},\n    \"webRTCViewerCount\": {\"@id\": \"antmedia:webrtc_viewer_count\", \"@type\": \"xsd:integer\"},\n    \"rtmpViewerCount\"\
  : {\"@id\": \"antmedia:rtmp_viewer_count\", \"@type\": \"xsd:integer\"},\n    \"mp4Enabled\": {\"@id\": \"antmedia:mp4_enabled\", \"@type\": \"xsd:integer\"},\n    \"duration\": {\"@id\": \"antmedia:duration\", \"@type\": \"xsd:integer\"},\n    \"startTime\": {\"@id\": \"schema:dateCreated\", \"@type\": \"xsd:integer\"},\n    \"is360\": {\"@id\": \"antmedia:is360\", \"@type\": \"xsd:boolean\"},\n    \"latitude\": {\"@id\": \"schema:latitude\", \"@type\": \"xsd:string\"},\n    \"longitude\": {\"@id\": \"schema:longitude\", \"@type\": \"xsd:string\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ant-media/refs/heads/main/json-ld/ant-media-context.jsonld
tags:
- Broadcasting
- Live Streaming
- Media
- Streaming
- Video
- WebRTC
- JSON-LD
- Linked Data
- Semantic Web
---
