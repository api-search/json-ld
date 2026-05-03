---
class_count: 17
classes:
- SQLQuery
- SQLResult
- SQLTable
- SQLColumn
- SQLDatabase
- SQLSchema
- Dataset
- sql_statement
- columnName
- dataType
- tableName
- schemaName
- databaseName
- name
- description
- version
- identifier
context_file: json-ld/sql-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sql/refs/heads/main/json-ld/sql-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sql from SQL.
layout: jsonld
name: Sql Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: sql
  uri: https://www.w3.org/ns/sql/
- prefix: dcat
  uri: https://www.w3.org/ns/dcat#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: list
  name: parameters
  type: ''
- container: list
  name: columns
  type: ''
- container: list
  name: rows
  type: ''
- container: ''
  name: rowCount
  type: integer
- container: ''
  name: nullable
  type: boolean
- container: ''
  name: primaryKey
  type: boolean
property_count: 6
provider_name: SQL
provider_slug: sql
slug: sql-context
source_filename: sql-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"sql\": \"https://www.w3.org/ns/sql/\",\n    \"dcat\": \"https://www.w3.org/ns/dcat#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"SQLQuery\": \"sql:SQLQuery\",\n    \"SQLResult\": \"sql:SQLResult\",\n    \"SQLTable\": \"sql:SQLTable\",\n    \"SQLColumn\": \"sql:SQLColumn\",\n    \"SQLDatabase\": \"sql:SQLDatabase\",\n    \"SQLSchema\": \"sql:SQLSchema\",\n    \"Dataset\": \"dcat:Dataset\",\n\n    \"sql_statement\": \"sql:statement\",\n    \"parameters\": {\n      \"@id\": \"sql:hasParameter\",\n      \"@container\": \"@list\"\n    },\n    \"columns\": {\n      \"@id\": \"sql:hasColumn\",\n      \"@container\": \"@list\"\n    },\n    \"rows\": {\n      \"@id\": \"sql:hasRow\",\n      \"@container\": \"@list\"\n    },\n    \"rowCount\": {\n      \"@id\": \"sql:rowCount\",\n      \"@type\": \"xsd:integer\"\n    },\n \
  \   \"columnName\": \"sql:columnName\",\n    \"dataType\": \"sql:dataType\",\n    \"nullable\": {\n      \"@id\": \"sql:nullable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"primaryKey\": {\n      \"@id\": \"sql:isPrimaryKey\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"tableName\": \"sql:tableName\",\n    \"schemaName\": \"sql:schemaName\",\n    \"databaseName\": \"sql:databaseName\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"version\": \"schema:version\",\n    \"identifier\": \"dcterms:identifier\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sql/refs/heads/main/json-ld/sql-context.jsonld
tags:
- ANSI Standard
- Data Management
- Database
- ISO Standard
- Query Language
- Relational Database
- SQL
- JSON-LD
- Linked Data
- Semantic Web
---
