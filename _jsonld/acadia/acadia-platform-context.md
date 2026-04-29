---
class_count: 10
classes:
- WorkInstruction
- description
- WorkInstructionStep
- Employee
- name
- email
- SkillRecord
- EmployeeSkillsMatrix
- Quiz
- Role
context_file: json-ld/acadia-platform-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/acadia/refs/heads/main/json-ld/acadia-platform-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Acadia Platform from Acadia.
layout: jsonld
name: Acadia Platform Context
namespaces:
- prefix: acadia
  uri: https://acadia-software.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: version
  type: integer
- container: ''
  name: steps
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: order
  type: integer
- container: ''
  name: department
  type: string
- container: ''
  name: role
  type: string
- container: ''
  name: trainingCompletion
  type: integer
- container: ''
  name: skillId
  type: string
- container: ''
  name: required
  type: boolean
- container: ''
  name: completed
  type: boolean
- container: ''
  name: completedAt
  type: dateTime
- container: ''
  name: score
  type: integer
- container: ''
  name: employeeId
  type: string
- container: ''
  name: employeeName
  type: string
- container: ''
  name: skills
  type: string
- container: ''
  name: overallCompletion
  type: integer
- container: ''
  name: questionCount
  type: integer
- container: ''
  name: passingScore
  type: integer
- container: ''
  name: requiredTrainings
  type: integer
- container: ''
  name: completionRate
  type: integer
property_count: 25
provider_name: Acadia
provider_slug: acadia
slug: acadia-platform-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"acadia\": \"https://acadia-software.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"WorkInstruction\": \"acadia:WorkInstruction\",\n    \"id\": {\n      \"@id\": \"acadia:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"acadia:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"acadia:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"acadia:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"acadia:version\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"description\": \"schema:description\",\n    \"steps\": {\n      \"@id\": \"acadia:steps\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"acadia:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n\
  \      \"@id\": \"acadia:updatedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"WorkInstructionStep\": \"acadia:WorkInstructionStep\",\n    \"order\": {\n      \"@id\": \"acadia:order\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Employee\": \"acadia:Employee\",\n    \"name\": \"schema:name\",\n    \"email\": \"schema:email\",\n    \"department\": {\n      \"@id\": \"acadia:department\",\n      \"@type\": \"xsd:string\"\n    },\n    \"role\": {\n      \"@id\": \"acadia:role\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trainingCompletion\": {\n      \"@id\": \"acadia:trainingCompletion\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"SkillRecord\": \"acadia:SkillRecord\",\n    \"skillId\": {\n      \"@id\": \"acadia:skillId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"required\": {\n      \"@id\": \"acadia:required\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"completed\": {\n      \"@id\": \"acadia:completed\",\n      \"@type\": \"xsd:boolean\"\n    },\n\
  \    \"completedAt\": {\n      \"@id\": \"acadia:completedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"score\": {\n      \"@id\": \"acadia:score\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"EmployeeSkillsMatrix\": \"acadia:EmployeeSkillsMatrix\",\n    \"employeeId\": {\n      \"@id\": \"acadia:employeeId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"employeeName\": {\n      \"@id\": \"acadia:employeeName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"skills\": {\n      \"@id\": \"acadia:skills\",\n      \"@type\": \"xsd:string\"\n    },\n    \"overallCompletion\": {\n      \"@id\": \"acadia:overallCompletion\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Quiz\": \"acadia:Quiz\",\n    \"questionCount\": {\n      \"@id\": \"acadia:questionCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"passingScore\": {\n      \"@id\": \"acadia:passingScore\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Role\": \"acadia:Role\",\n    \"requiredTrainings\": {\n\
  \      \"@id\": \"acadia:requiredTrainings\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"completionRate\": {\n      \"@id\": \"acadia:completionRate\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/acadia/refs/heads/main/json-ld/acadia-platform-context.jsonld
tags:
- Connected Worker
- Knowledge Management
- Manufacturing
- Skills Management
- Training
- Workforce Development
- JSON-LD
- Linked Data
- Semantic Web
---
