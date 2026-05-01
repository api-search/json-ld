---
api_specs:
- filename: bettercloud-platform-api.yaml
  format: yaml
  label: BetterCloud Platform API
  slug: bettercloud-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bettercloud/refs/heads/main/openapi/bettercloud-platform-api.yaml
class_count: 28
classes:
- EventListResponse
- Event
- GroupCreateRequest
- GroupListResponse
- GroupMemberAddRequest
- GroupMemberListResponse
- GroupMemberResponse
- GroupMember
- GroupResponse
- Group
- IntegrationListResponse
- Integration
- MetaResponse
- UserListResponse
- UserResponse
- User
- UserUpdateRequest
- WorkflowCreateRequest
- WorkflowListResponse
- WorkflowResponse
- WorkflowRunRequest
- WorkflowRunResponse
- Workflow
- description
- name
- email
- createdAt
- updatedAt
context_file: json-ld/bettercloud-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/bettercloud/refs/heads/main/json-ld/bettercloud-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Bettercloud from BetterCloud.
layout: jsonld
name: Bettercloud Context
namespaces:
- prefix: bc
  uri: https://bettercloud.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: data
  type: string
- container: ''
  name: meta
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: actorEmail
  type: string
- container: ''
  name: targetEmail
  type: string
- container: ''
  name: occurredAt
  type: dateTime
- container: ''
  name: userId
  type: string
- container: ''
  name: role
  type: string
- container: ''
  name: memberCount
  type: integer
- container: ''
  name: status
  type: string
- container: ''
  name: connectedAt
  type: dateTime
- container: ''
  name: page
  type: integer
- container: ''
  name: perPage
  type: integer
- container: ''
  name: total
  type: integer
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: department
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: managerEmail
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: triggerType
  type: string
- container: set
  name: userIds
  type: string
- container: ''
  name: actionCount
  type: integer
property_count: 24
provider_name: BetterCloud
provider_slug: bettercloud
slug: bettercloud-context
source_filename: bettercloud-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"bc\": \"https://bettercloud.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"EventListResponse\": \"bc:EventListResponse\",\n    \"Event\": \"bc:Event\",\n    \"GroupCreateRequest\": \"bc:GroupCreateRequest\",\n    \"GroupListResponse\": \"bc:GroupListResponse\",\n    \"GroupMemberAddRequest\": \"bc:GroupMemberAddRequest\",\n    \"GroupMemberListResponse\": \"bc:GroupMemberListResponse\",\n    \"GroupMemberResponse\": \"bc:GroupMemberResponse\",\n    \"GroupMember\": \"bc:GroupMember\",\n    \"GroupResponse\": \"bc:GroupResponse\",\n    \"Group\": \"bc:Group\",\n    \"IntegrationListResponse\": \"bc:IntegrationListResponse\",\n    \"Integration\": \"bc:Integration\",\n    \"MetaResponse\": \"bc:MetaResponse\",\n    \"UserListResponse\": \"bc:UserListResponse\",\n    \"UserResponse\": \"bc:UserResponse\",\n \
  \   \"User\": \"bc:User\",\n    \"UserUpdateRequest\": \"bc:UserUpdateRequest\",\n    \"WorkflowCreateRequest\": \"bc:WorkflowCreateRequest\",\n    \"WorkflowListResponse\": \"bc:WorkflowListResponse\",\n    \"WorkflowResponse\": \"bc:WorkflowResponse\",\n    \"WorkflowRunRequest\": \"bc:WorkflowRunRequest\",\n    \"WorkflowRunResponse\": \"bc:WorkflowRunResponse\",\n    \"Workflow\": \"bc:Workflow\",\n    \"data\": {\n      \"@id\": \"bc:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"meta\": {\n      \"@id\": \"bc:meta\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"bc:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"bc:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actorEmail\": {\n      \"@id\": \"bc:actor_email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetEmail\": {\n      \"@id\": \"bc:target_email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\"\
  : \"schema:description\",\n    \"occurredAt\": {\n      \"@id\": \"bc:occurred_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"name\": \"schema:name\",\n    \"email\": \"schema:email\",\n    \"userId\": {\n      \"@id\": \"bc:user_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"role\": {\n      \"@id\": \"bc:role\",\n      \"@type\": \"xsd:string\"\n    },\n    \"memberCount\": {\n      \"@id\": \"bc:member_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"createdAt\": \"schema:dateCreated\",\n    \"updatedAt\": \"schema:dateModified\",\n    \"status\": {\n      \"@id\": \"bc:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectedAt\": {\n      \"@id\": \"bc:connected_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"page\": {\n      \"@id\": \"bc:page\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"perPage\": {\n      \"@id\": \"bc:per_page\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"total\": {\n      \"@id\": \"bc:total\",\n      \"\
  @type\": \"xsd:integer\"\n    },\n    \"firstName\": {\n      \"@id\": \"bc:first_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"bc:last_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"department\": {\n      \"@id\": \"bc:department\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"bc:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"managerEmail\": {\n      \"@id\": \"bc:manager_email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"bc:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"triggerType\": {\n      \"@id\": \"bc:trigger_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userIds\": {\n      \"@id\": \"bc:user_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actionCount\": {\n      \"@id\": \"bc:action_count\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/bettercloud/refs/heads/main/json-ld/bettercloud-context.jsonld
tags:
- Automation
- Compliance
- Enterprise
- IT Operations
- SaaS Management
- Security
- Workflows
- User Lifecycle
- JSON-LD
- Linked Data
- Semantic Web
---
