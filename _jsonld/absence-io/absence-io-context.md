---
class_count: 9
classes:
- Timespan
- name
- Department
- Location
- ReasonType
- Absence
- User
- email
- Allowance
context_file: json-ld/absence-io-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/absence-io/refs/heads/main/json-ld/absence-io-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Absence Io from Absence.io.
layout: jsonld
name: Absence Io Context
namespaces:
- prefix: absence
  uri: https://absence.io/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Id
  type: string
- container: ''
  name: hoursPerDay
  type: decimal
- container: ''
  name: daysPerWeek
  type: integer
- container: ''
  name: managerId
  type: string
- container: ''
  name: parentId
  type: string
- container: ''
  name: timezone
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: color
  type: string
- container: ''
  name: requiresApproval
  type: boolean
- container: ''
  name: affectsAllowance
  type: boolean
- container: ''
  name: assignedToId
  type: string
- container: ''
  name: reasonId
  type: string
- container: ''
  name: approverId
  type: string
- container: ''
  name: start
  type: dateTime
- container: ''
  name: end
  type: dateTime
- container: ''
  name: days
  type: decimal
- container: ''
  name: status
  type: integer
- container: ''
  name: comment
  type: string
- container: ''
  name: departmentId
  type: string
- container: ''
  name: locationId
  type: string
- container: ''
  name: teamId
  type: string
- container: ''
  name: language
  type: string
- container: ''
  name: userId
  type: string
- container: ''
  name: year
  type: integer
- container: ''
  name: allowance
  type: decimal
- container: ''
  name: used
  type: decimal
- container: ''
  name: remaining
  type: decimal
- container: ''
  name: carryover
  type: decimal
property_count: 28
provider_name: Absence.io
provider_slug: absence-io
slug: absence-io-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"absence\": \"https://absence.io/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Timespan\": \"absence:Timespan\",\n    \"Id\": {\n      \"@id\": \"absence:_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"hoursPerDay\": {\n      \"@id\": \"absence:hoursPerDay\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"daysPerWeek\": {\n      \"@id\": \"absence:daysPerWeek\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Department\": \"absence:Department\",\n    \"managerId\": {\n      \"@id\": \"absence:managerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parentId\": {\n      \"@id\": \"absence:parentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Location\": \"absence:Location\",\n    \"timezone\": {\n      \"@id\": \"absence:timezone\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"country\": {\n      \"@id\": \"absence:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReasonType\": \"absence:ReasonType\",\n    \"color\": {\n      \"@id\": \"absence:color\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requiresApproval\": {\n      \"@id\": \"absence:requiresApproval\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"affectsAllowance\": {\n      \"@id\": \"absence:affectsAllowance\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"Absence\": \"absence:Absence\",\n    \"assignedToId\": {\n      \"@id\": \"absence:assignedToId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reasonId\": {\n      \"@id\": \"absence:reasonId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"approverId\": {\n      \"@id\": \"absence:approverId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"start\": {\n      \"@id\": \"absence:start\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"end\": {\n      \"@id\": \"absence:end\",\n      \"@type\": \"xsd:dateTime\"\
  \n    },\n    \"days\": {\n      \"@id\": \"absence:days\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"status\": {\n      \"@id\": \"absence:status\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"comment\": {\n      \"@id\": \"absence:comment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"User\": \"absence:User\",\n    \"email\": \"schema:email\",\n    \"departmentId\": {\n      \"@id\": \"absence:departmentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locationId\": {\n      \"@id\": \"absence:locationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"teamId\": {\n      \"@id\": \"absence:teamId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"language\": {\n      \"@id\": \"absence:language\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Allowance\": \"absence:Allowance\",\n    \"userId\": {\n      \"@id\": \"absence:userId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"year\": {\n      \"@id\": \"absence:year\",\n      \"@type\": \"xsd:integer\"\n  \
  \  },\n    \"allowance\": {\n      \"@id\": \"absence:allowance\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"used\": {\n      \"@id\": \"absence:used\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"remaining\": {\n      \"@id\": \"absence:remaining\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"carryover\": {\n      \"@id\": \"absence:carryover\",\n      \"@type\": \"xsd:decimal\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/absence-io/refs/heads/main/json-ld/absence-io-context.jsonld
tags:
- Absences
- Employees
- Leave Management
- HR
- JSON-LD
- Linked Data
- Semantic Web
---
