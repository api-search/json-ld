---
api_specs:
- filename: uipath-orchestrator-openapi.yml
  format: yaml
  label: UiPath Orchestrator API
  slug: uipath-orchestrator-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-orchestrator-openapi.yml
- filename: uipath-automation-hub-openapi.yml
  format: yaml
  label: UiPath Automation Hub API
  slug: uipath-automation-hub-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-automation-hub-openapi.yml
- filename: uipath-document-understanding-openapi.yml
  format: yaml
  label: UiPath Document Understanding API
  slug: uipath-document-understanding-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-document-understanding-openapi.yml
- filename: uipath-data-service-openapi.yml
  format: yaml
  label: UiPath Data Service API
  slug: uipath-data-service-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-data-service-openapi.yml
- filename: uipath-platform-management-openapi.yml
  format: yaml
  label: UiPath Platform Management API
  slug: uipath-platform-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-platform-management-openapi.yml
- filename: uipath-test-manager-openapi.yml
  format: yaml
  label: UiPath Test Manager API
  slug: uipath-test-manager-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-test-manager-openapi.yml
class_count: 14
classes:
- AuditEventCollection
- AuditEvent
- AuditSource
- AuditSources
- ClientInfo
- CreateGroupRequest
- CreateUserRequest
- GroupLicenseAllocation
- Group
- LicenseAllocationEntry
- UpdateGroupLicenseAllocationRequest
- User
- name
- email
context_file: json-ld/uipath-platform-management-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/json-ld/uipath-platform-management-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Uipath Platform Management from UiPath.
layout: jsonld
name: Uipath Platform Management Context
namespaces:
- prefix: uipath
  uri: https://uipath.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: auditEvents
  type: string
- container: ''
  name: next
  type: reference
- container: ''
  name: previous
  type: reference
- container: ''
  name: id
  type: string
- container: ''
  name: createdOn
  type: dateTime
- container: ''
  name: organizationId
  type: string
- container: ''
  name: actorId
  type: string
- container: ''
  name: actorEmail
  type: string
- container: ''
  name: eventType
  type: string
- container: ''
  name: eventSource
  type: string
- container: ''
  name: eventTarget
  type: string
- container: ''
  name: eventDetails
  type: reference
- container: ''
  name: eventSummary
  type: string
- container: ''
  name: status
  type: integer
- container: ''
  name: clientInfo
  type: string
- container: set
  name: targets
  type: string
- container: set
  name: sources
  type: string
- container: ''
  name: ipAddress
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: surname
  type: string
- container: ''
  name: groupId
  type: string
- container: set
  name: userLicenses
  type: string
- container: ''
  name: userCount
  type: integer
- container: ''
  name: code
  type: string
- container: ''
  name: totalCount
  type: integer
- container: ''
  name: usedCount
  type: integer
- container: ''
  name: isActive
  type: boolean
- container: ''
  name: lastLoginDate
  type: dateTime
property_count: 29
provider_name: UiPath
provider_slug: uipath
slug: uipath-platform-management-context
source_filename: uipath-platform-management-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"uipath\": \"https://uipath.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AuditEventCollection\": \"uipath:AuditEventCollection\",\n    \"AuditEvent\": \"uipath:AuditEvent\",\n    \"AuditSource\": \"uipath:AuditSource\",\n    \"AuditSources\": \"uipath:AuditSources\",\n    \"ClientInfo\": \"uipath:ClientInfo\",\n    \"CreateGroupRequest\": \"uipath:CreateGroupRequest\",\n    \"CreateUserRequest\": \"uipath:CreateUserRequest\",\n    \"GroupLicenseAllocation\": \"uipath:GroupLicenseAllocation\",\n    \"Group\": \"uipath:Group\",\n    \"LicenseAllocationEntry\": \"uipath:LicenseAllocationEntry\",\n    \"UpdateGroupLicenseAllocationRequest\": \"uipath:UpdateGroupLicenseAllocationRequest\",\n    \"User\": \"uipath:User\",\n    \"auditEvents\": {\n      \"@id\": \"uipath:auditEvents\",\n      \"@container\": \"@set\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"next\": {\n      \"@id\": \"uipath:next\",\n      \"@type\": \"@id\"\n    },\n    \"previous\": {\n      \"@id\": \"uipath:previous\",\n      \"@type\": \"@id\"\n    },\n    \"id\": {\n      \"@id\": \"uipath:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdOn\": {\n      \"@id\": \"uipath:createdOn\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"organizationId\": {\n      \"@id\": \"uipath:organizationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actorId\": {\n      \"@id\": \"uipath:actorId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actorEmail\": {\n      \"@id\": \"uipath:actorEmail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventType\": {\n      \"@id\": \"uipath:eventType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventSource\": {\n      \"@id\": \"uipath:eventSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventTarget\": {\n      \"@id\": \"uipath:eventTarget\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"eventDetails\": {\n      \"@id\": \"uipath:eventDetails\",\n      \"@type\": \"@id\"\n    },\n    \"eventSummary\": {\n      \"@id\": \"uipath:eventSummary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"uipath:status\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"clientInfo\": {\n      \"@id\": \"uipath:clientInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"targets\": {\n      \"@id\": \"uipath:targets\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sources\": {\n      \"@id\": \"uipath:sources\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipAddress\": {\n      \"@id\": \"uipath:ipAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"uipath:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"uipath:type\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"email\": \"schema:email\",\n    \"surname\": {\n      \"@id\": \"uipath:surname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groupId\": {\n      \"@id\": \"uipath:groupId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userLicenses\": {\n      \"@id\": \"uipath:userLicenses\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userCount\": {\n      \"@id\": \"uipath:userCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"code\": {\n      \"@id\": \"uipath:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalCount\": {\n      \"@id\": \"uipath:totalCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"usedCount\": {\n      \"@id\": \"uipath:usedCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"isActive\": {\n      \"@id\": \"uipath:isActive\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lastLoginDate\": {\n      \"@id\": \"uipath:lastLoginDate\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/json-ld/uipath-platform-management-context.jsonld
tags:
- Automation
- Robotic Process Automation
- RPA
- Artificial Intelligence
- Document Processing
- Enterprise Automation
- Orchestration
- Testing
- JSON-LD
- Linked Data
- Semantic Web
---
