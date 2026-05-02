---
api_specs:
- filename: longhorn-manager-api-openapi.yml
  format: yaml
  label: Longhorn Manager API
  slug: longhorn-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/longhorn/refs/heads/main/openapi/longhorn-manager-api-openapi.yml
class_count: 3
classes:
- name
- description
- id
context_file: json-ld/longhorn-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/longhorn/refs/heads/main/json-ld/longhorn-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Longhorn from Longhorn.
layout: jsonld
name: Longhorn Context
namespaces:
- prefix: longhorn
  uri: https://longhorn.io/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: skos
  uri: http://www.w3.org/2004/02/skos/core#
- prefix: k8s
  uri: https://kubernetes.io/docs/concepts/
- prefix: cncf
  uri: https://www.cncf.io/projects/
properties:
- container: ''
  name: Volume
  type: ''
- container: ''
  name: Replica
  type: ''
- container: ''
  name: Snapshot
  type: ''
- container: ''
  name: Backup
  type: ''
- container: ''
  name: Node
  type: ''
- container: ''
  name: DiskSpec
  type: ''
- container: ''
  name: RecurringJob
  type: ''
- container: ''
  name: EngineImage
  type: ''
- container: ''
  name: BackingImage
  type: ''
- container: ''
  name: Setting
  type: ''
- container: ''
  name: created
  type: dateTime
- container: ''
  name: modified
  type: dateTime
property_count: 12
provider_name: Longhorn
provider_slug: longhorn
slug: longhorn-context
source_filename: longhorn-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"longhorn\": \"https://longhorn.io/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"skos\": \"http://www.w3.org/2004/02/skos/core#\",\n    \"k8s\": \"https://kubernetes.io/docs/concepts/\",\n    \"cncf\": \"https://www.cncf.io/projects/\",\n\n    \"Volume\": {\n      \"@id\": \"longhorn:Volume\",\n      \"@context\": {\n        \"name\": \"dcterms:title\",\n        \"size\": {\n          \"@id\": \"longhorn:size\",\n          \"@type\": \"xsd:string\"\n        },\n        \"numberOfReplicas\": {\n          \"@id\": \"longhorn:numberOfReplicas\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"state\": \"longhorn:volumeState\",\n        \"robustness\": \"longhorn:volumeRobustness\",\n        \"frontend\": \"longhorn:volumeFrontend\",\n        \"\
  accessMode\": \"longhorn:accessMode\",\n        \"dataLocality\": \"longhorn:dataLocality\",\n        \"replicaAutoBalance\": \"longhorn:replicaAutoBalance\",\n        \"encrypted\": {\n          \"@id\": \"longhorn:encrypted\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"migratable\": {\n          \"@id\": \"longhorn:migratable\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"backingImage\": \"longhorn:backingImage\",\n        \"currentImage\": \"longhorn:currentImage\",\n        \"nodeSelector\": {\n          \"@id\": \"longhorn:nodeSelector\",\n          \"@container\": \"@set\"\n        },\n        \"diskSelector\": {\n          \"@id\": \"longhorn:diskSelector\",\n          \"@container\": \"@set\"\n        },\n        \"replicas\": {\n          \"@id\": \"longhorn:replicas\",\n          \"@container\": \"@set\"\n        },\n        \"conditions\": \"longhorn:conditions\",\n        \"kubernetesStatus\": \"longhorn:kubernetesStatus\"\n      },\n    \
  \  \"rdfs:label\": \"Longhorn Volume\",\n      \"rdfs:comment\": \"A Longhorn distributed block storage volume providing persistent storage for Kubernetes workloads with automatic replication.\",\n      \"skos:broader\": \"schema:Dataset\",\n      \"skos:exactMatch\": \"k8s:storage/persistent-volumes/\"\n    },\n\n    \"Replica\": {\n      \"@id\": \"longhorn:Replica\",\n      \"@context\": {\n        \"name\": \"dcterms:title\",\n        \"hostId\": {\n          \"@id\": \"longhorn:hostNode\",\n          \"@type\": \"@id\"\n        },\n        \"diskID\": \"longhorn:diskID\",\n        \"dataPath\": \"longhorn:dataPath\",\n        \"mode\": \"longhorn:replicaMode\",\n        \"running\": {\n          \"@id\": \"longhorn:running\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"failedAt\": {\n          \"@id\": \"longhorn:failedAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      },\n      \"rdfs:label\": \"Longhorn Replica\",\n      \"rdfs:comment\": \"A replica\
  \ of a Longhorn volume storing a complete copy of volume data on a specific node and disk.\",\n      \"skos:broader\": \"longhorn:Volume\"\n    },\n\n    \"Snapshot\": {\n      \"@id\": \"longhorn:Snapshot\",\n      \"@context\": {\n        \"name\": \"dcterms:title\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"size\": {\n          \"@id\": \"longhorn:snapshotSize\",\n          \"@type\": \"xsd:string\"\n        },\n        \"parent\": \"longhorn:parentSnapshot\",\n        \"removed\": {\n          \"@id\": \"longhorn:removed\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"usercreated\": {\n          \"@id\": \"longhorn:userCreated\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"labels\": \"longhorn:labels\"\n      },\n      \"rdfs:label\": \"Longhorn Snapshot\",\n      \"rdfs:comment\": \"A point-in-time snapshot of a Longhorn volume capturing the volume state at a specific\
  \ moment.\",\n      \"skos:broader\": \"longhorn:Volume\",\n      \"skos:related\": \"schema:DigitalDocument\"\n    },\n\n    \"Backup\": {\n      \"@id\": \"longhorn:Backup\",\n      \"@context\": {\n        \"name\": \"dcterms:title\",\n        \"state\": \"longhorn:backupState\",\n        \"snapshotName\": \"longhorn:sourceSnapshot\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"backupTargetName\": \"longhorn:backupTarget\",\n        \"volumeName\": {\n          \"@id\": \"longhorn:sourceVolume\",\n          \"@type\": \"@id\"\n        },\n        \"size\": {\n          \"@id\": \"longhorn:backupSize\",\n          \"@type\": \"xsd:string\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"labels\": \"longhorn:labels\"\n      },\n      \"rdfs:label\": \"Longhorn Backup\",\n      \"rdfs:comment\": \"A Longhorn volume backup stored in\
  \ an external S3-compatible or NFS backup target.\",\n      \"skos:broader\": \"longhorn:Snapshot\",\n      \"skos:related\": \"schema:DataDownload\"\n    },\n\n    \"Node\": {\n      \"@id\": \"longhorn:Node\",\n      \"@context\": {\n        \"name\": \"dcterms:title\",\n        \"allowScheduling\": {\n          \"@id\": \"longhorn:allowScheduling\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"evictionRequested\": {\n          \"@id\": \"longhorn:evictionRequested\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"tags\": {\n          \"@id\": \"longhorn:nodeTags\",\n          \"@container\": \"@set\"\n        },\n        \"disks\": \"longhorn:disks\",\n        \"conditions\": \"longhorn:conditions\"\n      },\n      \"rdfs:label\": \"Longhorn Node\",\n      \"rdfs:comment\": \"A Kubernetes node participating in the Longhorn storage cluster that can host volume replicas.\",\n      \"skos:broader\": \"schema:ComputerServer\",\n      \"skos:related\": \"k8s:architecture/nodes/\"\
  \n    },\n\n    \"DiskSpec\": {\n      \"@id\": \"longhorn:DiskSpec\",\n      \"@context\": {\n        \"path\": \"longhorn:diskPath\",\n        \"allowScheduling\": {\n          \"@id\": \"longhorn:allowScheduling\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"evictionRequested\": {\n          \"@id\": \"longhorn:evictionRequested\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"storageReserved\": {\n          \"@id\": \"longhorn:storageReserved\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"tags\": {\n          \"@id\": \"longhorn:diskTags\",\n          \"@container\": \"@set\"\n        }\n      },\n      \"rdfs:label\": \"Longhorn Disk\",\n      \"rdfs:comment\": \"A disk or directory on a Longhorn node available for hosting volume replica data.\",\n      \"skos:broader\": \"longhorn:Node\"\n    },\n\n    \"RecurringJob\": {\n      \"@id\": \"longhorn:RecurringJob\",\n      \"@context\": {\n        \"name\": \"dcterms:title\",\n     \
  \   \"task\": \"longhorn:jobTask\",\n        \"cron\": \"longhorn:cronExpression\",\n        \"retain\": {\n          \"@id\": \"longhorn:retentionCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"concurrency\": {\n          \"@id\": \"longhorn:concurrency\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"labels\": \"longhorn:labels\",\n        \"groups\": {\n          \"@id\": \"longhorn:jobGroups\",\n          \"@container\": \"@set\"\n        }\n      },\n      \"rdfs:label\": \"Longhorn Recurring Job\",\n      \"rdfs:comment\": \"A scheduled recurring job for automated snapshot or backup operations on Longhorn volumes.\",\n      \"skos:broader\": \"schema:Action\",\n      \"skos:related\": \"longhorn:Volume\"\n    },\n\n    \"EngineImage\": {\n      \"@id\": \"longhorn:EngineImage\",\n      \"@context\": {\n        \"name\": \"dcterms:title\",\n        \"image\": \"longhorn:containerImage\",\n        \"state\": \"longhorn:engineImageState\",\n    \
  \    \"default\": {\n          \"@id\": \"longhorn:isDefault\",\n          \"@type\": \"xsd:boolean\"\n        }\n      },\n      \"rdfs:label\": \"Longhorn Engine Image\",\n      \"rdfs:comment\": \"A container image for the Longhorn storage engine used to manage volume I/O operations.\",\n      \"skos:broader\": \"schema:SoftwareApplication\"\n    },\n\n    \"BackingImage\": {\n      \"@id\": \"longhorn:BackingImage\",\n      \"@context\": {\n        \"name\": \"dcterms:title\",\n        \"sourceType\": \"longhorn:sourceType\",\n        \"checksum\": \"longhorn:checksum\",\n        \"diskFileStatusMap\": \"longhorn:diskFileStatusMap\"\n      },\n      \"rdfs:label\": \"Longhorn Backing Image\",\n      \"rdfs:comment\": \"A pre-populated base image used as the data layer for Longhorn volumes, enabling fast volume provisioning from a known state.\",\n      \"skos:broader\": \"schema:ImageObject\",\n      \"skos:related\": \"longhorn:Volume\"\n    },\n\n    \"Setting\": {\n      \"@id\"\
  : \"longhorn:Setting\",\n      \"@context\": {\n        \"name\": \"dcterms:title\",\n        \"value\": \"longhorn:settingValue\",\n        \"definition\": \"longhorn:settingDefinition\"\n      },\n      \"rdfs:label\": \"Longhorn Setting\",\n      \"rdfs:comment\": \"A configurable system-wide setting for Longhorn cluster behavior and defaults.\",\n      \"skos:broader\": \"schema:PropertyValue\"\n    },\n\n    \"name\": \"dcterms:title\",\n    \"description\": \"dcterms:description\",\n    \"created\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modified\": {\n      \"@id\": \"dcterms:modified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"id\": \"dcterms:identifier\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/longhorn/refs/heads/main/json-ld/longhorn-context.jsonld
tags:
- Backup
- Block Storage
- Cloud Native
- Incubating
- Kubernetes
- Persistent Volumes
- JSON-LD
- Linked Data
- Semantic Web
---
