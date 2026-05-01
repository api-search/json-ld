---
api_specs:
- filename: gke-on-prem-api-openapi.yml
  format: yaml
  label: GKE On-Prem API
  slug: gke-on-prem-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-anthos/refs/heads/main/openapi/gke-on-prem-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/google-anthos-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-anthos/refs/heads/main/json-ld/google-anthos-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Anthos from Google Anthos.
layout: jsonld
name: Google Anthos Context
namespaces:
- prefix: anthos
  uri: https://cloud.google.com/anthos/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: VmwareCluster
  type: ''
- container: ''
  name: BareMetalCluster
  type: ''
- container: ''
  name: NodePool
  type: ''
property_count: 3
provider_name: Google Anthos
provider_slug: google-anthos
slug: google-anthos-context
source_filename: google-anthos-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"anthos\": \"https://cloud.google.com/anthos/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"VmwareCluster\": {\n      \"@id\": \"anthos:VmwareCluster\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"onPremVersion\": \"anthos:onPremVersion\",\n        \"adminClusterMembership\": {\n          \"@id\": \"anthos:adminClusterMembership\",\n          \"@type\": \"@id\"\n        },\n        \"state\": \"anthos:clusterState\",\n        \"endpoint\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\
  \n        }\n      }\n    },\n\n    \"BareMetalCluster\": {\n      \"@id\": \"anthos:BareMetalCluster\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"bareMetalVersion\": \"anthos:bareMetalVersion\",\n        \"adminClusterMembership\": {\n          \"@id\": \"anthos:adminClusterMembership\",\n          \"@type\": \"@id\"\n        },\n        \"state\": \"anthos:clusterState\",\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"NodePool\": {\n      \"@id\": \"anthos:NodePool\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"displayName\": \"schema:alternateName\",\n        \"cpus\": \"anthos:cpus\",\n        \"memoryMb\": \"anthos:memoryMb\",\n        \"replicas\": \"anthos:replicas\"\
  ,\n        \"imageType\": \"anthos:imageType\",\n        \"state\": \"anthos:nodePoolState\",\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-anthos/refs/heads/main/json-ld/google-anthos-context.jsonld
tags:
- Container Platform
- Hybrid Cloud
- Kubernetes
- Multi-Cloud
- On-Premises
- Service Mesh
- JSON-LD
- Linked Data
- Semantic Web
---
