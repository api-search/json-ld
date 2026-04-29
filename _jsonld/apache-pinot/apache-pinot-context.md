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
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pino\": \"https://pinot.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"SqlQueryRequest\": \"pino:SqlQueryRequest\",\n    \"SqlQueryResponse\": \"pino:SqlQueryResponse\",\n    \"ResultTable\": \"pino:ResultTable\",\n    \"DataSchema\": \"pino:DataSchema\",\n    \"TableList\": \"pino:TableList\",\n    \"TableConfig\": \"pino:TableConfig\",\n    \"Schema\": \"pino:Schema\",\n    \"FieldSpec\": \"pino:FieldSpec\",\n    \"SegmentList\": \"pino:SegmentList\",\n    \"ClusterInfo\": \"pino:ClusterInfo\",\n    \"InstanceList\": \"pino:InstanceList\",\n    \"SuccessResponse\": \"pino:SuccessResponse\",\n    \"sql\": {\n      \"@id\": \"pino:sql\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queryOptions\": {\n      \"@id\": \"pino:queryOptions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resultTable\": {\n      \"@id\": \"pino:resultTable\",\n   \
  \   \"@type\": \"xsd:string\"\n    },\n    \"numDocsScanned\": {\n      \"@id\": \"pino:numDocsScanned\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalDocs\": {\n      \"@id\": \"pino:totalDocs\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"timeUsedMs\": {\n      \"@id\": \"pino:timeUsedMs\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"numServersQueried\": {\n      \"@id\": \"pino:numServersQueried\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"numServersResponded\": {\n      \"@id\": \"pino:numServersResponded\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"dataSchema\": {\n      \"@id\": \"pino:dataSchema\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rows\": {\n      \"@id\": \"pino:rows\",\n      \"@container\": \"@set\"\n    },\n    \"columnNames\": {\n      \"@id\": \"pino:columnNames\",\n      \"@container\": \"@set\"\n    },\n    \"columnDataTypes\": {\n      \"@id\": \"pino:columnDataTypes\",\n      \"@container\": \"@set\"\n    },\n    \"tables\"\
  : {\n      \"@id\": \"pino:tables\",\n      \"@container\": \"@set\"\n    },\n    \"tableName\": {\n      \"@id\": \"pino:tableName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tableType\": {\n      \"@id\": \"pino:tableType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"segmentsConfig\": {\n      \"@id\": \"pino:segmentsConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tenants\": {\n      \"@id\": \"pino:tenants\",\n      \"@type\": \"xsd:string\"\n    },\n    \"schemaName\": {\n      \"@id\": \"pino:schemaName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dimensionFieldSpecs\": {\n      \"@id\": \"pino:dimensionFieldSpecs\",\n      \"@container\": \"@set\"\n    },\n    \"metricFieldSpecs\": {\n      \"@id\": \"pino:metricFieldSpecs\",\n      \"@container\": \"@set\"\n    },\n    \"dateTimeFieldSpecs\": {\n      \"@id\": \"pino:dateTimeFieldSpecs\",\n      \"@container\": \"@set\"\n    },\n    \"name\": {\n      \"@id\": \"pino:name\",\n      \"@type\": \"schema:name\"\
  \n    },\n    \"dataType\": {\n      \"@id\": \"pino:dataType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notNull\": {\n      \"@id\": \"pino:notNull\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"OFFLINE\": {\n      \"@id\": \"pino:OFFLINE\",\n      \"@container\": \"@set\"\n    },\n    \"REALTIME\": {\n      \"@id\": \"pino:REALTIME\",\n      \"@container\": \"@set\"\n    },\n    \"clusterName\": {\n      \"@id\": \"pino:clusterName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"pino:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"numOnlineControllers\": {\n      \"@id\": \"pino:numOnlineControllers\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"numOnlineBrokers\": {\n      \"@id\": \"pino:numOnlineBrokers\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"numOnlineServers\": {\n      \"@id\": \"pino:numOnlineServers\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"instances\": {\n      \"@id\": \"pino:instances\",\n\
  \      \"@container\": \"@set\"\n    },\n    \"status\": {\n      \"@id\": \"pino:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"pino:message\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-pinot/refs/heads/main/json-ld/apache-pinot-context.jsonld
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
