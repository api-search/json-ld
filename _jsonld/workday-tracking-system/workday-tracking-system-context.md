---
api_specs:
- filename: workday-tracking-system-time-tracking-openapi.yml
  format: yaml
  label: Workday Time Tracking API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/openapi/workday-tracking-system-time-tracking-openapi.yml
- filename: workday-tracking-system-absence-management-openapi.yml
  format: yaml
  label: Workday Absence Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/openapi/workday-tracking-system-absence-management-openapi.yml
- filename: workday-tracking-system-scheduling-openapi.yml
  format: yaml
  label: Workday Scheduling API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/openapi/workday-tracking-system-scheduling-openapi.yml
class_count: 1
classes:
- id
context_file: json-ld/workday-tracking-system-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-ld/workday-tracking-system-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Workday Tracking System from Workday Tracking System.
layout: jsonld
name: Workday Tracking System Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: workday
  uri: https://api.workday.com/ontology/tracking/
properties:
- container: ''
  name: TimeBlock
  type: reference
- container: ''
  name: Timesheet
  type: reference
- container: ''
  name: LeaveOfAbsence
  type: reference
- container: ''
  name: TimeOffEntry
  type: reference
- container: ''
  name: ScheduleShift
  type: reference
- container: ''
  name: WorkSchedule
  type: reference
- container: ''
  name: TimeClockEvent
  type: reference
- container: ''
  name: TimeRequest
  type: reference
- container: ''
  name: workerId
  type: string
- container: ''
  name: date
  type: date
- container: ''
  name: startTime
  type: time
- container: ''
  name: endTime
  type: time
- container: ''
  name: hours
  type: decimal
- container: ''
  name: type
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: periodStartDate
  type: date
- container: ''
  name: periodEndDate
  type: date
- container: ''
  name: totalHours
  type: decimal
- container: ''
  name: regularHours
  type: decimal
- container: ''
  name: overtimeHours
  type: decimal
- container: ''
  name: leaveType
  type: string
- container: ''
  name: startDate
  type: date
- container: ''
  name: endDate
  type: date
- container: ''
  name: expectedEndDate
  type: date
- container: ''
  name: actualReturnDate
  type: date
- container: ''
  name: timeOffType
  type: string
- container: ''
  name: projectId
  type: string
- container: ''
  name: taskId
  type: string
- container: ''
  name: comment
  type: string
- container: ''
  name: eventType
  type: string
- container: ''
  name: eventDateTime
  type: dateTime
- container: ''
  name: shiftDate
  type: date
- container: ''
  name: organizationId
  type: string
- container: ''
  name: scheduleName
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: modifiedAt
  type: dateTime
property_count: 36
provider_name: Workday Tracking System
provider_slug: workday-tracking-system
slug: workday-tracking-system-context
source_filename: workday-tracking-system-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"workday\": \"https://api.workday.com/ontology/tracking/\",\n\n    \"TimeBlock\": {\n      \"@id\": \"workday:TimeBlock\",\n      \"@type\": \"@id\",\n      \"comment\": \"A reported or calculated time block representing hours worked by an employee\"\n    },\n    \"Timesheet\": {\n      \"@id\": \"workday:Timesheet\",\n      \"@type\": \"@id\",\n      \"comment\": \"An employee timesheet covering a specific pay period\"\n    },\n    \"LeaveOfAbsence\": {\n      \"@id\": \"workday:LeaveOfAbsence\",\n      \"@type\": \"@id\",\n      \"comment\": \"A leave of absence record for an employee\"\n    },\n    \"TimeOffEntry\": {\n      \"@id\": \"workday:TimeOffEntry\",\n      \"@type\": \"@id\",\n      \"comment\": \"An employee time off request entry\"\n    },\n    \"ScheduleShift\": {\n      \"@id\": \"workday:ScheduleShift\",\n      \"\
  @type\": \"@id\",\n      \"comment\": \"A shift assigned to a worker in a schedule\"\n    },\n    \"WorkSchedule\": {\n      \"@id\": \"workday:WorkSchedule\",\n      \"@type\": \"@id\",\n      \"comment\": \"A work schedule assignment for a worker\"\n    },\n    \"TimeClockEvent\": {\n      \"@id\": \"workday:TimeClockEvent\",\n      \"@type\": \"@id\",\n      \"comment\": \"A punch-in or punch-out event from a time clock device\"\n    },\n    \"TimeRequest\": {\n      \"@id\": \"workday:TimeRequest\",\n      \"@type\": \"@id\",\n      \"comment\": \"A time request submitted by a worker for approval\"\n    },\n\n    \"id\": \"@id\",\n    \"workerId\": {\n      \"@id\": \"workday:workerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"date\": {\n      \"@id\": \"workday:date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"startTime\": {\n      \"@id\": \"workday:startTime\",\n      \"@type\": \"xsd:time\"\n    },\n    \"endTime\": {\n      \"@id\": \"workday:endTime\",\n      \"@type\"\
  : \"xsd:time\"\n    },\n    \"hours\": {\n      \"@id\": \"workday:hours\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"type\": {\n      \"@id\": \"workday:timeType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"workday:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"periodStartDate\": {\n      \"@id\": \"workday:periodStartDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"periodEndDate\": {\n      \"@id\": \"workday:periodEndDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"totalHours\": {\n      \"@id\": \"workday:totalHours\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"regularHours\": {\n      \"@id\": \"workday:regularHours\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"overtimeHours\": {\n      \"@id\": \"workday:overtimeHours\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"leaveType\": {\n      \"@id\": \"workday:leaveType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startDate\": {\n      \"@id\": \"workday:startDate\"\
  ,\n      \"@type\": \"xsd:date\"\n    },\n    \"endDate\": {\n      \"@id\": \"workday:endDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"expectedEndDate\": {\n      \"@id\": \"workday:expectedEndDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"actualReturnDate\": {\n      \"@id\": \"workday:actualReturnDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"timeOffType\": {\n      \"@id\": \"workday:timeOffType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"projectId\": {\n      \"@id\": \"workday:projectId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskId\": {\n      \"@id\": \"workday:taskId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"comment\": {\n      \"@id\": \"workday:comment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventType\": {\n      \"@id\": \"workday:eventType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventDateTime\": {\n      \"@id\": \"workday:eventDateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"shiftDate\": {\n\
  \      \"@id\": \"workday:shiftDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"organizationId\": {\n      \"@id\": \"workday:organizationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scheduleName\": {\n      \"@id\": \"workday:scheduleName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modifiedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-ld/workday-tracking-system-context.jsonld
tags:
- Absence Management
- Attendance
- Enterprise
- HCM
- Human Capital Management
- Payroll
- Scheduling
- Time Tracking
- Timesheets
- Workforce Management
- JSON-LD
- Linked Data
- Semantic Web
---
