---
api_specs:
- filename: yugabytedb-aeon-openapi.yml
  format: yaml
  label: YugabyteDB Aeon REST API
  slug: aeon
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/yugabytedb/refs/heads/main/openapi/yugabytedb-aeon-openapi.yml
- filename: yugabytedb-anywhere-v1-universes.yaml
  format: yaml
  label: YugabyteDB Anywhere REST API
  slug: anywhere
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/yugabytedb/refs/heads/main/openapi/yugabytedb-anywhere-v1-universes.yaml
class_count: 0
classes: []
context_file: json-ld/yugabytedb-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/yugabytedb/refs/heads/main/json-ld/yugabytedb-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Yugabytedb from YugabyteDB.
layout: jsonld
name: Yugabytedb Context
namespaces:
- prefix: yugabytedb
  uri: https://yugabyte.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: hydra
  uri: http://www.w3.org/ns/hydra/core#
properties:
- container: ''
  name: Cluster
  type: ''
- container: ''
  name: Universe
  type: ''
- container: ''
  name: CloudInfo
  type: ''
- container: ''
  name: ClusterInfo
  type: ''
- container: ''
  name: NodeInfo
  type: ''
- container: ''
  name: ClusterEndpoint
  type: ''
- container: ''
  name: BackupConfig
  type: ''
- container: ''
  name: Backup
  type: ''
- container: ''
  name: MaintenanceWindow
  type: ''
- container: ''
  name: AllowList
  type: ''
- container: ''
  name: Provider
  type: ''
- container: ''
  name: Region
  type: ''
- container: ''
  name: AvailabilityZone
  type: ''
- container: ''
  name: ReadReplica
  type: ''
- container: ''
  name: Customer
  type: ''
property_count: 15
provider_name: YugabyteDB
provider_slug: yugabytedb
slug: yugabytedb-context
source_filename: yugabytedb-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"yugabytedb\": \"https://yugabyte.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"hydra\": \"http://www.w3.org/ns/hydra/core#\",\n\n    \"Cluster\": {\n      \"@id\": \"yugabytedb:Cluster\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"deployment_model\": {\n          \"@id\": \"yugabytedb:deploymentModel\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": {\n          \"@id\": \"yugabytedb:clusterState\",\n          \"@type\": \"xsd:string\"\n        },\n        \"yugabytedb_version\": {\n          \"@id\": \"yugabytedb:softwareVersion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"cloud_info\": {\n          \"@id\": \"yugabytedb:cloudInfo\"\n        },\n        \"cluster_info\": {\n          \"@id\": \"yugabytedb:clusterInfo\"\
  \n        },\n        \"endpoints\": {\n          \"@id\": \"yugabytedb:endpoints\",\n          \"@container\": \"@set\"\n        },\n        \"backup_config\": {\n          \"@id\": \"yugabytedb:backupConfig\"\n        },\n        \"maintenance_window\": {\n          \"@id\": \"yugabytedb:maintenanceWindow\"\n        },\n        \"allow_list_ids\": {\n          \"@id\": \"yugabytedb:allowListIds\",\n          \"@container\": \"@set\"\n        },\n        \"read_replicas\": {\n          \"@id\": \"yugabytedb:readReplicas\",\n          \"@container\": \"@set\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Universe\": {\n      \"@id\": \"yugabytedb:Universe\",\n      \"@context\": {\n        \"universeUUID\": \"@id\",\n        \"name\": \"schema:name\",\n      \
  \  \"creationDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"universeDetails\": {\n          \"@id\": \"yugabytedb:universeDetails\"\n        },\n        \"taskUUID\": {\n          \"@id\": \"yugabytedb:currentTask\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"CloudInfo\": {\n      \"@id\": \"yugabytedb:CloudInfo\",\n      \"@context\": {\n        \"code\": {\n          \"@id\": \"yugabytedb:cloudProvider\",\n          \"@type\": \"xsd:string\"\n        },\n        \"region\": {\n          \"@id\": \"yugabytedb:cloudRegion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"multi_region\": {\n          \"@id\": \"yugabytedb:isMultiRegion\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"regions\": {\n          \"@id\": \"yugabytedb:regions\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"ClusterInfo\": {\n      \"@id\": \"yugabytedb:ClusterInfo\"\
  ,\n      \"@context\": {\n        \"num_nodes\": {\n          \"@id\": \"yugabytedb:nodeCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"replication_factor\": {\n          \"@id\": \"yugabytedb:replicationFactor\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"fault_tolerance\": {\n          \"@id\": \"yugabytedb:faultTolerance\",\n          \"@type\": \"xsd:string\"\n        },\n        \"cluster_tier\": {\n          \"@id\": \"yugabytedb:clusterTier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"enable_ysql\": {\n          \"@id\": \"yugabytedb:enableYSQL\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"enable_ycql\": {\n          \"@id\": \"yugabytedb:enableYCQL\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"NodeInfo\": {\n      \"@id\": \"yugabytedb:NodeInfo\",\n      \"@context\": {\n        \"num_cores\": {\n          \"@id\": \"yugabytedb:cpuCores\",\n          \"@type\": \"xsd:integer\"\
  \n        },\n        \"memory_mb\": {\n          \"@id\": \"yugabytedb:memoryMb\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"disk_size_gb\": {\n          \"@id\": \"yugabytedb:diskSizeGb\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"instance_type\": {\n          \"@id\": \"yugabytedb:instanceType\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"ClusterEndpoint\": {\n      \"@id\": \"yugabytedb:ClusterEndpoint\",\n      \"@context\": {\n        \"host\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"xsd:string\"\n        },\n        \"port\": {\n          \"@id\": \"schema:Integer\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"api_type\": {\n          \"@id\": \"yugabytedb:apiType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"accessibility_type\": {\n          \"@id\": \"yugabytedb:accessibilityType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"region\": {\n\
  \          \"@id\": \"yugabytedb:endpointRegion\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"BackupConfig\": {\n      \"@id\": \"yugabytedb:BackupConfig\",\n      \"@context\": {\n        \"schedule_enabled\": {\n          \"@id\": \"yugabytedb:scheduleEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"frequency_in_hours\": {\n          \"@id\": \"yugabytedb:backupFrequencyHours\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"retention_period_in_days\": {\n          \"@id\": \"yugabytedb:retentionDays\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"storage_location\": {\n          \"@id\": \"yugabytedb:storageLocation\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Backup\": {\n      \"@id\": \"yugabytedb:Backup\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"state\": {\n          \"@id\": \"yugabytedb:backupState\",\n          \"@type\": \"xsd:string\"\n        },\n\
  \        \"backup_type\": {\n          \"@id\": \"yugabytedb:backupType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"retention_period_in_days\": {\n          \"@id\": \"yugabytedb:retentionDays\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"cluster_id\": {\n          \"@id\": \"yugabytedb:cluster\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"expiry_time\": {\n          \"@id\": \"yugabytedb:expiresAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"MaintenanceWindow\": {\n      \"@id\": \"yugabytedb:MaintenanceWindow\",\n      \"@context\": {\n        \"day_of_week\": {\n          \"@id\": \"schema:dayOfWeek\",\n          \"@type\": \"xsd:string\"\n        },\n        \"start_time\": {\n          \"@id\": \"yugabytedb:windowStartTime\",\n          \"@type\": \"xsd:string\"\n        },\n        \"\
  duration_in_hours\": {\n          \"@id\": \"yugabytedb:windowDurationHours\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"AllowList\": {\n      \"@id\": \"yugabytedb:AllowList\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"allow_list\": {\n          \"@id\": \"yugabytedb:cidrEntries\",\n          \"@container\": \"@set\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Provider\": {\n      \"@id\": \"yugabytedb:Provider\",\n      \"@context\": {\n        \"uuid\": \"@id\",\n        \"name\": \"schema:name\",\n        \"code\": {\n          \"@id\": \"yugabytedb:providerCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"regions\": {\n          \"@id\": \"yugabytedb:regions\",\n          \"@container\": \"@set\"\n        }\n      }\n\
  \    },\n\n    \"Region\": {\n      \"@id\": \"yugabytedb:Region\",\n      \"@context\": {\n        \"uuid\": \"@id\",\n        \"name\": \"schema:name\",\n        \"code\": {\n          \"@id\": \"yugabytedb:regionCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"zones\": {\n          \"@id\": \"yugabytedb:availabilityZones\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"AvailabilityZone\": {\n      \"@id\": \"yugabytedb:AvailabilityZone\",\n      \"@context\": {\n        \"uuid\": \"@id\",\n        \"name\": \"schema:name\",\n        \"code\": {\n          \"@id\": \"yugabytedb:zoneCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subnet\": {\n          \"@id\": \"yugabytedb:subnet\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"ReadReplica\": {\n      \"@id\": \"yugabytedb:ReadReplica\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"state\": {\n          \"@id\": \"yugabytedb:replicaState\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"cloud_info\": {\n          \"@id\": \"yugabytedb:cloudInfo\"\n        },\n        \"cluster_info\": {\n          \"@id\": \"yugabytedb:clusterInfo\"\n        },\n        \"endpoints\": {\n          \"@id\": \"yugabytedb:endpoints\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Customer\": {\n      \"@id\": \"yugabytedb:Customer\",\n      \"@context\": {\n        \"uuid\": \"@id\",\n        \"name\": \"schema:name\",\n        \"code\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"creationDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/yugabytedb/refs/heads/main/json-ld/yugabytedb-context.jsonld
tags:
- Cloud Database
- Database
- DBaaS
- Distributed SQL
- PostgreSQL
- JSON-LD
- Linked Data
- Semantic Web
---
