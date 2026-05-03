---
api_specs:
- filename: rook-ceph-object-storage-openapi.yml
  format: yaml
  label: Rook Ceph Object Storage API
  slug: rook-ceph-object-storage-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rook/refs/heads/main/openapi/rook-ceph-object-storage-openapi.yml
class_count: 0
classes: []
context_file: json-ld/rook-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/rook/refs/heads/main/json-ld/rook-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Rook from Rook.
layout: jsonld
name: Rook Context
namespaces:
- prefix: rook
  uri: https://rook.io/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: k8s
  uri: https://kubernetes.io/vocab/
properties:
- container: ''
  name: CephCluster
  type: ''
- container: ''
  name: CephBlockPool
  type: ''
- container: ''
  name: CephFilesystem
  type: ''
- container: ''
  name: CephObjectStore
  type: ''
- container: ''
  name: CephObjectStoreUser
  type: ''
- container: ''
  name: StorageClassDeviceSet
  type: ''
property_count: 6
provider_name: Rook
provider_slug: rook
slug: rook-context
source_filename: rook-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"rook\": \"https://rook.io/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"k8s\": \"https://kubernetes.io/vocab/\",\n\n    \"CephCluster\": {\n      \"@id\": \"rook:CephCluster\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"namespace\": {\n          \"@id\": \"k8s:namespace\"\n        },\n        \"dataDirHostPath\": {\n          \"@id\": \"rook:dataDirHostPath\"\n        },\n        \"cephVersion\": {\n          \"@id\": \"rook:cephVersion\"\n        },\n        \"network\": {\n          \"@id\": \"rook:network\"\n        },\n        \"storage\": {\n          \"@id\": \"rook:storage\"\n        },\n        \"mon\": {\n          \"@id\": \"rook:mon\"\n        },\n        \"mgr\": {\n          \"@id\": \"rook:mgr\"\n        },\n        \"dashboard\": {\n  \
  \        \"@id\": \"rook:dashboard\"\n        },\n        \"monitoring\": {\n          \"@id\": \"rook:monitoring\"\n        }\n      }\n    },\n\n    \"CephBlockPool\": {\n      \"@id\": \"rook:CephBlockPool\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"namespace\": {\n          \"@id\": \"k8s:namespace\"\n        },\n        \"failureDomain\": {\n          \"@id\": \"rook:failureDomain\"\n        },\n        \"deviceClass\": {\n          \"@id\": \"rook:deviceClass\"\n        },\n        \"replicated\": {\n          \"@id\": \"rook:replicated\"\n        },\n        \"erasureCoded\": {\n          \"@id\": \"rook:erasureCoded\"\n        },\n        \"mirroring\": {\n          \"@id\": \"rook:mirroring\"\n        }\n      }\n    },\n\n    \"CephFilesystem\": {\n      \"@id\": \"rook:CephFilesystem\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"namespace\": {\n         \
  \ \"@id\": \"k8s:namespace\"\n        },\n        \"metadataPool\": {\n          \"@id\": \"rook:metadataPool\"\n        },\n        \"dataPools\": {\n          \"@id\": \"rook:dataPools\",\n          \"@container\": \"@set\"\n        },\n        \"metadataServer\": {\n          \"@id\": \"rook:metadataServer\"\n        },\n        \"preserveFilesystemOnDelete\": {\n          \"@id\": \"rook:preserveFilesystemOnDelete\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"CephObjectStore\": {\n      \"@id\": \"rook:CephObjectStore\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"namespace\": {\n          \"@id\": \"k8s:namespace\"\n        },\n        \"metadataPool\": {\n          \"@id\": \"rook:metadataPool\"\n        },\n        \"dataPool\": {\n          \"@id\": \"rook:dataPool\"\n        },\n        \"gateway\": {\n          \"@id\": \"rook:gateway\"\n        },\n        \"zone\": {\n          \"@id\"\
  : \"rook:zone\"\n        }\n      }\n    },\n\n    \"CephObjectStoreUser\": {\n      \"@id\": \"rook:CephObjectStoreUser\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"store\": {\n          \"@id\": \"rook:objectStore\"\n        },\n        \"displayName\": {\n          \"@id\": \"schema:alternateName\"\n        },\n        \"capabilities\": {\n          \"@id\": \"rook:capabilities\"\n        },\n        \"quotas\": {\n          \"@id\": \"rook:quotas\"\n        }\n      }\n    },\n\n    \"StorageClassDeviceSet\": {\n      \"@id\": \"rook:StorageClassDeviceSet\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"count\": {\n          \"@id\": \"schema:quantity\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"portable\": {\n          \"@id\": \"rook:portable\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"volumeClaimTemplates\": {\n          \"\
  @id\": \"k8s:volumeClaimTemplate\",\n          \"@container\": \"@set\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/rook/refs/heads/main/json-ld/rook-context.jsonld
tags:
- Block Storage
- CNCF
- Ceph
- Cloud Native
- File Storage
- Graduated
- Kubernetes
- Object Storage
- Orchestration
- Storage
- JSON-LD
- Linked Data
- Semantic Web
---
