---
api_specs:
- filename: reolink-camera-api-openapi.yml
  format: yaml
  label: Reolink Camera HTTP API
  slug: camera-http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/reolink/refs/heads/main/openapi/reolink-camera-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/reolink-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/reolink/refs/heads/main/json-ld/reolink-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Reolink from Reolink.
layout: jsonld
name: Reolink Context
namespaces:
- prefix: reolink
  uri: https://reolink.com/api/v1/
- prefix: iot
  uri: https://www.w3.org/2019/wot/td#
- prefix: sec
  uri: https://w3id.org/security#
properties:
- container: ''
  name: DeviceInfo
  type: ''
- container: ''
  name: Camera
  type: iot:Thing
- container: ''
  name: Authentication
  type: ''
- container: ''
  name: PTZControl
  type: ''
- container: ''
  name: Recording
  type: ''
- container: ''
  name: AlarmSettings
  type: ''
- container: ''
  name: AIDetection
  type: ''
- container: ''
  name: NetworkSettings
  type: ''
- container: ''
  name: LEDControl
  type: ''
- container: ''
  name: ImageSettings
  type: ''
property_count: 10
provider_name: Reolink
provider_slug: reolink
slug: reolink-context
source_filename: reolink-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"reolink\": \"https://reolink.com/api/v1/\",\n    \"iot\": \"https://www.w3.org/2019/wot/td#\",\n    \"sec\": \"https://w3id.org/security#\",\n    \"DeviceInfo\": {\n      \"@id\": \"reolink:DeviceInfo\",\n      \"@context\": {\n        \"model\": \"reolink:model\",\n        \"firmVer\": \"reolink:firmwareVersion\",\n        \"hardVer\": \"reolink:hardwareVersion\",\n        \"serial\": \"serialNumber\",\n        \"name\": \"name\",\n        \"channelNum\": \"reolink:channelCount\",\n        \"type\": \"reolink:deviceType\",\n        \"wifi\": \"reolink:wifiSupport\",\n        \"diskNum\": \"reolink:diskCount\",\n        \"buildDay\": \"reolink:buildDate\"\n      }\n    },\n    \"Camera\": {\n      \"@id\": \"reolink:Camera\",\n      \"@type\": \"iot:Thing\",\n      \"@context\": {\n        \"channel\": \"reolink:channel\",\n        \"status\": \"reolink:status\",\n        \"streamType\": \"reolink:streamType\"\
  \n      }\n    },\n    \"Authentication\": {\n      \"@id\": \"reolink:Authentication\",\n      \"@context\": {\n        \"token\": \"sec:token\",\n        \"leaseTime\": \"reolink:tokenLeaseTime\",\n        \"userName\": \"reolink:userName\"\n      }\n    },\n    \"PTZControl\": {\n      \"@id\": \"reolink:PTZControl\",\n      \"@context\": {\n        \"operation\": \"reolink:ptzOperation\",\n        \"speed\": \"reolink:ptzSpeed\",\n        \"presetId\": \"reolink:presetId\",\n        \"channel\": \"reolink:channel\"\n      }\n    },\n    \"Recording\": {\n      \"@id\": \"reolink:Recording\",\n      \"@context\": {\n        \"channel\": \"reolink:channel\",\n        \"startTime\": \"startDate\",\n        \"endTime\": \"endDate\",\n        \"streamType\": \"reolink:streamType\"\n      }\n    },\n    \"AlarmSettings\": {\n      \"@id\": \"reolink:AlarmSettings\",\n      \"@context\": {\n        \"alarmType\": \"reolink:alarmType\",\n        \"sensitivity\": \"reolink:sensitivity\",\n\
  \        \"enabled\": \"reolink:enabled\",\n        \"detectionArea\": \"reolink:detectionArea\"\n      }\n    },\n    \"AIDetection\": {\n      \"@id\": \"reolink:AIDetection\",\n      \"@context\": {\n        \"personDetection\": \"reolink:personDetection\",\n        \"vehicleDetection\": \"reolink:vehicleDetection\",\n        \"animalDetection\": \"reolink:animalDetection\",\n        \"autoTracking\": \"reolink:autoTracking\"\n      }\n    },\n    \"NetworkSettings\": {\n      \"@id\": \"reolink:NetworkSettings\",\n      \"@context\": {\n        \"httpPort\": \"reolink:httpPort\",\n        \"httpsPort\": \"reolink:httpsPort\",\n        \"rtspPort\": \"reolink:rtspPort\",\n        \"onvifPort\": \"reolink:onvifPort\",\n        \"ipAddress\": \"reolink:ipAddress\",\n        \"macAddress\": \"reolink:macAddress\"\n      }\n    },\n    \"LEDControl\": {\n      \"@id\": \"reolink:LEDControl\",\n      \"@context\": {\n        \"irLights\": \"reolink:infraredLights\",\n        \"whiteLed\"\
  : \"reolink:whiteLed\",\n        \"powerLed\": \"reolink:powerLed\"\n      }\n    },\n    \"ImageSettings\": {\n      \"@id\": \"reolink:ImageSettings\",\n      \"@context\": {\n        \"brightness\": \"reolink:brightness\",\n        \"contrast\": \"reolink:contrast\",\n        \"saturation\": \"reolink:saturation\",\n        \"osd\": \"reolink:onScreenDisplay\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/reolink/refs/heads/main/json-ld/reolink-context.jsonld
tags:
- IoT
- Security Cameras
- Surveillance
- Smart Home
- AI Detection
- JSON-LD
- Linked Data
- Semantic Web
---
