---
class_count: 2
classes:
- name
- description
context_file: json-ld/apidog-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apidog/refs/heads/main/json-ld/apidog-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apidog from Apidog.
layout: jsonld
name: Apidog Context
namespaces:
- prefix: apidog
  uri: https://api.apidog.com/v1/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: projectId
  type: integer
- container: ''
  name: endpointCount
  type: integer
- container: ''
  name: schemaCount
  type: integer
- container: ''
  name: environmentCount
  type: integer
- container: ''
  name: apiVersion
  type: string
- container: ''
  name: success
  type: boolean
- container: ''
  name: errorCode
  type: string
- container: ''
  name: errorMessage
  type: string
- container: ''
  name: exportData
  type: string
property_count: 9
provider_name: Apidog
provider_slug: apidog
slug: apidog-context
tags:
- API Design
- API Lifecycle
- API Testing
- Collaboration
- Design-First
- Documentation
- Mocking
- Platform
- JSON-LD
- Linked Data
- Semantic Web
---
