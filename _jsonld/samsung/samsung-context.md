---
api_specs:
- filename: samsung-smartthings-openapi.yml
  format: yaml
  label: SmartThings API
  slug: smartthings
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/samsung/refs/heads/main/openapi/samsung-smartthings-openapi.yml
class_count: 43
classes:
- Device
- Location
- Room
- Scene
- Rule
- Automation
- deviceId
- name
- label
- description
- locationId
- roomId
- ownerId
- manufacturerName
- deviceManufacturerCode
- presentationId
- type
- components
- capabilities
- categories
- switch
- level
- temperatureMeasurement
- motionSensor
- contactSensor
- lock
- colorControl
- powerMeter
- knoxDeviceId
- enrollmentType
- policyName
- deviceModel
- firmwareVersion
- serialNumber
- healthId
- stepCount
- heartRate
- sleepDuration
- appId
- platform
- version
- createdDate
- modifiedDate
context_file: json-ld/samsung-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/samsung/refs/heads/main/json-ld/samsung-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Samsung from Samsung.
layout: jsonld
name: Samsung Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: iot
  uri: https://www.w3.org/ns/ssn/
- prefix: sosa
  uri: http://www.w3.org/ns/sosa/
- prefix: samsung
  uri: https://developer.samsung.com/vocabulary#
- prefix: st
  uri: https://developer.smartthings.com/vocabulary#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties: []
property_count: 0
provider_name: Samsung
provider_slug: samsung
slug: samsung-context
source_filename: samsung-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"iot\": \"https://www.w3.org/ns/ssn/\",\n    \"sosa\": \"http://www.w3.org/ns/sosa/\",\n    \"samsung\": \"https://developer.samsung.com/vocabulary#\",\n    \"st\": \"https://developer.smartthings.com/vocabulary#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Device\": \"schema:Device\",\n    \"Location\": \"schema:Place\",\n    \"Room\": \"schema:Room\",\n    \"Scene\": \"schema:Action\",\n    \"Rule\": \"schema:Intangible\",\n    \"Automation\": \"schema:Intangible\",\n\n    \"deviceId\": \"@id\",\n    \"name\": \"schema:name\",\n    \"label\": \"schema:alternateName\",\n    \"description\": \"schema:description\",\n\n    \"locationId\": \"schema:containedInPlace\",\n    \"roomId\": \"st:room\",\n    \"ownerId\": \"schema:accountablePerson\",\n    \"manufacturerName\": \"schema:manufacturer\",\n    \"deviceManufacturerCode\": \"schema:productID\",\n    \"presentationId\"\
  : \"st:presentationId\",\n    \"type\": \"schema:additionalType\",\n\n    \"components\": \"schema:hasPart\",\n    \"capabilities\": \"st:capabilities\",\n    \"categories\": \"schema:category\",\n\n    \"switch\": \"st:switch\",\n    \"level\": \"st:level\",\n    \"temperatureMeasurement\": \"sosa:ObservableProperty\",\n    \"motionSensor\": \"sosa:ObservableProperty\",\n    \"contactSensor\": \"sosa:ObservableProperty\",\n    \"lock\": \"st:lock\",\n    \"colorControl\": \"st:colorControl\",\n    \"powerMeter\": \"sosa:ObservableProperty\",\n\n    \"knoxDeviceId\": \"samsung:knoxDeviceId\",\n    \"enrollmentType\": \"samsung:enrollmentType\",\n    \"policyName\": \"samsung:policyName\",\n    \"deviceModel\": \"schema:model\",\n    \"firmwareVersion\": \"schema:softwareVersion\",\n    \"serialNumber\": \"schema:serialNumber\",\n\n    \"healthId\": \"schema:identifier\",\n    \"stepCount\": \"samsung:stepCount\",\n    \"heartRate\": \"samsung:heartRate\",\n    \"sleepDuration\": \"samsung:sleepDuration\"\
  ,\n\n    \"appId\": \"schema:identifier\",\n    \"platform\": \"schema:operatingSystem\",\n    \"version\": \"schema:version\",\n    \"createdDate\": \"schema:dateCreated\",\n    \"modifiedDate\": \"schema:dateModified\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/samsung/refs/heads/main/json-ld/samsung-context.jsonld
tags:
- Consumer Electronics
- Developer Platform
- IoT
- Mobile
- Smart Home
- Smart TV
- Wearables
- JSON-LD
- Linked Data
- Semantic Web
---
