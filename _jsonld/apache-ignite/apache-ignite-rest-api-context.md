---
class_count: 37
classes:
- MetricSet
- InvalidParam
- ResetPartitionsRequest
- GlobalPartitionStateResponse
- LocalPartitionStatesResponse
- ClusterNode
- ResetZonePartitionsRequest
- NetworkAddress
- JobState
- ClusterTag
- MetricSource
- Problem
- LocalZonePartitionStateResponse
- ResetClusterRequest
- RestartZonePartitionsRequest
- NodeState
- GlobalPartitionStatesResponse
- UnitVersionStatus
- InitCommand
- MigrateRequest
- LocalPartitionStateResponse
- UpdateJobPriorityBody
- Metric
- ClusterState
- UnitStatus
- Transaction
- NodeVersion
- RestartPartitionsRequest
- SqlQuery
- NodeInfo
- GlobalZonePartitionStateResponse
- NodeMetadata
- GlobalZonePartitionStatesResponse
- LocalZonePartitionStatesResponse
- NodeMetricSources
- name
- version
context_file: json-ld/apache-ignite-rest-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-ignite/refs/heads/main/json-ld/apache-ignite-rest-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Ignite Rest Api from Apache Ignite.
layout: jsonld
name: Apache Ignite Rest Api Context
namespaces:
- prefix: ignite
  uri: https://apache-ignite.apache.org/schema/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: schema
  type: string
- container: set
  name: metrics
  type: string
- container: ''
  name: reason
  type: string
- container: ''
  name: zoneName
  type: string
- container: set
  name: partitionIds
  type: integer
- container: ''
  name: tableName
  type: string
- container: ''
  name: partitionId
  type: integer
- container: ''
  name: tableId
  type: integer
- container: ''
  name: schemaName
  type: string
- container: ''
  name: state
  type: string
- container: set
  name: states
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: address
  type: string
- container: ''
  name: metadata
  type: string
- container: ''
  name: host
  type: string
- container: ''
  name: port
  type: integer
- container: ''
  name: status
  type: string
- container: ''
  name: createTime
  type: dateTime
- container: ''
  name: startTime
  type: dateTime
- container: ''
  name: finishTime
  type: dateTime
- container: ''
  name: clusterId
  type: string
- container: ''
  name: clusterName
  type: string
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: title
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: detail
  type: string
- container: ''
  name: node
  type: string
- container: ''
  name: traceId
  type: string
- container: set
  name: invalidParams
  type: string
- container: ''
  name: nodeName
  type: string
- container: ''
  name: estimatedRows
  type: integer
- container: set
  name: cmgNodeNames
  type: string
- container: ''
  name: metastorageReplicationFactor
  type: integer
- container: set
  name: nodeNames
  type: string
- container: set
  name: metaStorageNodes
  type: string
- container: set
  name: cmgNodes
  type: string
- container: ''
  name: clusterConfiguration
  type: string
- container: set
  name: formerClusterIds
  type: string
- container: ''
  name: priority
  type: integer
- container: ''
  name: desc
  type: string
- container: set
  name: msNodes
  type: string
- container: ''
  name: igniteVersion
  type: string
- container: ''
  name: clusterTag
  type: string
- container: set
  name: versionToStatus
  type: string
- container: ''
  name: product
  type: string
- container: ''
  name: phase
  type: string
- container: ''
  name: sql
  type: string
- container: ''
  name: jdbcPort
  type: integer
- container: ''
  name: restHost
  type: string
- container: ''
  name: httpPort
  type: integer
- container: ''
  name: httpsPort
  type: integer
- container: set
  name: sources
  type: string
property_count: 53
provider_name: Apache Ignite
provider_slug: apache-ignite
slug: apache-ignite-rest-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ignite\": \"https://apache-ignite.apache.org/schema/\",\n    \"schema\": {\n      \"@id\": \"ignite:schema\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"MetricSet\": \"ignite:MetricSet\",\n    \"InvalidParam\": \"ignite:InvalidParam\",\n    \"ResetPartitionsRequest\": \"ignite:ResetPartitionsRequest\",\n    \"GlobalPartitionStateResponse\": \"ignite:GlobalPartitionStateResponse\",\n    \"LocalPartitionStatesResponse\": \"ignite:LocalPartitionStatesResponse\",\n    \"ClusterNode\": \"ignite:ClusterNode\",\n    \"ResetZonePartitionsRequest\": \"ignite:ResetZonePartitionsRequest\",\n    \"NetworkAddress\": \"ignite:NetworkAddress\",\n    \"JobState\": \"ignite:JobState\",\n    \"ClusterTag\": \"ignite:ClusterTag\",\n    \"MetricSource\": \"ignite:MetricSource\",\n    \"Problem\": \"ignite:Problem\",\n    \"LocalZonePartitionStateResponse\"\
  : \"ignite:LocalZonePartitionStateResponse\",\n    \"ResetClusterRequest\": \"ignite:ResetClusterRequest\",\n    \"RestartZonePartitionsRequest\": \"ignite:RestartZonePartitionsRequest\",\n    \"NodeState\": \"ignite:NodeState\",\n    \"GlobalPartitionStatesResponse\": \"ignite:GlobalPartitionStatesResponse\",\n    \"UnitVersionStatus\": \"ignite:UnitVersionStatus\",\n    \"InitCommand\": \"ignite:InitCommand\",\n    \"MigrateRequest\": \"ignite:MigrateRequest\",\n    \"LocalPartitionStateResponse\": \"ignite:LocalPartitionStateResponse\",\n    \"UpdateJobPriorityBody\": \"ignite:UpdateJobPriorityBody\",\n    \"Metric\": \"ignite:Metric\",\n    \"ClusterState\": \"ignite:ClusterState\",\n    \"UnitStatus\": \"ignite:UnitStatus\",\n    \"Transaction\": \"ignite:Transaction\",\n    \"NodeVersion\": \"ignite:NodeVersion\",\n    \"RestartPartitionsRequest\": \"ignite:RestartPartitionsRequest\",\n    \"SqlQuery\": \"ignite:SqlQuery\",\n    \"NodeInfo\": \"ignite:NodeInfo\",\n    \"GlobalZonePartitionStateResponse\"\
  : \"ignite:GlobalZonePartitionStateResponse\",\n    \"NodeMetadata\": \"ignite:NodeMetadata\",\n    \"GlobalZonePartitionStatesResponse\": \"ignite:GlobalZonePartitionStatesResponse\",\n    \"LocalZonePartitionStatesResponse\": \"ignite:LocalZonePartitionStatesResponse\",\n    \"NodeMetricSources\": \"ignite:NodeMetricSources\",\n    \"name\": \"schema:name\",\n    \"metrics\": {\n      \"@id\": \"ignite:metrics\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reason\": {\n      \"@id\": \"ignite:reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"zoneName\": {\n      \"@id\": \"ignite:zoneName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partitionIds\": {\n      \"@id\": \"ignite:partitionIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"tableName\": {\n      \"@id\": \"ignite:tableName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partitionId\": {\n      \"@id\": \"ignite:partitionId\",\n     \
  \ \"@type\": \"xsd:integer\"\n    },\n    \"tableId\": {\n      \"@id\": \"ignite:tableId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"schemaName\": {\n      \"@id\": \"ignite:schemaName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"ignite:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"states\": {\n      \"@id\": \"ignite:states\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"ignite:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address\": {\n      \"@id\": \"ignite:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"ignite:metadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"host\": {\n      \"@id\": \"ignite:host\",\n      \"@type\": \"xsd:string\"\n    },\n    \"port\": {\n      \"@id\": \"ignite:port\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"status\": {\n      \"@id\": \"ignite:status\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"createTime\": {\n      \"@id\": \"ignite:createTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"startTime\": {\n      \"@id\": \"ignite:startTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"finishTime\": {\n      \"@id\": \"ignite:finishTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"clusterId\": {\n      \"@id\": \"ignite:clusterId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clusterName\": {\n      \"@id\": \"ignite:clusterName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"ignite:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"title\": {\n      \"@id\": \"ignite:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"ignite:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"ignite:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detail\": {\n      \"@id\": \"ignite:detail\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"node\": {\n      \"@id\": \"ignite:node\",\n      \"@type\": \"xsd:string\"\n    },\n    \"traceId\": {\n      \"@id\": \"ignite:traceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"invalidParams\": {\n      \"@id\": \"ignite:invalidParams\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nodeName\": {\n      \"@id\": \"ignite:nodeName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"estimatedRows\": {\n      \"@id\": \"ignite:estimatedRows\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"cmgNodeNames\": {\n      \"@id\": \"ignite:cmgNodeNames\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metastorageReplicationFactor\": {\n      \"@id\": \"ignite:metastorageReplicationFactor\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"nodeNames\": {\n      \"@id\": \"ignite:nodeNames\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": \"schema:version\",\n\
  \    \"metaStorageNodes\": {\n      \"@id\": \"ignite:metaStorageNodes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cmgNodes\": {\n      \"@id\": \"ignite:cmgNodes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clusterConfiguration\": {\n      \"@id\": \"ignite:clusterConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"formerClusterIds\": {\n      \"@id\": \"ignite:formerClusterIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"priority\": {\n      \"@id\": \"ignite:priority\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"desc\": {\n      \"@id\": \"ignite:desc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"msNodes\": {\n      \"@id\": \"ignite:msNodes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"igniteVersion\": {\n      \"@id\": \"ignite:igniteVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clusterTag\"\
  : {\n      \"@id\": \"ignite:clusterTag\",\n      \"@type\": \"xsd:string\"\n    },\n    \"versionToStatus\": {\n      \"@id\": \"ignite:versionToStatus\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"product\": {\n      \"@id\": \"ignite:product\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phase\": {\n      \"@id\": \"ignite:phase\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sql\": {\n      \"@id\": \"ignite:sql\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jdbcPort\": {\n      \"@id\": \"ignite:jdbcPort\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"restHost\": {\n      \"@id\": \"ignite:restHost\",\n      \"@type\": \"xsd:string\"\n    },\n    \"httpPort\": {\n      \"@id\": \"ignite:httpPort\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"httpsPort\": {\n      \"@id\": \"ignite:httpsPort\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sources\": {\n      \"@id\": \"ignite:sources\",\n      \"@container\": \"@set\",\n\
  \      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-ignite/refs/heads/main/json-ld/apache-ignite-rest-api-context.jsonld
tags:
- Caching
- Compute Grid
- Distributed Database
- In-Memory
- Open Source
- SQL
- JSON-LD
- Linked Data
- Semantic Web
---
