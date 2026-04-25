---
class_count: 6
classes:
- name
- description
- uid
- namespace
- duration
- status
context_file: json-ld/chaos-mesh-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/chaos-mesh/refs/heads/main/json-ld/chaos-mesh-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Chaos Mesh from Chaos Mesh.
layout: jsonld
name: Chaos Mesh Context
namespaces:
- prefix: chaos
  uri: https://chaos-mesh.org/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: k8s
  uri: https://kubernetes.io/docs/concepts/
- prefix: cncf
  uri: https://www.cncf.io/projects/
properties:
- container: ''
  name: ChaosExperiment
  type: ''
- container: ''
  name: PodChaos
  type: ''
- container: ''
  name: NetworkChaos
  type: ''
- container: ''
  name: IOChaos
  type: ''
- container: ''
  name: StressChaos
  type: ''
- container: ''
  name: HTTPChaos
  type: ''
- container: ''
  name: TimeChaos
  type: ''
- container: ''
  name: Schedule
  type: ''
- container: ''
  name: Workflow
  type: ''
- container: ''
  name: PodSelector
  type: ''
- container: ''
  name: Event
  type: ''
- container: ''
  name: created_at
  type: dateTime
property_count: 12
provider_name: Chaos Mesh
provider_slug: chaos-mesh
slug: chaos-mesh-context
tags:
- Chaos Engineering
- Cloud Native
- CNCF
- Fault Injection
- Kubernetes
- Observability
- Open Source
- Reliability
- Resilience
- Testing
- JSON-LD
- Linked Data
- Semantic Web
---
