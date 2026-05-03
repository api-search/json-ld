---
api_specs:
- filename: red5-server-api-openapi.yml
  format: yaml
  label: Red5 Pro Server API
  slug: server-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/red5/refs/heads/main/openapi/red5-server-api-openapi.yml
- filename: red5-stream-manager-2-openapi.yml
  format: yaml
  label: Red5 Pro Stream Manager 2.0 API
  slug: stream-manager-2-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/red5/refs/heads/main/openapi/red5-stream-manager-2-openapi.yml
- filename: red5-brew-mixer-api-openapi.yml
  format: yaml
  label: Red5 Pro Brew Mixer API
  slug: brew-mixer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/red5/refs/heads/main/openapi/red5-brew-mixer-api-openapi.yml
- filename: red5-restreamer-api-openapi.yml
  format: yaml
  label: Red5 Pro Restreamer API
  slug: restreamer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/red5/refs/heads/main/openapi/red5-restreamer-api-openapi.yml
- filename: red5-webrtc-streaming-asyncapi.yml
  format: yaml
  label: Red5 Pro WebRTC SDK
  slug: webrtc-sdk
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/red5/refs/heads/main/asyncapi/red5-webrtc-streaming-asyncapi.yml
class_count: 0
classes: []
context_file: json-ld/red5-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/red5/refs/heads/main/json-ld/red5-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Red5 from Red5.
layout: jsonld
name: Red5 Context
namespaces:
- prefix: red5
  uri: https://www.red5.net/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Stream
  type: ''
- container: ''
  name: VideoTrack
  type: ''
- container: ''
  name: AudioTrack
  type: ''
- container: ''
  name: Application
  type: ''
- container: ''
  name: Mixer
  type: ''
- container: ''
  name: MixerInput
  type: ''
- container: ''
  name: RestreamProvision
  type: ''
- container: ''
  name: Node
  type: ''
- container: ''
  name: NodeGroup
  type: ''
property_count: 9
provider_name: Red5
provider_slug: red5
slug: red5-context
source_filename: red5-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"red5\": \"https://www.red5.net/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Stream\": {\n      \"@id\": \"red5:Stream\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"appName\": {\n          \"@id\": \"red5:appName\"\n        },\n        \"clientId\": {\n          \"@id\": \"red5:clientId\"\n        },\n        \"status\": {\n          \"@id\": \"schema:status\"\n        },\n        \"protocol\": {\n          \"@id\": \"red5:protocol\"\n        },\n        \"duration\": {\n          \"@id\": \"schema:duration\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"subscriberCount\": {\n          \"@id\": \"red5:subscriberCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"bytesIn\": {\n          \"@id\": \"red5:bytesIn\",\n\
  \          \"@type\": \"xsd:integer\"\n        },\n        \"bytesOut\": {\n          \"@id\": \"red5:bytesOut\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"video\": {\n          \"@id\": \"red5:video\"\n        },\n        \"audio\": {\n          \"@id\": \"red5:audio\"\n        }\n      }\n    },\n\n    \"VideoTrack\": {\n      \"@id\": \"red5:VideoTrack\",\n      \"@context\": {\n        \"codec\": {\n          \"@id\": \"red5:codec\"\n        },\n        \"width\": {\n          \"@id\": \"schema:width\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"height\": {\n          \"@id\": \"schema:height\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"frameRate\": {\n          \"@id\": \"red5:frameRate\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"bitrate\": {\n          \"@id\": \"red5:bitrate\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"AudioTrack\": {\n      \"@id\": \"red5:AudioTrack\",\n\
  \      \"@context\": {\n        \"codec\": {\n          \"@id\": \"red5:codec\"\n        },\n        \"sampleRate\": {\n          \"@id\": \"red5:sampleRate\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"channels\": {\n          \"@id\": \"red5:channels\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"bitrate\": {\n          \"@id\": \"red5:bitrate\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Application\": {\n      \"@id\": \"red5:Application\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"clientCount\": {\n          \"@id\": \"red5:clientCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"streamCount\": {\n          \"@id\": \"red5:streamCount\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Mixer\": {\n      \"@id\": \"red5:Mixer\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"@id\"\n        },\n\
  \        \"outputStreamName\": {\n          \"@id\": \"red5:outputStreamName\"\n        },\n        \"outputWidth\": {\n          \"@id\": \"red5:outputWidth\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"outputHeight\": {\n          \"@id\": \"red5:outputHeight\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"outputFrameRate\": {\n          \"@id\": \"red5:outputFrameRate\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"outputBitrate\": {\n          \"@id\": \"red5:outputBitrate\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"inputCount\": {\n          \"@id\": \"red5:inputCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"status\": {\n          \"@id\": \"schema:status\"\n        },\n        \"inputs\": {\n          \"@id\": \"red5:inputs\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"MixerInput\": {\n      \"@id\": \"red5:MixerInput\",\n      \"@context\": {\n        \"id\"\
  : {\n          \"@id\": \"@id\"\n        },\n        \"streamName\": {\n          \"@id\": \"red5:streamName\"\n        },\n        \"x\": {\n          \"@id\": \"red5:xPosition\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"y\": {\n          \"@id\": \"red5:yPosition\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"width\": {\n          \"@id\": \"schema:width\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"height\": {\n          \"@id\": \"schema:height\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"zOrder\": {\n          \"@id\": \"red5:zOrder\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"RestreamProvision\": {\n      \"@id\": \"red5:RestreamProvision\",\n      \"@context\": {\n        \"streamName\": {\n          \"@id\": \"red5:streamName\"\n        },\n        \"appName\": {\n          \"@id\": \"red5:appName\"\n        },\n        \"type\": {\n          \"@id\": \"red5:restreamType\"\
  \n        },\n        \"status\": {\n          \"@id\": \"schema:status\"\n        },\n        \"destinations\": {\n          \"@id\": \"red5:destinations\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Node\": {\n      \"@id\": \"red5:Node\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"@id\"\n        },\n        \"host\": {\n          \"@id\": \"schema:url\"\n        },\n        \"status\": {\n          \"@id\": \"schema:status\"\n        },\n        \"activeStreams\": {\n          \"@id\": \"red5:activeStreams\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"connectedClients\": {\n          \"@id\": \"red5:connectedClients\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"cpuLoad\": {\n          \"@id\": \"red5:cpuLoad\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"NodeGroup\": {\n      \"@id\": \"red5:NodeGroup\",\n      \"@context\": {\n        \"name\": {\n          \"@id\"\
  : \"schema:name\"\n        },\n        \"cloudProvider\": {\n          \"@id\": \"red5:cloudProvider\"\n        },\n        \"region\": {\n          \"@id\": \"schema:areaServed\"\n        },\n        \"minNodes\": {\n          \"@id\": \"red5:minNodes\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"maxNodes\": {\n          \"@id\": \"red5:maxNodes\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"currentNodes\": {\n          \"@id\": \"red5:currentNodes\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"nodes\": {\n          \"@id\": \"red5:nodes\",\n          \"@container\": \"@set\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/red5/refs/heads/main/json-ld/red5-context.jsonld
tags:
- Live Streaming
- Media
- Real-Time
- RTMP
- Streaming
- Video
- WebRTC
- JSON-LD
- Linked Data
- Semantic Web
---
