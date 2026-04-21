---
class_count: 14
classes:
- DatabaseList
- Database
- DatabaseRequest
- DataSourceList
- DataSource
- DataSourceRequest
- ShardingRuleList
- ShardingRule
- ShardingTable
- ShardingStrategy
- ReadwriteSplittingRuleList
- ReadwriteSplittingRule
- ClusterStatus
- Instance
context_file: json-ld/apache-shardingsphere-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-shardingsphere/refs/heads/main/json-ld/apache-shardingsphere-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Shardingsphere from Apache ShardingSphere.
layout: jsonld
name: Apache Shardingsphere Context
namespaces:
- prefix: shar
  uri: https://shardingsphere.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: databases
  type: ''
- container: ''
  name: name
  type: schema:name
- container: set
  name: dataSources
  type: ''
- container: ''
  name: url
  type: schema:url
- container: ''
  name: username
  type: string
- container: ''
  name: maxPoolSize
  type: integer
- container: ''
  name: minPoolSize
  type: integer
- container: ''
  name: type
  type: string
- container: ''
  name: password
  type: string
- container: set
  name: rules
  type: ''
- container: set
  name: tables
  type: ''
- container: set
  name: bindingTables
  type: ''
- container: ''
  name: logicTable
  type: string
- container: ''
  name: actualDataNodes
  type: string
- container: ''
  name: databaseStrategy
  type: string
- container: ''
  name: tableStrategy
  type: string
- container: ''
  name: shardingColumn
  type: string
- container: ''
  name: shardingAlgorithmName
  type: string
- container: ''
  name: writeDataSourceName
  type: string
- container: set
  name: readDataSourceNames
  type: ''
- container: ''
  name: loadBalancerName
  type: string
- container: ''
  name: mode
  type: string
- container: set
  name: instances
  type: ''
- container: ''
  name: instanceId
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: host
  type: string
- container: ''
  name: port
  type: integer
property_count: 27
provider_name: Apache ShardingSphere
provider_slug: apache-shardingsphere
slug: apache-shardingsphere-context
tags:
- Database
- Distributed SQL
- Read-Write Splitting
- Sharding
- SQL
- Apache
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
