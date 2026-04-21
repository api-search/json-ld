---
class_count: 6
classes:
- eventsource.CreateEventSourceRequest
- eventsource.EventSourceWatchEvent
- eventsource.LogEntry
- eventsource.UpdateEventSourceRequest
- eventsource.EventSourceDeletedResponse
- name
context_file: json-ld/argo-workflows-eventsource-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/argo-workflows/refs/heads/main/json-ld/argo-workflows-eventsource-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Argo Workflows Eventsource from Argo Workflows.
layout: jsonld
name: Argo Workflows Eventsource Context
namespaces:
- prefix: argo
  uri: https://argoproj.github.io/schema/argo-workflows/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: eventSource
  type: string
- container: ''
  name: namespace
  type: string
- container: ''
  name: object
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: eventName
  type: string
- container: ''
  name: eventSourceName
  type: string
- container: ''
  name: eventSourceType
  type: string
- container: ''
  name: level
  type: string
- container: ''
  name: msg
  type: string
- container: ''
  name: time
  type: string
property_count: 10
provider_name: Argo Workflows
provider_slug: argo-workflows
slug: argo-workflows-eventsource-context
tags:
- CNCF
- Containers
- Data Processing
- Kubernetes
- Machine Learning
- Open Source
- Workflow Engine
- JSON-LD
- Linked Data
- Semantic Web
---
