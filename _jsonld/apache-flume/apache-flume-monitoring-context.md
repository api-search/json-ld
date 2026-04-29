---
api_specs:
- filename: apache-flume-monitoring-openapi.yml
  format: yaml
  label: Apache Flume Monitoring API
  slug: apache-flume-monitoring-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-flume/refs/heads/main/openapi/apache-flume-monitoring-openapi.yml
class_count: 2
classes:
- ComponentMetrics
- AgentMetrics
context_file: json-ld/apache-flume-monitoring-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-flume/refs/heads/main/json-ld/apache-flume-monitoring-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Flume Monitoring from Apache Flume.
layout: jsonld
name: Apache Flume Monitoring Context
namespaces:
- prefix: flume
  uri: https://flume.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Type
  type: string
- container: ''
  name: StartTime
  type: string
- container: ''
  name: StopTime
  type: string
- container: ''
  name: EventReceivedCount
  type: string
- container: ''
  name: EventAcceptedCount
  type: string
- container: ''
  name: AppendBatchReceivedCount
  type: string
- container: ''
  name: AppendBatchAcceptedCount
  type: string
- container: ''
  name: EventPutAttemptCount
  type: string
- container: ''
  name: EventPutSuccessCount
  type: string
- container: ''
  name: EventTakeAttemptCount
  type: string
- container: ''
  name: EventTakeSuccessCount
  type: string
- container: ''
  name: ChannelSize
  type: string
- container: ''
  name: ChannelCapacity
  type: string
- container: ''
  name: EventDrainAttemptCount
  type: string
- container: ''
  name: EventDrainSuccessCount
  type: string
- container: ''
  name: ConnectionCreatedCount
  type: string
- container: ''
  name: ConnectionClosedCount
  type: string
- container: ''
  name: ConnectionFailedCount
  type: string
property_count: 18
provider_name: Apache Flume
provider_slug: apache-flume
slug: apache-flume-monitoring-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"flume\": \"https://flume.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ComponentMetrics\": \"flume:ComponentMetrics\",\n    \"Type\": {\n      \"@id\": \"flume:Type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StartTime\": {\n      \"@id\": \"flume:StartTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StopTime\": {\n      \"@id\": \"flume:StopTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventReceivedCount\": {\n      \"@id\": \"flume:EventReceivedCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventAcceptedCount\": {\n      \"@id\": \"flume:EventAcceptedCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AppendBatchReceivedCount\": {\n      \"@id\": \"flume:AppendBatchReceivedCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AppendBatchAcceptedCount\": {\n\
  \      \"@id\": \"flume:AppendBatchAcceptedCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventPutAttemptCount\": {\n      \"@id\": \"flume:EventPutAttemptCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventPutSuccessCount\": {\n      \"@id\": \"flume:EventPutSuccessCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventTakeAttemptCount\": {\n      \"@id\": \"flume:EventTakeAttemptCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventTakeSuccessCount\": {\n      \"@id\": \"flume:EventTakeSuccessCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ChannelSize\": {\n      \"@id\": \"flume:ChannelSize\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ChannelCapacity\": {\n      \"@id\": \"flume:ChannelCapacity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventDrainAttemptCount\": {\n      \"@id\": \"flume:EventDrainAttemptCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventDrainSuccessCount\": {\n      \"@id\": \"flume:EventDrainSuccessCount\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"ConnectionCreatedCount\": {\n      \"@id\": \"flume:ConnectionCreatedCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ConnectionClosedCount\": {\n      \"@id\": \"flume:ConnectionClosedCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ConnectionFailedCount\": {\n      \"@id\": \"flume:ConnectionFailedCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AgentMetrics\": \"flume:AgentMetrics\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-flume/refs/heads/main/json-ld/apache-flume-monitoring-context.jsonld
tags:
- Apache
- Data Collection
- ETL
- Log Aggregation
- Open Source
- Streaming
- JSON-LD
- Linked Data
- Semantic Web
---
