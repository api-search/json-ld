---
api_specs:
- filename: stackrox-openapi.yml
  format: yaml
  label: StackRox API
  slug: stackrox-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stackrox/refs/heads/main/openapi/stackrox-openapi.yml
class_count: 7
classes:
- severity
- state
- lifecycleStage
- namespace
- clusterId
- name
- description
context_file: json-ld/stackrox-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/stackrox/refs/heads/main/json-ld/stackrox-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Stackrox from StackRox.
layout: jsonld
name: Stackrox Context
namespaces:
- prefix: stackrox
  uri: https://stackrox.io/schema/
properties:
- container: ''
  name: Alert
  type: reference
- container: ''
  name: Policy
  type: reference
- container: ''
  name: Deployment
  type: reference
- container: ''
  name: Cluster
  type: reference
- container: ''
  name: Image
  type: reference
property_count: 5
provider_name: StackRox
provider_slug: stackrox
slug: stackrox-context
source_filename: stackrox-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"stackrox\": \"https://stackrox.io/schema/\",\n    \"Alert\": {\n      \"@id\": \"stackrox:SecurityAlert\",\n      \"@type\": \"@id\"\n    },\n    \"Policy\": {\n      \"@id\": \"stackrox:SecurityPolicy\",\n      \"@type\": \"@id\"\n    },\n    \"Deployment\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"@type\": \"@id\"\n    },\n    \"Cluster\": {\n      \"@id\": \"stackrox:KubernetesCluster\",\n      \"@type\": \"@id\"\n    },\n    \"Image\": {\n      \"@id\": \"stackrox:ContainerImage\",\n      \"@type\": \"@id\"\n    },\n    \"severity\": \"stackrox:severity\",\n    \"state\": \"stackrox:alertState\",\n    \"lifecycleStage\": \"stackrox:lifecycleStage\",\n    \"namespace\": \"stackrox:kubernetesNamespace\",\n    \"clusterId\": \"stackrox:clusterIdentifier\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/stackrox/refs/heads/main/json-ld/stackrox-context.jsonld
tags:
- Compliance
- Container Security
- Kubernetes
- Open Source
- Runtime Protection
- Security
- JSON-LD
- Linked Data
- Semantic Web
---
