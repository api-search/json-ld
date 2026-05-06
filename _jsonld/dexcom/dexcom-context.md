---
api_specs:
- filename: dexcom-dexcom-api.yml
  format: yaml
  label: Dexcom Developer API
  slug: dexcom-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/openapi/dexcom-dexcom-api.yml
class_count: 17
classes:
- AlertRecord
- AlertSchedule
- AlertSetting
- AlertsResponse
- CalibrationRecord
- CalibrationsResponse
- DataRangeMoment
- DataRangeResponse
- DataRangeWindow
- DeviceRecord
- DevicesResponse
- EGVRecord
- EgvsResponse
- EventRecord
- EventsResponse
- TokenRequest
- TokenResponse
context_file: json-ld/dexcom-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-ld/dexcom-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dexcom from Dexcom.
layout: jsonld
name: Dexcom Context
namespaces:
- prefix: dex
  uri: https://developer.dexcom.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: accessToken
  type: string
- container: ''
  name: alertName
  type: string
- container: ''
  name: alertScheduleName
  type: string
- container: ''
  name: alertScheduleSettings
  type: reference
- container: set
  name: alertSchedules
  type: reference
- container: set
  name: alertSettings
  type: reference
- container: ''
  name: alertState
  type: string
- container: ''
  name: calibrations
  type: reference
- container: ''
  name: clientId
  type: string
- container: ''
  name: clientSecret
  type: string
- container: ''
  name: code
  type: string
- container: set
  name: daysOfWeek
  type: string
- container: ''
  name: displayApp
  type: string
- container: ''
  name: displayDevice
  type: string
- container: ''
  name: displayTime
  type: dateTime
- container: ''
  name: egvs
  type: reference
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: end
  type: reference
- container: ''
  name: endTime
  type: string
- container: ''
  name: eventStatus
  type: string
- container: ''
  name: eventSubType
  type: string
- container: ''
  name: eventType
  type: string
- container: ''
  name: events
  type: reference
- container: ''
  name: expiresIn
  type: integer
- container: ''
  name: grantType
  type: string
- container: ''
  name: isDefaultSchedule
  type: boolean
- container: ''
  name: isEnabled
  type: boolean
- container: ''
  name: lastUploadDate
  type: dateTime
- container: ''
  name: rateUnit
  type: string
- container: ''
  name: recordId
  type: string
- container: ''
  name: recordType
  type: string
- container: ''
  name: recordVersion
  type: string
- container: set
  name: records
  type: reference
- container: ''
  name: redirectUri
  type: reference
- container: ''
  name: refreshToken
  type: string
- container: ''
  name: snooze
  type: integer
- container: ''
  name: start
  type: reference
- container: ''
  name: startTime
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: systemTime
  type: dateTime
- container: ''
  name: tokenType
  type: string
- container: ''
  name: transmitterGeneration
  type: string
- container: ''
  name: transmitterId
  type: string
- container: ''
  name: transmitterTicks
  type: integer
- container: ''
  name: trend
  type: string
- container: ''
  name: trendRate
  type: double
- container: ''
  name: unit
  type: string
- container: ''
  name: userId
  type: string
- container: ''
  name: value
  type: decimal
property_count: 49
provider_name: Dexcom
provider_slug: dexcom
slug: dexcom-context
source_filename: dexcom-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"dex\": \"https://developer.dexcom.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AlertRecord\": \"dex:AlertRecord\",\n    \"AlertSchedule\": \"dex:AlertSchedule\",\n    \"AlertSetting\": \"dex:AlertSetting\",\n    \"AlertsResponse\": \"dex:AlertsResponse\",\n    \"CalibrationRecord\": \"dex:CalibrationRecord\",\n    \"CalibrationsResponse\": \"dex:CalibrationsResponse\",\n    \"DataRangeMoment\": \"dex:DataRangeMoment\",\n    \"DataRangeResponse\": \"dex:DataRangeResponse\",\n    \"DataRangeWindow\": \"dex:DataRangeWindow\",\n    \"DeviceRecord\": \"dex:DeviceRecord\",\n    \"DevicesResponse\": \"dex:DevicesResponse\",\n    \"EGVRecord\": \"dex:EGVRecord\",\n    \"EgvsResponse\": \"dex:EgvsResponse\",\n    \"EventRecord\": \"dex:EventRecord\",\n    \"EventsResponse\": \"dex:EventsResponse\",\n    \"TokenRequest\"\
  : \"dex:TokenRequest\",\n    \"TokenResponse\": \"dex:TokenResponse\",\n    \"accessToken\": {\n      \"@id\": \"dex:access_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alertName\": {\n      \"@id\": \"dex:alertName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alertScheduleName\": {\n      \"@id\": \"dex:alertScheduleName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alertScheduleSettings\": {\n      \"@id\": \"dex:alertScheduleSettings\",\n      \"@type\": \"@id\"\n    },\n    \"alertSchedules\": {\n      \"@id\": \"dex:alertSchedules\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"alertSettings\": {\n      \"@id\": \"dex:alertSettings\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"alertState\": {\n      \"@id\": \"dex:alertState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"calibrations\": {\n      \"@id\": \"dex:calibrations\",\n      \"@type\": \"@id\"\n    },\n    \"clientId\": {\n      \"@id\"\
  : \"dex:client_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientSecret\": {\n      \"@id\": \"dex:client_secret\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"dex:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"daysOfWeek\": {\n      \"@id\": \"dex:daysOfWeek\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayApp\": {\n      \"@id\": \"dex:displayApp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayDevice\": {\n      \"@id\": \"dex:displayDevice\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayTime\": {\n      \"@id\": \"dex:displayTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"egvs\": {\n      \"@id\": \"dex:egvs\",\n      \"@type\": \"@id\"\n    },\n    \"enabled\": {\n      \"@id\": \"dex:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"end\": {\n      \"@id\": \"dex:end\",\n      \"@type\": \"@id\"\n    },\n    \"endTime\": {\n      \"@id\": \"dex:endTime\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"eventStatus\": {\n      \"@id\": \"dex:eventStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventSubType\": {\n      \"@id\": \"dex:eventSubType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventType\": {\n      \"@id\": \"dex:eventType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"events\": {\n      \"@id\": \"dex:events\",\n      \"@type\": \"@id\"\n    },\n    \"expiresIn\": {\n      \"@id\": \"dex:expires_in\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"grantType\": {\n      \"@id\": \"dex:grant_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isDefaultSchedule\": {\n      \"@id\": \"dex:isDefaultSchedule\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isEnabled\": {\n      \"@id\": \"dex:isEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lastUploadDate\": {\n      \"@id\": \"dex:lastUploadDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"rateUnit\": {\n      \"@id\": \"dex:rateUnit\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"recordId\": {\n      \"@id\": \"dex:recordId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recordType\": {\n      \"@id\": \"dex:recordType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recordVersion\": {\n      \"@id\": \"dex:recordVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"records\": {\n      \"@id\": \"dex:records\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"redirectUri\": {\n      \"@id\": \"dex:redirect_uri\",\n      \"@type\": \"@id\"\n    },\n    \"refreshToken\": {\n      \"@id\": \"dex:refresh_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"snooze\": {\n      \"@id\": \"dex:snooze\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"start\": {\n      \"@id\": \"dex:start\",\n      \"@type\": \"@id\"\n    },\n    \"startTime\": {\n      \"@id\": \"dex:startTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"dex:status\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"systemTime\": {\n      \"@id\": \"dex:systemTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"tokenType\": {\n      \"@id\": \"dex:token_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transmitterGeneration\": {\n      \"@id\": \"dex:transmitterGeneration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transmitterId\": {\n      \"@id\": \"dex:transmitterId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transmitterTicks\": {\n      \"@id\": \"dex:transmitterTicks\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"trend\": {\n      \"@id\": \"dex:trend\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trendRate\": {\n      \"@id\": \"dex:trendRate\",\n      \"@type\": \"xsd:double\"\n    },\n    \"unit\": {\n      \"@id\": \"dex:unit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userId\": {\n      \"@id\": \"dex:userId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"dex:value\",\n      \"\
  @type\": \"xsd:decimal\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-ld/dexcom-context.jsonld
tags:
- Continuous Glucose Monitoring
- Diabetes
- Digital Health
- Glucose
- Healthcare
- Medical Devices
- Wearables
- JSON-LD
- Linked Data
- Semantic Web
---
