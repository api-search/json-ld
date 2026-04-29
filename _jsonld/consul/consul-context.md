---
api_specs:
- filename: consul-http-api.yml
  format: yaml
  label: Consul HTTP API
  slug: http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/consul/refs/heads/main/openapi/consul-http-api.yml
class_count: 0
classes: []
context_file: json-ld/consul-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/consul/refs/heads/main/json-ld/consul-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Consul from HashiCorp Consul.
layout: jsonld
name: Consul Context
namespaces:
- prefix: consul
  uri: https://www.consul.io/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Service
  type: ''
- container: ''
  name: Node
  type: ''
- container: ''
  name: HealthCheck
  type: ''
- container: ''
  name: KVPair
  type: ''
- container: ''
  name: ACLToken
  type: ''
- container: ''
  name: Intention
  type: ''
property_count: 6
provider_name: HashiCorp Consul
provider_slug: consul
slug: consul-context
source_filename: consul-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"consul\": \"https://www.consul.io/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Service\": {\n      \"@id\": \"consul:Service\",\n      \"@context\": {\n        \"id\": \"consul:ID\",\n        \"name\": \"consul:Service\",\n        \"tags\": \"consul:Tags\",\n        \"address\": \"consul:Address\",\n        \"port\": \"consul:Port\",\n        \"meta\": \"consul:Meta\",\n        \"namespace\": \"consul:Namespace\",\n        \"datacenter\": \"consul:Datacenter\"\n      }\n    },\n\n    \"Node\": {\n      \"@id\": \"consul:Node\",\n      \"@context\": {\n        \"id\": \"consul:ID\",\n        \"node\": \"consul:Node\",\n        \"address\": \"consul:Address\",\n        \"datacenter\": \"consul:Datacenter\",\n        \"taggedAddresses\": \"consul:TaggedAddresses\",\n        \"meta\": \"consul:Meta\"\n      }\n\
  \    },\n\n    \"HealthCheck\": {\n      \"@id\": \"consul:HealthCheck\",\n      \"@context\": {\n        \"node\": \"consul:Node\",\n        \"checkID\": \"consul:CheckID\",\n        \"name\": \"consul:Name\",\n        \"status\": \"consul:Status\",\n        \"notes\": \"consul:Notes\",\n        \"output\": \"consul:Output\",\n        \"serviceID\": \"consul:ServiceID\",\n        \"serviceName\": \"consul:ServiceName\"\n      }\n    },\n\n    \"KVPair\": {\n      \"@id\": \"consul:KVPair\",\n      \"@context\": {\n        \"key\": \"consul:Key\",\n        \"value\": \"consul:Value\",\n        \"flags\": \"consul:Flags\",\n        \"createIndex\": \"consul:CreateIndex\",\n        \"modifyIndex\": \"consul:ModifyIndex\",\n        \"lockIndex\": \"consul:LockIndex\",\n        \"session\": \"consul:Session\"\n      }\n    },\n\n    \"ACLToken\": {\n      \"@id\": \"consul:ACLToken\",\n      \"@context\": {\n        \"accessorID\": \"consul:AccessorID\",\n        \"secretID\": \"consul:SecretID\"\
  ,\n        \"description\": \"schema:description\",\n        \"policies\": \"consul:Policies\",\n        \"roles\": \"consul:Roles\",\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Intention\": {\n      \"@id\": \"consul:Intention\",\n      \"@context\": {\n        \"id\": \"consul:ID\",\n        \"sourceName\": \"consul:SourceName\",\n        \"destinationName\": \"consul:DestinationName\",\n        \"action\": \"consul:Action\",\n        \"description\": \"schema:description\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/consul/refs/heads/main/json-ld/consul-context.jsonld
tags:
- ACL
- Configuration
- Health Checking
- Key/Value Store
- Multi-Datacenter
- Open Source
- Service Discovery
- Service Mesh
- JSON-LD
- Linked Data
- Semantic Web
---
