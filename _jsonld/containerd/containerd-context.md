---
api_specs:
- filename: containerd-metrics-openapi.yml
  format: yaml
  label: Containerd Metrics API
  slug: containerd-metrics-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/containerd/refs/heads/main/openapi/containerd-metrics-openapi.yml
class_count: 0
classes: []
context_file: json-ld/containerd-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/containerd/refs/heads/main/json-ld/containerd-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Containerd from Containerd.
layout: jsonld
name: Containerd Context
namespaces:
- prefix: containerd
  uri: https://containerd.io/ns/
- prefix: oci
  uri: https://opencontainers.org/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: cncf
  uri: https://www.cncf.io/ns/
- prefix: k8s
  uri: https://kubernetes.io/ns/
properties:
- container: ''
  name: ContainerRuntime
  type: ''
- container: ''
  name: Container
  type: ''
- container: ''
  name: Image
  type: ''
- container: ''
  name: Namespace
  type: ''
- container: ''
  name: Snapshot
  type: ''
- container: ''
  name: Task
  type: ''
- container: ''
  name: Content
  type: ''
- container: ''
  name: Lease
  type: ''
- container: ''
  name: OCIRuntimeSpec
  type: ''
- container: ''
  name: CRIRuntime
  type: ''
- container: ''
  name: Plugin
  type: ''
- container: ''
  name: Event
  type: ''
property_count: 12
provider_name: Containerd
provider_slug: containerd
slug: containerd-context
source_filename: containerd-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"containerd\": \"https://containerd.io/ns/\",\n    \"oci\": \"https://opencontainers.org/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"cncf\": \"https://www.cncf.io/ns/\",\n    \"k8s\": \"https://kubernetes.io/ns/\",\n\n    \"ContainerRuntime\": {\n      \"@id\": \"containerd:ContainerRuntime\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"version\": \"schema:softwareVersion\",\n        \"description\": \"schema:description\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"license\": \"schema:license\",\n        \"repository\": {\n          \"@id\": \"schema:codeRepository\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Container\": {\n      \"@id\": \"containerd:Container\",\n      \"@context\": {\n      \
  \  \"id\": \"containerd:containerId\",\n        \"image\": \"containerd:containerImage\",\n        \"runtime\": \"containerd:runtime\",\n        \"status\": \"containerd:containerStatus\",\n        \"pid\": \"containerd:processId\",\n        \"labels\": \"containerd:labels\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"snapshotter\": \"containerd:snapshotter\",\n        \"snapshotKey\": \"containerd:snapshotKey\",\n        \"extensions\": \"containerd:extensions\"\n      }\n    },\n\n    \"Image\": {\n      \"@id\": \"containerd:Image\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"target\": \"containerd:imageTarget\",\n        \"digest\": \"oci:digest\",\n        \"mediaType\": \"oci:mediaType\",\n        \"size\": {\n          \"@id\": \"schema:contentSize\"\
  ,\n          \"@type\": \"xsd:integer\"\n        },\n        \"labels\": \"containerd:labels\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Namespace\": {\n      \"@id\": \"containerd:Namespace\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"labels\": \"containerd:labels\"\n      }\n    },\n\n    \"Snapshot\": {\n      \"@id\": \"containerd:Snapshot\",\n      \"@context\": {\n        \"key\": \"containerd:snapshotKey\",\n        \"parent\": \"containerd:parentSnapshot\",\n        \"kind\": \"containerd:snapshotKind\",\n        \"inodes\": {\n          \"@id\": \"containerd:inodeUsage\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"diskSize\": {\n          \"@id\": \"containerd:diskSize\",\n          \"@type\": \"xsd:integer\"\n   \
  \     },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Task\": {\n      \"@id\": \"containerd:Task\",\n      \"@context\": {\n        \"containerId\": \"containerd:containerId\",\n        \"pid\": {\n          \"@id\": \"containerd:processId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"status\": \"containerd:taskStatus\",\n        \"stdin\": \"containerd:stdin\",\n        \"stdout\": \"containerd:stdout\",\n        \"stderr\": \"containerd:stderr\",\n        \"exitStatus\": {\n          \"@id\": \"containerd:exitStatus\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"exitedAt\": {\n          \"@id\": \"containerd:exitedAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Content\": {\n      \"@id\": \"containerd:Content\"\
  ,\n      \"@context\": {\n        \"digest\": \"oci:digest\",\n        \"mediaType\": \"oci:mediaType\",\n        \"size\": {\n          \"@id\": \"schema:contentSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"labels\": \"containerd:labels\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Lease\": {\n      \"@id\": \"containerd:Lease\",\n      \"@context\": {\n        \"id\": \"containerd:leaseId\",\n        \"labels\": \"containerd:labels\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"OCIRuntimeSpec\": {\n      \"@id\": \"oci:RuntimeSpec\",\n      \"@context\": {\n        \"ociVersion\": \"oci:specVersion\",\n        \"hostname\": \"schema:hostname\",\n  \
  \      \"root\": \"oci:rootFilesystem\",\n        \"mounts\": {\n          \"@id\": \"oci:mounts\",\n          \"@container\": \"@set\"\n        },\n        \"process\": \"oci:containerProcess\",\n        \"annotations\": \"oci:annotations\",\n        \"hooks\": \"oci:lifecycleHooks\"\n      }\n    },\n\n    \"CRIRuntime\": {\n      \"@id\": \"k8s:ContainerRuntimeInterface\",\n      \"@context\": {\n        \"sandboxImage\": \"k8s:pauseImage\",\n        \"runtimeHandler\": \"k8s:runtimeHandler\",\n        \"podSandbox\": \"k8s:podSandbox\",\n        \"containerConfig\": \"k8s:containerConfig\"\n      }\n    },\n\n    \"Plugin\": {\n      \"@id\": \"containerd:Plugin\",\n      \"@context\": {\n        \"type\": \"containerd:pluginType\",\n        \"id\": \"containerd:pluginId\",\n        \"requires\": {\n          \"@id\": \"containerd:requires\",\n          \"@container\": \"@set\"\n        },\n        \"platforms\": {\n          \"@id\": \"schema:operatingSystem\",\n          \"@container\"\
  : \"@set\"\n        }\n      }\n    },\n\n    \"Event\": {\n      \"@id\": \"containerd:Event\",\n      \"@context\": {\n        \"topic\": \"containerd:eventTopic\",\n        \"namespace\": \"containerd:namespace\",\n        \"timestamp\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"event\": \"containerd:eventPayload\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/containerd/refs/heads/main/json-ld/containerd-context.jsonld
tags:
- Cloud Native
- Container Runtime
- CRI
- Docker
- gRPC
- Kubernetes
- OCI
- JSON-LD
- Linked Data
- Semantic Web
---
