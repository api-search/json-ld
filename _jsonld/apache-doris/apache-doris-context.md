---
class_count: 4
classes:
- StreamLoadResponse
- TableSchema
- RoutineLoadJob
- name
context_file: json-ld/apache-doris-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-doris/refs/heads/main/json-ld/apache-doris-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Doris from Apache Doris.
layout: jsonld
name: Apache Doris Context
namespaces:
- prefix: doris
  uri: https://doris.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: BeginTxnTimeMs
  type: integer
- container: ''
  name: CommitAndPublishTimeMs
  type: integer
- container: ''
  name: ErrorURL
  type: string
- container: ''
  name: ExistingJobStatus
  type: string
- container: ''
  name: Label
  type: string
- container: ''
  name: LoadBytes
  type: integer
- container: ''
  name: LoadTimeMs
  type: integer
- container: ''
  name: Message
  type: string
- container: ''
  name: NumberFilteredRows
  type: integer
- container: ''
  name: NumberLoadedRows
  type: integer
- container: ''
  name: NumberTotalRows
  type: integer
- container: ''
  name: NumberUnselectedRows
  type: integer
- container: ''
  name: ReadDataTimeMs
  type: integer
- container: ''
  name: Status
  type: string
- container: ''
  name: StreamLoadPutTimeMs
  type: integer
- container: ''
  name: TxnId
  type: integer
- container: ''
  name: WriteDataTimeMs
  type: integer
- container: set
  name: columns
  type: reference
- container: ''
  name: comment
  type: string
- container: ''
  name: createTime
  type: dateTime
- container: ''
  name: dataSourceType
  type: string
- container: ''
  name: databaseName
  type: string
- container: ''
  name: dbName
  type: string
- container: ''
  name: filteredRows
  type: integer
- container: ''
  name: format
  type: string
- container: ''
  name: id
  type: integer
- container: ''
  name: isKey
  type: boolean
- container: ''
  name: kafkaBrokerList
  type: string
- container: ''
  name: kafkaTopic
  type: string
- container: ''
  name: keyType
  type: string
- container: ''
  name: loadedRows
  type: integer
- container: ''
  name: nullable
  type: boolean
- container: ''
  name: replicationNum
  type: integer
- container: ''
  name: state
  type: string
- container: ''
  name: tableName
  type: string
- container: ''
  name: tableType
  type: string
- container: ''
  name: totalRows
  type: integer
- container: ''
  name: type
  type: string
property_count: 38
provider_name: Apache Doris
provider_slug: apache-doris
slug: apache-doris-context
source_filename: apache-doris-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"doris\": \"https://doris.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"StreamLoadResponse\": \"doris:StreamLoadResponse\",\n    \"TableSchema\": \"doris:TableSchema\",\n    \"RoutineLoadJob\": \"doris:RoutineLoadJob\",\n    \"BeginTxnTimeMs\": {\n      \"@id\": \"doris:BeginTxnTimeMs\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"CommitAndPublishTimeMs\": {\n      \"@id\": \"doris:CommitAndPublishTimeMs\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ErrorURL\": {\n      \"@id\": \"doris:ErrorURL\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExistingJobStatus\": {\n      \"@id\": \"doris:ExistingJobStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Label\": {\n      \"@id\": \"doris:Label\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LoadBytes\": {\n      \"@id\": \"doris:LoadBytes\",\n      \"@type\": \"xsd:integer\"\n\
  \    },\n    \"LoadTimeMs\": {\n      \"@id\": \"doris:LoadTimeMs\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Message\": {\n      \"@id\": \"doris:Message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NumberFilteredRows\": {\n      \"@id\": \"doris:NumberFilteredRows\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"NumberLoadedRows\": {\n      \"@id\": \"doris:NumberLoadedRows\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"NumberTotalRows\": {\n      \"@id\": \"doris:NumberTotalRows\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"NumberUnselectedRows\": {\n      \"@id\": \"doris:NumberUnselectedRows\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ReadDataTimeMs\": {\n      \"@id\": \"doris:ReadDataTimeMs\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Status\": {\n      \"@id\": \"doris:Status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StreamLoadPutTimeMs\": {\n      \"@id\": \"doris:StreamLoadPutTimeMs\",\n      \"@type\": \"xsd:integer\"\n   \
  \ },\n    \"TxnId\": {\n      \"@id\": \"doris:TxnId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"WriteDataTimeMs\": {\n      \"@id\": \"doris:WriteDataTimeMs\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"columns\": {\n      \"@id\": \"doris:columns\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"comment\": {\n      \"@id\": \"doris:comment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createTime\": {\n      \"@id\": \"doris:createTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"dataSourceType\": {\n      \"@id\": \"doris:dataSourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"databaseName\": {\n      \"@id\": \"doris:databaseName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dbName\": {\n      \"@id\": \"doris:dbName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filteredRows\": {\n      \"@id\": \"doris:filteredRows\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"format\": {\n      \"@id\": \"doris:format\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"doris:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"isKey\": {\n      \"@id\": \"doris:isKey\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"kafkaBrokerList\": {\n      \"@id\": \"doris:kafkaBrokerList\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kafkaTopic\": {\n      \"@id\": \"doris:kafkaTopic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keyType\": {\n      \"@id\": \"doris:keyType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"loadedRows\": {\n      \"@id\": \"doris:loadedRows\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": \"schema:name\",\n    \"nullable\": {\n      \"@id\": \"doris:nullable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"replicationNum\": {\n      \"@id\": \"doris:replicationNum\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"state\": {\n      \"@id\": \"doris:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tableName\": {\n      \"\
  @id\": \"doris:tableName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tableType\": {\n      \"@id\": \"doris:tableType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalRows\": {\n      \"@id\": \"doris:totalRows\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"type\": {\n      \"@id\": \"doris:type\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-doris/refs/heads/main/json-ld/apache-doris-context.jsonld
tags:
- Analytics
- Apache
- Database
- Lakehouse
- MPP
- OLAP
- Open Source
- Real-Time
- SQL
- JSON-LD
- Linked Data
- Semantic Web
---
