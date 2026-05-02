---
api_specs:
- filename: kgateway-kubernetes-gateway-api-openapi.yml
  format: yaml
  label: Kgateway Kubernetes Gateway API
  slug: kgateway-kubernetes-gateway-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kgateway/refs/heads/main/openapi/kgateway-kubernetes-gateway-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/kgateway-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/kgateway/refs/heads/main/json-ld/kgateway-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Kgateway from Kgateway.
layout: jsonld
name: Kgateway Context
namespaces:
- prefix: kgateway
  uri: https://kgateway.dev/docs/envoy/latest/reference/api/
properties:
- container: ''
  name: TrafficPolicy
  type: ''
- container: ''
  name: Backend
  type: ''
- container: ''
  name: DirectResponse
  type: ''
- container: ''
  name: GatewayExtension
  type: ''
- container: ''
  name: GatewayParameters
  type: ''
- container: ''
  name: HTTPListenerPolicy
  type: ''
- container: ''
  name: AIBackend
  type: ''
property_count: 7
provider_name: Kgateway
provider_slug: kgateway
slug: kgateway-context
source_filename: kgateway-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"kgateway\": \"https://kgateway.dev/docs/envoy/latest/reference/api/\",\n    \"TrafficPolicy\": {\n      \"@id\": \"kgateway:trafficpolicy\",\n      \"@context\": {\n        \"targetRefs\": \"https://schema.org/target\",\n        \"cors\": \"https://schema.org/actionOption\",\n        \"extAuth\": \"https://schema.org/AuthorizeAction\",\n        \"extProc\": \"https://schema.org/actionOption\",\n        \"rateLimit\": \"https://schema.org/actionOption\",\n        \"timeout\": \"https://schema.org/duration\",\n        \"retries\": \"https://schema.org/repeatCount\",\n        \"requestHeaderModifier\": \"https://schema.org/httpHeaders\",\n        \"responseHeaderModifier\": \"https://schema.org/httpHeaders\"\n      }\n    },\n    \"Backend\": {\n      \"@id\": \"kgateway:backend\",\n      \"@context\": {\n        \"type\": \"https://schema.org/category\",\n        \"static\": \"https://schema.org/hasPart\",\n\
  \        \"aws\": \"https://schema.org/hasPart\",\n        \"ai\": \"https://schema.org/hasPart\",\n        \"host\": \"https://schema.org/hostingOrganization\",\n        \"port\": \"https://schema.org/identifier\",\n        \"region\": \"https://schema.org/areaServed\",\n        \"lambdaFunctionName\": \"https://schema.org/name\",\n        \"provider\": \"https://schema.org/provider\"\n      }\n    },\n    \"DirectResponse\": {\n      \"@id\": \"kgateway:directresponse\",\n      \"@context\": {\n        \"statusCode\": \"https://schema.org/httpStatusCode\",\n        \"body\": \"https://schema.org/text\"\n      }\n    },\n    \"GatewayExtension\": {\n      \"@id\": \"kgateway:gatewayextension\",\n      \"@context\": {\n        \"type\": \"https://schema.org/category\",\n        \"extAuth\": \"https://schema.org/AuthorizeAction\",\n        \"extProc\": \"https://schema.org/actionOption\",\n        \"rateLimit\": \"https://schema.org/actionOption\",\n        \"grpcService\": \"https://schema.org/serviceUrl\"\
  ,\n        \"backendRef\": {\n          \"@id\": \"kgateway:backend\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n    \"GatewayParameters\": {\n      \"@id\": \"kgateway:gatewayparameters\",\n      \"@context\": {\n        \"kube\": \"https://schema.org/actionOption\",\n        \"deployment\": \"https://schema.org/actionOption\",\n        \"replicas\": \"https://schema.org/amount\",\n        \"podTemplate\": \"https://schema.org/actionOption\",\n        \"envoyContainer\": \"https://schema.org/softwareRequirements\",\n        \"service\": \"https://schema.org/serviceType\"\n      }\n    },\n    \"HTTPListenerPolicy\": {\n      \"@id\": \"kgateway:httplistenerpolicy\",\n      \"@context\": {\n        \"targetRefs\": \"https://schema.org/target\",\n        \"accessLogging\": \"https://schema.org/actionOption\",\n        \"buffer\": \"https://schema.org/actionOption\",\n        \"celValidation\": \"https://schema.org/actionOption\",\n        \"basicAuth\": \"https://schema.org/AuthorizeAction\"\
  \n      }\n    },\n    \"AIBackend\": {\n      \"@id\": \"kgateway:aibackend\",\n      \"@context\": {\n        \"provider\": \"https://schema.org/provider\",\n        \"type\": \"https://schema.org/category\",\n        \"model\": \"https://schema.org/name\",\n        \"groups\": \"https://schema.org/hasPart\",\n        \"priority\": \"https://schema.org/position\",\n        \"weight\": \"https://schema.org/amount\",\n        \"backendRef\": {\n          \"@id\": \"kgateway:backend\",\n          \"@type\": \"@id\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/kgateway/refs/heads/main/json-ld/kgateway-context.jsonld
tags:
- Gateways
- JSON-LD
- Linked Data
- Semantic Web
---
