---
api_specs:
- filename: cockroachdb-cloud-api-openapi.yml
  format: yaml
  label: CockroachDB Cloud API
  slug: cloud-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cockroachdb/refs/heads/main/openapi/cockroachdb-cloud-api-openapi.yml
- filename: cockroachdb-cluster-api-openapi.yml
  format: yaml
  label: CockroachDB Cluster API
  slug: cluster-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cockroachdb/refs/heads/main/openapi/cockroachdb-cluster-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/cockroachdb-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cockroachdb/refs/heads/main/json-ld/cockroachdb-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cockroachdb from CockroachDB.
layout: jsonld
name: Cockroachdb Context
namespaces:
- prefix: cockroachdb
  uri: https://cockroachlabs.com/vocab/
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
  name: Region
  type: ''
- container: ''
  name: Organization
  type: ''
- container: ''
  name: Folder
  type: ''
- container: ''
  name: ServiceAccount
  type: ''
- container: ''
  name: ApiKey
  type: ''
- container: ''
  name: SQLUser
  type: ''
- container: ''
  name: Database
  type: ''
- container: ''
  name: AllowlistEntry
  type: ''
- container: ''
  name: Invoice
  type: ''
- container: ''
  name: BackupConfiguration
  type: ''
- container: ''
  name: MaintenanceWindow
  type: ''
- container: ''
  name: ClusterNode
  type: ''
- container: ''
  name: Session
  type: ''
property_count: 14
provider_name: CockroachDB
provider_slug: cockroachdb
slug: cockroachdb-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cockroachdb\": \"https://cockroachlabs.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"hydra\": \"http://www.w3.org/ns/hydra/core#\",\n\n    \"Cluster\": {\n      \"@id\": \"cockroachdb:Cluster\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"cloud_provider\": {\n          \"@id\": \"cockroachdb:cloudProvider\",\n          \"@type\": \"xsd:string\"\n        },\n        \"cockroach_version\": {\n          \"@id\": \"cockroachdb:cockroachVersion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"plan\": {\n          \"@id\": \"cockroachdb:plan\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": {\n          \"@id\": \"cockroachdb:state\",\n          \"@type\": \"xsd:string\"\n   \
  \     },\n        \"operation_status\": {\n          \"@id\": \"cockroachdb:operationStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"regions\": {\n          \"@id\": \"cockroachdb:regions\",\n          \"@container\": \"@set\"\n        },\n        \"config\": {\n          \"@id\": \"cockroachdb:config\"\n        },\n        \"creator_id\": {\n          \"@id\": \"dcterms:creator\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"deleted_at\": {\n          \"@id\": \"cockroachdb:deletedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"sql_dns\": {\n          \"@id\": \"cockroachdb:sqlDns\",\n          \"@type\": \"@id\"\n        },\n        \"upgrade_status\": {\n          \"@id\": \"cockroachdb:upgradeStatus\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"account_id\": {\n          \"@id\": \"cockroachdb:accountId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"parent_id\": {\n          \"@id\": \"cockroachdb:parentId\",\n          \"@type\": \"@id\"\n        },\n        \"labels\": {\n          \"@id\": \"schema:additionalProperty\"\n        },\n        \"delete_protection\": {\n          \"@id\": \"cockroachdb:deleteProtection\",\n          \"@type\": \"xsd:string\"\n        },\n        \"egress_traffic_policy\": {\n          \"@id\": \"cockroachdb:egressTrafficPolicy\",\n          \"@type\": \"xsd:string\"\n        },\n        \"network_visibility\": {\n          \"@id\": \"cockroachdb:networkVisibility\",\n          \"@type\": \"xsd:string\"\n        },\n        \"cidr_range\": {\n          \"@id\": \"cockroachdb:cidrRange\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Region\": {\n      \"@id\": \"cockroachdb:Region\",\n     \
  \ \"@context\": {\n        \"name\": \"schema:name\",\n        \"sql_dns\": {\n          \"@id\": \"cockroachdb:sqlDns\",\n          \"@type\": \"@id\"\n        },\n        \"node_count\": {\n          \"@id\": \"cockroachdb:nodeCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"primary\": {\n          \"@id\": \"cockroachdb:isPrimary\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Organization\": {\n      \"@id\": \"cockroachdb:Organization\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"label\": \"schema:alternateName\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Folder\": {\n      \"@id\": \"cockroachdb:Folder\",\n      \"@context\": {\n        \"resource_id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"parent_id\": {\n          \"@id\": \"cockroachdb:parentId\",\n       \
  \   \"@type\": \"@id\"\n        },\n        \"path\": {\n          \"@id\": \"cockroachdb:path\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"ServiceAccount\": {\n      \"@id\": \"cockroachdb:ServiceAccount\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"creator_id\": {\n          \"@id\": \"dcterms:creator\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ApiKey\": {\n      \"@id\": \"cockroachdb:ApiKey\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"service_account_id\": {\n          \"@id\": \"cockroachdb:serviceAccount\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\
  \n        }\n      }\n    },\n\n    \"SQLUser\": {\n      \"@id\": \"cockroachdb:SQLUser\",\n      \"@context\": {\n        \"name\": \"schema:name\"\n      }\n    },\n\n    \"Database\": {\n      \"@id\": \"cockroachdb:Database\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"table_count\": {\n          \"@id\": \"cockroachdb:tableCount\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"AllowlistEntry\": {\n      \"@id\": \"cockroachdb:AllowlistEntry\",\n      \"@context\": {\n        \"cidr_ip\": {\n          \"@id\": \"cockroachdb:cidrIp\",\n          \"@type\": \"xsd:string\"\n        },\n        \"cidr_mask\": {\n          \"@id\": \"cockroachdb:cidrMask\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"name\": \"schema:name\",\n        \"ui\": {\n          \"@id\": \"cockroachdb:allowsUI\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"sql\": {\n          \"@id\": \"cockroachdb:allowsSQL\",\n        \
  \  \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Invoice\": {\n      \"@id\": \"cockroachdb:Invoice\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"status\": {\n          \"@id\": \"cockroachdb:invoiceStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"period_start\": {\n          \"@id\": \"schema:temporalCoverage\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"period_end\": {\n          \"@id\": \"cockroachdb:periodEnd\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"total_amount\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"BackupConfiguration\": {\n      \"@id\": \"cockroachdb:BackupConfiguration\",\n      \"@context\": {\n        \"cluster_id\": {\n          \"@id\": \"cockroachdb:cluster\",\n          \"@type\": \"@id\"\n        },\n        \"frequency_minutes\": {\n          \"@id\": \"cockroachdb:frequencyMinutes\",\n      \
  \    \"@type\": \"xsd:integer\"\n        },\n        \"retention_days\": {\n          \"@id\": \"cockroachdb:retentionDays\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"MaintenanceWindow\": {\n      \"@id\": \"cockroachdb:MaintenanceWindow\",\n      \"@context\": {\n        \"day_of_week\": {\n          \"@id\": \"cockroachdb:dayOfWeek\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"start_hour\": {\n          \"@id\": \"cockroachdb:startHour\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"ClusterNode\": {\n      \"@id\": \"cockroachdb:ClusterNode\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"region_name\": {\n          \"@id\": \"cockroachdb:region\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"cockroachdb:nodeStatus\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Session\": {\n      \"@id\": \"cockroachdb:Session\"\
  ,\n      \"@context\": {\n        \"id\": \"@id\",\n        \"username\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"client_address\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"xsd:string\"\n        },\n        \"application_name\": {\n          \"@id\": \"schema:applicationCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"start\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"node_id\": {\n          \"@id\": \"cockroachdb:node\",\n          \"@type\": \"@id\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cockroachdb/refs/heads/main/json-ld/cockroachdb-context.jsonld
tags:
- Cluster Management
- Cloud
- Database
- Distributed SQL
- Infrastructure
- PostgreSQL Compatible
- SQL
- JSON-LD
- Linked Data
- Semantic Web
---
