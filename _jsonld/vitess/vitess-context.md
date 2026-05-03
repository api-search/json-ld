---
api_specs:
- filename: vitess-vtadmin-openapi.yml
  format: yaml
  label: Vitess VTAdmin API
  slug: vtadmin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vitess/refs/heads/main/openapi/vitess-vtadmin-openapi.yml
class_count: 0
classes: []
context_file: json-ld/vitess-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/vitess/refs/heads/main/json-ld/vitess-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Vitess from Vitess.
layout: jsonld
name: Vitess Context
namespaces:
- prefix: vitess
  uri: https://vitess.io/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
properties:
- container: ''
  name: Cluster
  type: ''
- container: ''
  name: Tablet
  type: ''
- container: ''
  name: TabletAlias
  type: ''
- container: ''
  name: Keyspace
  type: ''
- container: ''
  name: Shard
  type: ''
- container: ''
  name: VSchema
  type: ''
- container: ''
  name: Vindex
  type: ''
- container: ''
  name: Workflow
  type: ''
- container: ''
  name: Backup
  type: ''
property_count: 9
provider_name: Vitess
provider_slug: vitess
slug: vitess-context
source_filename: vitess-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"vitess\": \"https://vitess.io/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n\n    \"Cluster\": {\n      \"@id\": \"vitess:Cluster\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"schema:identifier\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\"\n        }\n      }\n    },\n\n    \"Tablet\": {\n      \"@id\": \"vitess:Tablet\",\n      \"@context\": {\n        \"alias\": {\n          \"@id\": \"vitess:alias\",\n          \"@type\": \"@id\"\n        },\n        \"hostname\": {\n          \"@id\": \"schema:hostName\"\n        },\n        \"keyspace\": {\n          \"@id\": \"vitess:keyspace\"\n        },\n        \"shard\": {\n          \"@id\": \"vitess:shard\"\n        },\n        \"type\": {\n          \"@id\": \"vitess:tabletType\"\
  \n        },\n        \"mysql_hostname\": {\n          \"@id\": \"vitess:mysqlHostname\"\n        },\n        \"mysql_port\": {\n          \"@id\": \"vitess:mysqlPort\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"tags\": {\n          \"@id\": \"vitess:tags\"\n        }\n      }\n    },\n\n    \"TabletAlias\": {\n      \"@id\": \"vitess:TabletAlias\",\n      \"@context\": {\n        \"cell\": {\n          \"@id\": \"vitess:cell\"\n        },\n        \"uid\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Keyspace\": {\n      \"@id\": \"vitess:Keyspace\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"sharding_column_name\": {\n          \"@id\": \"vitess:shardingColumnName\"\n        },\n        \"sharding_column_type\": {\n          \"@id\": \"vitess:shardingColumnType\"\n        }\n      }\n    },\n\n    \"Shard\": {\n      \"@id\": \"vitess:Shard\"\
  ,\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"keyspace\": {\n          \"@id\": \"vitess:keyspace\"\n        },\n        \"primary_alias\": {\n          \"@id\": \"vitess:primaryAlias\",\n          \"@type\": \"@id\"\n        },\n        \"primary_term_start_time\": {\n          \"@id\": \"vitess:primaryTermStartTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"is_primary_serving\": {\n          \"@id\": \"vitess:isPrimaryServing\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"VSchema\": {\n      \"@id\": \"vitess:VSchema\",\n      \"@context\": {\n        \"sharded\": {\n          \"@id\": \"vitess:sharded\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"vindexes\": {\n          \"@id\": \"vitess:vindexes\"\n        },\n        \"tables\": {\n          \"@id\": \"vitess:tables\"\n        }\n      }\n    },\n\n    \"Vindex\": {\n      \"@id\": \"vitess:Vindex\",\n\
  \      \"@context\": {\n        \"type\": {\n          \"@id\": \"vitess:vindexType\"\n        },\n        \"params\": {\n          \"@id\": \"vitess:vindexParams\"\n        },\n        \"owner\": {\n          \"@id\": \"vitess:vindexOwner\"\n        }\n      }\n    },\n\n    \"Workflow\": {\n      \"@id\": \"vitess:Workflow\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"workflow_type\": {\n          \"@id\": \"vitess:workflowType\"\n        },\n        \"source\": {\n          \"@id\": \"vitess:source\"\n        },\n        \"target\": {\n          \"@id\": \"vitess:target\"\n        },\n        \"max_v_replication_lag\": {\n          \"@id\": \"vitess:maxReplicationLag\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Backup\": {\n      \"@id\": \"vitess:Backup\",\n      \"@context\": {\n        \"keyspace\": {\n          \"@id\": \"vitess:keyspace\"\n        },\n        \"shard\": {\n          \"\
  @id\": \"vitess:shard\"\n        },\n        \"tablet_alias\": {\n          \"@id\": \"vitess:tabletAlias\",\n          \"@type\": \"@id\"\n        },\n        \"time\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"engine\": {\n          \"@id\": \"vitess:backupEngine\"\n        },\n        \"status\": {\n          \"@id\": \"vitess:backupStatus\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/vitess/refs/heads/main/json-ld/vitess-context.jsonld
tags:
- Cloud Native
- CNCF
- Database
- Distributed Systems
- Graduated
- MySQL
- Sharding
- JSON-LD
- Linked Data
- Semantic Web
---
