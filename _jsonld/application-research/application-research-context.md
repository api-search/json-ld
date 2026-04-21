---
class_count: 9
classes:
- WorkloadSpec
- ServiceDependency
- ComponentModel
- ResourceDiscovery
- ApplicationBundle
- name
- description
- version
- url
context_file: json-ld/application-research-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/application-research/refs/heads/main/json-ld/application-research-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Application Research from Application Research.
layout: jsonld
name: Application Research Context
namespaces:
- prefix: appdeps
  uri: https://application-research.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: apiVersion
  type: string
- container: ''
  name: kind
  type: string
- container: ''
  name: metadata
  type: reference
- container: ''
  name: spec
  type: reference
- container: set
  name: services
  type: ''
- container: set
  name: dependencies
  type: ''
- container: set
  name: containers
  type: ''
- container: set
  name: resources
  type: ''
- container: ''
  name: namespace
  type: string
- container: ''
  name: platform
  type: string
- container: ''
  name: image
  type: string
- container: ''
  name: port
  type: integer
- container: ''
  name: replicas
  type: integer
- container: set
  name: environment
  type: ''
- container: ''
  name: labels
  type: reference
- container: ''
  name: annotations
  type: reference
property_count: 16
provider_name: Application Research
provider_slug: application-research
slug: application-research-context
tags:
- Application Dependencies
- Cloud Native
- Integration
- Research
- Specifications
- Workload Specifications
- JSON-LD
- Linked Data
- Semantic Web
---
