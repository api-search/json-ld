---
api_specs:
- filename: dynatrace-metrics-api-v2-openapi.yml
  format: yaml
  label: Dynatrace Metrics API v2
  slug: dynatrace-metrics-api-v2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/openapi/dynatrace-metrics-api-v2-openapi.yml
- filename: dynatrace-log-monitoring-api-v2-openapi.yml
  format: yaml
  label: Dynatrace Log Monitoring API v2
  slug: dynatrace-log-monitoring-api-v2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/openapi/dynatrace-log-monitoring-api-v2-openapi.yml
- filename: dynatrace-account-management-api-openapi.yml
  format: yaml
  label: Dynatrace Account Management API
  slug: dynatrace-account-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/openapi/dynatrace-account-management-api-openapi.yml
- filename: dynatrace-events-api-v2-openapi.yml
  format: yaml
  label: Dynatrace Events API v2
  slug: dynatrace-events-api-v2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/openapi/dynatrace-events-api-v2-openapi.yml
- filename: dynatrace-problems-api-v2-openapi.yml
  format: yaml
  label: Dynatrace Problems API v2
  slug: dynatrace-problems-api-v2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/openapi/dynatrace-problems-api-v2-openapi.yml
- filename: dynatrace-entities-api-v2-openapi.yml
  format: yaml
  label: Dynatrace Entities API v2
  slug: dynatrace-entities-api-v2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/openapi/dynatrace-entities-api-v2-openapi.yml
class_count: 10
classes:
- EnvironmentCollection
- Environment
- GroupCollection
- GroupCreateRequest
- Group
- PermissionCollection
- Permission
- UserCollection
- UserCreateRequest
- User
context_file: json-ld/dynatrace-account-management-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-account-management-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dynatrace Account Management Api from Dynatrace.
layout: jsonld
name: Dynatrace Account Management Api Context
namespaces:
- prefix: dt
  uri: https://dt.dynatrace.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: nextPageKey
  type: string
- container: ''
  name: totalCount
  type: integer
- container: set
  name: environments
  type: ''
- container: ''
  name: id
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: trial
  type: boolean
- container: set
  name: items
  type: ''
- container: ''
  name: description
  type: string
- container: ''
  name: groupId
  type: string
- container: ''
  name: owner
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: set
  name: permissions
  type: ''
- container: ''
  name: permissionName
  type: string
- container: ''
  name: scope
  type: string
- container: ''
  name: scopeType
  type: string
- container: ''
  name: email
  type: string
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: set
  name: groups
  type: ''
- container: ''
  name: uid
  type: string
- container: ''
  name: userStatus
  type: string
property_count: 23
provider_name: Dynatrace
provider_slug: dynatrace
slug: dynatrace-account-management-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"dt\": \"https://dt.dynatrace.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"EnvironmentCollection\": \"dt:EnvironmentCollection\",\n    \"nextPageKey\": {\n      \"@id\": \"dt:nextPageKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalCount\": {\n      \"@id\": \"dt:totalCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"environments\": {\n      \"@id\": \"dt:environments\",\n      \"@container\": \"@set\"\n    },\n    \"Environment\": \"dt:Environment\",\n    \"id\": {\n      \"@id\": \"dt:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"dt:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trial\": {\n      \"@id\": \"dt:trial\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"GroupCollection\": \"dt:GroupCollection\"\
  ,\n    \"items\": {\n      \"@id\": \"dt:items\",\n      \"@container\": \"@set\"\n    },\n    \"GroupCreateRequest\": \"dt:GroupCreateRequest\",\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Group\": \"dt:Group\",\n    \"groupId\": {\n      \"@id\": \"dt:groupId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"owner\": {\n      \"@id\": \"dt:owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"dt:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"dt:updatedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"PermissionCollection\": \"dt:PermissionCollection\",\n    \"permissions\": {\n      \"@id\": \"dt:permissions\",\n      \"@container\": \"@set\"\n    },\n    \"Permission\": \"dt:Permission\",\n    \"permissionName\": {\n      \"@id\": \"dt:permissionName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scope\": {\n      \"@id\"\
  : \"dt:scope\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scopeType\": {\n      \"@id\": \"dt:scopeType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UserCollection\": \"dt:UserCollection\",\n    \"UserCreateRequest\": \"dt:UserCreateRequest\",\n    \"email\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstName\": {\n      \"@id\": \"dt:firstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"dt:lastName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groups\": {\n      \"@id\": \"dt:groups\",\n      \"@container\": \"@set\"\n    },\n    \"User\": \"dt:User\",\n    \"uid\": {\n      \"@id\": \"dt:uid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userStatus\": {\n      \"@id\": \"dt:userStatus\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-account-management-api-context.jsonld
tags:
- AI Operations
- Analytics
- APM
- Application Performance Monitoring
- Application Security
- Automation
- Cloud Monitoring
- Digital Experience Management
- Intelligence
- Observability
- JSON-LD
- Linked Data
- Semantic Web
---
