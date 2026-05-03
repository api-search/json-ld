---
api_specs:
- filename: rancher-management-api-openapi.yml
  format: yaml
  label: Rancher Management API
  slug: rancher-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rancher/refs/heads/main/openapi/rancher-management-api-openapi.yml
class_count: 17
classes:
- Cluster
- Project
- Node
- User
- Token
- Catalog
- App
- RoleTemplate
- id
- type
- name
- description
- kubernetesVersion
- provider
- state
- hostname
- roles
context_file: json-ld/rancher-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/rancher/refs/heads/main/json-ld/rancher-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Rancher from Rancher.
layout: jsonld
name: Rancher Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: rancher
  uri: https://rancher.com/ns#
- prefix: k8s
  uri: https://kubernetes.io/docs/reference/#
properties:
- container: ''
  name: clusterId
  type: reference
property_count: 1
provider_name: Rancher
provider_slug: rancher
slug: rancher-context
source_filename: rancher-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"rancher\": \"https://rancher.com/ns#\",\n    \"k8s\": \"https://kubernetes.io/docs/reference/#\",\n    \"Cluster\": \"rancher:Cluster\",\n    \"Project\": \"rancher:Project\",\n    \"Node\": \"rancher:Node\",\n    \"User\": \"rancher:User\",\n    \"Token\": \"rancher:Token\",\n    \"Catalog\": \"rancher:Catalog\",\n    \"App\": \"rancher:App\",\n    \"RoleTemplate\": \"rancher:RoleTemplate\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"clusterId\": { \"@id\": \"rancher:cluster\", \"@type\": \"@id\" },\n    \"kubernetesVersion\": \"rancher:kubernetesVersion\",\n    \"provider\": \"rancher:provider\",\n    \"state\": \"rancher:state\",\n    \"hostname\": \"schema:name\",\n    \"roles\": \"rancher:role\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/rancher/refs/heads/main/json-ld/rancher-context.jsonld
tags:
- Cluster Management
- Containers
- Kubernetes
- Multi-Cluster
- Open Source
- SUSE
- Platform Engineering
- JSON-LD
- Linked Data
- Semantic Web
---
