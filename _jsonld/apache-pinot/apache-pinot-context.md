---
class_count: 12
classes:
- SqlQueryRequest
- SqlQueryResponse
- ResultTable
- DataSchema
- TableList
- TableConfig
- Schema
- FieldSpec
- SegmentList
- ClusterInfo
- InstanceList
- SuccessResponse
context_file: json-ld/apache-pinot-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-pinot/refs/heads/main/json-ld/apache-pinot-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Pinot from Apache Pinot.
layout: jsonld
name: Apache Pinot Context
namespaces:
- prefix: pino
  uri: https://pinot.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: sql
  type: string
- container: ''
  name: queryOptions
  type: string
- container: ''
  name: resultTable
  type: string
- container: ''
  name: numDocsScanned
  type: integer
- container: ''
  name: totalDocs
  type: integer
- container: ''
  name: timeUsedMs
  type: integer
- container: ''
  name: numServersQueried
  type: integer
- container: ''
  name: numServersResponded
  type: integer
- container: ''
  name: dataSchema
  type: string
- container: set
  name: rows
  type: ''
- container: set
  name: columnNames
  type: ''
- container: set
  name: columnDataTypes
  type: ''
- container: set
  name: tables
  type: ''
- container: ''
  name: tableName
  type: string
- container: ''
  name: tableType
  type: string
- container: ''
  name: segmentsConfig
  type: string
- container: ''
  name: tenants
  type: string
- container: ''
  name: schemaName
  type: string
- container: set
  name: dimensionFieldSpecs
  type: ''
- container: set
  name: metricFieldSpecs
  type: ''
- container: set
  name: dateTimeFieldSpecs
  type: ''
- container: ''
  name: name
  type: schema:name
- container: ''
  name: dataType
  type: string
- container: ''
  name: notNull
  type: boolean
- container: set
  name: OFFLINE
  type: ''
- container: set
  name: REALTIME
  type: ''
- container: ''
  name: clusterName
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: numOnlineControllers
  type: integer
- container: ''
  name: numOnlineBrokers
  type: integer
- container: ''
  name: numOnlineServers
  type: integer
- container: set
  name: instances
  type: ''
- container: ''
  name: status
  type: string
- container: ''
  name: message
  type: string
property_count: 34
provider_name: Apache Pinot
provider_slug: apache-pinot
slug: apache-pinot-context
tags:
- Analytics
- Database
- Low Latency
- OLAP
- Real-Time
- Apache
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
