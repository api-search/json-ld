---
class_count: 2
classes:
- name
- description
context_file: json-ld/appmixer-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/appmixer/refs/heads/main/json-ld/appmixer-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Appmixer from Appmixer.
layout: jsonld
name: Appmixer Context
namespaces:
- prefix: appmixer
  uri: https://api.appmixer.com/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: flowId
  type: string
- container: ''
  name: stage
  type: string
- container: ''
  name: btime
  type: dateTime
- container: ''
  name: mtime
  type: dateTime
- container: ''
  name: customFields
  type: '@json'
- container: ''
  name: accountId
  type: string
- container: ''
  name: service
  type: string
- container: ''
  name: profileInfo
  type: '@json'
- container: ''
  name: valid
  type: boolean
- container: ''
  name: fileId
  type: string
- container: ''
  name: filename
  type: string
- container: ''
  name: contentType
  type: string
- container: ''
  name: storeId
  type: string
- container: ''
  name: componentId
  type: string
- container: ''
  name: messageId
  type: string
- container: ''
  name: role
  type: string
- container: ''
  name: plan
  type: string
- container: ''
  name: token
  type: string
property_count: 18
provider_name: Appmixer
provider_slug: appmixer
slug: appmixer-context
tags:
- Agentic
- Automation
- Embedded iPaaS
- Integrations
- Low-Code
- Workflows
- JSON-LD
- Linked Data
- Semantic Web
---
