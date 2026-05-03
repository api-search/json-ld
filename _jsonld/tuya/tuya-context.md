---
class_count: 0
classes: []
context_file: json-ld/tuya-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tuya/refs/heads/main/json-ld/tuya-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tuya from Tuya.
layout: jsonld
name: Tuya Context
namespaces:
- prefix: tuya
  uri: https://developer.tuya.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: iot
  uri: https://www.w3.org/ns/iot/core#
properties:
- container: ''
  name: Device
  type: ''
- container: ''
  name: DataPoint
  type: ''
- container: ''
  name: DeviceLog
  type: ''
- container: ''
  name: DeviceCommand
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: FactoryInfo
  type: ''
property_count: 6
provider_name: Tuya
provider_slug: tuya
slug: tuya-context
source_filename: tuya-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"tuya\": \"https://developer.tuya.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"iot\": \"https://www.w3.org/ns/iot/core#\",\n\n    \"Device\": {\n      \"@id\": \"tuya:Device\",\n      \"@context\": {\n        \"id\": \"tuya:deviceId\",\n        \"name\": \"schema:name\",\n        \"uid\": \"tuya:ownerId\",\n        \"local_key\": \"tuya:localKey\",\n        \"category\": \"tuya:productCategory\",\n        \"product_id\": \"tuya:productId\",\n        \"product_name\": \"tuya:productName\",\n        \"sub\": {\n          \"@id\": \"tuya:isSubDevice\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"uuid\": \"tuya:deviceUUID\",\n        \"owner_id\": \"tuya:homeId\",\n        \"online\": {\n          \"@id\": \"iot:online\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"status\"\
  : \"tuya:dataPoints\",\n        \"active_time\": {\n          \"@id\": \"tuya:activationTime\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"create_time\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"update_time\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"time_zone\": \"tuya:timeZone\",\n        \"ip\": \"schema:ipAddressId\"\n      }\n    },\n\n    \"DataPoint\": {\n      \"@id\": \"tuya:DataPoint\",\n      \"@context\": {\n        \"code\": \"tuya:dpCode\",\n        \"value\": \"tuya:dpValue\"\n      }\n    },\n\n    \"DeviceLog\": {\n      \"@id\": \"tuya:DeviceLog\",\n      \"@context\": {\n        \"event_time\": {\n          \"@id\": \"tuya:eventTime\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"code\": \"tuya:dpCode\",\n        \"value\": \"tuya:dpValue\",\n        \"event_id\": \"tuya:eventId\"\n      }\n    },\n\n    \"DeviceCommand\"\
  : {\n      \"@id\": \"tuya:DeviceCommand\",\n      \"@context\": {\n        \"commands\": \"tuya:commandList\",\n        \"code\": \"tuya:dpCode\",\n        \"value\": \"tuya:commandValue\"\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"tuya:User\",\n      \"@context\": {\n        \"uid\": \"tuya:userId\",\n        \"nick_name\": \"schema:name\",\n        \"user_type\": \"tuya:userRole\"\n      }\n    },\n\n    \"FactoryInfo\": {\n      \"@id\": \"tuya:FactoryInfo\",\n      \"@context\": {\n        \"id\": \"tuya:deviceId\",\n        \"uuid\": \"tuya:deviceUUID\",\n        \"sn\": \"tuya:serialNumber\",\n        \"mac\": \"schema:identifier\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tuya/refs/heads/main/json-ld/tuya-context.jsonld
tags:
- IoT
- Smart Home
- Devices
- Cloud Platform
- Automation
- Industrial IoT
- Device Management
- JSON-LD
- Linked Data
- Semantic Web
---
