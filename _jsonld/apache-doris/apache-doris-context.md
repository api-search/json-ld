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
