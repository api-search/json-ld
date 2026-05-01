---
api_specs:
- filename: envoy-proxy-admin-api-openapi.yml
  format: yaml
  label: Envoy Proxy Admin API
  slug: admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/envoy-proxy/refs/heads/main/openapi/envoy-proxy-admin-api-openapi.yml
- filename: envoy-proxy-xds-discovery-api-openapi.yml
  format: yaml
  label: Envoy Proxy xDS Discovery API
  slug: xds-discovery-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/envoy-proxy/refs/heads/main/openapi/envoy-proxy-xds-discovery-api-openapi.yml
class_count: 4
classes:
- name
- description
- url
- version
context_file: json-ld/envoy-proxy-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/envoy-proxy/refs/heads/main/json-ld/envoy-proxy-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Envoy Proxy from Envoy Proxy.
layout: jsonld
name: Envoy Proxy Context
namespaces:
- prefix: envoy
  uri: https://www.envoyproxy.io/docs/envoy/latest/api-v3/
- prefix: xds
  uri: https://www.envoyproxy.io/docs/envoy/latest/api-docs/xds_protocol
properties:
- container: ''
  name: Cluster
  type: schema:SoftwareApplication
- container: ''
  name: Listener
  type: schema:EntryPoint
- container: ''
  name: RouteConfiguration
  type: schema:WebAPI
- container: ''
  name: VirtualHost
  type: ''
- container: ''
  name: Endpoint
  type: schema:ServiceChannel
- container: ''
  name: DiscoveryRequest
  type: ''
- container: ''
  name: DiscoveryResponse
  type: ''
- container: ''
  name: Node
  type: ''
- container: ''
  name: SocketAddress
  type: ''
- container: ''
  name: Locality
  type: ''
property_count: 10
provider_name: Envoy Proxy
provider_slug: envoy-proxy
slug: envoy-proxy-context
source_filename: envoy-proxy-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"envoy\": \"https://www.envoyproxy.io/docs/envoy/latest/api-v3/\",\n    \"xds\": \"https://www.envoyproxy.io/docs/envoy/latest/api-docs/xds_protocol\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"version\": \"schema:softwareVersion\",\n    \"Cluster\": {\n      \"@id\": \"envoy:config/cluster/v3/cluster.proto\",\n      \"@type\": \"schema:SoftwareApplication\",\n      \"name\": \"schema:name\",\n      \"type\": \"envoy:config/cluster/v3/cluster.proto#Cluster.DiscoveryType\",\n      \"connect_timeout\": \"schema:duration\",\n      \"lb_policy\": \"envoy:config/cluster/v3/cluster.proto#Cluster.LbPolicy\",\n      \"load_assignment\": \"envoy:config/endpoint/v3/endpoint.proto#ClusterLoadAssignment\",\n      \"health_checks\": \"envoy:config/core/v3/health_check.proto#HealthCheck\",\n      \"circuit_breakers\": \"envoy:config/cluster/v3/circuit_breaker.proto#CircuitBreakers\"\
  \n    },\n    \"Listener\": {\n      \"@id\": \"envoy:config/listener/v3/listener.proto\",\n      \"@type\": \"schema:EntryPoint\",\n      \"name\": \"schema:name\",\n      \"address\": \"envoy:config/core/v3/address.proto#Address\",\n      \"filter_chains\": \"envoy:config/listener/v3/listener_components.proto#FilterChain\",\n      \"listener_filters\": \"envoy:config/listener/v3/listener_components.proto#ListenerFilter\",\n      \"traffic_direction\": \"envoy:config/core/v3/base.proto#TrafficDirection\"\n    },\n    \"RouteConfiguration\": {\n      \"@id\": \"envoy:config/route/v3/route.proto\",\n      \"@type\": \"schema:WebAPI\",\n      \"name\": \"schema:name\",\n      \"virtual_hosts\": \"envoy:config/route/v3/route_components.proto#VirtualHost\"\n    },\n    \"VirtualHost\": {\n      \"@id\": \"envoy:config/route/v3/route_components.proto#VirtualHost\",\n      \"name\": \"schema:name\",\n      \"domains\": \"schema:url\",\n      \"routes\": \"envoy:config/route/v3/route_components.proto#Route\"\
  \n    },\n    \"Endpoint\": {\n      \"@id\": \"envoy:config/endpoint/v3/endpoint.proto\",\n      \"@type\": \"schema:ServiceChannel\",\n      \"cluster_name\": \"schema:name\",\n      \"endpoints\": \"envoy:config/endpoint/v3/endpoint_components.proto#LocalityLbEndpoints\"\n    },\n    \"DiscoveryRequest\": {\n      \"@id\": \"xds#DiscoveryRequest\",\n      \"version_info\": \"schema:version\",\n      \"node\": \"envoy:config/core/v3/base.proto#Node\",\n      \"resource_names\": \"schema:name\",\n      \"type_url\": \"schema:additionalType\"\n    },\n    \"DiscoveryResponse\": {\n      \"@id\": \"xds#DiscoveryResponse\",\n      \"version_info\": \"schema:version\",\n      \"resources\": \"schema:itemListElement\",\n      \"type_url\": \"schema:additionalType\",\n      \"nonce\": \"schema:identifier\"\n    },\n    \"Node\": {\n      \"@id\": \"envoy:config/core/v3/base.proto#Node\",\n      \"id\": \"schema:identifier\",\n      \"cluster\": \"schema:memberOf\",\n      \"locality\": \"schema:location\"\
  ,\n      \"user_agent_name\": \"schema:applicationCategory\"\n    },\n    \"SocketAddress\": {\n      \"@id\": \"envoy:config/core/v3/address.proto#SocketAddress\",\n      \"address\": \"schema:url\",\n      \"port_value\": \"schema:identifier\",\n      \"protocol\": \"schema:encodingFormat\"\n    },\n    \"Locality\": {\n      \"@id\": \"envoy:config/core/v3/base.proto#Locality\",\n      \"region\": \"schema:addressRegion\",\n      \"zone\": \"schema:addressLocality\",\n      \"sub_zone\": \"schema:addressLocality\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/envoy-proxy/refs/heads/main/json-ld/envoy-proxy-context.jsonld
tags:
- Gateways
- Proxies
- JSON-LD
- Linked Data
- Semantic Web
---
