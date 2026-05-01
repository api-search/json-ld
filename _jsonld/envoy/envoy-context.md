---
api_specs:
- filename: envoy-admin-api-openapi.yml
  format: yaml
  label: Envoy Admin API
  slug: envoy-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/envoy/refs/heads/main/openapi/envoy-admin-api-openapi.yml
- filename: envoy-ai-gateway-openapi.yml
  format: yaml
  label: Envoy AI Gateway API
  slug: envoy-ai-gateway-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/envoy/refs/heads/main/openapi/envoy-ai-gateway-openapi.yml
class_count: 0
classes: []
context_file: json-ld/envoy-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/envoy/refs/heads/main/json-ld/envoy-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Envoy from Envoy.
layout: jsonld
name: Envoy Context
namespaces:
- prefix: envoy
  uri: https://www.envoyproxy.io/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: cncf
  uri: https://www.cncf.io/schemas/
properties:
- container: ''
  name: Cluster
  type: ''
- container: ''
  name: Listener
  type: ''
- container: ''
  name: RouteConfiguration
  type: ''
- container: ''
  name: VirtualHost
  type: ''
- container: ''
  name: Route
  type: ''
- container: ''
  name: Bootstrap
  type: ''
- container: ''
  name: Endpoint
  type: ''
- container: ''
  name: HealthCheck
  type: ''
- container: ''
  name: FilterChain
  type: ''
- container: ''
  name: ServerInfo
  type: ''
property_count: 10
provider_name: Envoy
provider_slug: envoy
slug: envoy-context
source_filename: envoy-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"envoy\": \"https://www.envoyproxy.io/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"cncf\": \"https://www.cncf.io/schemas/\",\n    \"Cluster\": {\n      \"@id\": \"envoy:Cluster\",\n      \"@context\": {\n        \"name\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n        \"type\": {\"@id\": \"envoy:discoveryType\", \"@type\": \"xsd:string\"},\n        \"connect_timeout\": {\"@id\": \"envoy:connectTimeout\", \"@type\": \"xsd:string\"},\n        \"lb_policy\": {\"@id\": \"envoy:loadBalancingPolicy\", \"@type\": \"xsd:string\"},\n        \"load_assignment\": {\"@id\": \"envoy:loadAssignment\", \"@type\": \"@json\"},\n        \"health_checks\": {\"@id\": \"envoy:healthChecks\", \"@container\": \"@list\"},\n        \"circuit_breakers\": {\"@id\": \"envoy:circuitBreakers\", \"@type\": \"@json\"},\n        \"outlier_detection\": {\"@id\": \"envoy:outlierDetection\"\
  , \"@type\": \"@json\"},\n        \"dns_lookup_family\": {\"@id\": \"envoy:dnsLookupFamily\", \"@type\": \"xsd:string\"},\n        \"metadata\": {\"@id\": \"envoy:metadata\", \"@type\": \"@json\"}\n      }\n    },\n    \"Listener\": {\n      \"@id\": \"envoy:Listener\",\n      \"@context\": {\n        \"name\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n        \"address\": {\"@id\": \"envoy:address\", \"@type\": \"@json\"},\n        \"filter_chains\": {\"@id\": \"envoy:filterChains\", \"@container\": \"@list\"},\n        \"listener_filters\": {\"@id\": \"envoy:listenerFilters\", \"@container\": \"@list\"},\n        \"traffic_direction\": {\"@id\": \"envoy:trafficDirection\", \"@type\": \"xsd:string\"},\n        \"per_connection_buffer_limit_bytes\": {\"@id\": \"envoy:perConnectionBufferLimitBytes\", \"@type\": \"xsd:integer\"},\n        \"bind_to_port\": {\"@id\": \"envoy:bindToPort\", \"@type\": \"xsd:boolean\"},\n        \"metadata\": {\"@id\": \"envoy:metadata\", \"@type\"\
  : \"@json\"}\n      }\n    },\n    \"RouteConfiguration\": {\n      \"@id\": \"envoy:RouteConfiguration\",\n      \"@context\": {\n        \"name\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n        \"virtual_hosts\": {\"@id\": \"envoy:virtualHosts\", \"@container\": \"@list\"},\n        \"internal_only_headers\": {\"@id\": \"envoy:internalOnlyHeaders\", \"@container\": \"@list\"},\n        \"response_headers_to_add\": {\"@id\": \"envoy:responseHeadersToAdd\", \"@container\": \"@list\"},\n        \"request_headers_to_add\": {\"@id\": \"envoy:requestHeadersToAdd\", \"@container\": \"@list\"}\n      }\n    },\n    \"VirtualHost\": {\n      \"@id\": \"envoy:VirtualHost\",\n      \"@context\": {\n        \"name\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n        \"domains\": {\"@id\": \"envoy:domains\", \"@container\": \"@list\"},\n        \"routes\": {\"@id\": \"envoy:routes\", \"@container\": \"@list\"},\n        \"require_tls\": {\"@id\": \"envoy:requireTls\"\
  , \"@type\": \"xsd:string\"},\n        \"cors\": {\"@id\": \"envoy:corsPolicy\", \"@type\": \"@json\"},\n        \"retry_policy\": {\"@id\": \"envoy:retryPolicy\", \"@type\": \"@json\"}\n      }\n    },\n    \"Route\": {\n      \"@id\": \"envoy:Route\",\n      \"@context\": {\n        \"name\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n        \"match\": {\"@id\": \"envoy:routeMatch\", \"@type\": \"@json\"},\n        \"route\": {\"@id\": \"envoy:routeAction\", \"@type\": \"@json\"},\n        \"redirect\": {\"@id\": \"envoy:redirectAction\", \"@type\": \"@json\"},\n        \"direct_response\": {\"@id\": \"envoy:directResponseAction\", \"@type\": \"@json\"},\n        \"decorator\": {\"@id\": \"envoy:decorator\", \"@type\": \"@json\"},\n        \"metadata\": {\"@id\": \"envoy:metadata\", \"@type\": \"@json\"}\n      }\n    },\n    \"Bootstrap\": {\n      \"@id\": \"envoy:Bootstrap\",\n      \"@context\": {\n        \"node\": {\"@id\": \"envoy:node\", \"@type\": \"@json\"},\n\
  \        \"static_resources\": {\"@id\": \"envoy:staticResources\", \"@type\": \"@json\"},\n        \"dynamic_resources\": {\"@id\": \"envoy:dynamicResources\", \"@type\": \"@json\"},\n        \"admin\": {\"@id\": \"envoy:adminConfig\", \"@type\": \"@json\"},\n        \"stats_config\": {\"@id\": \"envoy:statsConfig\", \"@type\": \"@json\"},\n        \"tracing\": {\"@id\": \"envoy:tracingConfig\", \"@type\": \"@json\"},\n        \"overload_manager\": {\"@id\": \"envoy:overloadManager\", \"@type\": \"@json\"},\n        \"layered_runtime\": {\"@id\": \"envoy:layeredRuntime\", \"@type\": \"@json\"}\n      }\n    },\n    \"Endpoint\": {\n      \"@id\": \"envoy:Endpoint\",\n      \"@context\": {\n        \"address\": {\"@id\": \"envoy:address\", \"@type\": \"@json\"},\n        \"health_status\": {\"@id\": \"envoy:healthStatus\", \"@type\": \"xsd:string\"},\n        \"load_balancing_weight\": {\"@id\": \"envoy:loadBalancingWeight\", \"@type\": \"xsd:integer\"},\n        \"locality\": {\"@id\"\
  : \"envoy:locality\", \"@type\": \"@json\"}\n      }\n    },\n    \"HealthCheck\": {\n      \"@id\": \"envoy:HealthCheck\",\n      \"@context\": {\n        \"timeout\": {\"@id\": \"envoy:timeout\", \"@type\": \"xsd:string\"},\n        \"interval\": {\"@id\": \"envoy:interval\", \"@type\": \"xsd:string\"},\n        \"unhealthy_threshold\": {\"@id\": \"envoy:unhealthyThreshold\", \"@type\": \"xsd:integer\"},\n        \"healthy_threshold\": {\"@id\": \"envoy:healthyThreshold\", \"@type\": \"xsd:integer\"},\n        \"http_health_check\": {\"@id\": \"envoy:httpHealthCheck\", \"@type\": \"@json\"},\n        \"tcp_health_check\": {\"@id\": \"envoy:tcpHealthCheck\", \"@type\": \"@json\"},\n        \"grpc_health_check\": {\"@id\": \"envoy:grpcHealthCheck\", \"@type\": \"@json\"}\n      }\n    },\n    \"FilterChain\": {\n      \"@id\": \"envoy:FilterChain\",\n      \"@context\": {\n        \"filter_chain_match\": {\"@id\": \"envoy:filterChainMatch\", \"@type\": \"@json\"},\n        \"filters\"\
  : {\"@id\": \"envoy:filters\", \"@container\": \"@list\"},\n        \"transport_socket\": {\"@id\": \"envoy:transportSocket\", \"@type\": \"@json\"}\n      }\n    },\n    \"ServerInfo\": {\n      \"@id\": \"envoy:ServerInfo\",\n      \"@context\": {\n        \"version\": {\"@id\": \"schema:softwareVersion\", \"@type\": \"xsd:string\"},\n        \"state\": {\"@id\": \"envoy:serverState\", \"@type\": \"xsd:string\"},\n        \"uptime_current_epoch\": {\"@id\": \"envoy:uptimeCurrentEpoch\", \"@type\": \"xsd:string\"},\n        \"uptime_all_epochs\": {\"@id\": \"envoy:uptimeAllEpochs\", \"@type\": \"xsd:string\"},\n        \"hot_restart_version\": {\"@id\": \"envoy:hotRestartVersion\", \"@type\": \"xsd:string\"},\n        \"command_line_options\": {\"@id\": \"envoy:commandLineOptions\", \"@type\": \"@json\"},\n        \"node\": {\"@id\": \"envoy:node\", \"@type\": \"@json\"}\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/envoy/refs/heads/main/json-ld/envoy-context.jsonld
tags:
- Cloud Native
- Load Balancing
- Proxy
- Service Mesh
- JSON-LD
- Linked Data
- Semantic Web
---
