---
api_specs:
- filename: istio-networking-api-openapi.yml
  format: yaml
  label: Istio Networking API
  slug: networking-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/istio/refs/heads/main/openapi/istio-networking-api-openapi.yml
- filename: istio-security-api-openapi.yml
  format: yaml
  label: Istio Security API
  slug: security-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/istio/refs/heads/main/openapi/istio-security-api-openapi.yml
- filename: istio-telemetry-api-openapi.yml
  format: yaml
  label: Istio Telemetry API
  slug: telemetry-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/istio/refs/heads/main/openapi/istio-telemetry-api-openapi.yml
- filename: istio-extensions-api-openapi.yml
  format: yaml
  label: Istio Extensions API
  slug: extensions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/istio/refs/heads/main/openapi/istio-extensions-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/istio-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/istio/refs/heads/main/json-ld/istio-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Istio from Istio.
layout: jsonld
name: Istio Context
namespaces:
- prefix: istio
  uri: https://istio.io/latest/docs/reference/config/
- prefix: networking
  uri: https://istio.io/latest/docs/reference/config/networking/
- prefix: security
  uri: https://istio.io/latest/docs/reference/config/security/
- prefix: telemetry
  uri: https://istio.io/latest/docs/reference/config/telemetry/
- prefix: extensions
  uri: https://istio.io/latest/docs/reference/config/
properties:
- container: ''
  name: VirtualService
  type: ''
- container: ''
  name: DestinationRule
  type: ''
- container: ''
  name: Gateway
  type: ''
- container: ''
  name: ServiceEntry
  type: ''
- container: ''
  name: Sidecar
  type: ''
- container: ''
  name: AuthorizationPolicy
  type: ''
- container: ''
  name: PeerAuthentication
  type: ''
- container: ''
  name: RequestAuthentication
  type: ''
- container: ''
  name: Telemetry
  type: ''
- container: ''
  name: WasmPlugin
  type: ''
property_count: 10
provider_name: Istio
provider_slug: istio
slug: istio-context
source_filename: istio-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"istio\": \"https://istio.io/latest/docs/reference/config/\",\n    \"networking\": \"https://istio.io/latest/docs/reference/config/networking/\",\n    \"security\": \"https://istio.io/latest/docs/reference/config/security/\",\n    \"telemetry\": \"https://istio.io/latest/docs/reference/config/telemetry/\",\n    \"extensions\": \"https://istio.io/latest/docs/reference/config/\",\n    \"VirtualService\": {\n      \"@id\": \"networking:virtual-service\",\n      \"@context\": {\n        \"hosts\": \"https://schema.org/url\",\n        \"gateways\": \"https://schema.org/identifier\",\n        \"http\": \"https://schema.org/hasPart\",\n        \"tls\": \"https://schema.org/hasPart\",\n        \"tcp\": \"https://schema.org/hasPart\",\n        \"exportTo\": \"https://schema.org/audience\"\n      }\n    },\n    \"DestinationRule\": {\n      \"@id\": \"networking:destination-rule\",\n      \"@context\": {\n        \"\
  host\": \"https://schema.org/url\",\n        \"trafficPolicy\": \"https://schema.org/hasPart\",\n        \"subsets\": \"https://schema.org/hasPart\",\n        \"exportTo\": \"https://schema.org/audience\",\n        \"workloadSelector\": \"https://schema.org/targetCollection\"\n      }\n    },\n    \"Gateway\": {\n      \"@id\": \"networking:gateway\",\n      \"@context\": {\n        \"selector\": \"https://schema.org/targetCollection\",\n        \"servers\": \"https://schema.org/hasPart\"\n      }\n    },\n    \"ServiceEntry\": {\n      \"@id\": \"networking:service-entry\",\n      \"@context\": {\n        \"hosts\": \"https://schema.org/url\",\n        \"addresses\": \"https://schema.org/identifier\",\n        \"ports\": \"https://schema.org/hasPart\",\n        \"location\": \"https://schema.org/category\",\n        \"resolution\": \"https://schema.org/category\",\n        \"endpoints\": \"https://schema.org/hasPart\",\n        \"exportTo\": \"https://schema.org/audience\",\n        \"\
  subjectAltNames\": \"https://schema.org/identifier\"\n      }\n    },\n    \"Sidecar\": {\n      \"@id\": \"networking:sidecar\",\n      \"@context\": {\n        \"workloadSelector\": \"https://schema.org/targetCollection\",\n        \"ingress\": \"https://schema.org/hasPart\",\n        \"egress\": \"https://schema.org/hasPart\",\n        \"outboundTrafficPolicy\": \"https://schema.org/actionOption\"\n      }\n    },\n    \"AuthorizationPolicy\": {\n      \"@id\": \"security:authorization-policy\",\n      \"@context\": {\n        \"selector\": \"https://schema.org/targetCollection\",\n        \"targetRefs\": \"https://schema.org/targetCollection\",\n        \"action\": \"https://schema.org/actionOption\",\n        \"provider\": \"https://schema.org/provider\",\n        \"rules\": \"https://schema.org/hasPart\"\n      }\n    },\n    \"PeerAuthentication\": {\n      \"@id\": \"security:peer_authentication\",\n      \"@context\": {\n        \"selector\": \"https://schema.org/targetCollection\"\
  ,\n        \"mtls\": \"https://schema.org/securityClearance\",\n        \"portLevelMtls\": \"https://schema.org/securityClearance\"\n      }\n    },\n    \"RequestAuthentication\": {\n      \"@id\": \"security:request_authentication\",\n      \"@context\": {\n        \"selector\": \"https://schema.org/targetCollection\",\n        \"targetRefs\": \"https://schema.org/targetCollection\",\n        \"jwtRules\": \"https://schema.org/hasPart\"\n      }\n    },\n    \"Telemetry\": {\n      \"@id\": \"telemetry:telemetry\",\n      \"@context\": {\n        \"selector\": \"https://schema.org/targetCollection\",\n        \"targetRefs\": \"https://schema.org/targetCollection\",\n        \"tracing\": \"https://schema.org/hasPart\",\n        \"metrics\": \"https://schema.org/hasPart\",\n        \"accessLogging\": \"https://schema.org/hasPart\"\n      }\n    },\n    \"WasmPlugin\": {\n      \"@id\": \"extensions:wasm-plugin\",\n      \"@context\": {\n        \"selector\": \"https://schema.org/targetCollection\"\
  ,\n        \"targetRefs\": \"https://schema.org/targetCollection\",\n        \"url\": \"https://schema.org/url\",\n        \"sha256\": \"https://schema.org/identifier\",\n        \"imagePullPolicy\": \"https://schema.org/actionOption\",\n        \"pluginConfig\": \"https://schema.org/softwareRequirements\",\n        \"pluginName\": \"https://schema.org/name\",\n        \"phase\": \"https://schema.org/category\",\n        \"priority\": \"https://schema.org/position\",\n        \"failStrategy\": \"https://schema.org/actionOption\",\n        \"type\": \"https://schema.org/category\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/istio/refs/heads/main/json-ld/istio-context.jsonld
tags:
- CNCF
- Kubernetes
- Microservices
- Open Source
- Service Mesh
- JSON-LD
- Linked Data
- Semantic Web
---
