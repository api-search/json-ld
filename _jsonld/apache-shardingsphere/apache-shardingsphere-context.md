---
api_specs:
- filename: apache-shardingsphere-rest-api.yaml
  format: yaml
  label: Apache ShardingSphere
  slug: apache-shardingsphere
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-shardingsphere/refs/heads/main/openapi/apache-shardingsphere-rest-api.yaml
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
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"shar\": \"https://shardingsphere.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DatabaseList\": \"shar:DatabaseList\",\n    \"Database\": \"shar:Database\",\n    \"DatabaseRequest\": \"shar:DatabaseRequest\",\n    \"DataSourceList\": \"shar:DataSourceList\",\n    \"DataSource\": \"shar:DataSource\",\n    \"DataSourceRequest\": \"shar:DataSourceRequest\",\n    \"ShardingRuleList\": \"shar:ShardingRuleList\",\n    \"ShardingRule\": \"shar:ShardingRule\",\n    \"ShardingTable\": \"shar:ShardingTable\",\n    \"ShardingStrategy\": \"shar:ShardingStrategy\",\n    \"ReadwriteSplittingRuleList\": \"shar:ReadwriteSplittingRuleList\",\n    \"ReadwriteSplittingRule\": \"shar:ReadwriteSplittingRule\",\n    \"ClusterStatus\": \"shar:ClusterStatus\",\n    \"Instance\": \"shar:Instance\",\n    \"databases\": {\n      \"@id\": \"shar:databases\",\n      \"@container\"\
  : \"@set\"\n    },\n    \"name\": {\n      \"@id\": \"shar:name\",\n      \"@type\": \"schema:name\"\n    },\n    \"dataSources\": {\n      \"@id\": \"shar:dataSources\",\n      \"@container\": \"@set\"\n    },\n    \"url\": {\n      \"@id\": \"shar:url\",\n      \"@type\": \"schema:url\"\n    },\n    \"username\": {\n      \"@id\": \"shar:username\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxPoolSize\": {\n      \"@id\": \"shar:maxPoolSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"minPoolSize\": {\n      \"@id\": \"shar:minPoolSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"type\": {\n      \"@id\": \"shar:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"password\": {\n      \"@id\": \"shar:password\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rules\": {\n      \"@id\": \"shar:rules\",\n      \"@container\": \"@set\"\n    },\n    \"tables\": {\n      \"@id\": \"shar:tables\",\n      \"@container\": \"@set\"\n    },\n    \"bindingTables\": {\n \
  \     \"@id\": \"shar:bindingTables\",\n      \"@container\": \"@set\"\n    },\n    \"logicTable\": {\n      \"@id\": \"shar:logicTable\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actualDataNodes\": {\n      \"@id\": \"shar:actualDataNodes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"databaseStrategy\": {\n      \"@id\": \"shar:databaseStrategy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tableStrategy\": {\n      \"@id\": \"shar:tableStrategy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shardingColumn\": {\n      \"@id\": \"shar:shardingColumn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shardingAlgorithmName\": {\n      \"@id\": \"shar:shardingAlgorithmName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"writeDataSourceName\": {\n      \"@id\": \"shar:writeDataSourceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"readDataSourceNames\": {\n      \"@id\": \"shar:readDataSourceNames\",\n      \"@container\": \"@set\"\n    },\n    \"loadBalancerName\"\
  : {\n      \"@id\": \"shar:loadBalancerName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mode\": {\n      \"@id\": \"shar:mode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instances\": {\n      \"@id\": \"shar:instances\",\n      \"@container\": \"@set\"\n    },\n    \"instanceId\": {\n      \"@id\": \"shar:instanceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"shar:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"host\": {\n      \"@id\": \"shar:host\",\n      \"@type\": \"xsd:string\"\n    },\n    \"port\": {\n      \"@id\": \"shar:port\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-shardingsphere/refs/heads/main/json-ld/apache-shardingsphere-context.jsonld
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
