---
api_specs:
- filename: absentify-openapi.yml
  format: yaml
  label: Absentify API
  slug: absentify
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/absentify/refs/heads/main/openapi/absentify-openapi.yml
class_count: 9
classes:
- id
- type
- Member
- Department
- LeaveType
- Request
- Absence
- Workspace
- PublicHolidayCalendar
context_file: json-ld/absentify-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/absentify/refs/heads/main/json-ld/absentify-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Absentify from Absentify.
layout: jsonld
name: Absentify Context
namespaces:
- prefix: absentify
  uri: https://absentify.com/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: name
  type: string
- container: ''
  name: email
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: member_id
  type: string
- container: ''
  name: department_id
  type: string
- container: ''
  name: leave_type_id
  type: string
- container: ''
  name: request_id
  type: string
- container: ''
  name: start
  type: date
- container: ''
  name: end
  type: date
- container: ''
  name: date
  type: date
- container: ''
  name: created_at
  type: dateTime
- container: ''
  name: updated_at
  type: dateTime
- container: ''
  name: color
  type: string
- container: ''
  name: approval_required
  type: boolean
- container: ''
  name: approved_by_id
  type: string
- container: ''
  name: approved_at
  type: dateTime
- container: ''
  name: workdays
  type: integer
- container: ''
  name: half_day
  type: boolean
- container: ''
  name: half_day_part
  type: string
- container: ''
  name: limit
  type: integer
- container: ''
  name: limit_type
  type: string
- container: ''
  name: active
  type: boolean
- container: ''
  name: reason
  type: string
- container: ''
  name: reason_required
  type: boolean
- container: ''
  name: country_code
  type: string
- container: ''
  name: year
  type: integer
- container: set
  name: holidays
  type: ''
- container: ''
  name: employment_start
  type: date
- container: ''
  name: employment_end
  type: date
- container: ''
  name: timezone
  type: string
- container: ''
  name: language
  type: string
- container: set
  name: manager_ids
  type: ''
- container: ''
  name: microsoft_365_id
  type: string
- container: ''
  name: plan
  type: string
- container: ''
  name: fiscal_year_start_month
  type: integer
property_count: 36
provider_name: Absentify
provider_slug: absentify
slug: absentify-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"absentify\": \"https://absentify.com/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"Member\": \"absentify:Member\",\n    \"Department\": \"absentify:Department\",\n    \"LeaveType\": \"absentify:LeaveType\",\n    \"Request\": \"absentify:Request\",\n    \"Absence\": \"absentify:Absence\",\n    \"Workspace\": \"absentify:Workspace\",\n    \"PublicHolidayCalendar\": \"absentify:PublicHolidayCalendar\",\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"absentify:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"member_id\": {\n      \"\
  @id\": \"absentify:memberId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"department_id\": {\n      \"@id\": \"absentify:departmentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"leave_type_id\": {\n      \"@id\": \"absentify:leaveTypeId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"request_id\": {\n      \"@id\": \"absentify:requestId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"start\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"end\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"date\": {\n      \"@id\": \"schema:date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"created_at\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updated_at\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"color\": {\n      \"@id\": \"absentify:color\",\n      \"@type\": \"xsd:string\"\n    },\n    \"approval_required\"\
  : {\n      \"@id\": \"absentify:approvalRequired\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"approved_by_id\": {\n      \"@id\": \"absentify:approvedById\",\n      \"@type\": \"xsd:string\"\n    },\n    \"approved_at\": {\n      \"@id\": \"absentify:approvedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"workdays\": {\n      \"@id\": \"absentify:workdays\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"half_day\": {\n      \"@id\": \"absentify:halfDay\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"half_day_part\": {\n      \"@id\": \"absentify:halfDayPart\",\n      \"@type\": \"xsd:string\"\n    },\n    \"limit\": {\n      \"@id\": \"absentify:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"limit_type\": {\n      \"@id\": \"absentify:limitType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"active\": {\n      \"@id\": \"absentify:active\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"reason\": {\n      \"@id\": \"absentify:reason\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"reason_required\": {\n      \"@id\": \"absentify:reasonRequired\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"country_code\": {\n      \"@id\": \"absentify:countryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"year\": {\n      \"@id\": \"schema:copyrightYear\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"holidays\": {\n      \"@id\": \"absentify:holidays\",\n      \"@container\": \"@set\"\n    },\n    \"employment_start\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"employment_end\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"timezone\": {\n      \"@id\": \"absentify:timezone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"language\": {\n      \"@id\": \"absentify:language\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manager_ids\": {\n      \"@id\": \"absentify:managerIds\",\n      \"@container\": \"@set\"\n    },\n    \"microsoft_365_id\": {\n\
  \      \"@id\": \"absentify:microsoft365Id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"plan\": {\n      \"@id\": \"absentify:plan\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fiscal_year_start_month\": {\n      \"@id\": \"absentify:fiscalYearStartMonth\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/absentify/refs/heads/main/json-ld/absentify-context.jsonld
tags:
- Absence Management
- HR
- Leave Management
- Microsoft Teams
- Human Resources
- JSON-LD
- Linked Data
- Semantic Web
---
