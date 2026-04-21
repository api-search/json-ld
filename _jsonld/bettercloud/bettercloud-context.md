---
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
