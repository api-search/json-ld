---
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
