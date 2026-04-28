---
class_count: 4
classes:
- id
- name
- type
- status
context_file: json-ld/cloudally-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cloudally/refs/heads/main/json-ld/cloudally-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cloudally from CloudAlly.
layout: jsonld
name: Cloudally Context
namespaces:
- prefix: cloudally
  uri: https://api.cloudally.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: BackupTask
  type: schema:Action
- container: ''
  name: RestoreJob
  type: schema:Action
- container: ''
  name: Partner
  type: schema:Organization
- container: ''
  name: Reseller
  type: schema:Organization
- container: ''
  name: User
  type: schema:Person
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: lastBackup
  type: dateTime
- container: ''
  name: size
  type: integer
property_count: 8
provider_name: CloudAlly
provider_slug: cloudally
slug: cloudally-context
tags:
- Backup
- Box
- Data Protection
- Disaster Recovery
- Dropbox
- Google Workspace
- Microsoft 365
- OpenText
- SaaS Backup
- Salesforce
- JSON-LD
- Linked Data
- Semantic Web
---
