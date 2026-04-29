---
class_count: 11
classes:
- ParameterGroup
- Cluster
- Snapshot
- SubnetGroup
- ACL
- CreateClusterRequest
- User
- Tag
- DescribeClustersResponse
- description
- name
context_file: json-ld/amazon-memorydb-memorydb-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-memorydb/refs/heads/main/json-ld/amazon-memorydb-memorydb-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Memorydb Memorydb Api from Amazon MemoryDB.
layout: jsonld
name: Amazon Memorydb Memorydb Api Context
namespaces:
- prefix: pan
  uri: https://pan.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: arn
  type: string
- container: ''
  name: family
  type: string
- container: ''
  name: availabilityMode
  type: string
- container: ''
  name: engineVersion
  type: string
- container: ''
  name: nodeType
  type: string
- container: ''
  name: numberOfShards
  type: integer
- container: ''
  name: status
  type: string
- container: ''
  name: tlsEnabled
  type: boolean
- container: ''
  name: clusterConfiguration
  type: reference
- container: ''
  name: kmsKeyId
  type: string
- container: ''
  name: vpcId
  type: string
- container: set
  name: userNames
  type: string
- container: ''
  name: aclName
  type: string
- container: ''
  name: clusterName
  type: string
- container: ''
  name: numReplicasPerShard
  type: integer
- container: ''
  name: numShards
  type: integer
- container: set
  name: aclNames
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: value
  type: string
- container: set
  name: clusters
  type: string
- container: ''
  name: nextToken
  type: string
property_count: 21
provider_name: Amazon MemoryDB
provider_slug: amazon-memorydb
slug: amazon-memorydb-memorydb-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ParameterGroup\": \"pan:ParameterGroup\",\n    \"Cluster\": \"pan:Cluster\",\n    \"Snapshot\": \"pan:Snapshot\",\n    \"SubnetGroup\": \"pan:SubnetGroup\",\n    \"ACL\": \"pan:ACL\",\n    \"CreateClusterRequest\": \"pan:CreateClusterRequest\",\n    \"User\": \"pan:User\",\n    \"Tag\": \"pan:Tag\",\n    \"DescribeClustersResponse\": \"pan:DescribeClustersResponse\",\n    \"arn\": {\n      \"@id\": \"pan:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"family\": {\n      \"@id\": \"pan:family\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"availabilityMode\": {\n      \"@id\": \"pan:availability_mode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"engineVersion\"\
  : {\n      \"@id\": \"pan:engine_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nodeType\": {\n      \"@id\": \"pan:node_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"numberOfShards\": {\n      \"@id\": \"pan:number_of_shards\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tlsEnabled\": {\n      \"@id\": \"pan:tls_enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"clusterConfiguration\": {\n      \"@id\": \"pan:cluster_configuration\",\n      \"@type\": \"@id\"\n    },\n    \"kmsKeyId\": {\n      \"@id\": \"pan:kms_key_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vpcId\": {\n      \"@id\": \"pan:vpc_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userNames\": {\n      \"@id\": \"pan:user_names\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aclName\": {\n      \"@id\": \"pan:acl_name\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"clusterName\": {\n      \"@id\": \"pan:cluster_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"numReplicasPerShard\": {\n      \"@id\": \"pan:num_replicas_per_shard\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"numShards\": {\n      \"@id\": \"pan:num_shards\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"aclNames\": {\n      \"@id\": \"pan:acl_names\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"key\": {\n      \"@id\": \"pan:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"pan:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clusters\": {\n      \"@id\": \"pan:clusters\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"pan:next_token\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-memorydb/refs/heads/main/json-ld/amazon-memorydb-memorydb-api-context.jsonld
tags:
- AWS
- Broadcasting
- Media Processing
- Media
- JSON-LD
- Linked Data
- Semantic Web
---
