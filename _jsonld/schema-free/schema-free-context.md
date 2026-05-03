---
class_count: 0
classes: []
context_file: json-ld/schema-free-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/schema-free/refs/heads/main/json-ld/schema-free-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Schema Free from Schema Free.
layout: jsonld
name: Schema Free Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: sf
  uri: https://api-evangelist.github.io/schema-free/vocab#
properties:
- container: ''
  name: SchemaFreeDocument
  type: rdfs:Class
- container: ''
  name: NoSQLDatabase
  type: rdfs:Class
- container: ''
  name: DocumentCollection
  type: rdfs:Class
- container: ''
  name: _id
  type: string
- container: ''
  name: _collection
  type: string
- container: ''
  name: _version
  type: integer
- container: ''
  name: _created
  type: dateTime
- container: ''
  name: _modified
  type: dateTime
- container: ''
  name: _type
  type: string
- container: ''
  name: embeddedDocument
  type: reference
- container: ''
  name: documentReference
  type: reference
- container: ''
  name: indexedField
  type: string
- container: ''
  name: shardKey
  type: string
property_count: 13
provider_name: Schema Free
provider_slug: schema-free
slug: schema-free-context
source_filename: schema-free-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"sf\": \"https://api-evangelist.github.io/schema-free/vocab#\",\n\n    \"SchemaFreeDocument\": {\n      \"@id\": \"sf:SchemaFreeDocument\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:comment\": \"A document stored in a schema-free database without a predefined fixed schema\"\n    },\n    \"NoSQLDatabase\": {\n      \"@id\": \"sf:NoSQLDatabase\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:comment\": \"A database that does not require a fixed relational schema\"\n    },\n    \"DocumentCollection\": {\n      \"@id\": \"sf:DocumentCollection\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:comment\": \"A collection of related documents in a document store\"\n    },\n\n    \"_id\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n  \
  \  \"_collection\": {\n      \"@id\": \"sf:collection\",\n      \"@type\": \"xsd:string\"\n    },\n    \"_version\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"_created\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"_modified\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"_type\": {\n      \"@id\": \"sf:documentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"embeddedDocument\": {\n      \"@id\": \"sf:embeddedDocument\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"A document embedded within a parent document\"\n    },\n    \"documentReference\": {\n      \"@id\": \"sf:documentReference\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"A reference to an external document by ID\"\n    },\n    \"indexedField\": {\n      \"@id\": \"sf:indexedField\",\n      \"@type\": \"xsd:string\",\n      \"rdfs:comment\": \"A field that has\
  \ been indexed for query performance\"\n    },\n    \"shardKey\": {\n      \"@id\": \"sf:shardKey\",\n      \"@type\": \"xsd:string\",\n      \"rdfs:comment\": \"The field used to determine data partitioning/sharding\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/schema-free/refs/heads/main/json-ld/schema-free-context.jsonld
tags:
- Schema Free
- Schemaless
- NoSQL
- Document Store
- Flexible Schema
- MongoDB
- DynamoDB
- Elasticsearch
- JSON-LD
- Linked Data
- Semantic Web
---
