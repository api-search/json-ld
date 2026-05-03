---
api_specs:
- filename: haproxy_spec.yaml
  format: yaml
  label: HAProxy Data Plane API
  slug: haproxy
  spec_type: OpenAPI
  url: https://github.com/haproxytech/dataplaneapi/blob/master/specification/build/haproxy_spec.yaml
- filename: management-api.json
  format: json
  label: RabbitMQ Management API
  slug: rabbitmq
  spec_type: OpenAPI
  url: https://www.rabbitmq.com/resources/specs/management-api.json
class_count: 38
classes:
- DistributedSystem
- CachingLayer
- MessageBroker
- LoadBalancer
- ServiceRegistry
- DatabaseCluster
- AutoScalingGroup
- name
- description
- url
- documentation
- version
- license
- provider
- dateCreated
- dateModified
- SoftwareApplication
- SoftwareSourceCode
- WebAPI
- baseUrl
- apiType
- authType
- tags
- consistencyModel
- replicationFactor
- partitionStrategy
- ttlSeconds
- evictionPolicy
- quorumSize
- raftEnabled
- sloTarget
- errorBudget
- rto
- rpo
- maxQueueDepth
- deadLetterQueue
- shardCount
- readReplicaCount
context_file: json-ld/scalable-systems-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/scalable-systems/refs/heads/main/json-ld/scalable-systems-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Scalable Systems from Scalable Systems.
layout: jsonld
name: Scalable Systems Context
namespaces:
- prefix: api
  uri: https://api-evangelist.com/vocabulary/
- prefix: sys
  uri: https://api-evangelist.com/vocabulary/scalable-systems/
properties: []
property_count: 0
provider_name: Scalable Systems
provider_slug: scalable-systems
slug: scalable-systems-context
source_filename: scalable-systems-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.org/\",\n    \"api\": \"https://api-evangelist.com/vocabulary/\",\n    \"sys\": \"https://api-evangelist.com/vocabulary/scalable-systems/\",\n\n    \"DistributedSystem\": \"sys:DistributedSystem\",\n    \"CachingLayer\": \"sys:CachingLayer\",\n    \"MessageBroker\": \"sys:MessageBroker\",\n    \"LoadBalancer\": \"sys:LoadBalancer\",\n    \"ServiceRegistry\": \"sys:ServiceRegistry\",\n    \"DatabaseCluster\": \"sys:DatabaseCluster\",\n    \"AutoScalingGroup\": \"sys:AutoScalingGroup\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"documentation\": \"schema:documentation\",\n    \"version\": \"schema:version\",\n    \"license\": \"schema:license\",\n    \"provider\": \"schema:provider\",\n    \"dateCreated\": \"schema:dateCreated\",\n    \"dateModified\": \"schema:dateModified\",\n\n    \"SoftwareApplication\": \"schema:SoftwareApplication\"\
  ,\n    \"SoftwareSourceCode\": \"schema:SoftwareSourceCode\",\n    \"WebAPI\": \"schema:WebAPI\",\n\n    \"baseUrl\": \"api:baseUrl\",\n    \"apiType\": \"api:apiType\",\n    \"authType\": \"api:authType\",\n    \"tags\": \"api:tags\",\n\n    \"consistencyModel\": \"sys:consistencyModel\",\n    \"replicationFactor\": \"sys:replicationFactor\",\n    \"partitionStrategy\": \"sys:partitionStrategy\",\n    \"ttlSeconds\": \"sys:ttlSeconds\",\n    \"evictionPolicy\": \"sys:evictionPolicy\",\n    \"quorumSize\": \"sys:quorumSize\",\n    \"raftEnabled\": \"sys:raftEnabled\",\n    \"sloTarget\": \"sys:sloTarget\",\n    \"errorBudget\": \"sys:errorBudget\",\n    \"rto\": \"sys:rto\",\n    \"rpo\": \"sys:rpo\",\n    \"maxQueueDepth\": \"sys:maxQueueDepth\",\n    \"deadLetterQueue\": \"sys:deadLetterQueue\",\n    \"shardCount\": \"sys:shardCount\",\n    \"readReplicaCount\": \"sys:readReplicaCount\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/scalable-systems/refs/heads/main/json-ld/scalable-systems-context.jsonld
tags:
- Auto Scaling
- Caching
- Cloud Infrastructure
- Distributed Systems
- High Availability
- Infrastructure
- Load Balancing
- Message Queues
- Platform Engineering
- Scalable Architecture
- Service Discovery
- JSON-LD
- Linked Data
- Semantic Web
---
