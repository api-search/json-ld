---
api_specs:
- filename: kubevirt-vm-openapi.yml
  format: yaml
  label: KubeVirt VM Management API
  slug: kubevirt-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kubevirt/refs/heads/main/openapi/kubevirt-vm-openapi.yml
- filename: kubevirt-cdi-openapi.yml
  format: yaml
  label: KubeVirt Containerized Data Importer API
  slug: kubevirt-cdi-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kubevirt/refs/heads/main/openapi/kubevirt-cdi-openapi.yml
class_count: 0
classes: []
context_file: json-ld/kubevirt-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/kubevirt/refs/heads/main/json-ld/kubevirt-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Kubevirt from KubeVirt.
layout: jsonld
name: Kubevirt Context
namespaces:
- prefix: kubevirt
  uri: https://kubevirt.io/vocabulary#
- prefix: k8s
  uri: https://kubernetes.io/vocabulary#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: prov
  uri: http://www.w3.org/ns/prov#
properties:
- container: ''
  name: VirtualMachine
  type: ''
- container: ''
  name: VirtualMachineInstance
  type: ''
- container: ''
  name: VirtualMachineInstanceMigration
  type: ''
- container: ''
  name: DomainSpec
  type: ''
- container: ''
  name: Disk
  type: ''
- container: ''
  name: Interface
  type: ''
- container: ''
  name: Volume
  type: ''
- container: ''
  name: DataVolume
  type: ''
- container: ''
  name: DataSource
  type: ''
- container: ''
  name: StorageProfile
  type: ''
property_count: 10
provider_name: KubeVirt
provider_slug: kubevirt
slug: kubevirt-context
source_filename: kubevirt-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"kubevirt\": \"https://kubevirt.io/vocabulary#\",\n    \"k8s\": \"https://kubernetes.io/vocabulary#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"prov\": \"http://www.w3.org/ns/prov#\",\n\n    \"VirtualMachine\": {\n      \"@id\": \"kubevirt:VirtualMachine\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"namespace\": \"k8s:namespace\",\n        \"runStrategy\": \"kubevirt:runStrategy\",\n        \"status\": \"kubevirt:vmStatus\",\n        \"labels\": \"k8s:labels\",\n        \"creationTimestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"VirtualMachineInstance\": {\n      \"@id\": \"kubevirt:VirtualMachineInstance\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"namespace\": \"k8s:namespace\",\n\
  \        \"nodeName\": {\n          \"@id\": \"kubevirt:scheduledNode\",\n          \"@type\": \"@id\"\n        },\n        \"phase\": \"kubevirt:vmiPhase\",\n        \"creationTimestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"VirtualMachineInstanceMigration\": {\n      \"@id\": \"kubevirt:Migration\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"namespace\": \"k8s:namespace\",\n        \"vmiName\": {\n          \"@id\": \"kubevirt:migratedInstance\",\n          \"@type\": \"@id\"\n        },\n        \"phase\": \"kubevirt:migrationPhase\",\n        \"targetNode\": {\n          \"@id\": \"kubevirt:targetNode\",\n          \"@type\": \"@id\"\n        },\n        \"sourceNode\": {\n          \"@id\": \"kubevirt:sourceNode\",\n          \"@type\": \"@id\"\n        },\n        \"startTimestamp\": {\n          \"@id\": \"prov:startedAtTime\",\n          \"@type\": \"xsd:dateTime\"\n  \
  \      },\n        \"endTimestamp\": {\n          \"@id\": \"prov:endedAtTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"DomainSpec\": {\n      \"@id\": \"kubevirt:VirtualHardware\",\n      \"@context\": {\n        \"cpu\": \"kubevirt:cpuConfig\",\n        \"memory\": \"kubevirt:memoryConfig\",\n        \"devices\": \"kubevirt:deviceConfig\",\n        \"firmware\": \"kubevirt:firmwareConfig\",\n        \"machine\": \"kubevirt:machineType\"\n      }\n    },\n\n    \"Disk\": {\n      \"@id\": \"kubevirt:VirtualDisk\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"bootOrder\": \"kubevirt:bootOrder\",\n        \"cache\": \"kubevirt:diskCache\"\n      }\n    },\n\n    \"Interface\": {\n      \"@id\": \"kubevirt:VirtualInterface\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"model\": \"kubevirt:nicModel\",\n        \"macAddress\": \"schema:identifier\"\n      }\n    },\n\n    \"Volume\": {\n      \"@id\": \"\
  kubevirt:StorageVolume\",\n      \"@context\": {\n        \"name\": \"schema:name\"\n      }\n    },\n\n    \"DataVolume\": {\n      \"@id\": \"kubevirt:DataVolume\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"namespace\": \"k8s:namespace\",\n        \"phase\": \"kubevirt:dvPhase\",\n        \"progress\": \"kubevirt:importProgress\",\n        \"claimName\": {\n          \"@id\": \"kubevirt:managedPVC\",\n          \"@type\": \"@id\"\n        },\n        \"creationTimestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"DataSource\": {\n      \"@id\": \"kubevirt:DataSource\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"namespace\": \"k8s:namespace\",\n        \"source\": {\n          \"@id\": \"kubevirt:cloneSource\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"StorageProfile\": {\n      \"@id\": \"kubevirt:StorageProfile\",\n      \"@context\"\
  : {\n        \"name\": \"schema:name\",\n        \"storageClass\": {\n          \"@id\": \"kubevirt:storageClass\",\n          \"@type\": \"@id\"\n        },\n        \"provisioner\": \"kubevirt:csiProvisioner\",\n        \"cloneStrategy\": \"kubevirt:cloneStrategy\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/kubevirt/refs/heads/main/json-ld/kubevirt-context.jsonld
tags:
- Cloud Native
- Incubating
- Kubernetes
- Migration
- Virtual Machines
- Virtualization
- JSON-LD
- Linked Data
- Semantic Web
---
