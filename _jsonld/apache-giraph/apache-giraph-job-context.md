---
api_specs:
- filename: apache-giraph-job-openapi.yml
  format: yaml
  label: Apache Giraph Job Monitoring API
  slug: apache-giraph-job-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-giraph/refs/heads/main/openapi/apache-giraph-job-openapi.yml
class_count: 5
classes:
- ApplicationsResponse
- ApplicationResponse
- ApplicationInfo
- name
- ClusterMetricsResponse
context_file: json-ld/apache-giraph-job-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-giraph/refs/heads/main/json-ld/apache-giraph-job-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Giraph Job from Apache Giraph.
layout: jsonld
name: Apache Giraph Job Context
namespaces:
- prefix: giraph
  uri: https://giraph.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: apps
  type: reference
- container: ''
  name: app
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: applicationType
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: finalStatus
  type: string
- container: ''
  name: progress
  type: integer
- container: ''
  name: trackingUrl
  type: string
- container: ''
  name: queue
  type: string
- container: ''
  name: startedTime
  type: integer
- container: ''
  name: finishedTime
  type: integer
- container: ''
  name: elapsedTime
  type: integer
- container: ''
  name: numContainers
  type: integer
- container: ''
  name: clusterMetrics
  type: reference
property_count: 14
provider_name: Apache Giraph
provider_slug: apache-giraph
slug: apache-giraph-job-context
source_filename: apache-giraph-job-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"giraph\": \"https://giraph.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ApplicationsResponse\": \"giraph:ApplicationsResponse\",\n    \"apps\": {\n      \"@id\": \"giraph:apps\",\n      \"@type\": \"@id\"\n    },\n    \"ApplicationResponse\": \"giraph:ApplicationResponse\",\n    \"app\": {\n      \"@id\": \"giraph:app\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ApplicationInfo\": \"giraph:ApplicationInfo\",\n    \"id\": {\n      \"@id\": \"giraph:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"applicationType\": {\n      \"@id\": \"giraph:applicationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"giraph:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"finalStatus\": {\n      \"@id\": \"giraph:finalStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"progress\"\
  : {\n      \"@id\": \"giraph:progress\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"trackingUrl\": {\n      \"@id\": \"giraph:trackingUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queue\": {\n      \"@id\": \"giraph:queue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startedTime\": {\n      \"@id\": \"giraph:startedTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"finishedTime\": {\n      \"@id\": \"giraph:finishedTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"elapsedTime\": {\n      \"@id\": \"giraph:elapsedTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"numContainers\": {\n      \"@id\": \"giraph:numContainers\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ClusterMetricsResponse\": \"giraph:ClusterMetricsResponse\",\n    \"clusterMetrics\": {\n      \"@id\": \"giraph:clusterMetrics\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-giraph/refs/heads/main/json-ld/apache-giraph-job-context.jsonld
tags:
- Apache
- Big Data
- BSP
- Graph Processing
- Hadoop
- Open Source
- Retired
- JSON-LD
- Linked Data
- Semantic Web
---
