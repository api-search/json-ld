---
class_count: 0
classes: []
context_file: json-ld/vmware-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/vmware/refs/heads/main/json-ld/vmware-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Vmware from VMware.
layout: jsonld
name: Vmware Context
namespaces:
- prefix: vmw
  uri: https://vmware.com/ns/vsphere/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: VirtualMachine
  type: ''
- container: ''
  name: ESXiHost
  type: ''
- container: ''
  name: Datastore
  type: ''
- container: ''
  name: Cluster
  type: ''
- container: ''
  name: Datacenter
  type: ''
- container: ''
  name: Network
  type: ''
- container: ''
  name: VirtualDisk
  type: ''
- container: ''
  name: NetworkAdapter
  type: ''
- container: ''
  name: ResourcePool
  type: ''
- container: ''
  name: ContentLibrary
  type: ''
- container: ''
  name: StoragePolicy
  type: ''
- container: ''
  name: Tag
  type: ''
property_count: 12
provider_name: VMware
provider_slug: vmware
slug: vmware-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"vmw\": \"https://vmware.com/ns/vsphere/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"VirtualMachine\": {\n      \"@id\": \"vmw:VirtualMachine\",\n      \"@context\": {\n        \"vm\": \"vmw:vmIdentifier\",\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"powerState\": \"vmw:powerState\",\n        \"guestOS\": \"vmw:guestOS\",\n        \"instanceUuid\": {\n          \"@id\": \"vmw:instanceUuid\",\n          \"@type\": \"xsd:string\"\n        },\n        \"biosUuid\": {\n          \"@id\": \"vmw:biosUuid\",\n          \"@type\": \"xsd:string\"\n        },\n        \"hardwareVersion\": \"vmw:hardwareVersion\",\n        \"cpuCount\": {\n          \"@id\": \"vmw:cpuCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"coresPerSocket\"\
  : {\n          \"@id\": \"vmw:coresPerSocket\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"memorySizeMiB\": {\n          \"@id\": \"vmw:memorySizeMiB\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"bootType\": \"vmw:bootType\",\n        \"storageCommitted\": {\n          \"@id\": \"vmw:storageCommitted\",\n          \"@type\": \"xsd:long\"\n        },\n        \"storageUncommitted\": {\n          \"@id\": \"vmw:storageUncommitted\",\n          \"@type\": \"xsd:long\"\n        },\n        \"host\": {\n          \"@id\": \"vmw:placedOnHost\",\n          \"@type\": \"@id\"\n        },\n        \"cluster\": {\n          \"@id\": \"vmw:memberOfCluster\",\n          \"@type\": \"@id\"\n        },\n        \"datastore\": {\n          \"@id\": \"vmw:storedOnDatastore\",\n          \"@type\": \"@id\"\n        },\n        \"resourcePool\": {\n          \"@id\": \"vmw:assignedToResourcePool\",\n          \"@type\": \"@id\"\n        },\n        \"datacenter\": {\n\
  \          \"@id\": \"vmw:withinDatacenter\",\n          \"@type\": \"@id\"\n        },\n        \"folder\": {\n          \"@id\": \"vmw:withinFolder\",\n          \"@type\": \"@id\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"disks\": {\n          \"@id\": \"vmw:hasVirtualDisk\",\n          \"@container\": \"@set\"\n        },\n        \"nics\": {\n          \"@id\": \"vmw:hasNetworkAdapter\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"ESXiHost\": {\n      \"@id\": \"vmw:ESXiHost\",\n      \"@context\": {\n        \"host\": \"vmw:hostIdentifier\",\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"connectionState\": \"vmw:connectionState\",\n        \"powerState\": \"vmw:powerState\",\n        \"cluster\": {\n          \"@id\": \"vmw:memberOfCluster\",\n          \"@type\": \"@id\"\n        },\n      \
  \  \"datacenter\": {\n          \"@id\": \"vmw:withinDatacenter\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Datastore\": {\n      \"@id\": \"vmw:Datastore\",\n      \"@context\": {\n        \"datastore\": \"vmw:datastoreIdentifier\",\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": \"vmw:datastoreType\",\n        \"capacity\": {\n          \"@id\": \"vmw:capacityBytes\",\n          \"@type\": \"xsd:long\"\n        },\n        \"freeSpace\": {\n          \"@id\": \"vmw:freeSpaceBytes\",\n          \"@type\": \"xsd:long\"\n        },\n        \"accessible\": {\n          \"@id\": \"vmw:accessible\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"thinProvisioningSupported\": {\n          \"@id\": \"vmw:thinProvisioningSupported\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"multipleHostAccess\": {\n          \"@id\": \"vmw:multipleHostAccess\",\n          \"\
  @type\": \"xsd:boolean\"\n        },\n        \"datacenter\": {\n          \"@id\": \"vmw:withinDatacenter\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Cluster\": {\n      \"@id\": \"vmw:Cluster\",\n      \"@context\": {\n        \"cluster\": \"vmw:clusterIdentifier\",\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"haEnabled\": {\n          \"@id\": \"vmw:haEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"drsEnabled\": {\n          \"@id\": \"vmw:drsEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"resourcePool\": {\n          \"@id\": \"vmw:rootResourcePool\",\n          \"@type\": \"@id\"\n        },\n        \"datacenter\": {\n          \"@id\": \"vmw:withinDatacenter\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Datacenter\": {\n      \"@id\": \"vmw:Datacenter\",\n      \"@context\": {\n        \"datacenter\": \"vmw:datacenterIdentifier\"\
  ,\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"datastoreFolder\": {\n          \"@id\": \"vmw:datastoreFolder\",\n          \"@type\": \"@id\"\n        },\n        \"hostFolder\": {\n          \"@id\": \"vmw:hostFolder\",\n          \"@type\": \"@id\"\n        },\n        \"networkFolder\": {\n          \"@id\": \"vmw:networkFolder\",\n          \"@type\": \"@id\"\n        },\n        \"vmFolder\": {\n          \"@id\": \"vmw:vmFolder\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Network\": {\n      \"@id\": \"vmw:Network\",\n      \"@context\": {\n        \"network\": \"vmw:networkIdentifier\",\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": \"vmw:networkType\",\n        \"datacenter\": {\n          \"@id\": \"vmw:withinDatacenter\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"VirtualDisk\"\
  : {\n      \"@id\": \"vmw:VirtualDisk\",\n      \"@context\": {\n        \"label\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"controllerType\": \"vmw:controllerType\",\n        \"capacityBytes\": {\n          \"@id\": \"vmw:capacityBytes\",\n          \"@type\": \"xsd:long\"\n        },\n        \"vmdkFile\": {\n          \"@id\": \"vmw:vmdkFile\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"NetworkAdapter\": {\n      \"@id\": \"vmw:NetworkAdapter\",\n      \"@context\": {\n        \"label\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"adapterType\": \"vmw:adapterType\",\n        \"macAddress\": {\n          \"@id\": \"vmw:macAddress\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": \"vmw:connectionState\",\n        \"network\": {\n          \"@id\": \"vmw:connectedToNetwork\",\n          \"@type\": \"@id\"\n        }\n    \
  \  }\n    },\n\n    \"ResourcePool\": {\n      \"@id\": \"vmw:ResourcePool\",\n      \"@context\": {\n        \"resourcePool\": \"vmw:resourcePoolIdentifier\",\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"cluster\": {\n          \"@id\": \"vmw:memberOfCluster\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"ContentLibrary\": {\n      \"@id\": \"vmw:ContentLibrary\",\n      \"@context\": {\n        \"id\": \"vmw:libraryIdentifier\",\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": \"vmw:libraryType\",\n        \"creationTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModifiedTime\": {\n          \"@id\": \"dcterms:modified\",\n    \
  \      \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"StoragePolicy\": {\n      \"@id\": \"vmw:StoragePolicy\",\n      \"@context\": {\n        \"policy\": \"vmw:policyIdentifier\",\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Tag\": {\n      \"@id\": \"vmw:Tag\",\n      \"@context\": {\n        \"tagId\": \"vmw:tagIdentifier\",\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"category\": {\n          \"@id\": \"vmw:belongsToCategory\",\n          \"@type\": \"@id\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/vmware/refs/heads/main/json-ld/vmware-context.jsonld
tags:
- Cloud Computing
- Container Management
- Hybrid Cloud
- Infrastructure
- Virtualization
- JSON-LD
- Linked Data
- Semantic Web
---
