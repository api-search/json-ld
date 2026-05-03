---
class_count: 7
classes:
- name
- description
- url
- version
- dateCreated
- dateModified
- SoftwareApplication
context_file: json-ld/speedscale-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/speedscale/refs/heads/main/json-ld/speedscale-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Speedscale from Speedscale.
layout: jsonld
name: Speedscale Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: speedscale
  uri: https://speedscale.com/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: TrafficSnapshot
  type: reference
- container: ''
  name: TrafficReplay
  type: reference
- container: ''
  name: TestReport
  type: reference
- container: ''
  name: ServiceMock
  type: reference
- container: ''
  name: requestCount
  type: integer
- container: ''
  name: durationMs
  type: integer
- container: ''
  name: piiSanitized
  type: boolean
- container: ''
  name: environment
  type: '@vocab'
- container: ''
  name: capturedAt
  type: dateTime
- container: ''
  name: errorRate
  type: decimal
- container: ''
  name: latencyP99Ms
  type: integer
property_count: 11
provider_name: Speedscale
provider_slug: speedscale
slug: speedscale-context
source_filename: speedscale-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"speedscale\": \"https://speedscale.com/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"TrafficSnapshot\": {\n      \"@id\": \"speedscale:TrafficSnapshot\",\n      \"@type\": \"@id\",\n      \"schema:description\": \"A saved collection of captured API traffic for replay.\"\n    },\n    \"TrafficReplay\": {\n      \"@id\": \"speedscale:TrafficReplay\",\n      \"@type\": \"@id\",\n      \"schema:description\": \"A replay run of a captured traffic snapshot against a target service.\"\n    },\n    \"TestReport\": {\n      \"@id\": \"speedscale:TestReport\",\n      \"@type\": \"@id\",\n      \"schema:description\": \"Results of a Speedscale traffic replay test run.\"\n    },\n    \"ServiceMock\": {\n      \"@id\": \"speedscale:ServiceMock\",\n      \"@type\": \"@id\",\n      \"schema:description\": \"A simulated backend service created from captured traffic responses.\"\
  \n    },\n\n    \"requestCount\": {\n      \"@id\": \"speedscale:requestCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"durationMs\": {\n      \"@id\": \"speedscale:durationMs\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"piiSanitized\": {\n      \"@id\": \"speedscale:piiSanitized\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"environment\": {\n      \"@id\": \"speedscale:environment\",\n      \"@type\": \"@vocab\"\n    },\n    \"capturedAt\": {\n      \"@id\": \"speedscale:capturedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"errorRate\": {\n      \"@id\": \"speedscale:errorRate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"latencyP99Ms\": {\n      \"@id\": \"speedscale:latencyP99Ms\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"version\": \"schema:version\",\n    \"dateCreated\": \"schema:dateCreated\",\n    \"dateModified\": \"schema:dateModified\"\
  ,\n    \"SoftwareApplication\": \"schema:SoftwareApplication\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/speedscale/refs/heads/main/json-ld/speedscale-context.jsonld
tags:
- API Mocking
- API Testing
- Kubernetes
- Load Testing
- Performance Testing
- Regression Testing
- Service Virtualization
- Traffic Replay
- JSON-LD
- Linked Data
- Semantic Web
---
