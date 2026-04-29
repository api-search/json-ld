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
source_filename: apache-druid-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"druid\": \"https://druid.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"SqlQueryRequest\": \"druid:SqlQueryRequest\",\n    \"SqlQueryResponse\": \"druid:SqlQueryResponse\",\n    \"IngestionTask\": \"druid:IngestionTask\",\n    \"Supervisor\": \"druid:Supervisor\",\n    \"activeTasks\": {\n      \"@id\": \"druid:activeTasks\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"columnTypes\": {\n      \"@id\": \"druid:columnTypes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"columns\": {\n      \"@id\": \"druid:columns\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"context\": {\n      \"@id\": \"druid:context\",\n      \"@type\": \"@id\"\n    },\n    \"createdTime\": {\n      \"@id\": \"druid:createdTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"dataSource\": {\n   \
  \   \"@id\": \"druid:dataSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detailedState\": {\n      \"@id\": \"druid:detailedState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"duration\": {\n      \"@id\": \"druid:duration\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"groupId\": {\n      \"@id\": \"druid:groupId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"header\": {\n      \"@id\": \"druid:header\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"healthStatus\": {\n      \"@id\": \"druid:healthStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"host\": {\n      \"@id\": \"druid:host\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"druid:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastTaskCompletionTime\": {\n      \"@id\": \"druid:lastTaskCompletionTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"location\": {\n      \"@id\": \"druid:location\",\n      \"@type\": \"@id\"\n    },\n    \"parameters\": {\n\
  \      \"@id\": \"druid:parameters\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"port\": {\n      \"@id\": \"druid:port\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"priority\": {\n      \"@id\": \"druid:priority\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"publishingTasks\": {\n      \"@id\": \"druid:publishingTasks\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"query\": \"schema:query\",\n    \"queryId\": {\n      \"@id\": \"druid:queryId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queueInsertionTime\": {\n      \"@id\": \"druid:queueInsertionTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"resultFormat\": {\n      \"@id\": \"druid:resultFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"results\": {\n      \"@id\": \"druid:results\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"spec\": {\n      \"@id\": \"druid:spec\",\n      \"@type\": \"@id\"\n    },\n    \"sqlTypes\": {\n      \"\
  @id\": \"druid:sqlTypes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sqlTypesHeader\": {\n      \"@id\": \"druid:sqlTypesHeader\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"state\": {\n      \"@id\": \"druid:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"druid:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeout\": {\n      \"@id\": \"druid:timeout\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"type\": {\n      \"@id\": \"druid:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"typesHeader\": {\n      \"@id\": \"druid:typesHeader\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"value\": {\n      \"@id\": \"druid:value\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/json-ld/apache-druid-context.jsonld
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
