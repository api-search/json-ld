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
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"bkp\": \"https://api.datto.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"BulkSeatChangeRequest\": \"bkp:BulkSeatChangeRequest\",\n    \"BulkSeatChangeResponse\": \"bkp:BulkSeatChangeResponse\",\n    \"Domain\": \"bkp:Domain\",\n    \"DomainsResponse\": \"bkp:DomainsResponse\",\n    \"Seat\": \"bkp:Seat\",\n    \"SeatChange\": \"bkp:SeatChange\",\n    \"SeatChangeResult\": \"bkp:SeatChangeResult\",\n    \"SeatsResponse\": \"bkp:SeatsResponse\",\n    \"action\": {\n      \"@id\": \"bkp:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": {\n      \"@id\": \"bkp:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domain\": {\n      \"@id\": \"bkp:domain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domains\": {\n      \"@id\": \"bkp:domains\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n  \
  \  \"email\": {\n      \"@id\": \"schema:email\"\n    },\n    \"externalSubscriptionId\": {\n      \"@id\": \"bkp:externalSubscriptionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastBackup\": {\n      \"@id\": \"bkp:lastBackup\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"licenseStatus\": {\n      \"@id\": \"bkp:licenseStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"bkp:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"remoteId\": {\n      \"@id\": \"bkp:remoteId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"results\": {\n      \"@id\": \"bkp:results\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"saasCustomerId\": {\n      \"@id\": \"bkp:saasCustomerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"seatType\": {\n      \"@id\": \"bkp:seatType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"seats\": {\n      \"@id\": \"bkp:seats\",\n      \"@container\": \"@set\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"bkp:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"success\": {\n      \"@id\": \"bkp:success\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/backupify/refs/heads/main/json-ld/backupify-context.jsonld
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
