---
api_specs:
- filename: amazon-elasticache-openapi.yml
  format: yaml
  label: Amazon ElastiCache API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-elasticache/refs/heads/main/openapi/amazon-elasticache-openapi.yml
class_count: 0
classes: []
context_file: json-ld/amazon-elasticache-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-elasticache/refs/heads/main/json-ld/amazon-elasticache-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Elasticache from Amazon ElastiCache.
layout: jsonld
name: Amazon Elasticache Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/elasticache/
- prefix: elasticache
  uri: https://docs.aws.amazon.com/AmazonElastiCache/latest/APIReference/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: CacheCluster
  type: SoftwareApplication
- container: ''
  name: ReplicationGroup
  type: SoftwareApplication
- container: ''
  name: CacheNode
  type: Thing
property_count: 3
provider_name: Amazon ElastiCache
provider_slug: amazon-elasticache
slug: amazon-elasticache-context
source_filename: amazon-elasticache-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"aws\": \"https://aws.amazon.com/elasticache/\",\n    \"elasticache\": \"https://docs.aws.amazon.com/AmazonElastiCache/latest/APIReference/\",\n    \"CacheCluster\": {\n      \"@id\": \"aws:CacheCluster\",\n      \"@type\": \"SoftwareApplication\",\n      \"@context\": {\n        \"CacheClusterId\": {\n          \"@id\": \"aws:CacheClusterId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ARN\": {\n          \"@id\": \"aws:ARN\",\n          \"@type\": \"@id\"\n        },\n        \"CacheClusterStatus\": {\n          \"@id\": \"schema:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Engine\": {\n          \"@id\": \"aws:Engine\",\n          \"@type\": \"xsd:string\"\n        },\n        \"EngineVersion\": {\n          \"@id\": \"schema:softwareVersion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"CacheNodeType\": {\n          \"@id\": \"aws:CacheNodeType\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"NumCacheNodes\": {\n          \"@id\": \"aws:NumCacheNodes\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"PreferredAvailabilityZone\": {\n          \"@id\": \"aws:PreferredAvailabilityZone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"CacheClusterCreateTime\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"CacheSubnetGroupName\": {\n          \"@id\": \"aws:CacheSubnetGroupName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Port\": {\n          \"@id\": \"aws:Port\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"TransitEncryptionEnabled\": {\n          \"@id\": \"aws:TransitEncryptionEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"AtRestEncryptionEnabled\": {\n          \"@id\": \"aws:AtRestEncryptionEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"SnapshotRetentionLimit\"\
  : {\n          \"@id\": \"aws:SnapshotRetentionLimit\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"AutoMinorVersionUpgrade\": {\n          \"@id\": \"aws:AutoMinorVersionUpgrade\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n    \"ReplicationGroup\": {\n      \"@id\": \"aws:ReplicationGroup\",\n      \"@type\": \"SoftwareApplication\",\n      \"@context\": {\n        \"ReplicationGroupId\": {\n          \"@id\": \"aws:ReplicationGroupId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Status\": {\n          \"@id\": \"schema:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"AutomaticFailover\": {\n          \"@id\": \"aws:AutomaticFailover\",\n          \"@type\": \"xsd:string\"\n        },\n        \"MemberClusters\": {\n          \"@id\": \"aws:MemberClusters\",\n          \"@type\": \"@id\"\
  \n        }\n      }\n    },\n    \"CacheNode\": {\n      \"@id\": \"aws:CacheNode\",\n      \"@type\": \"Thing\",\n      \"@context\": {\n        \"CacheNodeId\": {\n          \"@id\": \"aws:CacheNodeId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"CacheNodeStatus\": {\n          \"@id\": \"schema:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"CacheNodeCreateTime\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"Endpoint\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"CustomerAvailabilityZone\": {\n          \"@id\": \"aws:CustomerAvailabilityZone\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-elasticache/refs/heads/main/json-ld/amazon-elasticache-context.jsonld
tags:
- Amazon Web Services
- Caching
- Database
- ElastiCache
- In-Memory
- Memcached
- Redis
- JSON-LD
- Linked Data
- Semantic Web
---
