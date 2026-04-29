---
api_specs:
- filename: argo-workflows-openapi.json
  format: json
  label: Argo Workflows API
  slug: argo-workflows
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/argo-workflows/refs/heads/main/openapi/argo-workflows-openapi.json
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
source_filename: argo-workflows-eventsource-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"argo\": \"https://argoproj.github.io/schema/argo-workflows/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"eventsource.CreateEventSourceRequest\": \"argo:eventsource.CreateEventSourceRequest\",\n    \"eventsource.EventSourceWatchEvent\": \"argo:eventsource.EventSourceWatchEvent\",\n    \"eventsource.LogEntry\": \"argo:eventsource.LogEntry\",\n    \"eventsource.UpdateEventSourceRequest\": \"argo:eventsource.UpdateEventSourceRequest\",\n    \"eventsource.EventSourceDeletedResponse\": \"argo:eventsource.EventSourceDeletedResponse\",\n    \"eventSource\": {\n      \"@id\": \"argo:eventSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"namespace\": {\n      \"@id\": \"argo:namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"object\": {\n      \"@id\": \"argo:object\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"argo:type\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"eventName\": {\n      \"@id\": \"argo:eventName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventSourceName\": {\n      \"@id\": \"argo:eventSourceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventSourceType\": {\n      \"@id\": \"argo:eventSourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"level\": {\n      \"@id\": \"argo:level\",\n      \"@type\": \"xsd:string\"\n    },\n    \"msg\": {\n      \"@id\": \"argo:msg\",\n      \"@type\": \"xsd:string\"\n    },\n    \"time\": {\n      \"@id\": \"argo:time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/argo-workflows/refs/heads/main/json-ld/argo-workflows-eventsource-context.jsonld
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
