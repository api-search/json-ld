---
class_count: 0
classes: []
context_file: json-ld/solo-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/solo/refs/heads/main/json-ld/solo-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Solo from Solo.io.
layout: jsonld
name: Solo Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: k8s
  uri: https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.28/#
- prefix: gloo
  uri: https://docs.solo.io/gloo-edge/latest/reference/api/github.com/solo-io/gloo/projects/gloo/api/v1/
- prefix: gateway
  uri: https://docs.solo.io/gloo-edge/latest/reference/api/github.com/solo-io/gloo/projects/gateway/api/v1/
- prefix: agentgateway
  uri: https://docs.solo.io/agentgateway/
properties:
- container: ''
  name: SoloIO
  type: ''
- container: ''
  name: Upstream
  type: ''
- container: ''
  name: VirtualService
  type: ''
- container: ''
  name: RouteTable
  type: ''
- container: ''
  name: Gateway
  type: ''
- container: ''
  name: AgentgatewayBackend
  type: ''
- container: ''
  name: AgentgatewayPolicy
  type: ''
- container: ''
  name: AuthConfig
  type: ''
- container: ''
  name: RateLimitConfig
  type: ''
property_count: 9
provider_name: Solo.io
provider_slug: solo
slug: solo-context
source_filename: solo-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"k8s\": \"https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.28/#\",\n    \"gloo\": \"https://docs.solo.io/gloo-edge/latest/reference/api/github.com/solo-io/gloo/projects/gloo/api/v1/\",\n    \"gateway\": \"https://docs.solo.io/gloo-edge/latest/reference/api/github.com/solo-io/gloo/projects/gateway/api/v1/\",\n    \"agentgateway\": \"https://docs.solo.io/agentgateway/\",\n\n    \"SoloIO\": {\n      \"@id\": \"schema:Organization\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"url\": \"schema:url\",\n        \"description\": \"schema:description\"\n      }\n    },\n\n    \"Upstream\": {\n      \"@id\": \"gloo:Upstream\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"namespace\": \"k8s:namespace\",\n        \"host\": \"schema:url\",\n        \"port\": \"schema:portNumber\",\n        \"upstreamType\": \"schema:additionalType\"\
  \n      }\n    },\n\n    \"VirtualService\": {\n      \"@id\": \"gateway:VirtualService\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"namespace\": \"k8s:namespace\",\n        \"domains\": \"schema:url\",\n        \"displayName\": \"schema:name\"\n      }\n    },\n\n    \"RouteTable\": {\n      \"@id\": \"gateway:RouteTable\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"namespace\": \"k8s:namespace\"\n      }\n    },\n\n    \"Gateway\": {\n      \"@id\": \"gateway:Gateway\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"namespace\": \"k8s:namespace\",\n        \"bindAddress\": \"schema:url\",\n        \"bindPort\": \"schema:portNumber\"\n      }\n    },\n\n    \"AgentgatewayBackend\": {\n      \"@id\": \"agentgateway:AgentgatewayBackend\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"namespace\": \"k8s:namespace\",\n        \"host\": \"schema:url\",\n        \"port\": \"schema:portNumber\"\
  \n      }\n    },\n\n    \"AgentgatewayPolicy\": {\n      \"@id\": \"agentgateway:AgentgatewayPolicy\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"namespace\": \"k8s:namespace\"\n      }\n    },\n\n    \"AuthConfig\": {\n      \"@id\": \"gloo:AuthConfig\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"namespace\": \"k8s:namespace\"\n      }\n    },\n\n    \"RateLimitConfig\": {\n      \"@id\": \"gloo:RateLimitConfig\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"namespace\": \"k8s:namespace\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/solo/refs/heads/main/json-ld/solo-context.jsonld
tags:
- AI Gateway
- Agentic AI
- API Gateway
- Envoy
- Istio
- Kubernetes
- MCP
- Service Mesh
- JSON-LD
- Linked Data
- Semantic Web
---
