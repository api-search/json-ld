---
class_count: 13
classes:
- RocksDB
- Database
- ColumnFamily
- KeyValueEntry
- Snapshot
- Iterator
- Transaction
- CompactionJob
- SSTableFile
- WriteAheadLog
- MemTable
- BlockCache
- BlobDB
context_file: json-ld/rocksdb-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/rocksdb/refs/heads/main/json-ld/rocksdb-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Rocksdb from RocksDB.
layout: jsonld
name: Rocksdb Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: rocksdb
  uri: https://api-evangelist.github.io/rocksdb/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: key
  type: string
- container: ''
  name: value
  type: ''
- container: ''
  name: columnFamily
  type: string
- container: ''
  name: sequenceNumber
  type: integer
- container: ''
  name: ttl
  type: integer
- container: ''
  name: compression
  type: string
- container: ''
  name: compactionStyle
  type: string
- container: ''
  name: writeBufferSize
  type: integer
- container: ''
  name: bloomFilterBitsPerKey
  type: integer
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: license
  type: reference
- container: ''
  name: url
  type: reference
property_count: 14
provider_name: RocksDB
provider_slug: rocksdb
slug: rocksdb-context
source_filename: rocksdb-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"rocksdb\": \"https://api-evangelist.github.io/rocksdb/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"RocksDB\": \"rocksdb:RocksDB\",\n    \"Database\": \"rocksdb:Database\",\n    \"ColumnFamily\": \"rocksdb:ColumnFamily\",\n    \"KeyValueEntry\": \"rocksdb:KeyValueEntry\",\n    \"Snapshot\": \"rocksdb:Snapshot\",\n    \"Iterator\": \"rocksdb:Iterator\",\n    \"Transaction\": \"rocksdb:Transaction\",\n    \"CompactionJob\": \"rocksdb:CompactionJob\",\n    \"SSTableFile\": \"rocksdb:SSTableFile\",\n    \"WriteAheadLog\": \"rocksdb:WriteAheadLog\",\n    \"MemTable\": \"rocksdb:MemTable\",\n    \"BlockCache\": \"rocksdb:BlockCache\",\n    \"BlobDB\": \"rocksdb:BlobDB\",\n\n    \"key\": {\n      \"@id\": \"rocksdb:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"rocksdb:value\"\n    },\n    \"columnFamily\": {\n      \"@id\": \"\
  rocksdb:columnFamily\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sequenceNumber\": {\n      \"@id\": \"rocksdb:sequenceNumber\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ttl\": {\n      \"@id\": \"rocksdb:ttl\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"compression\": {\n      \"@id\": \"rocksdb:compression\",\n      \"@type\": \"xsd:string\"\n    },\n    \"compactionStyle\": {\n      \"@id\": \"rocksdb:compactionStyle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"writeBufferSize\": {\n      \"@id\": \"rocksdb:writeBufferSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"bloomFilterBitsPerKey\": {\n      \"@id\": \"rocksdb:bloomFilterBitsPerKey\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"license\": {\n      \"@id\": \"schema:license\",\n      \"@type\": \"@id\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/rocksdb/refs/heads/main/json-ld/rocksdb-context.jsonld
tags:
- RocksDB
- Key-Value Store
- Embedded Database
- Storage Engine
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
