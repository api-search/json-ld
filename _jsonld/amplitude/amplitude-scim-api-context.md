---
class_count: 8
classes:
- ScimGroup
- ScimUser
- ScimGroupRequest
- ScimUserRequest
- ScimGroupListResponse
- ScimPatchRequest
- ScimUserListResponse
- name
context_file: json-ld/amplitude-scim-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/json-ld/amplitude-scim-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amplitude Scim Api from Amplitude.
layout: jsonld
name: Amplitude Scim Api Context
namespaces:
- prefix: amplitude
  uri: https://amplitude.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: schemas
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: displayName
  type: string
- container: set
  name: members
  type: reference
- container: ''
  name: value
  type: string
- container: ''
  name: display
  type: string
- container: ''
  name: meta
  type: reference
- container: ''
  name: resourceType
  type: string
- container: ''
  name: created
  type: dateTime
- container: ''
  name: lastModified
  type: dateTime
- container: ''
  name: userName
  type: string
- container: ''
  name: givenName
  type: string
- container: ''
  name: familyName
  type: string
- container: set
  name: emails
  type: reference
- container: ''
  name: primary
  type: boolean
- container: ''
  name: type
  type: string
- container: ''
  name: active
  type: boolean
- container: set
  name: groups
  type: reference
- container: ''
  name: totalResults
  type: integer
- container: set
  name: Resources
  type: reference
- container: set
  name: Operations
  type: reference
- container: ''
  name: op
  type: string
- container: ''
  name: path
  type: string
- container: ''
  name: startIndex
  type: integer
- container: ''
  name: itemsPerPage
  type: integer
property_count: 25
provider_name: Amplitude
provider_slug: amplitude
slug: amplitude-scim-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amplitude\": \"https://amplitude.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ScimGroup\": \"amplitude:ScimGroup\",\n    \"ScimUser\": \"amplitude:ScimUser\",\n    \"ScimGroupRequest\": \"amplitude:ScimGroupRequest\",\n    \"ScimUserRequest\": \"amplitude:ScimUserRequest\",\n    \"ScimGroupListResponse\": \"amplitude:ScimGroupListResponse\",\n    \"ScimPatchRequest\": \"amplitude:ScimPatchRequest\",\n    \"ScimUserListResponse\": \"amplitude:ScimUserListResponse\",\n    \"schemas\": {\n      \"@id\": \"amplitude:schemas\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"amplitude:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": {\n      \"@id\": \"amplitude:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"members\"\
  : {\n      \"@id\": \"amplitude:members\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"value\": {\n      \"@id\": \"amplitude:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"display\": {\n      \"@id\": \"amplitude:display\",\n      \"@type\": \"xsd:string\"\n    },\n    \"meta\": {\n      \"@id\": \"amplitude:meta\",\n      \"@type\": \"@id\"\n    },\n    \"resourceType\": {\n      \"@id\": \"amplitude:resourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"created\": {\n      \"@id\": \"amplitude:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastModified\": {\n      \"@id\": \"amplitude:lastModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"userName\": {\n      \"@id\": \"amplitude:userName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"givenName\": {\n      \"@id\": \"amplitude:givenName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"familyName\": {\n      \"@id\": \"amplitude:familyName\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"emails\": {\n      \"@id\": \"amplitude:emails\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"primary\": {\n      \"@id\": \"amplitude:primary\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"type\": {\n      \"@id\": \"amplitude:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"active\": {\n      \"@id\": \"amplitude:active\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"groups\": {\n      \"@id\": \"amplitude:groups\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"totalResults\": {\n      \"@id\": \"amplitude:totalResults\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Resources\": {\n      \"@id\": \"amplitude:Resources\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"Operations\": {\n      \"@id\": \"amplitude:Operations\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"op\": {\n      \"@id\": \"amplitude:op\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"path\": {\n      \"@id\": \"amplitude:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startIndex\": {\n      \"@id\": \"amplitude:startIndex\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"itemsPerPage\": {\n      \"@id\": \"amplitude:itemsPerPage\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/json-ld/amplitude-scim-api-context.jsonld
tags:
- A/B Testing
- Analytics
- Experimentation
- Feature Flags
- Product Analytics
- User Behavior
- JSON-LD
- Linked Data
- Semantic Web
---
