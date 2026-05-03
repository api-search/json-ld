---
api_specs:
- filename: vmware-tanzu-service-mesh-openapi.yml
  format: yaml
  label: VMware Tanzu Service Mesh API
  slug: tanzu-service-mesh-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vmware-tanzu/refs/heads/main/openapi/vmware-tanzu-service-mesh-openapi.yml
- filename: vmware-tanzu-kubernetes-grid-openapi.yml
  format: yaml
  label: VMware Tanzu Kubernetes Grid API
  slug: tanzu-kubernetes-grid-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vmware-tanzu/refs/heads/main/openapi/vmware-tanzu-kubernetes-grid-openapi.yml
class_count: 8
classes:
- TanzuCluster
- GlobalNamespace
- ResourceGroup
- TanzuKubernetesCluster
- ClusterConfig
- NodePool
- SoftwareApplication
- Organization
context_file: json-ld/vmware-tanzu-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/vmware-tanzu/refs/heads/main/json-ld/vmware-tanzu-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Vmware Tanzu from VMware Tanzu.
layout: jsonld
name: Vmware Tanzu Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: tanzu
  uri: https://tanzu.vmware.com/vocabulary#
- prefix: k8s
  uri: https://kubernetes.io/vocabulary#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: name
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: display_name
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: cloud_provider
  type: string
- container: ''
  name: region
  type: string
- container: ''
  name: k8s_version
  type: string
- container: ''
  name: tsm_version
  type: string
- container: ''
  name: namespace_count
  type: integer
- container: ''
  name: domain_name
  type: string
- container: ''
  name: mtls_enforced
  type: boolean
- container: ''
  name: ca_type
  type: string
- container: ''
  name: status
  type: string
- container: list
  name: cluster_configs
  type: ''
- container: ''
  name: cluster_name
  type: string
- container: list
  name: namespaces
  type: ''
- container: ''
  name: resource_type
  type: string
- container: list
  name: membership_criteria
  type: ''
- container: ''
  name: apiVersion
  type: string
- container: ''
  name: kind
  type: string
- container: ''
  name: spec
  type: ''
- container: ''
  name: metadata
  type: ''
- container: ''
  name: phase
  type: string
- container: list
  name: conditions
  type: ''
- container: ''
  name: apiEndpoint
  type: reference
property_count: 25
provider_name: VMware Tanzu
provider_slug: vmware-tanzu
slug: vmware-tanzu-context
source_filename: vmware-tanzu-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"tanzu\": \"https://tanzu.vmware.com/vocabulary#\",\n    \"k8s\": \"https://kubernetes.io/vocabulary#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"TanzuCluster\": \"tanzu:Cluster\",\n    \"GlobalNamespace\": \"tanzu:GlobalNamespace\",\n    \"ResourceGroup\": \"tanzu:ResourceGroup\",\n    \"TanzuKubernetesCluster\": \"tanzu:TanzuKubernetesCluster\",\n    \"ClusterConfig\": \"tanzu:ClusterConfig\",\n    \"NodePool\": \"tanzu:NodePool\",\n\n    \"name\": {\"@id\": \"schema:name\"},\n    \"description\": {\"@id\": \"schema:description\"},\n    \"display_name\": {\"@id\": \"tanzu:displayName\", \"@type\": \"xsd:string\"},\n    \"state\": {\"@id\": \"tanzu:state\", \"@type\": \"xsd:string\"},\n    \"cloud_provider\": {\"@id\": \"tanzu:cloudProvider\", \"@type\": \"xsd:string\"},\n    \"region\": {\"@id\": \"tanzu:region\", \"@type\": \"xsd:string\"},\n    \"k8s_version\"\
  : {\"@id\": \"tanzu:kubernetesVersion\", \"@type\": \"xsd:string\"},\n    \"tsm_version\": {\"@id\": \"tanzu:tsmVersion\", \"@type\": \"xsd:string\"},\n    \"namespace_count\": {\"@id\": \"tanzu:namespaceCount\", \"@type\": \"xsd:integer\"},\n\n    \"domain_name\": {\"@id\": \"tanzu:domainName\", \"@type\": \"xsd:string\"},\n    \"mtls_enforced\": {\"@id\": \"tanzu:mtlsEnforced\", \"@type\": \"xsd:boolean\"},\n    \"ca_type\": {\"@id\": \"tanzu:caType\", \"@type\": \"xsd:string\"},\n    \"status\": {\"@id\": \"tanzu:status\", \"@type\": \"xsd:string\"},\n    \"cluster_configs\": {\"@id\": \"tanzu:clusterConfigs\", \"@container\": \"@list\"},\n    \"cluster_name\": {\"@id\": \"tanzu:clusterName\", \"@type\": \"xsd:string\"},\n    \"namespaces\": {\"@id\": \"k8s:namespaces\", \"@container\": \"@list\"},\n\n    \"resource_type\": {\"@id\": \"tanzu:resourceType\", \"@type\": \"xsd:string\"},\n    \"membership_criteria\": {\"@id\": \"tanzu:membershipCriteria\", \"@container\": \"@list\"},\n\
  \n    \"apiVersion\": {\"@id\": \"k8s:apiVersion\", \"@type\": \"xsd:string\"},\n    \"kind\": {\"@id\": \"k8s:kind\", \"@type\": \"xsd:string\"},\n    \"spec\": {\"@id\": \"k8s:spec\"},\n    \"metadata\": {\"@id\": \"k8s:metadata\"},\n    \"phase\": {\"@id\": \"k8s:phase\", \"@type\": \"xsd:string\"},\n    \"conditions\": {\"@id\": \"k8s:conditions\", \"@container\": \"@list\"},\n    \"apiEndpoint\": {\"@id\": \"tanzu:apiEndpoint\", \"@type\": \"@id\"},\n\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"Organization\": \"schema:Organization\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/vmware-tanzu/refs/heads/main/json-ld/vmware-tanzu-context.jsonld
tags:
- Cloud Native
- Containers
- Enterprise
- Kubernetes
- Multi-Cloud
- Service Mesh
- VMware
- JSON-LD
- Linked Data
- Semantic Web
---
