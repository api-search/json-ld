---
api_specs:
- filename: service-fabric-cluster-openapi.yml
  format: yaml
  label: Service Fabric Cluster Management API
  slug: service-fabric-cluster-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/service-fabric/refs/heads/main/openapi/service-fabric-cluster-openapi.yml
class_count: 21
classes:
- Application
- Service
- Node
- Cluster
- Partition
- Replica
- Name
- TypeName
- TypeVersion
- Status
- HealthState
- Id
- IpAddressOrFQDN
- NodeStatus
- IsSeedNode
- ServiceKind
- ServiceStatus
- AggregatedHealthState
- HealthEvents
- Description
- Parameters
context_file: json-ld/service-fabric-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/service-fabric/refs/heads/main/json-ld/service-fabric-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Service Fabric from Service Fabric.
layout: jsonld
name: Service Fabric Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: sf
  uri: https://api-evangelist.github.io/service-fabric/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: StartedTimestamp
  type: dateTime
- container: ''
  name: LastModifiedUtcTimestamp
  type: dateTime
- container: ''
  name: SourceUtcTimestamp
  type: dateTime
property_count: 3
provider_name: Service Fabric
provider_slug: service-fabric
slug: service-fabric-context
source_filename: service-fabric-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"sf\": \"https://api-evangelist.github.io/service-fabric/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Application\": \"schema:SoftwareApplication\",\n    \"Service\": \"schema:Service\",\n    \"Node\": \"sf:ClusterNode\",\n    \"Cluster\": \"sf:ServiceFabricCluster\",\n    \"Partition\": \"sf:ServicePartition\",\n    \"Replica\": \"sf:ServiceReplica\",\n\n    \"Name\": \"schema:name\",\n    \"TypeName\": \"sf:typeName\",\n    \"TypeVersion\": \"schema:version\",\n    \"Status\": \"sf:lifecycleStatus\",\n    \"HealthState\": \"sf:healthState\",\n\n    \"Id\": \"@id\",\n    \"IpAddressOrFQDN\": \"schema:serverAddress\",\n    \"NodeStatus\": \"sf:nodeStatus\",\n    \"IsSeedNode\": \"sf:isSeedNode\",\n\n    \"ServiceKind\": \"sf:serviceKind\",\n    \"ServiceStatus\": \"sf:serviceStatus\",\n\n    \"AggregatedHealthState\": \"sf:aggregatedHealthState\",\n    \"\
  HealthEvents\": \"sf:healthEvents\",\n    \"Description\": \"schema:description\",\n\n    \"Parameters\": \"sf:applicationParameters\",\n\n    \"StartedTimestamp\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"LastModifiedUtcTimestamp\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"SourceUtcTimestamp\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/service-fabric/refs/heads/main/json-ld/service-fabric-context.jsonld
tags:
- Distributed Systems
- Microservices
- Containers
- Cloud Native
- Kubernetes
- Azure
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
