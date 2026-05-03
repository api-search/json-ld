---
api_specs:
- filename: timoni-openapi.yml
  format: yaml
  label: Timoni Module Registry API
  slug: timoni
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/timoni/refs/heads/main/openapi/timoni-openapi.yml
class_count: 33
classes:
- Module
- ModuleInstance
- Bundle
- BundleRuntime
- Artifact
- OciManifest
- OciLayer
- Registry
- SoftwarePackage
- id
- name
- description
- version
- module
- instance
- namespace
- cluster
- values
- bundle
- runtime
- digest
- mediaType
- size
- layers
- annotations
- tags
- registry
- repository
- cueModule
- schemaVersion
- source
- revision
- license
context_file: json-ld/timoni-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/timoni/refs/heads/main/json-ld/timoni-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Timoni from Timoni.
layout: jsonld
name: Timoni Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: timoni
  uri: https://timoni.sh/vocab/
- prefix: oci
  uri: https://opencontainers.org/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: created
  type: dateTime
property_count: 1
provider_name: Timoni
provider_slug: timoni
slug: timoni-context
source_filename: timoni-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"timoni\": \"https://timoni.sh/vocab/\",\n    \"oci\": \"https://opencontainers.org/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Module\": \"timoni:Module\",\n    \"ModuleInstance\": \"timoni:ModuleInstance\",\n    \"Bundle\": \"timoni:Bundle\",\n    \"BundleRuntime\": \"timoni:BundleRuntime\",\n    \"Artifact\": \"timoni:Artifact\",\n    \"OciManifest\": \"oci:Manifest\",\n    \"OciLayer\": \"oci:Layer\",\n    \"Registry\": \"timoni:Registry\",\n    \"SoftwarePackage\": \"schema:SoftwareApplication\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"version\": \"schema:version\",\n    \"created\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"module\": \"timoni:module\",\n    \"instance\": \"timoni:instance\",\n    \"namespace\": \"timoni:kubernetesNamespace\"\
  ,\n    \"cluster\": \"timoni:kubernetesCluster\",\n    \"values\": \"timoni:configurationValues\",\n    \"bundle\": \"timoni:bundle\",\n    \"runtime\": \"timoni:runtime\",\n\n    \"digest\": \"oci:digest\",\n    \"mediaType\": \"oci:mediaType\",\n    \"size\": \"oci:size\",\n    \"layers\": \"oci:layer\",\n    \"annotations\": \"oci:annotations\",\n\n    \"tags\": \"schema:keywords\",\n    \"registry\": \"schema:url\",\n    \"repository\": \"timoni:ociRepository\",\n\n    \"cueModule\": \"timoni:cueModule\",\n    \"schemaVersion\": \"oci:schemaVersion\",\n    \"source\": \"schema:codeRepository\",\n    \"revision\": \"schema:softwareVersion\",\n    \"license\": \"schema:license\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/timoni/refs/heads/main/json-ld/timoni-context.jsonld
tags:
- Containers
- Kubernetes
- Package Manager
- CUE
- JSON-LD
- Linked Data
- Semantic Web
---
