---
api_specs:
- filename: gke-openapi.yml
  format: yaml
  label: Google Kubernetes Engine API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-kubernetes-engine/refs/heads/main/openapi/gke-openapi.yml
class_count: 11
classes:
- Cluster
- NodePool
- Operation
- name
- description
- status
- location
- endpoint
- network
- subnetwork
- machineType
context_file: json-ld/gke-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-kubernetes-engine/refs/heads/main/json-ld/gke-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Gke from Google Cloud Kubernetes Engine.
layout: jsonld
name: Gke Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: gcp
  uri: https://cloud.google.com/schema#
properties:
- container: ''
  name: createTime
  type: dateTime
- container: ''
  name: initialNodeCount
  type: integer
- container: ''
  name: diskSizeGb
  type: integer
property_count: 3
provider_name: Google Cloud Kubernetes Engine
provider_slug: google-cloud-kubernetes-engine
slug: gke-context
source_filename: gke-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://cloud.google.com/kubernetes-engine/schema#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"gcp\": \"https://cloud.google.com/schema#\",\n    \"Cluster\": \"gcp:GKECluster\",\n    \"NodePool\": \"gcp:GKENodePool\",\n    \"Operation\": \"gcp:GKEOperation\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"status\": \"gcp:status\",\n    \"location\": \"gcp:location\",\n    \"endpoint\": \"schema:url\",\n    \"network\": \"gcp:network\",\n    \"subnetwork\": \"gcp:subnetwork\",\n    \"machineType\": \"gcp:machineType\",\n    \"createTime\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"initialNodeCount\": {\n      \"@id\": \"gcp:initialNodeCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"diskSizeGb\": {\n      \"@id\": \"gcp:diskSizeGb\",\n\
  \      \"@type\": \"xsd:integer\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-kubernetes-engine/refs/heads/main/json-ld/gke-context.jsonld
tags:
- Compute
- Containers
- GKE
- Google Cloud
- Kubernetes
- Orchestration
- JSON-LD
- Linked Data
- Semantic Web
---
