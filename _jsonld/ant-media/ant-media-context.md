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
