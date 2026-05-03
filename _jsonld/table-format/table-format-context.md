---
api_specs:
- filename: rest-catalog-open-api.yaml
  format: yaml
  label: Apache Iceberg REST Catalog API
  slug: apache-iceberg-rest-catalog
  spec_type: OpenAPI
  url: https://github.com/apache/iceberg/blob/main/open-api/rest-catalog-open-api.yaml
- filename: all.yaml
  format: yaml
  label: Unity Catalog
  slug: unity-catalog
  spec_type: OpenAPI
  url: https://github.com/unitycatalog/unitycatalog/blob/main/api/all.yaml
class_count: 26
classes:
- TableFormat
- TableMetadata
- Schema
- Namespace
- Snapshot
- PartitionSpec
- SortOrder
- DataFile
- ManifestFile
- Catalog
- tableUuid
- location
- formatVersion
- snapshotId
- parentSnapshotId
- sequenceNumber
- manifestList
- schemaId
- specId
- lastUpdatedMs
- properties
- namespace
- tableName
- operation
- recordCount
- fileSizeBytes
context_file: json-ld/table-format-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/table-format/refs/heads/main/json-ld/table-format-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Table Format from Table Format.
layout: jsonld
name: Table Format Context
namespaces:
- prefix: iceberg
  uri: https://iceberg.apache.org/vocabulary/
- prefix: delta
  uri: https://delta.io/vocabulary/
- prefix: hudi
  uri: https://hudi.apache.org/vocabulary/
properties: []
property_count: 0
provider_name: Table Format
provider_slug: table-format
slug: table-format-context
source_filename: table-format-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"iceberg\": \"https://iceberg.apache.org/vocabulary/\",\n    \"delta\": \"https://delta.io/vocabulary/\",\n    \"hudi\": \"https://hudi.apache.org/vocabulary/\",\n    \"TableFormat\": \"iceberg:TableFormat\",\n    \"TableMetadata\": \"iceberg:TableMetadata\",\n    \"Schema\": \"iceberg:Schema\",\n    \"Namespace\": \"iceberg:Namespace\",\n    \"Snapshot\": \"iceberg:Snapshot\",\n    \"PartitionSpec\": \"iceberg:PartitionSpec\",\n    \"SortOrder\": \"iceberg:SortOrder\",\n    \"DataFile\": \"iceberg:DataFile\",\n    \"ManifestFile\": \"iceberg:ManifestFile\",\n    \"Catalog\": \"iceberg:Catalog\",\n    \"tableUuid\": \"iceberg:tableUuid\",\n    \"location\": \"schema:contentLocation\",\n    \"formatVersion\": \"iceberg:formatVersion\",\n    \"snapshotId\": \"iceberg:snapshotId\",\n    \"parentSnapshotId\": \"iceberg:parentSnapshotId\",\n    \"sequenceNumber\": \"iceberg:sequenceNumber\",\n    \"manifestList\"\
  : \"iceberg:manifestList\",\n    \"schemaId\": \"iceberg:schemaId\",\n    \"specId\": \"iceberg:specId\",\n    \"lastUpdatedMs\": \"schema:dateModified\",\n    \"properties\": \"schema:additionalProperty\",\n    \"namespace\": \"iceberg:namespace\",\n    \"tableName\": \"schema:name\",\n    \"operation\": \"iceberg:operation\",\n    \"recordCount\": \"iceberg:recordCount\",\n    \"fileSizeBytes\": \"iceberg:fileSizeBytes\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/table-format/refs/heads/main/json-ld/table-format-context.jsonld
tags:
- Data Lakehouse
- Open Table Format
- Apache Iceberg
- Delta Lake
- Apache Hudi
- Data Lake
- ACID Transactions
- Schema Evolution
- Time Travel
- JSON-LD
- Linked Data
- Semantic Web
---
