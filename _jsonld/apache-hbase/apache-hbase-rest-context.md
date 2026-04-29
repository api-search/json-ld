---
api_specs:
- filename: apache-hbase-rest-openapi.yml
  format: yaml
  label: Apache HBase REST API
  slug: apache-hbase-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-hbase/refs/heads/main/openapi/apache-hbase-rest-openapi.yml
class_count: 26
classes:
- Server
- JVM
- OS
- REST
- Jersey
- table
- name
- ColumnSchema
- VERSIONS
- COMPRESSION
- BLOOMFILTER
- TTL
- Row
- key
- Cell
- column
- timestamp
- startRow
- endRow
- batch
- maxVersions
- Region
- id
- startKey
- endKey
- location
context_file: json-ld/apache-hbase-rest-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-hbase/refs/heads/main/json-ld/apache-hbase-rest-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Hbase Rest from Apache HBase.
layout: jsonld
name: Apache Hbase Rest Context
namespaces:
- prefix: hbase
  uri: https://hbase.apache.org/vocab#
properties: []
property_count: 0
provider_name: Apache HBase
provider_slug: apache-hbase
slug: apache-hbase-rest-context
source_filename: apache-hbase-rest-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"hbase\": \"https://hbase.apache.org/vocab#\",\n    \"Server\": \"hbase:Server\",\n    \"JVM\": \"hbase:JVM\",\n    \"OS\": \"hbase:OS\",\n    \"REST\": \"hbase:REST\",\n    \"Jersey\": \"hbase:Jersey\",\n    \"table\": \"hbase:table\",\n    \"name\": \"schema:name\",\n    \"ColumnSchema\": \"hbase:ColumnSchema\",\n    \"VERSIONS\": \"hbase:VERSIONS\",\n    \"COMPRESSION\": \"hbase:COMPRESSION\",\n    \"BLOOMFILTER\": \"hbase:BLOOMFILTER\",\n    \"TTL\": \"hbase:TTL\",\n    \"Row\": \"hbase:Row\",\n    \"key\": \"hbase:key\",\n    \"Cell\": \"hbase:Cell\",\n    \"column\": \"hbase:column\",\n    \"timestamp\": \"schema:dateCreated\",\n    \"startRow\": \"hbase:startRow\",\n    \"endRow\": \"hbase:endRow\",\n    \"batch\": \"hbase:batch\",\n    \"maxVersions\": \"hbase:maxVersions\",\n    \"Region\": \"hbase:Region\",\n    \"id\": \"schema:identifier\",\n    \"startKey\": \"hbase:startKey\",\n    \"endKey\"\
  : \"hbase:endKey\",\n    \"location\": \"schema:location\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-hbase/refs/heads/main/json-ld/apache-hbase-rest-context.jsonld
tags:
- Apache
- Big Data
- Bigtable
- Database
- Hadoop
- NoSQL
- Open Source
- Wide Column
- JSON-LD
- Linked Data
- Semantic Web
---
