---
api_specs:
- filename: virtual_service.proto
  format: yaml
  label: Istio Service Mesh API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/istio/api/master/networking/v1alpha3/virtual_service.proto
- filename: api
  format: yaml
  label: Envoy Proxy Admin API
  slug: ''
  spec_type: OpenAPI
  url: https://www.envoyproxy.io/docs/envoy/latest/api-v3/api
- filename: openapi.yaml
  format: yaml
  label: Apache Kafka REST Proxy API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/confluentinc/kafka-rest/master/api/v3/openapi.yaml
- filename: index.json
  format: json
  label: RabbitMQ Management HTTP API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/rabbitmq/rabbitmq-server/main/deps/rabbitmq_management/priv/www/api/index.json
- filename: swagger.json
  format: json
  label: Kubernetes API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/kubernetes/kubernetes/master/api/openapi-spec/swagger.json
- filename: swagger.json
  format: json
  label: Argo Workflows API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/argoproj/argo-workflows/main/api/openapi-spec/swagger.json
class_count: 17
classes:
- name
- description
- version
- domain
- team
- api
- protocol
- circuitBreaker
- retry
- tracing
- serviceMesh
- eventDriven
- boundedContext
- sagaPattern
- cqrs
- eventSourcing
- tags
context_file: json-ld/scalable-architecture-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/scalable-architecture/refs/heads/main/json-ld/scalable-architecture-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Scalable Architecture from Scalable Architecture.
layout: jsonld
name: Scalable Architecture Context
namespaces:
- prefix: arch
  uri: https://raw.githubusercontent.com/api-evangelist/scalable-architecture/main/json-ld/scalable-architecture-context.jsonld#
- prefix: k8s
  uri: https://kubernetes.io/ns/
- prefix: cncf
  uri: https://cncf.io/ns/
properties:
- container: ''
  name: Microservice
  type: reference
- container: ''
  name: ServiceMesh
  type: reference
- container: ''
  name: MessageBroker
  type: reference
- container: ''
  name: EventStream
  type: reference
- container: ''
  name: ContainerOrchestrator
  type: reference
- container: ''
  name: WorkflowEngine
  type: reference
- container: ''
  name: Cache
  type: reference
- container: list
  name: dependencies
  type: ''
property_count: 8
provider_name: Scalable Architecture
provider_slug: scalable-architecture
slug: scalable-architecture-context
source_filename: scalable-architecture-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.org/\",\n    \"arch\": \"https://raw.githubusercontent.com/api-evangelist/scalable-architecture/main/json-ld/scalable-architecture-context.jsonld#\",\n    \"k8s\": \"https://kubernetes.io/ns/\",\n    \"cncf\": \"https://cncf.io/ns/\",\n\n    \"Microservice\": {\n      \"@id\": \"arch:Microservice\",\n      \"@type\": \"@id\",\n      \"comment\": \"An independently deployable service with a single bounded context and API contract.\"\n    },\n    \"ServiceMesh\": {\n      \"@id\": \"arch:ServiceMesh\",\n      \"@type\": \"@id\",\n      \"comment\": \"Infrastructure layer for service-to-service communication with mTLS, observability, and traffic management.\"\n    },\n    \"MessageBroker\": {\n      \"@id\": \"arch:MessageBroker\",\n      \"@type\": \"@id\",\n      \"comment\": \"A component that mediates asynchronous communication between services via message queues or event streams.\"\n    },\n  \
  \  \"EventStream\": {\n      \"@id\": \"arch:EventStream\",\n      \"@type\": \"@id\",\n      \"comment\": \"An ordered, durable log of events used for event sourcing and stream processing.\"\n    },\n    \"ContainerOrchestrator\": {\n      \"@id\": \"arch:ContainerOrchestrator\",\n      \"@type\": \"@id\",\n      \"comment\": \"A system that automates deployment, scaling, and management of containerized workloads.\"\n    },\n    \"WorkflowEngine\": {\n      \"@id\": \"arch:WorkflowEngine\",\n      \"@type\": \"@id\",\n      \"comment\": \"A system that orchestrates multi-step processes including parallel and conditional execution.\"\n    },\n    \"Cache\": {\n      \"@id\": \"arch:Cache\",\n      \"@type\": \"@id\",\n      \"comment\": \"A high-speed data storage layer for reducing load on primary data stores.\"\n    },\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"version\": \"schema:version\",\n    \"domain\": \"arch:domain\",\n    \"team\":\
  \ \"arch:team\",\n    \"api\": \"arch:api\",\n    \"protocol\": \"schema:protocol\",\n    \"dependencies\": {\n      \"@id\": \"arch:dependencies\",\n      \"@container\": \"@list\"\n    },\n    \"circuitBreaker\": \"arch:circuitBreaker\",\n    \"retry\": \"arch:retry\",\n    \"tracing\": \"arch:tracing\",\n    \"serviceMesh\": \"arch:serviceMesh\",\n    \"eventDriven\": \"arch:eventDriven\",\n    \"boundedContext\": \"arch:boundedContext\",\n    \"sagaPattern\": \"arch:sagaPattern\",\n    \"cqrs\": \"arch:cqrs\",\n    \"eventSourcing\": \"arch:eventSourcing\",\n    \"tags\": \"schema:keywords\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/scalable-architecture/refs/heads/main/json-ld/scalable-architecture-context.jsonld
tags:
- Cloud Architecture
- Cloud Native
- Distributed Systems
- High Availability
- Infrastructure
- Microservices
- Performance
- Resilience
- Scalability
- Service Mesh
- JSON-LD
- Linked Data
- Semantic Web
---
