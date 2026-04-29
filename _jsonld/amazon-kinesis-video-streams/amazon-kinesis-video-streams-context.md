---
class_count: 2
classes:
- Stream
- Channel
context_file: json-ld/amazon-kinesis-video-streams-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-kinesis-video-streams/refs/heads/main/json-ld/amazon-kinesis-video-streams-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Kinesis Video Streams from Amazon Kinesis Video Streams.
layout: jsonld
name: Amazon Kinesis Video Streams Context
namespaces:
- prefix: kinesisvideostreams
  uri: https://kinesisvideostreams.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
property_count: 7
provider_name: Amazon Kinesis Video Streams
provider_slug: amazon-kinesis-video-streams
slug: amazon-kinesis-video-streams-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"kinesisvideostreams\": \"https://kinesisvideostreams.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Stream\": \"kinesisvideostreams:Stream\",\n    \"Channel\": \"kinesisvideostreams:Channel\",\n    \"id\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"kinesisvideostreams:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"kinesisvideostreams:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"\
  updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-kinesis-video-streams/refs/heads/main/json-ld/amazon-kinesis-video-streams-context.jsonld
tags:
- AWS
- IoT
- Machine Learning
- Media
- Video Streaming
- JSON-LD
- Linked Data
- Semantic Web
---
