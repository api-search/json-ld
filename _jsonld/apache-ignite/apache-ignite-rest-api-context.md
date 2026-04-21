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
