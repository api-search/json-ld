---
api_specs:
- filename: apache-hive-webhcat-openapi.yml
  format: yaml
  label: Apache Hive WebHCat REST API
  slug: apache-hive-webhcat-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-hive/refs/heads/main/openapi/apache-hive-webhcat-openapi.yml
class_count: 21
classes:
- name
- comment
- location
- ownerName
- ownerType
- tableName
- dbName
- tableType
- inputFormat
- outputFormat
- numRows
- type
- values
- status
- schema
- rows
- database
- id
- percentComplete
- query
- statusdir
context_file: json-ld/apache-hive-webhcat-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-hive/refs/heads/main/json-ld/apache-hive-webhcat-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Hive Webhcat from Apache Hive.
layout: jsonld
name: Apache Hive Webhcat Context
namespaces:
- prefix: hive
  uri: https://hive.apache.org/vocab#
properties: []
property_count: 0
provider_name: Apache Hive
provider_slug: apache-hive
slug: apache-hive-webhcat-context
source_filename: apache-hive-webhcat-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"hive\": \"https://hive.apache.org/vocab#\",\n    \"name\": \"schema:name\",\n    \"comment\": \"schema:description\",\n    \"location\": \"schema:url\",\n    \"ownerName\": \"schema:creator\",\n    \"ownerType\": \"hive:ownerType\",\n    \"tableName\": \"hive:tableName\",\n    \"dbName\": \"hive:dbName\",\n    \"tableType\": \"hive:tableType\",\n    \"inputFormat\": \"hive:inputFormat\",\n    \"outputFormat\": \"hive:outputFormat\",\n    \"numRows\": \"hive:numRows\",\n    \"type\": \"schema:DataType\",\n    \"values\": \"hive:values\",\n    \"status\": \"schema:status\",\n    \"schema\": \"hive:schema\",\n    \"rows\": \"hive:rows\",\n    \"database\": \"hive:database\",\n    \"id\": \"schema:identifier\",\n    \"percentComplete\": \"hive:percentComplete\",\n    \"query\": \"hive:query\",\n    \"statusdir\": \"hive:statusdir\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-hive/refs/heads/main/json-ld/apache-hive-webhcat-context.jsonld
tags:
- Apache
- Big Data
- Data Warehouse
- ETL
- Hadoop
- Open Source
- SQL
- JSON-LD
- Linked Data
- Semantic Web
---
