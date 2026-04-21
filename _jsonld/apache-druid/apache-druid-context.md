---
class_count: 5
classes:
- SqlQueryRequest
- SqlQueryResponse
- IngestionTask
- Supervisor
- query
context_file: json-ld/apache-druid-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/json-ld/apache-druid-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Druid from Apache Druid.
layout: jsonld
name: Apache Druid Context
namespaces:
- prefix: druid
  uri: https://druid.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: activeTasks
  type: integer
- container: set
  name: columnTypes
  type: string
- container: set
  name: columns
  type: string
- container: ''
  name: context
  type: reference
- container: ''
  name: createdTime
  type: dateTime
- container: ''
  name: dataSource
  type: string
- container: ''
  name: detailedState
  type: string
- container: ''
  name: duration
  type: integer
- container: ''
  name: groupId
  type: string
- container: ''
  name: header
  type: boolean
- container: ''
  name: healthStatus
  type: string
- container: ''
  name: host
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: lastTaskCompletionTime
  type: dateTime
- container: ''
  name: location
  type: reference
- container: set
  name: parameters
  type: reference
- container: ''
  name: port
  type: integer
- container: ''
  name: priority
  type: integer
- container: ''
  name: publishingTasks
  type: integer
- container: ''
  name: queryId
  type: string
- container: ''
  name: queueInsertionTime
  type: dateTime
- container: ''
  name: resultFormat
  type: string
- container: set
  name: results
  type: reference
- container: ''
  name: spec
  type: reference
- container: set
  name: sqlTypes
  type: string
- container: ''
  name: sqlTypesHeader
  type: boolean
- container: ''
  name: state
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: timeout
  type: integer
- container: ''
  name: type
  type: string
- container: ''
  name: typesHeader
  type: boolean
- container: ''
  name: value
  type: string
property_count: 32
provider_name: Apache Druid
provider_slug: apache-druid
slug: apache-druid-context
tags:
- Analytics
- Apache
- Database
- Kafka
- OLAP
- Open Source
- Real-Time
- SQL
- Time Series
- JSON-LD
- Linked Data
- Semantic Web
---
