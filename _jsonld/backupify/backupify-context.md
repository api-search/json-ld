---
class_count: 8
classes:
- BulkSeatChangeRequest
- BulkSeatChangeResponse
- Domain
- DomainsResponse
- Seat
- SeatChange
- SeatChangeResult
- SeatsResponse
context_file: json-ld/backupify-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/backupify/refs/heads/main/json-ld/backupify-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Backupify from Backupify.
layout: jsonld
name: Backupify Context
namespaces:
- prefix: bkp
  uri: https://api.datto.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: action
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: domain
  type: string
- container: set
  name: domains
  type: string
- container: ''
  name: email
  type: ''
- container: ''
  name: externalSubscriptionId
  type: string
- container: ''
  name: lastBackup
  type: dateTime
- container: ''
  name: licenseStatus
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: remoteId
  type: string
- container: set
  name: results
  type: string
- container: ''
  name: saasCustomerId
  type: string
- container: ''
  name: seatType
  type: string
- container: set
  name: seats
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: success
  type: boolean
property_count: 16
provider_name: Backupify
provider_slug: backupify
slug: backupify-context
tags:
- SaaS Backup
- Data Protection
- Cloud Backup
- Microsoft 365
- Google Workspace
- JSON-LD
- Linked Data
- Semantic Web
---
