---
api_specs:
- filename: relativityone-legal-hold-openapi.yml
  format: yaml
  label: Legal Hold API
  slug: legal-hold-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/relativityone/refs/heads/main/openapi/relativityone-legal-hold-openapi.yml
class_count: 0
classes: []
context_file: json-ld/relativityone-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/relativityone/refs/heads/main/json-ld/relativityone-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Relativityone from RelativityOne.
layout: jsonld
name: Relativityone Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: relativity
  uri: https://platform.relativity.com/vocab/
properties:
- container: ''
  name: LegalHoldProject
  type: reference
- container: ''
  name: Custodian
  type: reference
- container: ''
  name: Entity
  type: reference
- container: ''
  name: Communication
  type: reference
- container: ''
  name: Task
  type: reference
- container: ''
  name: artifactId
  type: integer
- container: ''
  name: name
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: status
  type: ''
- container: ''
  name: ownerEmailAddress
  type: ''
- container: ''
  name: emailAddress
  type: ''
- container: ''
  name: firstName
  type: ''
- container: ''
  name: lastName
  type: ''
- container: ''
  name: employeeId
  type: ''
- container: ''
  name: employeeStatus
  type: ''
- container: ''
  name: dueDate
  type: date
- container: ''
  name: createdDate
  type: dateTime
- container: ''
  name: modifiedDate
  type: dateTime
- container: set
  name: custodians
  type: ''
- container: set
  name: tasks
  type: ''
- container: set
  name: communications
  type: ''
- container: ''
  name: assignedTo
  type: ''
- container: ''
  name: workspaceId
  type: integer
- container: ''
  name: projectId
  type: integer
- container: ''
  name: escalationEnabled
  type: boolean
- container: ''
  name: reminderIntervalDays
  type: integer
- container: set
  name: dataSources
  type: ''
property_count: 27
provider_name: RelativityOne
provider_slug: relativityone
slug: relativityone-context
source_filename: relativityone-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"relativity\": \"https://platform.relativity.com/vocab/\",\n    \"LegalHoldProject\": {\n      \"@id\": \"relativity:LegalHoldProject\",\n      \"@type\": \"@id\"\n    },\n    \"Custodian\": {\n      \"@id\": \"relativity:Custodian\",\n      \"@type\": \"@id\"\n    },\n    \"Entity\": {\n      \"@id\": \"relativity:Entity\",\n      \"@type\": \"@id\"\n    },\n    \"Communication\": {\n      \"@id\": \"relativity:Communication\",\n      \"@type\": \"@id\"\n    },\n    \"Task\": {\n      \"@id\": \"relativity:Task\",\n      \"@type\": \"@id\"\n    },\n    \"artifactId\": {\n      \"@id\": \"relativity:artifactId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"status\": {\n      \"@id\": \"relativity:status\"\
  \n    },\n    \"ownerEmailAddress\": {\n      \"@id\": \"schema:email\"\n    },\n    \"emailAddress\": {\n      \"@id\": \"schema:email\"\n    },\n    \"firstName\": {\n      \"@id\": \"schema:givenName\"\n    },\n    \"lastName\": {\n      \"@id\": \"schema:familyName\"\n    },\n    \"employeeId\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"employeeStatus\": {\n      \"@id\": \"schema:employmentType\"\n    },\n    \"dueDate\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"createdDate\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modifiedDate\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"custodians\": {\n      \"@id\": \"relativity:hasCustodian\",\n      \"@container\": \"@set\"\n    },\n    \"tasks\": {\n      \"@id\": \"relativity:hasTask\",\n      \"@container\": \"@set\"\n    },\n    \"communications\": {\n      \"@id\": \"relativity:hasCommunication\"\
  ,\n      \"@container\": \"@set\"\n    },\n    \"assignedTo\": {\n      \"@id\": \"schema:assignee\"\n    },\n    \"workspaceId\": {\n      \"@id\": \"relativity:workspaceId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"projectId\": {\n      \"@id\": \"relativity:projectId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"escalationEnabled\": {\n      \"@id\": \"relativity:escalationEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"reminderIntervalDays\": {\n      \"@id\": \"relativity:reminderIntervalDays\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"dataSources\": {\n      \"@id\": \"relativity:dataSource\",\n      \"@container\": \"@set\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/relativityone/refs/heads/main/json-ld/relativityone-context.jsonld
tags:
- eDiscovery
- Legal
- Legal Hold
- Document Management
- Compliance
- Litigation
- JSON-LD
- Linked Data
- Semantic Web
---
