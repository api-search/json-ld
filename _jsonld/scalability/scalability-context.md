---
api_specs:
- filename: openapi.yaml
  format: yaml
  label: KEDA (Kubernetes Event-Driven Autoscaling) API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/kedacore/keda/main/apis/keda/v1alpha1/
- filename: openapi.yaml
  format: yaml
  label: AWS Auto Scaling API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/APIs-guru/openapi-directory/main/APIs/amazonaws.com/autoscaling/2011-01-01/openapi.yaml
- filename: openapi.yaml
  format: yaml
  label: Google Cloud Compute Engine Autoscaler API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/APIs-guru/openapi-directory/main/APIs/googleapis.com/compute/v1/openapi.yaml
- filename: autoScale_API.json
  format: json
  label: Azure Autoscale REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2022-10-01/autoScale_API.json
- filename: openapi.yaml
  format: yaml
  label: CloudWatch Application Signals API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/APIs-guru/openapi-directory/main/APIs/amazonaws.com/monitoring/2010-08-01/openapi.yaml
- filename: api.go
  format: yaml
  label: Prometheus HTTP API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/prometheus/prometheus/main/web/api/v1/api.go
class_count: 21
classes:
- name
- description
- namespace
- targetRef
- minReplicaCount
- maxReplicaCount
- pollingInterval
- cooldownPeriod
- threshold
- algorithm
- protocol
- healthCheck
- weight
- status
- address
- port
- tags
- scaleToZero
- horizontalScaling
- verticalScaling
- eventDriven
context_file: json-ld/scalability-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/scalability/refs/heads/main/json-ld/scalability-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Scalability from Scalability.
layout: jsonld
name: Scalability Context
namespaces:
- prefix: xapi
  uri: https://raw.githubusercontent.com/api-evangelist/scalability/main/json-ld/scalability-context.jsonld#
- prefix: keda
  uri: https://keda.sh/ns/
- prefix: k8s
  uri: https://kubernetes.io/ns/
properties:
- container: ''
  name: ScalingPolicy
  type: reference
- container: ''
  name: LoadBalancer
  type: reference
- container: ''
  name: ScalingTrigger
  type: reference
- container: ''
  name: Backend
  type: reference
- container: ''
  name: HealthCheck
  type: reference
- container: list
  name: triggers
  type: ''
- container: list
  name: backends
  type: ''
property_count: 7
provider_name: Scalability
provider_slug: scalability
slug: scalability-context
source_filename: scalability-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.org/\",\n    \"xapi\": \"https://raw.githubusercontent.com/api-evangelist/scalability/main/json-ld/scalability-context.jsonld#\",\n    \"keda\": \"https://keda.sh/ns/\",\n    \"k8s\": \"https://kubernetes.io/ns/\",\n\n    \"ScalingPolicy\": {\n      \"@id\": \"xapi:ScalingPolicy\",\n      \"@type\": \"@id\",\n      \"comment\": \"A policy that governs automatic scaling of compute resources based on demand signals.\"\n    },\n    \"LoadBalancer\": {\n      \"@id\": \"xapi:LoadBalancer\",\n      \"@type\": \"@id\",\n      \"comment\": \"A component that distributes incoming network traffic across multiple backend servers.\"\n    },\n    \"ScalingTrigger\": {\n      \"@id\": \"xapi:ScalingTrigger\",\n      \"@type\": \"@id\",\n      \"comment\": \"A metric or event source that drives autoscaling decisions.\"\n    },\n    \"Backend\": {\n      \"@id\": \"xapi:Backend\",\n      \"@type\": \"@id\",\n \
  \     \"comment\": \"A backend server in a load balancer pool.\"\n    },\n    \"HealthCheck\": {\n      \"@id\": \"xapi:HealthCheck\",\n      \"@type\": \"@id\",\n      \"comment\": \"Configuration for probing backend availability.\"\n    },\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"namespace\": \"xapi:namespace\",\n    \"targetRef\": \"xapi:targetRef\",\n    \"minReplicaCount\": \"xapi:minReplicaCount\",\n    \"maxReplicaCount\": \"xapi:maxReplicaCount\",\n    \"pollingInterval\": \"xapi:pollingInterval\",\n    \"cooldownPeriod\": \"xapi:cooldownPeriod\",\n    \"triggers\": {\n      \"@id\": \"xapi:triggers\",\n      \"@container\": \"@list\"\n    },\n    \"threshold\": \"xapi:threshold\",\n    \"algorithm\": \"xapi:algorithm\",\n    \"protocol\": \"schema:protocol\",\n    \"backends\": {\n      \"@id\": \"xapi:backends\",\n      \"@container\": \"@list\"\n    },\n    \"healthCheck\": \"xapi:healthCheck\",\n    \"weight\": \"xapi:weight\",\n\
  \    \"status\": \"schema:status\",\n    \"address\": \"schema:address\",\n    \"port\": \"xapi:port\",\n    \"tags\": \"schema:keywords\",\n    \"scaleToZero\": \"xapi:scaleToZero\",\n    \"horizontalScaling\": \"xapi:horizontalScaling\",\n    \"verticalScaling\": \"xapi:verticalScaling\",\n    \"eventDriven\": \"xapi:eventDriven\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/scalability/refs/heads/main/json-ld/scalability-context.jsonld
tags:
- Auto Scaling
- Cloud Computing
- DevOps
- Distributed Systems
- Elasticity
- High Availability
- Infrastructure
- Load Balancing
- Performance
- Scalability
- JSON-LD
- Linked Data
- Semantic Web
---
