---
class_count: 10
classes:
- id
- type
- name
- description
- status
- configuration
- policies
- endpoints
- totalRequests
- averageLatency
context_file: json-ld/apinizer-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apinizer/refs/heads/main/json-ld/apinizer-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apinizer from Apinizer.
layout: jsonld
name: Apinizer Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: apinizer
  uri: https://apinizer.com/vocab/
properties:
- container: ''
  name: baseUrl
  type: reference
- container: ''
  name: createdAt
  type: dateTime
property_count: 2
provider_name: Apinizer
provider_slug: apinizer
slug: apinizer-context
tags:
- API Gateway
- API Management
- API Monitoring
- API Security
- Policies
- JSON-LD
- Linked Data
- Semantic Web
---
