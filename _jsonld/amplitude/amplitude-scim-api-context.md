---
api_specs:
- filename: amplitude-http-v2-api-openapi.yml
  format: yaml
  label: Amplitude HTTP V2 API
  slug: http-v2-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-http-v2-api-openapi.yml
- filename: amplitude-identify-api-openapi.yml
  format: yaml
  label: Amplitude Identify API
  slug: identify-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-identify-api-openapi.yml
- filename: amplitude-dashboard-rest-api-openapi.yml
  format: yaml
  label: Amplitude Dashboard REST API
  slug: dashboard-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-dashboard-rest-api-openapi.yml
- filename: amplitude-export-api-openapi.yml
  format: yaml
  label: Amplitude Export API
  slug: export-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-export-api-openapi.yml
- filename: amplitude-behavioral-cohorts-api-openapi.yml
  format: yaml
  label: Amplitude Behavioral Cohorts API
  slug: behavioral-cohorts-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-behavioral-cohorts-api-openapi.yml
- filename: amplitude-taxonomy-api-openapi.yml
  format: yaml
  label: Amplitude Taxonomy API
  slug: taxonomy-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-taxonomy-api-openapi.yml
- filename: amplitude-attribution-api-openapi.yml
  format: yaml
  label: Amplitude Attribution API
  slug: attribution-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-attribution-api-openapi.yml
- filename: amplitude-chart-annotations-api-openapi.yml
  format: yaml
  label: Amplitude Chart Annotations API
  slug: chart-annotations-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-chart-annotations-api-openapi.yml
- filename: amplitude-user-profile-api-openapi.yml
  format: yaml
  label: Amplitude User Profile API
  slug: user-profile-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-user-profile-api-openapi.yml
- filename: amplitude-user-mapping-api-openapi.yml
  format: yaml
  label: Amplitude User Mapping API
  slug: user-mapping-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-user-mapping-api-openapi.yml
- filename: amplitude-scim-api-openapi.yml
  format: yaml
  label: Amplitude SCIM API
  slug: scim-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-scim-api-openapi.yml
- filename: amplitude-dsar-api-openapi.yml
  format: yaml
  label: Amplitude Data Subject Access Request API
  slug: dsar-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-dsar-api-openapi.yml
- filename: amplitude-experiment-evaluation-api-openapi.yml
  format: yaml
  label: Amplitude Experiment Evaluation API
  slug: experiment-evaluation-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-experiment-evaluation-api-openapi.yml
- filename: amplitude-experiment-management-api-openapi.yml
  format: yaml
  label: Amplitude Experiment Management API
  slug: experiment-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-experiment-management-api-openapi.yml
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
