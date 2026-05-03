---
api_specs:
- filename: trino-client-api-openapi.yml
  format: yaml
  label: Trino Client REST API
  slug: trino-client-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trino/refs/heads/main/openapi/trino-client-api-openapi.yml
class_count: 25
classes:
- QueryResults
- QueryStats
- QueryError
- Column
- ServerInfo
- NodeStatus
- id
- updateType
- stats
- error
- name
- type
- typeSignature
- state
- message
- errorCode
- errorName
- errorType
- errorLocation
- nodeVersion
- version
- environment
- uptime
- nodeId
- nodeIp
context_file: json-ld/trino-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/trino/refs/heads/main/json-ld/trino-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Trino from Trino.
layout: jsonld
name: Trino Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: trino
  uri: https://trino.io/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: infoUri
  type: reference
- container: ''
  name: nextUri
  type: reference
- container: list
  name: columns
  type: ''
- container: list
  name: data
  type: ''
- container: ''
  name: updateCount
  type: integer
- container: list
  name: warnings
  type: ''
- container: ''
  name: queued
  type: boolean
- container: ''
  name: scheduled
  type: boolean
- container: ''
  name: nodes
  type: integer
- container: ''
  name: totalSplits
  type: long
- container: ''
  name: completedSplits
  type: long
- container: ''
  name: cpuTimeMillis
  type: long
- container: ''
  name: wallTimeMillis
  type: long
- container: ''
  name: processedRows
  type: long
- container: ''
  name: processedBytes
  type: long
- container: ''
  name: progressPercentage
  type: double
- container: ''
  name: lineNumber
  type: integer
- container: ''
  name: columnNumber
  type: integer
- container: ''
  name: coordinator
  type: boolean
- container: ''
  name: starting
  type: boolean
- container: ''
  name: lastResponseTime
  type: dateTime
property_count: 21
provider_name: Trino
provider_slug: trino
slug: trino-context
source_filename: trino-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"trino\": \"https://trino.io/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"QueryResults\": \"trino:QueryResults\",\n    \"QueryStats\": \"trino:QueryStats\",\n    \"QueryError\": \"trino:QueryError\",\n    \"Column\": \"trino:Column\",\n    \"ServerInfo\": \"trino:ServerInfo\",\n    \"NodeStatus\": \"trino:NodeStatus\",\n\n    \"id\": \"@id\",\n    \"infoUri\": {\n      \"@id\": \"trino:infoUri\",\n      \"@type\": \"@id\"\n    },\n    \"nextUri\": {\n      \"@id\": \"trino:nextUri\",\n      \"@type\": \"@id\"\n    },\n    \"columns\": {\n      \"@id\": \"trino:columns\",\n      \"@container\": \"@list\"\n    },\n    \"data\": {\n      \"@id\": \"trino:data\",\n      \"@container\": \"@list\"\n    },\n    \"updateType\": \"trino:updateType\",\n    \"updateCount\": {\n      \"@id\": \"trino:updateCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"stats\"\
  : \"trino:stats\",\n    \"error\": \"trino:error\",\n    \"warnings\": {\n      \"@id\": \"trino:warnings\",\n      \"@container\": \"@list\"\n    },\n\n    \"name\": \"schema:name\",\n    \"type\": \"trino:columnType\",\n    \"typeSignature\": \"trino:typeSignature\",\n\n    \"state\": \"trino:queryState\",\n    \"queued\": { \"@id\": \"trino:queued\", \"@type\": \"xsd:boolean\" },\n    \"scheduled\": { \"@id\": \"trino:scheduled\", \"@type\": \"xsd:boolean\" },\n    \"nodes\": { \"@id\": \"trino:nodes\", \"@type\": \"xsd:integer\" },\n    \"totalSplits\": { \"@id\": \"trino:totalSplits\", \"@type\": \"xsd:long\" },\n    \"completedSplits\": { \"@id\": \"trino:completedSplits\", \"@type\": \"xsd:long\" },\n    \"cpuTimeMillis\": { \"@id\": \"trino:cpuTimeMillis\", \"@type\": \"xsd:long\" },\n    \"wallTimeMillis\": { \"@id\": \"trino:wallTimeMillis\", \"@type\": \"xsd:long\" },\n    \"processedRows\": { \"@id\": \"trino:processedRows\", \"@type\": \"xsd:long\" },\n    \"processedBytes\"\
  : { \"@id\": \"trino:processedBytes\", \"@type\": \"xsd:long\" },\n    \"progressPercentage\": { \"@id\": \"trino:progressPercentage\", \"@type\": \"xsd:double\" },\n\n    \"message\": \"schema:description\",\n    \"errorCode\": \"trino:errorCode\",\n    \"errorName\": \"trino:errorName\",\n    \"errorType\": \"trino:errorType\",\n    \"errorLocation\": \"trino:errorLocation\",\n    \"lineNumber\": { \"@id\": \"trino:lineNumber\", \"@type\": \"xsd:integer\" },\n    \"columnNumber\": { \"@id\": \"trino:columnNumber\", \"@type\": \"xsd:integer\" },\n\n    \"nodeVersion\": \"trino:nodeVersion\",\n    \"version\": \"schema:version\",\n    \"environment\": \"trino:environment\",\n    \"coordinator\": { \"@id\": \"trino:coordinator\", \"@type\": \"xsd:boolean\" },\n    \"starting\": { \"@id\": \"trino:starting\", \"@type\": \"xsd:boolean\" },\n    \"uptime\": \"trino:uptime\",\n\n    \"nodeId\": \"trino:nodeId\",\n    \"nodeIp\": \"trino:nodeIp\",\n    \"lastResponseTime\": { \"@id\": \"trino:lastResponseTime\"\
  , \"@type\": \"xsd:dateTime\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/trino/refs/heads/main/json-ld/trino-context.jsonld
tags:
- Analytics
- Big Data
- Distributed SQL
- MySQL
- NoSQL
- Queries
- SQL
- JSON-LD
- Linked Data
- Semantic Web
---
