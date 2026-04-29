---
class_count: 25
classes:
- tableName
- basePath
- tableType
- schema
- preCombineField
- recordKeyField
- partitionPathField
- operation
- batchSize
- parallelism
- smallFileLimit
- compactionEnabled
- timestamp
- action
- state
- commitTime
- totalWriteBytes
- totalRecordsWritten
- totalUpdateRecordsWritten
- totalInsertRecordsWritten
- policy
- retainCommits
- queryType
- beginInstantTime
- endInstantTime
context_file: json-ld/apache-hudi-timeline-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-hudi/refs/heads/main/json-ld/apache-hudi-timeline-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Hudi Timeline from Apache Hudi.
layout: jsonld
name: Apache Hudi Timeline Context
namespaces:
- prefix: hudi
  uri: https://hudi.apache.org/vocab#
properties: []
property_count: 0
provider_name: Apache Hudi
provider_slug: apache-hudi
slug: apache-hudi-timeline-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"hudi\": \"https://hudi.apache.org/vocab#\",\n    \"tableName\": \"schema:name\",\n    \"basePath\": \"schema:url\",\n    \"tableType\": \"hudi:tableType\",\n    \"schema\": \"hudi:schema\",\n    \"preCombineField\": \"hudi:preCombineField\",\n    \"recordKeyField\": \"hudi:recordKeyField\",\n    \"partitionPathField\": \"hudi:partitionPathField\",\n    \"operation\": \"hudi:operation\",\n    \"batchSize\": \"hudi:batchSize\",\n    \"parallelism\": \"hudi:parallelism\",\n    \"smallFileLimit\": \"hudi:smallFileLimit\",\n    \"compactionEnabled\": \"hudi:compactionEnabled\",\n    \"timestamp\": \"schema:dateCreated\",\n    \"action\": \"hudi:action\",\n    \"state\": \"schema:status\",\n    \"commitTime\": \"hudi:commitTime\",\n    \"totalWriteBytes\": \"hudi:totalWriteBytes\",\n    \"totalRecordsWritten\": \"hudi:totalRecordsWritten\",\n    \"totalUpdateRecordsWritten\": \"hudi:totalUpdateRecordsWritten\"\
  ,\n    \"totalInsertRecordsWritten\": \"hudi:totalInsertRecordsWritten\",\n    \"policy\": \"hudi:policy\",\n    \"retainCommits\": \"hudi:retainCommits\",\n    \"queryType\": \"hudi:queryType\",\n    \"beginInstantTime\": \"hudi:beginInstantTime\",\n    \"endInstantTime\": \"hudi:endInstantTime\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-hudi/refs/heads/main/json-ld/apache-hudi-timeline-context.jsonld
tags:
- ACID
- Apache
- Big Data
- Data Lake
- Incremental Processing
- Lakehouse
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
