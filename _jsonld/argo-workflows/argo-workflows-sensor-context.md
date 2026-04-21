---
class_count: 6
classes:
- sensor.DeleteSensorResponse
- sensor.UpdateSensorRequest
- sensor.LogEntry
- sensor.SensorWatchEvent
- sensor.CreateSensorRequest
- name
context_file: json-ld/argo-workflows-sensor-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/argo-workflows/refs/heads/main/json-ld/argo-workflows-sensor-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Argo Workflows Sensor from Argo Workflows.
layout: jsonld
name: Argo Workflows Sensor Context
namespaces:
- prefix: argo
  uri: https://argoproj.github.io/schema/argo-workflows/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: namespace
  type: string
- container: ''
  name: sensor
  type: string
- container: ''
  name: dependencyName
  type: string
- container: ''
  name: eventContext
  type: string
- container: ''
  name: level
  type: string
- container: ''
  name: msg
  type: string
- container: ''
  name: sensorName
  type: string
- container: ''
  name: time
  type: string
- container: ''
  name: triggerName
  type: string
- container: ''
  name: object
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: createOptions
  type: string
property_count: 12
provider_name: Argo Workflows
provider_slug: argo-workflows
slug: argo-workflows-sensor-context
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
