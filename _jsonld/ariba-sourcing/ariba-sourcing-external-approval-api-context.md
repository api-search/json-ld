---
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
