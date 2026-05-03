---
api_specs:
- filename: oracle-database-19c-ords-openapi.yml
  format: yaml
  label: Oracle REST Data Services (ORDS)
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-database-19c/refs/heads/main/openapi/oracle-database-19c-ords-openapi.yml
class_count: 11
classes:
- Database
- Schema
- Table
- View
- Column
- Collection
- Document
- RestEnabledObject
- Module
- Template
- Handler
context_file: json-ld/oracle-database-19c-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/oracle-database-19c/refs/heads/main/json-ld/oracle-database-19c-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Oracle Database 19C from Oracle Database 19c.
layout: jsonld
name: Oracle Database 19C Context
namespaces:
- prefix: oracle
  uri: https://oracle.com/schemas/database/
- prefix: ords
  uri: https://oracle.com/schemas/database/ords/
- prefix: soda
  uri: https://oracle.com/schemas/database/soda/
properties:
- container: ''
  name: schemaName
  type: string
- container: ''
  name: tableName
  type: string
- container: ''
  name: columnName
  type: string
- container: ''
  name: dataType
  type: string
- container: ''
  name: primaryKey
  type: boolean
- container: ''
  name: nullable
  type: boolean
- container: ''
  name: collectionName
  type: string
- container: ''
  name: documentKey
  type: string
- container: ''
  name: mediaType
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: modulePattern
  type: string
- container: ''
  name: uriTemplate
  type: string
- container: ''
  name: method
  type: string
- container: ''
  name: sourceType
  type: string
property_count: 14
provider_name: Oracle Database 19c
provider_slug: oracle-database-19c
slug: oracle-database-19c-context
source_filename: oracle-database-19c-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"oracle\": \"https://oracle.com/schemas/database/\",\n    \"ords\": \"https://oracle.com/schemas/database/ords/\",\n    \"soda\": \"https://oracle.com/schemas/database/soda/\",\n\n    \"Database\": \"oracle:Database\",\n    \"Schema\": \"oracle:Schema\",\n    \"Table\": \"oracle:Table\",\n    \"View\": \"oracle:View\",\n    \"Column\": \"oracle:Column\",\n    \"Collection\": \"soda:Collection\",\n    \"Document\": \"soda:Document\",\n    \"RestEnabledObject\": \"ords:RestEnabledObject\",\n    \"Module\": \"ords:Module\",\n    \"Template\": \"ords:Template\",\n    \"Handler\": \"ords:Handler\",\n\n    \"schemaName\": { \"@id\": \"oracle:schemaName\", \"@type\": \"xsd:string\" },\n    \"tableName\": { \"@id\": \"oracle:tableName\", \"@type\": \"xsd:string\" },\n    \"columnName\": { \"@id\": \"oracle:columnName\", \"@type\": \"xsd:string\" },\n    \"dataType\": { \"@id\": \"oracle:dataType\", \"@type\": \"xsd:string\"\
  \ },\n    \"primaryKey\": { \"@id\": \"oracle:primaryKey\", \"@type\": \"xsd:boolean\" },\n    \"nullable\": { \"@id\": \"oracle:nullable\", \"@type\": \"xsd:boolean\" },\n\n    \"collectionName\": { \"@id\": \"soda:collectionName\", \"@type\": \"xsd:string\" },\n    \"documentKey\": { \"@id\": \"soda:documentKey\", \"@type\": \"xsd:string\" },\n    \"mediaType\": { \"@id\": \"soda:mediaType\", \"@type\": \"xsd:string\" },\n    \"version\": { \"@id\": \"soda:version\", \"@type\": \"xsd:string\" },\n\n    \"modulePattern\": { \"@id\": \"ords:modulePattern\", \"@type\": \"xsd:string\" },\n    \"uriTemplate\": { \"@id\": \"ords:uriTemplate\", \"@type\": \"xsd:string\" },\n    \"method\": { \"@id\": \"ords:method\", \"@type\": \"xsd:string\" },\n    \"sourceType\": { \"@id\": \"ords:sourceType\", \"@type\": \"xsd:string\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/oracle-database-19c/refs/heads/main/json-ld/oracle-database-19c-context.jsonld
tags:
- Database
- Enterprise
- Json
- Machine-Learning
- Nosql
- Oracle
- Rest
- Sql
- JSON-LD
- Linked Data
- Semantic Web
---
