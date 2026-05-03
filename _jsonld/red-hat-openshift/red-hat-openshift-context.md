---
api_specs:
- filename: red-hat-openshift-api-openapi.yml
  format: yaml
  label: Red Hat OpenShift Container Platform API
  slug: openshift-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/red-hat-openshift/refs/heads/main/openapi/red-hat-openshift-api-openapi.yml
- filename: openapi
  format: yaml
  label: Red Hat OpenShift Cluster Manager API
  slug: openshift-cluster-manager-api
  spec_type: OpenAPI
  url: https://api.openshift.com/openapi
class_count: 3
classes:
- id
- name
- description
context_file: json-ld/red-hat-openshift-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/red-hat-openshift/refs/heads/main/json-ld/red-hat-openshift-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Red Hat Openshift from Red Hat OpenShift.
layout: jsonld
name: Red Hat Openshift Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: k8s
  uri: https://kubernetes.io/docs/reference/kubernetes-api/
- prefix: openshift
  uri: https://docs.openshift.com/container-platform/latest/rest_api/
properties:
- container: ''
  name: Cluster
  type: schema:ComputerSystem
- container: ''
  name: Project
  type: schema:Project
- container: ''
  name: Route
  type: schema:EntryPoint
- container: ''
  name: BuildConfig
  type: schema:SoftwareSourceCode
- container: ''
  name: ImageStream
  type: schema:SoftwareApplication
- container: ''
  name: DeploymentConfig
  type: schema:SoftwareApplication
- container: ''
  name: namespace
  type: string
- container: ''
  name: uid
  type: string
- container: ''
  name: creationTimestamp
  type: dateTime
- container: ''
  name: labels
  type: string
- container: ''
  name: apiVersion
  type: string
- container: ''
  name: kind
  type: string
- container: ''
  name: phase
  type: string
- container: ''
  name: host
  type: string
- container: ''
  name: replicas
  type: integer
- container: ''
  name: cloudProvider
  type: string
- container: ''
  name: region
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: apiUrl
  type: string
- container: ''
  name: consoleUrl
  type: string
property_count: 20
provider_name: Red Hat OpenShift
provider_slug: red-hat-openshift
slug: red-hat-openshift-context
source_filename: red-hat-openshift-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"k8s\": \"https://kubernetes.io/docs/reference/kubernetes-api/\",\n    \"openshift\": \"https://docs.openshift.com/container-platform/latest/rest_api/\",\n    \"Cluster\": {\n      \"@id\": \"schema:ComputerSystem\",\n      \"@type\": \"schema:ComputerSystem\"\n    },\n    \"Project\": {\n      \"@id\": \"schema:Project\",\n      \"@type\": \"schema:Project\"\n    },\n    \"Route\": {\n      \"@id\": \"schema:EntryPoint\",\n      \"@type\": \"schema:EntryPoint\"\n    },\n    \"BuildConfig\": {\n      \"@id\": \"schema:SoftwareSourceCode\",\n      \"@type\": \"schema:SoftwareSourceCode\"\n    },\n    \"ImageStream\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"@type\": \"schema:SoftwareApplication\"\n    },\n    \"DeploymentConfig\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"@type\": \"schema:SoftwareApplication\"\
  \n    },\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"namespace\": {\n      \"@id\": \"schema:containedInPlace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uid\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationTimestamp\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"labels\": {\n      \"@id\": \"schema:keywords\",\n      \"@type\": \"xsd:string\"\n    },\n    \"apiVersion\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kind\": {\n      \"@id\": \"schema:additionalType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phase\": {\n      \"@id\": \"schema:actionStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"host\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"replicas\": {\n      \"@id\": \"schema:numberOfItems\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"cloudProvider\": {\n      \"@id\": \"schema:provider\",\n      \"@type\": \"xsd:string\"\n    },\n    \"region\": {\n      \"@id\": \"schema:contentLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"schema:actionStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"apiUrl\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"consoleUrl\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/red-hat-openshift/refs/heads/main/json-ld/red-hat-openshift-context.jsonld
tags:
- Containers
- Enterprise
- Hybrid Cloud
- Kubernetes
- PaaS
- Red Hat
- JSON-LD
- Linked Data
- Semantic Web
---
