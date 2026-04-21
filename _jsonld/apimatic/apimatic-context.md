---
class_count: 9
classes:
- id
- type
- name
- description
- version
- platform
- errors
- warnings
- valid
context_file: json-ld/apimatic-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apimatic/refs/heads/main/json-ld/apimatic-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apimatic from APIMatic.
layout: jsonld
name: Apimatic Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: apimatic
  uri: https://www.apimatic.io/vocab/
properties:
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: downloadUrl
  type: reference
- container: ''
  name: expiresAt
  type: dateTime
property_count: 4
provider_name: APIMatic
provider_slug: apimatic
slug: apimatic-context
tags:
- API Transformation
- Code Generation
- Developer Experience
- Documentation
- SDK Generation
- JSON-LD
- Linked Data
- Semantic Web
---
