---
class_count: 2
classes:
- ConnectionConfig
- TableInfo
context_file: json-ld/apache-derby-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-derby/refs/heads/main/json-ld/apache-derby-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Derby from Apache Derby.
layout: jsonld
name: Apache Derby Context
namespaces:
- prefix: derby
  uri: https://db.apache.org/derby/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: bootPassword
  type: string
- container: ''
  name: createDatabase
  type: string
- container: ''
  name: dataEncryption
  type: boolean
- container: ''
  name: databaseName
  type: string
- container: ''
  name: encryptionAlgorithm
  type: string
- container: ''
  name: host
  type: string
- container: ''
  name: mode
  type: string
- container: ''
  name: password
  type: string
- container: ''
  name: port
  type: integer
- container: ''
  name: remarks
  type: string
- container: ''
  name: tableCatalog
  type: string
- container: ''
  name: tableName
  type: string
- container: ''
  name: tableSchema
  type: string
- container: ''
  name: tableType
  type: string
- container: ''
  name: user
  type: string
property_count: 15
provider_name: Apache Derby
provider_slug: apache-derby
slug: apache-derby-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"derby\": \"https://db.apache.org/derby/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ConnectionConfig\": \"derby:ConnectionConfig\",\n    \"TableInfo\": \"derby:TableInfo\",\n    \"bootPassword\": {\n      \"@id\": \"derby:bootPassword\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createDatabase\": {\n      \"@id\": \"derby:createDatabase\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataEncryption\": {\n      \"@id\": \"derby:dataEncryption\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"databaseName\": {\n      \"@id\": \"derby:databaseName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encryptionAlgorithm\": {\n      \"@id\": \"derby:encryptionAlgorithm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"host\": {\n      \"@id\": \"derby:host\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mode\": {\n      \"@id\": \"derby:mode\",\n \
  \     \"@type\": \"xsd:string\"\n    },\n    \"password\": {\n      \"@id\": \"derby:password\",\n      \"@type\": \"xsd:string\"\n    },\n    \"port\": {\n      \"@id\": \"derby:port\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"remarks\": {\n      \"@id\": \"derby:remarks\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tableCatalog\": {\n      \"@id\": \"derby:tableCatalog\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tableName\": {\n      \"@id\": \"derby:tableName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tableSchema\": {\n      \"@id\": \"derby:tableSchema\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tableType\": {\n      \"@id\": \"derby:tableType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"user\": {\n      \"@id\": \"derby:user\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-derby/refs/heads/main/json-ld/apache-derby-context.jsonld
tags:
- Apache
- Database
- Embedded
- Java
- JDBC
- Open Source
- Relational
- SQL
- JSON-LD
- Linked Data
- Semantic Web
---
