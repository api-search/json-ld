---
api_specs:
- filename: ariba-sourcing-external-approval-api.yaml
  format: yaml
  label: Ariba Sourcing - External Approval API
  slug: ariba-sourcing-external-approval-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ariba-sourcing/refs/heads/main/openapi/ariba-sourcing-external-approval-api.yaml
class_count: 13
classes:
- ApprovalChangesResponse
- ApprovalChange
- PendingApprovablesResponse
- PendingApprovalTask
- ApprovalTask
- ApprovalRequest
- Approver
- name
- ApprovableDocument
- ApprovalActionRequest
- ApprovalActionResponse
- GroupMembersResponse
- GroupMember
context_file: json-ld/ariba-sourcing-external-approval-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ariba-sourcing/refs/heads/main/json-ld/ariba-sourcing-external-approval-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ariba Sourcing External Approval Api from Ariba Sourcing.
layout: jsonld
name: Ariba Sourcing External Approval Api Context
namespaces:
- prefix: ariba
  uri: https://openapi.ariba.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: changes
  type: string
- container: ''
  name: changeSequenceId
  type: string
- container: ''
  name: taskId
  type: string
- container: ''
  name: documentType
  type: string
- container: ''
  name: documentId
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: fullURL
  type: string
- container: set
  name: tasks
  type: string
- container: ''
  name: assignedTo
  type: string
- container: set
  name: approvalRequests
  type: string
- container: set
  name: approvers
  type: string
- container: ''
  name: userId
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: realm
  type: string
- container: ''
  name: action
  type: string
- container: ''
  name: comment
  type: string
- container: ''
  name: groupId
  type: string
- container: set
  name: members
  type: string
property_count: 20
provider_name: Ariba Sourcing
provider_slug: ariba-sourcing
slug: ariba-sourcing-external-approval-api-context
source_filename: ariba-sourcing-external-approval-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ariba\": \"https://openapi.ariba.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ApprovalChangesResponse\": \"ariba:ApprovalChangesResponse\",\n    \"changes\": {\n      \"@id\": \"ariba:changes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ApprovalChange\": \"ariba:ApprovalChange\",\n    \"changeSequenceId\": {\n      \"@id\": \"ariba:changeSequenceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskId\": {\n      \"@id\": \"ariba:taskId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"documentType\": {\n      \"@id\": \"ariba:documentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"documentId\": {\n      \"@id\": \"ariba:documentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"ariba:status\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"fullURL\": {\n      \"@id\": \"ariba:fullURL\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PendingApprovablesResponse\": \"ariba:PendingApprovablesResponse\",\n    \"tasks\": {\n      \"@id\": \"ariba:tasks\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PendingApprovalTask\": \"ariba:PendingApprovalTask\",\n    \"assignedTo\": {\n      \"@id\": \"ariba:assignedTo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ApprovalTask\": \"ariba:ApprovalTask\",\n    \"approvalRequests\": {\n      \"@id\": \"ariba:approvalRequests\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ApprovalRequest\": \"ariba:ApprovalRequest\",\n    \"approvers\": {\n      \"@id\": \"ariba:approvers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Approver\": \"ariba:Approver\",\n    \"userId\": {\n      \"@id\": \"ariba:userId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\"\
  ,\n    \"ApprovableDocument\": \"ariba:ApprovableDocument\",\n    \"id\": {\n      \"@id\": \"ariba:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"ariba:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"ariba:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"realm\": {\n      \"@id\": \"ariba:realm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ApprovalActionRequest\": \"ariba:ApprovalActionRequest\",\n    \"action\": {\n      \"@id\": \"ariba:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"comment\": {\n      \"@id\": \"ariba:comment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ApprovalActionResponse\": \"ariba:ApprovalActionResponse\",\n    \"GroupMembersResponse\": \"ariba:GroupMembersResponse\",\n    \"groupId\": {\n      \"@id\": \"ariba:groupId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"members\": {\n      \"@id\": \"ariba:members\",\n      \"@container\": \"@set\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"GroupMember\": \"ariba:GroupMember\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ariba-sourcing/refs/heads/main/json-ld/ariba-sourcing-external-approval-api-context.jsonld
tags:
- Approvals
- Auctions
- B2B
- Contracts
- Procurement
- RFx
- SAP
- Sourcing
- Supplier Management
- Supply Chain
- JSON-LD
- Linked Data
- Semantic Web
---
