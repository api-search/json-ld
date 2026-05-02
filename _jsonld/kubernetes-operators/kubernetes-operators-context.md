---
api_specs:
- filename: kubernetes-operators-watch-asyncapi.yml
  format: yaml
  label: Kubernetes Operators
  slug: kubernetes-operators
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/kubernetes-operators/refs/heads/main/asyncapi/kubernetes-operators-watch-asyncapi.yml
- filename: kubernetes-crd-openapi.yml
  format: yaml
  label: Kubernetes Custom Resource Definitions
  slug: custom-resource-definitions
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kubernetes-operators/refs/heads/main/openapi/kubernetes-crd-openapi.yml
- filename: kubernetes-olm-openapi.yml
  format: yaml
  label: Operator Lifecycle Manager
  slug: operator-lifecycle-manager
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kubernetes-operators/refs/heads/main/openapi/kubernetes-olm-openapi.yml
class_count: 0
classes: []
context_file: json-ld/kubernetes-operators-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/kubernetes-operators/refs/heads/main/json-ld/kubernetes-operators-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Kubernetes Operators from Kubernetes Operators.
layout: jsonld
name: Kubernetes Operators Context
namespaces:
- prefix: k8s
  uri: https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.32/#
- prefix: apiext
  uri: https://kubernetes.io/docs/reference/kubernetes-api/extend-resources/custom-resource-definition-v1/#
- prefix: olm
  uri: https://olm.operatorframework.io/docs/concepts/crds/
- prefix: opfw
  uri: https://operatorframework.io/operator-capabilities/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: prov
  uri: http://www.w3.org/ns/prov#
properties:
- container: ''
  name: CustomResourceDefinition
  type: ''
- container: ''
  name: CatalogSource
  type: ''
- container: ''
  name: OperatorGroup
  type: ''
- container: ''
  name: Subscription
  type: ''
- container: ''
  name: InstallPlan
  type: ''
- container: ''
  name: ClusterServiceVersion
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
  name: name
  type: string
- container: ''
  name: namespace
  type: string
- container: ''
  name: uid
  type: string
- container: ''
  name: creationTimestamp
  type: dateTime
- container: index
  name: labels
  type: ''
- container: index
  name: annotations
  type: ''
- container: ''
  name: spec
  type: ''
- container: ''
  name: status
  type: ''
- container: set
  name: conditions
  type: ''
- container: ''
  name: generation
  type: integer
- container: ''
  name: resourceVersion
  type: string
property_count: 20
provider_name: Kubernetes Operators
provider_slug: kubernetes-operators
slug: kubernetes-operators-context
source_filename: kubernetes-operators-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"k8s\": \"https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.32/#\",\n    \"apiext\": \"https://kubernetes.io/docs/reference/kubernetes-api/extend-resources/custom-resource-definition-v1/#\",\n    \"olm\": \"https://olm.operatorframework.io/docs/concepts/crds/\",\n    \"opfw\": \"https://operatorframework.io/operator-capabilities/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"prov\": \"http://www.w3.org/ns/prov#\",\n\n    \"CustomResourceDefinition\": {\n      \"@id\": \"apiext:CustomResourceDefinition\",\n      \"@context\": {\n        \"spec\": \"apiext:CustomResourceDefinitionSpec\",\n        \"status\": \"apiext:CustomResourceDefinitionStatus\",\n        \"group\": {\n          \"@id\": \"apiext:CustomResourceDefinitionSpec.group\",\n        \
  \  \"@type\": \"xsd:string\"\n        },\n        \"scope\": {\n          \"@id\": \"apiext:CustomResourceDefinitionSpec.scope\",\n          \"@type\": \"xsd:string\"\n        },\n        \"versions\": {\n          \"@id\": \"apiext:CustomResourceDefinitionSpec.versions\",\n          \"@container\": \"@set\"\n        },\n        \"names\": \"apiext:CustomResourceDefinitionNames\"\n      }\n    },\n\n    \"CatalogSource\": {\n      \"@id\": \"olm:catalogsource\",\n      \"@context\": {\n        \"sourceType\": {\n          \"@id\": \"olm:catalogsource-sourceType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"image\": {\n          \"@id\": \"olm:catalogsource-image\",\n          \"@type\": \"xsd:string\"\n        },\n        \"address\": {\n          \"@id\": \"olm:catalogsource-address\",\n          \"@type\": \"xsd:string\"\n        },\n        \"displayName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"publisher\"\
  : {\n          \"@id\": \"schema:publisher\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"OperatorGroup\": {\n      \"@id\": \"olm:operatorgroup\",\n      \"@context\": {\n        \"targetNamespaces\": {\n          \"@id\": \"olm:operatorgroup-targetNamespaces\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Subscription\": {\n      \"@id\": \"olm:subscription\",\n      \"@context\": {\n        \"channel\": {\n          \"@id\": \"olm:subscription-channel\",\n          \"@type\": \"xsd:string\"\n        },\n        \"source\": {\n          \"@id\": \"olm:subscription-source\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sourceNamespace\": {\n          \"@id\": \"olm:subscription-sourceNamespace\",\n          \"@type\": \"xsd:string\"\n        },\n        \"startingCSV\": {\n          \"@id\": \"\
  olm:subscription-startingCSV\",\n          \"@type\": \"xsd:string\"\n        },\n        \"installPlanApproval\": {\n          \"@id\": \"olm:subscription-installPlanApproval\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"InstallPlan\": {\n      \"@id\": \"olm:installplan\",\n      \"@context\": {\n        \"clusterServiceVersionNames\": {\n          \"@id\": \"olm:installplan-clusterServiceVersionNames\",\n          \"@container\": \"@set\"\n        },\n        \"approval\": {\n          \"@id\": \"olm:installplan-approval\",\n          \"@type\": \"xsd:string\"\n        },\n        \"approved\": {\n          \"@id\": \"olm:installplan-approved\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"phase\": {\n          \"@id\": \"olm:installplan-phase\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"ClusterServiceVersion\": {\n      \"@id\": \"olm:clusterserviceversion\",\n      \"@context\": {\n        \"displayName\"\
  : {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"version\": {\n          \"@id\": \"schema:version\",\n          \"@type\": \"xsd:string\"\n        },\n        \"maturity\": {\n          \"@id\": \"olm:clusterserviceversion-maturity\",\n          \"@type\": \"xsd:string\"\n        },\n        \"replaces\": {\n          \"@id\": \"olm:clusterserviceversion-replaces\",\n          \"@type\": \"xsd:string\"\n        },\n        \"installModes\": {\n          \"@id\": \"olm:clusterserviceversion-installModes\",\n          \"@container\": \"@set\"\n        },\n        \"customresourcedefinitions\": {\n          \"@id\": \"olm:clusterserviceversion-crds\"\n        },\n        \"minKubeVersion\": {\n          \"@id\": \"olm:clusterserviceversion-minKubeVersion\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n  \
  \  },\n\n    \"apiVersion\": {\n      \"@id\": \"k8s:apiversion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kind\": {\n      \"@id\": \"k8s:kind\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"k8s:objectmeta-v1-meta\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"namespace\": {\n      \"@id\": \"k8s:namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uid\": {\n      \"@id\": \"dcterms:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationTimestamp\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"labels\": {\n      \"@id\": \"k8s:labels\",\n      \"@container\": \"@index\"\n    },\n    \"annotations\": {\n      \"@id\": \"k8s:annotations\",\n      \"@container\": \"@index\"\n    },\n    \"spec\": {\n      \"@id\": \"k8s:spec\"\n    },\n    \"status\": {\n      \"@id\": \"k8s:status\"\n    },\n    \"conditions\": {\n   \
  \   \"@id\": \"k8s:conditions\",\n      \"@container\": \"@set\"\n    },\n    \"generation\": {\n      \"@id\": \"k8s:generation\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"resourceVersion\": {\n      \"@id\": \"k8s:resourceVersion\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/kubernetes-operators/refs/heads/main/json-ld/kubernetes-operators-context.jsonld
tags:
- Automation
- Cloud Native
- DevOps
- Infrastructure
- Kubernetes
- JSON-LD
- Linked Data
- Semantic Web
---
