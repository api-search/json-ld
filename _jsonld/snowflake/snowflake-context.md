---
class_count: 0
classes: []
context_file: json-ld/snowflake-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/snowflake/refs/heads/main/json-ld/snowflake-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Snowflake from Snowflake.
layout: jsonld
name: Snowflake Context
namespaces:
- prefix: snowflake
  uri: https://docs.snowflake.com/en/developer-guide/snowflake-rest-api/reference/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: dc
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Warehouse
  type: ''
- container: ''
  name: Database
  type: ''
- container: ''
  name: Statement
  type: ''
- container: ''
  name: ResultSet
  type: ''
property_count: 4
provider_name: Snowflake
provider_slug: snowflake
slug: snowflake-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"snowflake\": \"https://docs.snowflake.com/en/developer-guide/snowflake-rest-api/reference/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"dc\": \"http://purl.org/dc/terms/\",\n    \"Warehouse\": {\n      \"@id\": \"snowflake:warehouse\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"warehouse_type\": {\n          \"@id\": \"snowflake:warehouse#warehouse_type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"warehouse_size\": {\n          \"@id\": \"snowflake:warehouse#warehouse_size\",\n          \"@type\": \"xsd:string\"\n        },\n        \"max_cluster_count\": {\n          \"@id\": \"snowflake:warehouse#max_cluster_count\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"min_cluster_count\"\
  : {\n          \"@id\": \"snowflake:warehouse#min_cluster_count\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"scaling_policy\": {\n          \"@id\": \"snowflake:warehouse#scaling_policy\",\n          \"@type\": \"xsd:string\"\n        },\n        \"auto_suspend\": {\n          \"@id\": \"snowflake:warehouse#auto_suspend\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"auto_resume\": {\n          \"@id\": \"snowflake:warehouse#auto_resume\",\n          \"@type\": \"xsd:string\"\n        },\n        \"resource_monitor\": {\n          \"@id\": \"snowflake:warehouse#resource_monitor\",\n          \"@type\": \"xsd:string\"\n        },\n        \"comment\": {\n          \"@id\": \"rdfs:comment\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": {\n          \"@id\": \"snowflake:warehouse#state\",\n          \"@type\": \"xsd:string\"\n        },\n        \"owner\": {\n          \"@id\": \"schema:owner\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"created_on\": {\n          \"@id\": \"dc:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_on\": {\n          \"@id\": \"dc:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"resumed_on\": {\n          \"@id\": \"snowflake:warehouse#resumed_on\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"enable_query_acceleration\": {\n          \"@id\": \"snowflake:warehouse#enable_query_acceleration\",\n          \"@type\": \"xsd:string\"\n        },\n        \"query_acceleration_max_scale_factor\": {\n          \"@id\": \"snowflake:warehouse#query_acceleration_max_scale_factor\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"max_concurrency_level\": {\n          \"@id\": \"snowflake:warehouse#max_concurrency_level\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"statement_queued_timeout_in_seconds\": {\n          \"@id\": \"snowflake:warehouse#statement_queued_timeout_in_seconds\"\
  ,\n          \"@type\": \"xsd:integer\"\n        },\n        \"statement_timeout_in_seconds\": {\n          \"@id\": \"snowflake:warehouse#statement_timeout_in_seconds\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n    \"Database\": {\n      \"@id\": \"snowflake:database\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"kind\": {\n          \"@id\": \"snowflake:database#kind\",\n          \"@type\": \"xsd:string\"\n        },\n        \"comment\": {\n          \"@id\": \"rdfs:comment\",\n          \"@type\": \"xsd:string\"\n        },\n        \"data_retention_time_in_days\": {\n          \"@id\": \"snowflake:database#data_retention_time_in_days\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"default_ddl_collation\": {\n          \"@id\": \"snowflake:database#default_ddl_collation\",\n          \"@type\": \"xsd:string\"\n        },\n        \"log_level\"\
  : {\n          \"@id\": \"snowflake:database#log_level\",\n          \"@type\": \"xsd:string\"\n        },\n        \"trace_level\": {\n          \"@id\": \"snowflake:database#trace_level\",\n          \"@type\": \"xsd:string\"\n        },\n        \"max_data_extension_time_in_days\": {\n          \"@id\": \"snowflake:database#max_data_extension_time_in_days\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"owner\": {\n          \"@id\": \"schema:owner\",\n          \"@type\": \"xsd:string\"\n        },\n        \"owner_role_type\": {\n          \"@id\": \"snowflake:database#owner_role_type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"created_on\": {\n          \"@id\": \"dc:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"dropped_on\": {\n          \"@id\": \"snowflake:database#dropped_on\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"is_default\": {\n          \"@id\": \"snowflake:database#is_default\",\n     \
  \     \"@type\": \"xsd:boolean\"\n        },\n        \"is_current\": {\n          \"@id\": \"snowflake:database#is_current\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"origin\": {\n          \"@id\": \"snowflake:database#origin\",\n          \"@type\": \"xsd:string\"\n        },\n        \"retention_time\": {\n          \"@id\": \"snowflake:database#retention_time\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"budget\": {\n          \"@id\": \"snowflake:database#budget\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Statement\": {\n      \"@id\": \"snowflake:sql-api\",\n      \"@context\": {\n        \"statement\": {\n          \"@id\": \"snowflake:sql-api#statement\",\n          \"@type\": \"xsd:string\"\n        },\n        \"timeout\": {\n          \"@id\": \"snowflake:sql-api#timeout\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"database\": {\n          \"@id\": \"snowflake:sql-api#database\",\n     \
  \     \"@type\": \"xsd:string\"\n        },\n        \"schema_name\": {\n          \"@id\": \"snowflake:sql-api#schema\",\n          \"@type\": \"xsd:string\"\n        },\n        \"warehouse\": {\n          \"@id\": \"snowflake:sql-api#warehouse\",\n          \"@type\": \"xsd:string\"\n        },\n        \"role\": {\n          \"@id\": \"snowflake:sql-api#role\",\n          \"@type\": \"xsd:string\"\n        },\n        \"statementHandle\": {\n          \"@id\": \"snowflake:sql-api#statementHandle\",\n          \"@type\": \"xsd:string\"\n        },\n        \"statementStatusUrl\": {\n          \"@id\": \"snowflake:sql-api#statementStatusUrl\",\n          \"@type\": \"@id\"\n        },\n        \"createdOn\": {\n          \"@id\": \"dc:created\",\n          \"@type\": \"xsd:long\"\n        }\n      }\n    },\n    \"ResultSet\": {\n      \"@id\": \"snowflake:sql-api#ResultSet\",\n      \"@context\": {\n        \"code\": {\n          \"@id\": \"snowflake:sql-api#code\",\n          \"@type\"\
  : \"xsd:string\"\n        },\n        \"sqlState\": {\n          \"@id\": \"snowflake:sql-api#sqlState\",\n          \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"snowflake:sql-api#message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"numRows\": {\n          \"@id\": \"snowflake:sql-api#numRows\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"data\": {\n          \"@id\": \"snowflake:sql-api#data\",\n          \"@container\": \"@list\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/snowflake/refs/heads/main/json-ld/snowflake-context.jsonld
tags:
- Data Lakes
- Data Sharing
- Data Warehousing
- Database
- SQL
- JSON-LD
- Linked Data
- Semantic Web
---
