---
api_specs:
- filename: cloud-sql-openapi.yml
  format: yaml
  label: Cloud SQL Admin API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-sql/refs/heads/main/openapi/cloud-sql-openapi.yml
class_count: 17
classes:
- DatabaseInstance
- Database
- User
- BackupRun
- Operation
- name
- description
- state
- region
- databaseVersion
- tier
- createTime
- connectionName
- ipAddress
- settings
- project
- selfLink
context_file: json-ld/google-cloud-sql-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-sql/refs/heads/main/json-ld/google-cloud-sql-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Cloud Sql from Google Cloud SQL.
layout: jsonld
name: Google Cloud Sql Context
namespaces:
- prefix: sqladmin
  uri: https://cloud.google.com/sql/docs/mysql/admin-api/rest/v1/
- prefix: gcloud
  uri: https://cloud.google.com/apis/
properties: []
property_count: 0
provider_name: Google Cloud SQL
provider_slug: google-cloud-sql
slug: google-cloud-sql-context
source_filename: google-cloud-sql-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"sqladmin\": \"https://cloud.google.com/sql/docs/mysql/admin-api/rest/v1/\",\n    \"gcloud\": \"https://cloud.google.com/apis/\",\n    \"DatabaseInstance\": \"sqladmin:instances\",\n    \"Database\": \"sqladmin:databases\",\n    \"User\": \"sqladmin:users\",\n    \"BackupRun\": \"sqladmin:backupRuns\",\n    \"Operation\": \"sqladmin:operations\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"state\": \"sqladmin:state\",\n    \"region\": \"schema:location\",\n    \"databaseVersion\": \"sqladmin:databaseVersion\",\n    \"tier\": \"sqladmin:tier\",\n    \"createTime\": \"schema:dateCreated\",\n    \"connectionName\": \"sqladmin:connectionName\",\n    \"ipAddress\": \"sqladmin:ipAddress\",\n    \"settings\": \"sqladmin:settings\",\n    \"project\": \"gcloud:project\",\n    \"selfLink\": \"schema:url\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-sql/refs/heads/main/json-ld/google-cloud-sql-context.jsonld
tags:
- Database
- Google Cloud
- MySQL
- PostgreSQL
- Relational
- SQL
- JSON-LD
- Linked Data
- Semantic Web
---
