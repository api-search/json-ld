---
api_specs:
- filename: solaris-zones-management-openapi.yml
  format: yaml
  label: Solaris Zones Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/solaris-zones/refs/heads/main/openapi/solaris-zones-management-openapi.yml
- filename: solaris-zone-configuration-openapi.yml
  format: yaml
  label: Zone Configuration API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/solaris-zones/refs/heads/main/openapi/solaris-zone-configuration-openapi.yml
- filename: solaris-zone-administration-openapi.yml
  format: yaml
  label: Zone Administration API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/solaris-zones/refs/heads/main/openapi/solaris-zone-administration-openapi.yml
- filename: solaris-zone-monitoring-openapi.yml
  format: yaml
  label: Zone Monitoring API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/solaris-zones/refs/heads/main/openapi/solaris-zone-monitoring-openapi.yml
- filename: solaris-rad-zonemgr-openapi.yml
  format: yaml
  label: RAD Zone Management REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/solaris-zones/refs/heads/main/openapi/solaris-rad-zonemgr-openapi.yml
- filename: solaris-zone-stats-openapi.yml
  format: yaml
  label: Zones Monitoring Statistics API (libzonestat)
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/solaris-zones/refs/heads/main/openapi/solaris-zone-stats-openapi.yml
- filename: solaris-kernel-zones-openapi.yml
  format: yaml
  label: Oracle Solaris Kernel Zones API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/solaris-zones/refs/heads/main/openapi/solaris-kernel-zones-openapi.yml
- filename: solaris-statsstore-openapi.yml
  format: yaml
  label: Oracle Solaris StatsStore and Analytics API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/solaris-zones/refs/heads/main/openapi/solaris-statsstore-openapi.yml
- filename: solaris-unified-archives-openapi.yml
  format: yaml
  label: Oracle Solaris Unified Archives Zones API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/solaris-zones/refs/heads/main/openapi/solaris-unified-archives-openapi.yml
class_count: 0
classes: []
context_file: json-ld/solaris-zones-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/solaris-zones/refs/heads/main/json-ld/solaris-zones-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Solaris Zones from Solaris Zones.
layout: jsonld
name: Solaris Zones Context
namespaces:
- prefix: solaris
  uri: https://docs.oracle.com/schemas/solaris/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Zone
  type: ''
- container: ''
  name: ZoneConfiguration
  type: ''
- container: ''
  name: AnetResource
  type: ''
- container: ''
  name: CappedCpuResource
  type: ''
- container: ''
  name: CappedMemoryResource
  type: ''
- container: ''
  name: DedicatedCpuResource
  type: ''
- container: ''
  name: DeviceResource
  type: ''
- container: ''
  name: FsResource
  type: ''
- container: ''
  name: DatasetResource
  type: ''
- container: ''
  name: NetResource
  type: ''
- container: ''
  name: StateChange
  type: ''
- container: ''
  name: MigrationProgress
  type: ''
- container: ''
  name: EvacuationResult
  type: ''
- container: ''
  name: ZoneManager
  type: ''
- container: ''
  name: ZoneInfo
  type: ''
property_count: 15
provider_name: Solaris Zones
provider_slug: solaris-zones
slug: solaris-zones-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"solaris\": \"https://docs.oracle.com/schemas/solaris/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Zone\": {\n      \"@id\": \"solaris:Zone\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"uuid\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"brand\": \"solaris:brand\",\n        \"state\": \"solaris:zoneState\",\n        \"zonepath\": \"solaris:zonepath\",\n        \"autoboot\": {\n          \"@id\": \"solaris:autoboot\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"ipType\": \"solaris:ipType\",\n        \"id\": {\n          \"@id\": \"solaris:zoneId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"isGlobal\": {\n          \"@id\": \"solaris:isGlobal\",\n          \"@type\": \"xsd:boolean\"\n        }\n\
  \      }\n    },\n\n    \"ZoneConfiguration\": {\n      \"@id\": \"solaris:ZoneConfiguration\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"brand\": \"solaris:brand\",\n        \"zonepath\": \"solaris:zonepath\",\n        \"autoboot\": {\n          \"@id\": \"solaris:autoboot\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"limitpriv\": \"solaris:limitpriv\",\n        \"schedulingClass\": \"solaris:schedulingClass\",\n        \"maxLwps\": {\n          \"@id\": \"solaris:maxLwps\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"maxProcesses\": {\n          \"@id\": \"solaris:maxProcesses\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"AnetResource\": {\n      \"@id\": \"solaris:AnetResource\",\n      \"@context\": {\n        \"linkname\": \"solaris:linkname\",\n        \"lowerLink\": \"solaris:lowerLink\",\n        \"macAddress\": \"solaris:macAddress\",\n        \"vlanId\": {\n          \"@id\": \"solaris:vlanId\"\
  ,\n          \"@type\": \"xsd:integer\"\n        },\n        \"mtu\": {\n          \"@id\": \"solaris:mtu\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"defrouter\": \"solaris:defrouter\",\n        \"allowedAddress\": \"solaris:allowedAddress\",\n        \"linkProtection\": \"solaris:linkProtection\"\n      }\n    },\n\n    \"CappedCpuResource\": {\n      \"@id\": \"solaris:CappedCpuResource\",\n      \"@context\": {\n        \"ncpus\": {\n          \"@id\": \"solaris:ncpus\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"CappedMemoryResource\": {\n      \"@id\": \"solaris:CappedMemoryResource\",\n      \"@context\": {\n        \"physical\": \"solaris:physicalMemory\",\n        \"swap\": \"solaris:swapMemory\",\n        \"locked\": \"solaris:lockedMemory\"\n      }\n    },\n\n    \"DedicatedCpuResource\": {\n      \"@id\": \"solaris:DedicatedCpuResource\",\n      \"@context\": {\n        \"ncpus\": \"solaris:dedicatedNcpus\",\n        \"importance\"\
  : {\n          \"@id\": \"solaris:importance\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"DeviceResource\": {\n      \"@id\": \"solaris:DeviceResource\",\n      \"@context\": {\n        \"match\": \"solaris:deviceMatch\",\n        \"allowPartition\": {\n          \"@id\": \"solaris:allowPartition\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"allowRawIo\": {\n          \"@id\": \"solaris:allowRawIo\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"FsResource\": {\n      \"@id\": \"solaris:FsResource\",\n      \"@context\": {\n        \"dir\": \"solaris:mountPoint\",\n        \"special\": \"solaris:fsSpecial\",\n        \"type\": \"solaris:fsType\"\n      }\n    },\n\n    \"DatasetResource\": {\n      \"@id\": \"solaris:DatasetResource\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"alias\": \"solaris:datasetAlias\"\n      }\n    },\n\n    \"NetResource\": {\n      \"@id\": \"solaris:NetResource\"\
  ,\n      \"@context\": {\n        \"address\": \"solaris:networkAddress\",\n        \"physical\": \"solaris:physicalInterface\",\n        \"defrouter\": \"solaris:defrouter\"\n      }\n    },\n\n    \"StateChange\": {\n      \"@id\": \"solaris:StateChange\",\n      \"@context\": {\n        \"zone\": \"schema:name\",\n        \"oldState\": \"solaris:oldState\",\n        \"newState\": \"solaris:newState\"\n      }\n    },\n\n    \"MigrationProgress\": {\n      \"@id\": \"solaris:MigrationProgress\",\n      \"@context\": {\n        \"zone\": \"schema:name\",\n        \"operation\": \"solaris:migrationOperation\",\n        \"message\": \"schema:description\",\n        \"percentComplete\": {\n          \"@id\": \"solaris:percentComplete\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"EvacuationResult\": {\n      \"@id\": \"solaris:EvacuationResult\",\n      \"@context\": {\n        \"status\": \"solaris:evacuationStatus\",\n        \"returning\": {\n          \"\
  @id\": \"solaris:returning\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"zoneCount\": {\n          \"@id\": \"solaris:zoneCount\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"ZoneManager\": {\n      \"@id\": \"solaris:ZoneManager\",\n      \"@context\": {\n        \"evacuationState\": \"solaris:evacuationState\"\n      }\n    },\n\n    \"ZoneInfo\": {\n      \"@id\": \"solaris:ZoneInfo\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"brand\": \"solaris:brand\",\n        \"id\": {\n          \"@id\": \"solaris:zoneId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"uuid\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"isGlobal\": {\n          \"@id\": \"solaris:isGlobal\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/solaris-zones/refs/heads/main/json-ld/solaris-zones-context.jsonld
tags:
- Containers
- Kernel Zones
- Operating Systems
- Oracle
- RAD
- Resource Management
- Solaris
- StatsStore
- Virtualization
- Zones
- JSON-LD
- Linked Data
- Semantic Web
---
