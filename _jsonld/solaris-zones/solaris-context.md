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
context_file: json-ld/solaris-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/solaris-zones/refs/heads/main/json-ld/solaris-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Solaris from Solaris Zones.
layout: jsonld
name: Solaris Context
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
  name: KernelZone
  type: ''
- container: ''
  name: ZoneInfo
  type: ''
- container: ''
  name: ZoneResource
  type: ''
- container: ''
  name: ZoneProperty
  type: ''
- container: ''
  name: ZoneStatistics
  type: ''
- container: ''
  name: ZoneMigration
  type: ''
- container: ''
  name: MigrationConnection
  type: ''
- container: ''
  name: ZoneEvacuation
  type: ''
- container: ''
  name: StatsStoreStatistic
  type: ''
- container: ''
  name: ZoneResult
  type: ''
- container: ''
  name: StateChange
  type: ''
property_count: 12
provider_name: Solaris Zones
provider_slug: solaris-zones
slug: solaris-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"solaris\": \"https://docs.oracle.com/schemas/solaris/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Zone\": {\n      \"@id\": \"solaris:Zone\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"brand\": \"solaris:brand\",\n        \"id\": {\n          \"@id\": \"solaris:zoneId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"uuid\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": \"solaris:zoneState\",\n        \"auxstate\": \"solaris:auxState\"\n      }\n    },\n\n    \"KernelZone\": {\n      \"@id\": \"solaris:KernelZone\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"brand\": \"solaris:brand\",\n        \"id\": {\n          \"@id\": \"solaris:zoneId\",\n          \"@type\": \"xsd:integer\"\
  \n        },\n        \"uuid\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": \"solaris:zoneState\"\n      }\n    },\n\n    \"ZoneInfo\": {\n      \"@id\": \"solaris:ZoneInfo\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"brand\": \"solaris:brand\",\n        \"id\": {\n          \"@id\": \"solaris:zoneId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"uuid\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"isGlobal\": {\n          \"@id\": \"solaris:isGlobal\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"ZoneResource\": {\n      \"@id\": \"solaris:ZoneResource\",\n      \"@context\": {\n        \"type\": \"solaris:resourceType\",\n        \"properties\": \"solaris:resourceProperties\",\n        \"parent\": \"solaris:parentResource\"\n      }\n    },\n\n    \"ZoneProperty\": {\n      \"@id\"\
  : \"solaris:ZoneProperty\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"value\": \"schema:value\",\n        \"type\": \"solaris:propertyValueType\",\n        \"listvalue\": \"solaris:listValue\",\n        \"complexvalue\": \"solaris:complexValue\"\n      }\n    },\n\n    \"ZoneStatistics\": {\n      \"@id\": \"solaris:ZoneStatistics\",\n      \"@context\": {\n        \"zonename\": \"schema:name\",\n        \"zone_id\": {\n          \"@id\": \"solaris:zoneId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"cpu_cap\": {\n          \"@id\": \"solaris:cpuCap\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"cpu_usage\": {\n          \"@id\": \"solaris:cpuUsage\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"memory_cap\": {\n          \"@id\": \"solaris:memoryCap\",\n          \"@type\": \"xsd:long\"\n        },\n        \"memory_usage\": {\n          \"@id\": \"solaris:memoryUsage\",\n          \"@type\": \"xsd:long\"\n\
  \        },\n        \"swap_cap\": {\n          \"@id\": \"solaris:swapCap\",\n          \"@type\": \"xsd:long\"\n        },\n        \"swap_usage\": {\n          \"@id\": \"solaris:swapUsage\",\n          \"@type\": \"xsd:long\"\n        },\n        \"nprocs\": {\n          \"@id\": \"solaris:processCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"nlwps\": {\n          \"@id\": \"solaris:threadCount\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"ZoneMigration\": {\n      \"@id\": \"solaris:ZoneMigration\",\n      \"@context\": {\n        \"zoneName\": \"schema:name\",\n        \"host\": \"solaris:migrationHost\",\n        \"type\": \"solaris:migrationType\",\n        \"state\": \"solaris:migrationState\",\n        \"cipher\": \"solaris:migrationCipher\"\n      }\n    },\n\n    \"MigrationConnection\": {\n      \"@id\": \"solaris:MigrationConnection\",\n      \"@context\": {\n        \"hostname\": \"schema:url\",\n        \"supportsMultipleZones\"\
  : {\n          \"@id\": \"solaris:supportsMultipleZones\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"supportsSolarisZones\": {\n          \"@id\": \"solaris:supportsSolarisZones\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"supportsSolaris10Zones\": {\n          \"@id\": \"solaris:supportsSolaris10Zones\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"ZoneEvacuation\": {\n      \"@id\": \"solaris:ZoneEvacuation\",\n      \"@context\": {\n        \"status\": \"solaris:evacuationStatus\",\n        \"returning\": {\n          \"@id\": \"solaris:returning\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"migrationResults\": \"solaris:migrationResults\"\n      }\n    },\n\n    \"StatsStoreStatistic\": {\n      \"@id\": \"solaris:StatsStoreStatistic\",\n      \"@context\": {\n        \"ssid\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"value\": \"schema:value\"\
  ,\n        \"timestamp\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"unit\": \"schema:unitCode\",\n        \"description\": \"schema:description\"\n      }\n    },\n\n    \"ZoneResult\": {\n      \"@id\": \"solaris:ZoneResult\",\n      \"@context\": {\n        \"code\": \"solaris:errorCode\",\n        \"message\": \"schema:description\",\n        \"stdout\": \"solaris:stdout\",\n        \"stderr\": \"solaris:stderr\"\n      }\n    },\n\n    \"StateChange\": {\n      \"@id\": \"solaris:StateChange\",\n      \"@context\": {\n        \"zone\": \"schema:name\",\n        \"oldstate\": \"solaris:previousState\",\n        \"newstate\": \"solaris:currentState\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/solaris-zones/refs/heads/main/json-ld/solaris-context.jsonld
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
