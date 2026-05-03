---
api_specs:
- filename: swagger.json
  format: json
  label: Kubernetes API
  slug: kubernetes
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/kubernetes/kubernetes/master/api/openapi-spec/swagger.json
class_count: 35
classes:
- ScalableService
- APIGateway
- LoadBalancer
- ServiceMesh
- Container
- Microservice
- ServerlessFunction
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
- TechArticle
- baseUrl
- apiType
- authType
- tags
- healthEndpoint
- scalingPolicy
- replicaCount
- targetCPUPercent
- loadBalancingAlgorithm
- circuitBreakerEnabled
- rateLimitPerSecond
- retryPolicy
- serviceDiscovery
- metricsEndpoint
- tracingEnabled
context_file: json-ld/scalable-services-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/scalable-services/refs/heads/main/json-ld/scalable-services-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Scalable Services from Scalable Services.
layout: jsonld
name: Scalable Services Context
namespaces:
- prefix: api
  uri: https://api-evangelist.com/vocabulary/
- prefix: svc
  uri: https://api-evangelist.com/vocabulary/scalable-services/
properties: []
property_count: 0
provider_name: Scalable Services
provider_slug: scalable-services
slug: scalable-services-context
source_filename: scalable-services-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.org/\",\n    \"api\": \"https://api-evangelist.com/vocabulary/\",\n    \"svc\": \"https://api-evangelist.com/vocabulary/scalable-services/\",\n\n    \"ScalableService\": \"svc:ScalableService\",\n    \"APIGateway\": \"svc:APIGateway\",\n    \"LoadBalancer\": \"svc:LoadBalancer\",\n    \"ServiceMesh\": \"svc:ServiceMesh\",\n    \"Container\": \"svc:Container\",\n    \"Microservice\": \"svc:Microservice\",\n    \"ServerlessFunction\": \"svc:ServerlessFunction\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"documentation\": \"schema:documentation\",\n    \"version\": \"schema:version\",\n    \"license\": \"schema:license\",\n    \"provider\": \"schema:provider\",\n    \"dateCreated\": \"schema:dateCreated\",\n    \"dateModified\": \"schema:dateModified\",\n\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"SoftwareSourceCode\"\
  : \"schema:SoftwareSourceCode\",\n    \"WebAPI\": \"schema:WebAPI\",\n    \"TechArticle\": \"schema:TechArticle\",\n\n    \"baseUrl\": \"api:baseUrl\",\n    \"apiType\": \"api:apiType\",\n    \"authType\": \"api:authType\",\n    \"tags\": \"api:tags\",\n    \"healthEndpoint\": \"svc:healthEndpoint\",\n    \"scalingPolicy\": \"svc:scalingPolicy\",\n    \"replicaCount\": \"svc:replicaCount\",\n    \"targetCPUPercent\": \"svc:targetCPUPercent\",\n    \"loadBalancingAlgorithm\": \"svc:loadBalancingAlgorithm\",\n    \"circuitBreakerEnabled\": \"svc:circuitBreakerEnabled\",\n    \"rateLimitPerSecond\": \"svc:rateLimitPerSecond\",\n    \"retryPolicy\": \"svc:retryPolicy\",\n    \"serviceDiscovery\": \"svc:serviceDiscovery\",\n    \"metricsEndpoint\": \"svc:metricsEndpoint\",\n    \"tracingEnabled\": \"svc:tracingEnabled\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/scalable-services/refs/heads/main/json-ld/scalable-services-context.jsonld
tags:
- API Gateway
- Cloud Native
- Containers
- Distributed Systems
- High Availability
- Kubernetes
- Load Balancing
- Microservices
- Scalable Architecture
- Serverless
- Service Mesh
- JSON-LD
- Linked Data
- Semantic Web
---
