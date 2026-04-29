---
api_specs:
- filename: adt-platform-api-openapi.yml
  format: yaml
  label: ADT+ Platform API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adt/refs/heads/main/openapi/adt-platform-api-openapi.yml
- filename: adt-business-api-openapi.yml
  format: yaml
  label: ADT Business API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adt/refs/heads/main/openapi/adt-business-api-openapi.yml
class_count: 19
classes:
- ArmRequest
- System
- DeviceList
- AccessCode
- VideoClipList
- AutomationList
- Event
- EventList
- VideoClip
- AccessCodeList
- Device
- Automation
- SystemList
- DisarmRequest
- SystemStatusResponse
- AccessCodeInput
- name
- address
- description
context_file: json-ld/adt-platform-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adt/refs/heads/main/json-ld/adt-platform-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adt Platform Api from ADT.
layout: jsonld
name: Adt Platform Api Context
namespaces:
- prefix: adt
  uri: https://api.adt.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: mode
  type: string
- container: ''
  name: accessCode
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: lastModified
  type: dateTime
- container: set
  name: devices
  type: string
- container: ''
  name: expiresAt
  type: dateTime
- container: set
  name: permissions
  type: string
- container: set
  name: clips
  type: string
- container: set
  name: automations
  type: string
- container: ''
  name: deviceId
  type: string
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: userId
  type: string
- container: set
  name: events
  type: string
- container: ''
  name: total
  type: integer
- container: ''
  name: cameraId
  type: string
- container: ''
  name: startTime
  type: dateTime
- container: ''
  name: endTime
  type: dateTime
- container: ''
  name: trigger
  type: string
- container: ''
  name: downloadUrl
  type: reference
- container: ''
  name: thumbnailUrl
  type: reference
- container: set
  name: accessCodes
  type: string
- container: ''
  name: zone
  type: string
- container: ''
  name: batteryLevel
  type: integer
- container: ''
  name: lastActivity
  type: dateTime
- container: ''
  name: enabled
  type: boolean
- container: set
  name: actions
  type: string
- container: set
  name: systems
  type: string
- container: ''
  name: systemId
  type: string
- container: ''
  name: code
  type: string
property_count: 31
provider_name: ADT
provider_slug: adt
slug: adt-platform-api-context
source_filename: adt-platform-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adt\": \"https://api.adt.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ArmRequest\": \"adt:ArmRequest\",\n    \"System\": \"adt:System\",\n    \"DeviceList\": \"adt:DeviceList\",\n    \"AccessCode\": \"adt:AccessCode\",\n    \"VideoClipList\": \"adt:VideoClipList\",\n    \"AutomationList\": \"adt:AutomationList\",\n    \"Event\": \"adt:Event\",\n    \"EventList\": \"adt:EventList\",\n    \"VideoClip\": \"adt:VideoClip\",\n    \"AccessCodeList\": \"adt:AccessCodeList\",\n    \"Device\": \"adt:Device\",\n    \"Automation\": \"adt:Automation\",\n    \"SystemList\": \"adt:SystemList\",\n    \"DisarmRequest\": \"adt:DisarmRequest\",\n    \"SystemStatusResponse\": \"adt:SystemStatusResponse\",\n    \"AccessCodeInput\": \"adt:AccessCodeInput\",\n    \"mode\": {\n      \"@id\": \"adt:mode\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"accessCode\": {\n      \"@id\": \"adt:accessCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"adt:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"status\": {\n      \"@id\": \"adt:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address\": \"schema:address\",\n    \"type\": {\n      \"@id\": \"adt:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastModified\": {\n      \"@id\": \"adt:lastModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"devices\": {\n      \"@id\": \"adt:devices\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiresAt\": {\n      \"@id\": \"adt:expiresAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"permissions\": {\n      \"@id\": \"adt:permissions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clips\": {\n      \"@id\": \"adt:clips\",\n      \"@container\": \"@set\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"automations\": {\n      \"@id\": \"adt:automations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"deviceId\": {\n      \"@id\": \"adt:deviceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"adt:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"userId\": {\n      \"@id\": \"adt:userId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"events\": {\n      \"@id\": \"adt:events\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"total\": {\n      \"@id\": \"adt:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"cameraId\": {\n      \"@id\": \"adt:cameraId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"adt:startTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"endTime\": {\n      \"@id\": \"adt:endTime\",\n      \"@type\": \"xsd:dateTime\"\
  \n    },\n    \"trigger\": {\n      \"@id\": \"adt:trigger\",\n      \"@type\": \"xsd:string\"\n    },\n    \"downloadUrl\": {\n      \"@id\": \"adt:downloadUrl\",\n      \"@type\": \"@id\"\n    },\n    \"thumbnailUrl\": {\n      \"@id\": \"adt:thumbnailUrl\",\n      \"@type\": \"@id\"\n    },\n    \"accessCodes\": {\n      \"@id\": \"adt:accessCodes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"zone\": {\n      \"@id\": \"adt:zone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"batteryLevel\": {\n      \"@id\": \"adt:batteryLevel\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"lastActivity\": {\n      \"@id\": \"adt:lastActivity\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"enabled\": {\n      \"@id\": \"adt:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"actions\": {\n      \"@id\": \"adt:actions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"systems\": {\n      \"@id\": \"adt:systems\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"systemId\": {\n      \"@id\": \"adt:systemId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"adt:code\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adt/refs/heads/main/json-ld/adt-platform-api-context.jsonld
tags:
- Access Control
- Automation
- Home Security
- IoT
- Monitoring
- Security
- Smart Home
- JSON-LD
- Linked Data
- Semantic Web
---
