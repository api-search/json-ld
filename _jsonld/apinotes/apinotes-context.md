---
class_count: 7
classes:
- id
- type
- name
- description
- version
- languages
- liveTestingEnabled
context_file: json-ld/apinotes-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apinotes/refs/heads/main/json-ld/apinotes-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apinotes from ApiNotes.
layout: jsonld
name: Apinotes Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: apinotes
  uri: https://apinotes.io/vocab/
properties:
- container: ''
  name: specificationUrl
  type: reference
- container: ''
  name: portalUrl
  type: reference
- container: ''
  name: createdAt
  type: dateTime
property_count: 3
provider_name: ApiNotes
provider_slug: apinotes
slug: apinotes-context
tags:
- API Reference
- Developer Portal
- Documentation
- Interactive
- OpenAPI
- JSON-LD
- Linked Data
- Semantic Web
---
