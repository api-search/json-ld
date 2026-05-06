---
api_specs:
- filename: roku-external-control-protocol.yaml
  format: yaml
  label: Roku External Control Protocol (ECP)
  slug: external-control-protocol
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/roku/refs/heads/main/openapi/roku-external-control-protocol.yaml
- filename: roku-pay-web-services.yaml
  format: yaml
  label: Roku Pay Web Services
  slug: pay
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/roku/refs/heads/main/openapi/roku-pay-web-services.yaml
- filename: roku-nabu-cloud.yaml
  format: yaml
  label: Roku Nabu Cloud
  slug: nabu-cloud
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/roku/refs/heads/main/openapi/roku-nabu-cloud.yaml
class_count: 5
classes:
- ActiveApp
- App
- AppList
- DeviceInfo
- MediaPlayer
context_file: json-ld/roku-external-control-protocol-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/roku/refs/heads/main/json-ld/roku-external-control-protocol-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Roku External Control Protocol from Roku.
layout: jsonld
name: Roku External Control Protocol Context
namespaces:
- prefix: roku
  uri: https://developer.roku.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: app
  type: ''
- container: set
  name: apps
  type: ''
- container: ''
  name: audio
  type: string
- container: ''
  name: bitrate
  type: integer
- container: ''
  name: buffering
  type: reference
- container: ''
  name: captions
  type: string
- container: ''
  name: container
  type: string
- container: ''
  name: countryCode
  type: string
- container: ''
  name: current
  type: integer
- container: ''
  name: developerEnabled
  type: boolean
- container: ''
  name: deviceId
  type: string
- container: ''
  name: drm
  type: string
- container: ''
  name: duration
  type: integer
- container: ''
  name: error
  type: boolean
- container: ''
  name: ethernetMac
  type: string
- container: ''
  name: format
  type: reference
- container: ''
  name: friendlyDeviceName
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: isLive
  type: boolean
- container: ''
  name: language
  type: string
- container: ''
  name: max
  type: integer
- container: ''
  name: mediaSequence
  type: integer
- container: ''
  name: modelName
  type: string
- container: ''
  name: modelNumber
  type: string
- container: ''
  name: name
  type: ''
- container: ''
  name: networkType
  type: string
- container: ''
  name: newStream
  type: reference
- container: ''
  name: plugin
  type: reference
- container: ''
  name: position
  type: integer
- container: ''
  name: powerMode
  type: string
- container: ''
  name: runtime
  type: integer
- container: ''
  name: screensaver
  type: ''
- container: ''
  name: segmentType
  type: string
- container: ''
  name: serialNumber
  type: string
- container: ''
  name: softwareBuild
  type: string
- container: ''
  name: softwareVersion
  type: string
- container: ''
  name: speed
  type: integer
- container: ''
  name: state
  type: string
- container: ''
  name: streamSegment
  type: reference
- container: ''
  name: subtype
  type: string
- container: ''
  name: supportsEcsMicrophone
  type: boolean
- container: ''
  name: supportsEcsTextedit
  type: boolean
- container: ''
  name: supportsWakeOnWlan
  type: boolean
- container: ''
  name: target
  type: integer
- container: ''
  name: time
  type: integer
- container: ''
  name: timeZone
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: udn
  type: string
- container: ''
  name: userDeviceName
  type: string
- container: ''
  name: version
  type: ''
- container: ''
  name: video
  type: string
- container: ''
  name: videoRes
  type: string
- container: ''
  name: wifiMac
  type: string
property_count: 53
provider_name: Roku
provider_slug: roku
slug: roku-external-control-protocol-context
source_filename: roku-external-control-protocol-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"roku\": \"https://developer.roku.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ActiveApp\": \"roku:ActiveApp\",\n    \"App\": \"roku:App\",\n    \"AppList\": \"roku:AppList\",\n    \"DeviceInfo\": \"roku:DeviceInfo\",\n    \"MediaPlayer\": \"roku:MediaPlayer\",\n    \"app\": {\n      \"@id\": \"roku:app\"\n    },\n    \"apps\": {\n      \"@id\": \"roku:apps\",\n      \"@container\": \"@set\"\n    },\n    \"audio\": {\n      \"@id\": \"roku:audio\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bitrate\": {\n      \"@id\": \"roku:bitrate\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"buffering\": {\n      \"@id\": \"roku:buffering\",\n      \"@type\": \"@id\"\n    },\n    \"captions\": {\n      \"@id\": \"roku:captions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"container\": {\n      \"@id\"\
  : \"roku:container\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryCode\": {\n      \"@id\": \"roku:countryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"current\": {\n      \"@id\": \"roku:current\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"developerEnabled\": {\n      \"@id\": \"roku:developerEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"deviceId\": {\n      \"@id\": \"roku:deviceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"drm\": {\n      \"@id\": \"roku:drm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"duration\": {\n      \"@id\": \"roku:duration\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"error\": {\n      \"@id\": \"roku:error\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ethernetMac\": {\n      \"@id\": \"roku:ethernetMac\",\n      \"@type\": \"xsd:string\"\n    },\n    \"format\": {\n      \"@id\": \"roku:format\",\n      \"@type\": \"@id\"\n    },\n    \"friendlyDeviceName\": {\n      \"@id\": \"roku:friendlyDeviceName\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"roku:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isLive\": {\n      \"@id\": \"roku:is_live\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"language\": {\n      \"@id\": \"roku:language\",\n      \"@type\": \"xsd:string\"\n    },\n    \"max\": {\n      \"@id\": \"roku:max\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"mediaSequence\": {\n      \"@id\": \"roku:media_sequence\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"modelName\": {\n      \"@id\": \"roku:modelName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modelNumber\": {\n      \"@id\": \"roku:modelNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"networkType\": {\n      \"@id\": \"roku:networkType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"newStream\": {\n      \"@id\": \"roku:new_stream\",\n      \"@type\": \"@id\"\n    },\n    \"plugin\": {\n      \"\
  @id\": \"roku:plugin\",\n      \"@type\": \"@id\"\n    },\n    \"position\": {\n      \"@id\": \"roku:position\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"powerMode\": {\n      \"@id\": \"roku:powerMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"runtime\": {\n      \"@id\": \"roku:runtime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"screensaver\": {\n      \"@id\": \"roku:screensaver\"\n    },\n    \"segmentType\": {\n      \"@id\": \"roku:segment_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serialNumber\": {\n      \"@id\": \"roku:serialNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"softwareBuild\": {\n      \"@id\": \"roku:softwareBuild\",\n      \"@type\": \"xsd:string\"\n    },\n    \"softwareVersion\": {\n      \"@id\": \"roku:softwareVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"speed\": {\n      \"@id\": \"roku:speed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"state\": {\n      \"@id\": \"roku:state\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"streamSegment\": {\n      \"@id\": \"roku:stream_segment\",\n      \"@type\": \"@id\"\n    },\n    \"subtype\": {\n      \"@id\": \"roku:subtype\",\n      \"@type\": \"xsd:string\"\n    },\n    \"supportsEcsMicrophone\": {\n      \"@id\": \"roku:supportsEcsMicrophone\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"supportsEcsTextedit\": {\n      \"@id\": \"roku:supportsEcsTextedit\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"supportsWakeOnWlan\": {\n      \"@id\": \"roku:supportsWakeOnWlan\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"target\": {\n      \"@id\": \"roku:target\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"time\": {\n      \"@id\": \"roku:time\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"timeZone\": {\n      \"@id\": \"roku:timeZone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"roku:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"udn\": {\n      \"@id\": \"roku:udn\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"userDeviceName\": {\n      \"@id\": \"roku:userDeviceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\"\n    },\n    \"video\": {\n      \"@id\": \"roku:video\",\n      \"@type\": \"xsd:string\"\n    },\n    \"videoRes\": {\n      \"@id\": \"roku:videoRes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"wifiMac\": {\n      \"@id\": \"roku:wifiMac\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/roku/refs/heads/main/json-ld/roku-external-control-protocol-context.jsonld
tags:
- Streaming
- Television
- Media
- Entertainment
- Connected TV
- Consumer Electronics
- JSON-LD
- Linked Data
- Semantic Web
---
