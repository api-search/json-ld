---
class_count: 3
classes:
- Session
- Request
- Response
context_file: json-ld/rtsp-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/rtsp/refs/heads/main/json-ld/rtsp-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Rtsp from RTSP.
layout: jsonld
name: Rtsp Context
namespaces:
- prefix: rtsp
  uri: https://datatracker.ietf.org/doc/html/rfc7826#section-
- prefix: schema
  uri: https://schema.org/
- prefix: iana
  uri: https://www.iana.org/assignments/rtsp-parameters/
properties:
- container: ''
  name: sessionId
  type: schema:Text
- container: ''
  name: url
  type: reference
- container: ''
  name: state
  type: schema:Text
- container: ''
  name: method
  type: schema:Text
- container: ''
  name: statusCode
  type: schema:Integer
- container: ''
  name: transport
  type: schema:Text
- container: ''
  name: sdp
  type: schema:Text
- container: ''
  name: timeout
  type: schema:Integer
property_count: 8
provider_name: RTSP
provider_slug: rtsp
slug: rtsp-context
source_filename: rtsp-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"rtsp\": \"https://datatracker.ietf.org/doc/html/rfc7826#section-\",\n    \"schema\": \"https://schema.org/\",\n    \"iana\": \"https://www.iana.org/assignments/rtsp-parameters/\",\n\n    \"Session\": \"rtsp:Session\",\n    \"Request\": \"rtsp:Request\",\n    \"Response\": \"rtsp:Response\",\n\n    \"sessionId\": {\n      \"@id\": \"rtsp:session-id\",\n      \"@type\": \"schema:Text\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"state\": {\n      \"@id\": \"rtsp:session-state\",\n      \"@type\": \"schema:Text\"\n    },\n    \"method\": {\n      \"@id\": \"rtsp:method\",\n      \"@type\": \"schema:Text\"\n    },\n    \"statusCode\": {\n      \"@id\": \"rtsp:status-code\",\n      \"@type\": \"schema:Integer\"\n    },\n    \"transport\": {\n      \"@id\": \"rtsp:transport-header\",\n      \"@type\": \"schema:Text\"\n    },\n    \"sdp\": {\n      \"@id\": \"schema:contentUrl\"\
  ,\n      \"@type\": \"schema:Text\"\n    },\n    \"timeout\": {\n      \"@id\": \"rtsp:session-timeout\",\n      \"@type\": \"schema:Integer\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/rtsp/refs/heads/main/json-ld/rtsp-context.jsonld
tags:
- Streaming
- Video
- Media
- Protocol
- Real-Time
- JSON-LD
- Linked Data
- Semantic Web
---
