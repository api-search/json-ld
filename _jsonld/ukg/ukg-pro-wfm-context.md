---
api_specs:
- filename: ukg-pro-hcm-openapi.yml
  format: yaml
  label: UKG Pro HCM API
  slug: ukg-pro-hcm-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ukg/refs/heads/main/openapi/ukg-pro-hcm-openapi.yml
- filename: ukg-pro-wfm-openapi.yml
  format: yaml
  label: UKG Pro Workforce Management API
  slug: ukg-pro-wfm-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ukg/refs/heads/main/openapi/ukg-pro-wfm-openapi.yml
class_count: 6
classes:
- WfmEmployee
- Timecard
- Punch
- PunchRequest
- AccrualBalance
- Shift
context_file: json-ld/ukg-pro-wfm-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ukg/refs/heads/main/json-ld/ukg-pro-wfm-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ukg Pro Wfm from UKG.
layout: jsonld
name: Ukg Pro Wfm Context
namespaces:
- prefix: ukg
  uri: https://ukg.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: employeeId
  type: string
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: badge
  type: string
- container: ''
  name: homeLocationId
  type: string
- container: ''
  name: jobCode
  type: string
- container: ''
  name: workRule
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: timecardId
  type: string
- container: ''
  name: periodStart
  type: date
- container: ''
  name: periodEnd
  type: date
- container: ''
  name: totalHours
  type: double
- container: ''
  name: regularHours
  type: double
- container: ''
  name: overtimeHours
  type: double
- container: ''
  name: punchId
  type: string
- container: ''
  name: punchTime
  type: dateTime
- container: ''
  name: punchType
  type: string
- container: ''
  name: locationId
  type: string
- container: ''
  name: accrualCodeId
  type: string
- container: ''
  name: accrualName
  type: string
- container: ''
  name: balance
  type: double
- container: ''
  name: pendingBalance
  type: double
- container: ''
  name: takingBalance
  type: double
- container: ''
  name: asOfDate
  type: date
- container: ''
  name: shiftId
  type: string
- container: ''
  name: shiftDate
  type: date
- container: ''
  name: startTime
  type: string
- container: ''
  name: endTime
  type: string
property_count: 28
provider_name: UKG
provider_slug: ukg
slug: ukg-pro-wfm-context
source_filename: ukg-pro-wfm-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ukg\": \"https://ukg.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"WfmEmployee\": \"ukg:WfmEmployee\",\n    \"employeeId\": {\n      \"@id\": \"ukg:employeeId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstName\": {\n      \"@id\": \"ukg:firstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"ukg:lastName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"badge\": {\n      \"@id\": \"ukg:badge\",\n      \"@type\": \"xsd:string\"\n    },\n    \"homeLocationId\": {\n      \"@id\": \"ukg:homeLocationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobCode\": {\n      \"@id\": \"ukg:jobCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"workRule\": {\n      \"@id\": \"ukg:workRule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\"\
  : \"ukg:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Timecard\": \"ukg:Timecard\",\n    \"timecardId\": {\n      \"@id\": \"ukg:timecardId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"periodStart\": {\n      \"@id\": \"ukg:periodStart\",\n      \"@type\": \"xsd:date\"\n    },\n    \"periodEnd\": {\n      \"@id\": \"ukg:periodEnd\",\n      \"@type\": \"xsd:date\"\n    },\n    \"totalHours\": {\n      \"@id\": \"ukg:totalHours\",\n      \"@type\": \"xsd:double\"\n    },\n    \"regularHours\": {\n      \"@id\": \"ukg:regularHours\",\n      \"@type\": \"xsd:double\"\n    },\n    \"overtimeHours\": {\n      \"@id\": \"ukg:overtimeHours\",\n      \"@type\": \"xsd:double\"\n    },\n    \"Punch\": \"ukg:Punch\",\n    \"punchId\": {\n      \"@id\": \"ukg:punchId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"punchTime\": {\n      \"@id\": \"ukg:punchTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"punchType\": {\n      \"@id\": \"ukg:punchType\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"locationId\": {\n      \"@id\": \"ukg:locationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PunchRequest\": \"ukg:PunchRequest\",\n    \"AccrualBalance\": \"ukg:AccrualBalance\",\n    \"accrualCodeId\": {\n      \"@id\": \"ukg:accrualCodeId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accrualName\": {\n      \"@id\": \"ukg:accrualName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"balance\": {\n      \"@id\": \"ukg:balance\",\n      \"@type\": \"xsd:double\"\n    },\n    \"pendingBalance\": {\n      \"@id\": \"ukg:pendingBalance\",\n      \"@type\": \"xsd:double\"\n    },\n    \"takingBalance\": {\n      \"@id\": \"ukg:takingBalance\",\n      \"@type\": \"xsd:double\"\n    },\n    \"asOfDate\": {\n      \"@id\": \"ukg:asOfDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"Shift\": \"ukg:Shift\",\n    \"shiftId\": {\n      \"@id\": \"ukg:shiftId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shiftDate\": {\n      \"@id\": \"ukg:shiftDate\"\
  ,\n      \"@type\": \"xsd:date\"\n    },\n    \"startTime\": {\n      \"@id\": \"ukg:startTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endTime\": {\n      \"@id\": \"ukg:endTime\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ukg/refs/heads/main/json-ld/ukg-pro-wfm-context.jsonld
tags:
- Human Capital Management
- HCM
- Workforce Management
- HR
- Payroll
- Time and Attendance
- Benefits
- Scheduling
- JSON-LD
- Linked Data
- Semantic Web
---
