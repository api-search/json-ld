---
api_specs:
- filename: microsoft-project-rest-api.yaml
  format: yaml
  label: Microsoft Project Online REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-project/refs/heads/main/openapi/microsoft-project-rest-api.yaml
class_count: 11
classes:
- Project
- Task
- EnterpriseResource
- Assignment
- Calendar
- CustomField
- LookupTable
- TimeSheet
- Phase
- Stage
- EnterpriseProjectType
context_file: json-ld/microsoft-project-rest-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/microsoft-project/refs/heads/main/json-ld/microsoft-project-rest-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Microsoft Project Rest Api from Microsoft Project.
layout: jsonld
name: Microsoft Project Rest Api Context
namespaces:
- prefix: msproject
  uri: https://learn.microsoft.com/en-us/office/client-developer/project/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: startDate
  type: dateTime
- container: ''
  name: finishDate
  type: dateTime
- container: ''
  name: createdDate
  type: dateTime
- container: ''
  name: modifiedDate
  type: dateTime
- container: ''
  name: isCheckedOut
  type: boolean
- container: ''
  name: checkedOutBy
  type: string
- container: ''
  name: percentComplete
  type: integer
- container: ''
  name: projectType
  type: integer
- container: ''
  name: projectSiteUrl
  type: reference
- container: ''
  name: start
  type: dateTime
- container: ''
  name: finish
  type: dateTime
- container: ''
  name: duration
  type: string
- container: ''
  name: isSummary
  type: boolean
- container: ''
  name: isMilestone
  type: boolean
- container: ''
  name: priority
  type: integer
- container: ''
  name: parentId
  type: string
- container: ''
  name: notes
  type: string
- container: ''
  name: isManuallyScheduled
  type: boolean
- container: ''
  name: work
  type: string
- container: ''
  name: remainingWork
  type: string
- container: ''
  name: actualWork
  type: string
- container: ''
  name: cost
  type: double
- container: ''
  name: email
  type: string
- container: ''
  name: resourceType
  type: integer
- container: ''
  name: isActive
  type: boolean
- container: ''
  name: isGeneric
  type: boolean
- container: ''
  name: maxUnits
  type: double
- container: ''
  name: standardRate
  type: double
- container: ''
  name: costCenter
  type: string
- container: ''
  name: group
  type: string
- container: ''
  name: baseCalendar
  type: string
- container: ''
  name: projectId
  type: string
- container: ''
  name: taskId
  type: string
- container: ''
  name: resourceId
  type: string
- container: ''
  name: resourceName
  type: string
- container: ''
  name: percentWorkComplete
  type: integer
- container: ''
  name: isStandardCalendar
  type: boolean
- container: ''
  name: fieldType
  type: integer
- container: ''
  name: entityType
  type: integer
- container: ''
  name: isRequired
  type: boolean
- container: ''
  name: status
  type: integer
- container: ''
  name: totalWork
  type: string
- container: ''
  name: totalActualWork
  type: string
- container: ''
  name: phaseId
  type: string
property_count: 47
provider_name: Microsoft Project
provider_slug: microsoft-project
slug: microsoft-project-rest-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"msproject\": \"https://learn.microsoft.com/en-us/office/client-developer/project/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Project\": \"msproject:Project\",\n    \"Task\": \"msproject:Task\",\n    \"EnterpriseResource\": \"msproject:EnterpriseResource\",\n    \"Assignment\": \"msproject:Assignment\",\n    \"Calendar\": \"msproject:Calendar\",\n    \"CustomField\": \"msproject:CustomField\",\n    \"LookupTable\": \"msproject:LookupTable\",\n    \"TimeSheet\": \"msproject:TimeSheet\",\n    \"Phase\": \"msproject:Phase\",\n    \"Stage\": \"msproject:Stage\",\n    \"EnterpriseProjectType\": \"msproject:EnterpriseProjectType\",\n\n    \"id\": {\n      \"@id\": \"dcterms:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startDate\": {\n      \"@id\": \"msproject:StartDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"finishDate\": {\n      \"@id\": \"msproject:FinishDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"createdDate\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modifiedDate\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"isCheckedOut\": {\n      \"@id\": \"msproject:IsCheckedOut\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"checkedOutBy\": {\n      \"@id\": \"msproject:CheckedOutBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"percentComplete\": {\n      \"@id\": \"msproject:PercentComplete\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"projectType\": {\n      \"@id\": \"msproject:ProjectType\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"projectSiteUrl\"\
  : {\n      \"@id\": \"msproject:ProjectSiteUrl\",\n      \"@type\": \"@id\"\n    },\n    \"start\": {\n      \"@id\": \"msproject:Start\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"finish\": {\n      \"@id\": \"msproject:Finish\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"duration\": {\n      \"@id\": \"msproject:Duration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isSummary\": {\n      \"@id\": \"msproject:IsSummary\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isMilestone\": {\n      \"@id\": \"msproject:IsMilestone\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"priority\": {\n      \"@id\": \"msproject:Priority\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"parentId\": {\n      \"@id\": \"msproject:ParentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notes\": {\n      \"@id\": \"msproject:Notes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isManuallyScheduled\": {\n      \"@id\": \"msproject:IsManuallyScheduled\",\n      \"@type\":\
  \ \"xsd:boolean\"\n    },\n    \"work\": {\n      \"@id\": \"msproject:Work\",\n      \"@type\": \"xsd:string\"\n    },\n    \"remainingWork\": {\n      \"@id\": \"msproject:RemainingWork\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actualWork\": {\n      \"@id\": \"msproject:ActualWork\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cost\": {\n      \"@id\": \"msproject:Cost\",\n      \"@type\": \"xsd:double\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceType\": {\n      \"@id\": \"msproject:ResourceType\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"isActive\": {\n      \"@id\": \"msproject:IsActive\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isGeneric\": {\n      \"@id\": \"msproject:IsGeneric\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"maxUnits\": {\n      \"@id\": \"msproject:MaxUnits\",\n      \"@type\": \"xsd:double\"\n    },\n    \"standardRate\": {\n      \"@id\": \"msproject:StandardRate\"\
  ,\n      \"@type\": \"xsd:double\"\n    },\n    \"costCenter\": {\n      \"@id\": \"msproject:CostCenter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"group\": {\n      \"@id\": \"msproject:Group\",\n      \"@type\": \"xsd:string\"\n    },\n    \"baseCalendar\": {\n      \"@id\": \"msproject:BaseCalendar\",\n      \"@type\": \"xsd:string\"\n    },\n    \"projectId\": {\n      \"@id\": \"msproject:ProjectId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskId\": {\n      \"@id\": \"msproject:TaskId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceId\": {\n      \"@id\": \"msproject:ResourceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceName\": {\n      \"@id\": \"msproject:ResourceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"percentWorkComplete\": {\n      \"@id\": \"msproject:PercentWorkComplete\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"isStandardCalendar\": {\n      \"@id\": \"msproject:IsStandardCalendar\",\n      \"@type\": \"\
  xsd:boolean\"\n    },\n    \"fieldType\": {\n      \"@id\": \"msproject:FieldType\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"entityType\": {\n      \"@id\": \"msproject:EntityType\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"isRequired\": {\n      \"@id\": \"msproject:IsRequired\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"status\": {\n      \"@id\": \"msproject:Status\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalWork\": {\n      \"@id\": \"msproject:TotalWork\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalActualWork\": {\n      \"@id\": \"msproject:TotalActualWork\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phaseId\": {\n      \"@id\": \"msproject:PhaseId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/microsoft-project/refs/heads/main/json-ld/microsoft-project-rest-api-context.jsonld
tags:
- Budgeting
- Gantt Charts
- Microsoft
- Portfolio Management
- Project Management
- Resource Management
- Scheduling
- Task Management
- JSON-LD
- Linked Data
- Semantic Web
---
