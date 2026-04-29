---
api_specs:
- filename: crossplane-kubernetes-api-openapi.yml
  format: yaml
  label: Crossplane Kubernetes API
  slug: crossplane-kubernetes-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/crossplane/refs/heads/main/openapi/crossplane-kubernetes-api-openapi.yml
class_count: 6
classes:
- name
- description
- created
- modified
- version
- license
context_file: json-ld/crossplane-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/crossplane/refs/heads/main/json-ld/crossplane-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Crossplane from Crossplane.
layout: jsonld
name: Crossplane Context
namespaces:
- prefix: crossplane
  uri: https://crossplane.io/docs/concepts/
- prefix: k8s
  uri: https://kubernetes.io/docs/reference/
- prefix: iac
  uri: https://w3id.org/infrastructure-as-code#
- prefix: cncf
  uri: https://www.cncf.io/projects/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: skos
  uri: http://www.w3.org/2004/02/skos/core#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Composition
  type: reference
- container: ''
  name: CompositeResourceDefinition
  type: reference
- container: ''
  name: Provider
  type: reference
- container: ''
  name: ProviderConfig
  type: reference
- container: ''
  name: ManagedResource
  type: reference
- container: ''
  name: Claim
  type: reference
- container: ''
  name: CompositionFunction
  type: reference
- container: ''
  name: ControlPlane
  type: reference
- container: ''
  name: compositeTypeRef
  type: reference
- container: ''
  name: providerConfigRef
  type: reference
- container: ''
  name: patch
  type: ''
- container: ''
  name: connectionSecret
  type: ''
- container: ''
  name: apiVersion
  type: string
- container: ''
  name: kind
  type: string
- container: ''
  name: metadata
  type: ''
- container: ''
  name: spec
  type: ''
- container: ''
  name: status
  type: ''
property_count: 17
provider_name: Crossplane
provider_slug: crossplane
slug: crossplane-context
source_filename: crossplane-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"crossplane\": \"https://crossplane.io/docs/concepts/\",\n    \"k8s\": \"https://kubernetes.io/docs/reference/\",\n    \"iac\": \"https://w3id.org/infrastructure-as-code#\",\n    \"cncf\": \"https://www.cncf.io/projects/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"skos\": \"http://www.w3.org/2004/02/skos/core#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Composition\": {\n      \"@id\": \"crossplane:compositions\",\n      \"@type\": \"@id\",\n      \"rdfs:label\": \"Composition\",\n      \"rdfs:comment\": \"A Crossplane Composition defines how to transform a composite resource into one or more composed managed resources, including field mapping and patching.\",\n      \"skos:broader\": \"iac:ResourceTemplate\",\n      \"skos:related\": [\"k8s:custom-resources\", \"crossplane:composite-resources\"]\n    },\n\n    \"\
  CompositeResourceDefinition\": {\n      \"@id\": \"crossplane:composite-resource-definitions\",\n      \"@type\": \"@id\",\n      \"rdfs:label\": \"CompositeResourceDefinition (XRD)\",\n      \"rdfs:comment\": \"Defines the schema and API surface for a composite resource, extending the Kubernetes API with a custom infrastructure abstraction.\",\n      \"skos:broader\": \"k8s:custom-resources\",\n      \"skos:related\": [\"crossplane:compositions\", \"crossplane:claims\"]\n    },\n\n    \"Provider\": {\n      \"@id\": \"crossplane:providers\",\n      \"@type\": \"@id\",\n      \"rdfs:label\": \"Provider\",\n      \"rdfs:comment\": \"A Crossplane Provider package that installs controllers and CRDs for managing resources on a specific infrastructure platform such as AWS, GCP, or Azure.\",\n      \"skos:broader\": \"k8s:operators\",\n      \"skos:related\": [\"crossplane:provider-configs\", \"crossplane:managed-resources\"]\n    },\n\n    \"ProviderConfig\": {\n      \"@id\": \"crossplane:provider-configs\"\
  ,\n      \"@type\": \"@id\",\n      \"rdfs:label\": \"ProviderConfig\",\n      \"rdfs:comment\": \"Authentication and configuration for a Crossplane Provider, specifying how the provider connects to an infrastructure platform.\",\n      \"skos:broader\": \"iac:ProviderConfiguration\",\n      \"skos:related\": \"crossplane:providers\"\n    },\n\n    \"ManagedResource\": {\n      \"@id\": \"crossplane:managed-resources\",\n      \"@type\": \"@id\",\n      \"rdfs:label\": \"Managed Resource\",\n      \"rdfs:comment\": \"A Kubernetes custom resource representing a single piece of external infrastructure managed by a Crossplane Provider.\",\n      \"skos:broader\": \"iac:InfrastructureResource\",\n      \"skos:related\": [\"crossplane:providers\", \"crossplane:compositions\"]\n    },\n\n    \"Claim\": {\n      \"@id\": \"crossplane:claims\",\n      \"@type\": \"@id\",\n      \"rdfs:label\": \"Claim\",\n      \"rdfs:comment\": \"A namespace-scoped resource that requests a composite resource,\
  \ providing a self-service interface for application teams.\",\n      \"skos:broader\": \"k8s:namespaced-resources\",\n      \"skos:related\": \"crossplane:composite-resource-definitions\"\n    },\n\n    \"CompositionFunction\": {\n      \"@id\": \"crossplane:composition-functions\",\n      \"@type\": \"@id\",\n      \"rdfs:label\": \"Composition Function\",\n      \"rdfs:comment\": \"A containerized function invoked during composition to perform advanced resource templating, transformation, or validation logic.\",\n      \"skos:broader\": \"iac:TransformFunction\",\n      \"skos:related\": \"crossplane:compositions\"\n    },\n\n    \"ControlPlane\": {\n      \"@id\": \"crossplane:control-planes\",\n      \"@type\": \"@id\",\n      \"rdfs:label\": \"Control Plane\",\n      \"rdfs:comment\": \"A Kubernetes cluster running Crossplane that serves as a universal control plane for managing infrastructure across multiple providers.\",\n      \"skos:broader\": \"k8s:clusters\",\n      \"skos:exactMatch\"\
  : \"cncf:crossplane\"\n    },\n\n    \"compositeTypeRef\": {\n      \"@id\": \"crossplane:compositeTypeRef\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"Reference linking a Composition to the CompositeResourceDefinition it satisfies.\"\n    },\n\n    \"providerConfigRef\": {\n      \"@id\": \"crossplane:providerConfigRef\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"Reference from a managed resource to its ProviderConfig for authentication.\"\n    },\n\n    \"patch\": {\n      \"@id\": \"crossplane:patches\",\n      \"rdfs:comment\": \"A field-level mapping that copies or transforms values between composite and composed resources.\"\n    },\n\n    \"connectionSecret\": {\n      \"@id\": \"crossplane:connection-secrets\",\n      \"rdfs:comment\": \"A Kubernetes Secret containing connection details propagated from composed resources to the composite resource or claim.\"\n    },\n\n    \"apiVersion\": {\n      \"@id\": \"k8s:api-version\",\n      \"@type\": \"xsd:string\"\
  ,\n      \"rdfs:comment\": \"Kubernetes API group and version identifier.\"\n    },\n\n    \"kind\": {\n      \"@id\": \"k8s:resource-kind\",\n      \"@type\": \"xsd:string\",\n      \"rdfs:comment\": \"Kubernetes resource type identifier.\"\n    },\n\n    \"metadata\": {\n      \"@id\": \"k8s:object-metadata\",\n      \"rdfs:comment\": \"Standard Kubernetes object metadata including name, namespace, labels, and annotations.\"\n    },\n\n    \"spec\": {\n      \"@id\": \"k8s:resource-spec\",\n      \"rdfs:comment\": \"Desired state specification for the Kubernetes resource.\"\n    },\n\n    \"status\": {\n      \"@id\": \"k8s:resource-status\",\n      \"rdfs:comment\": \"Observed state and conditions of the Kubernetes resource.\"\n    },\n\n    \"name\": \"dcterms:title\",\n    \"description\": \"dcterms:description\",\n    \"created\": \"dcterms:created\",\n    \"modified\": \"dcterms:modified\",\n    \"version\": \"dcterms:hasVersion\",\n    \"license\": \"dcterms:license\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/crossplane/refs/heads/main/json-ld/crossplane-context.jsonld
tags:
- Apache 2.0
- CNCF
- Cloud Native
- Composition
- Control Plane
- Custom Resource Definitions
- Graduated
- Infrastructure as Code
- Kubernetes
- Multi-Cloud
- Open Source
- Platform Engineering
- Providers
- JSON-LD
- Linked Data
- Semantic Web
---
