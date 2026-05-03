---
api_specs:
- filename: virtual_service.proto
  format: yaml
  label: Istio API
  slug: istio-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/istio/api/master/networking/v1alpha3/virtual_service.proto
- filename: swagger.json
  format: json
  label: Consul Connect / Service Mesh API
  slug: consul-api
  spec_type: OpenAPI
  url: https://github.com/hashicorp/consul/blob/main/api/openapi-spec/swagger.json
class_count: 38
classes:
- ServiceMesh
- VirtualService
- DestinationRule
- TrafficSplit
- TrafficPolicy
- AuthorizationPolicy
- PeerAuthentication
- Gateway
- Sidecar
- ServiceEntry
- HTTPRoute
- HTTPRouteGroup
- name
- description
- namespace
- labels
- annotations
- host
- port
- weight
- protocol
- timeout
- retries
- outlierDetection
- connectionPool
- loadBalancer
- mode
- action
- source
- destination
- mtls
- trafficManagement
- observability
- accessControl
- backends
- routes
- matches
- headers
context_file: json-ld/service-mesh-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/service-mesh/refs/heads/main/json-ld/service-mesh-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Service Mesh from Service Mesh.
layout: jsonld
name: Service Mesh Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: mesh
  uri: https://api-evangelist.github.io/service-mesh/vocab/
- prefix: smi
  uri: https://smi-spec.io/vocab/
- prefix: k8s
  uri: https://kubernetes.io/docs/reference/kubernetes-api/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: created
  type: dateTime
- container: ''
  name: modified
  type: dateTime
property_count: 2
provider_name: Service Mesh
provider_slug: service-mesh
slug: service-mesh-context
source_filename: service-mesh-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"mesh\": \"https://api-evangelist.github.io/service-mesh/vocab/\",\n    \"smi\": \"https://smi-spec.io/vocab/\",\n    \"k8s\": \"https://kubernetes.io/docs/reference/kubernetes-api/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"ServiceMesh\": \"mesh:ServiceMesh\",\n    \"VirtualService\": \"mesh:VirtualService\",\n    \"DestinationRule\": \"mesh:DestinationRule\",\n    \"TrafficSplit\": \"smi:TrafficSplit\",\n    \"TrafficPolicy\": \"mesh:TrafficPolicy\",\n    \"AuthorizationPolicy\": \"mesh:AuthorizationPolicy\",\n    \"PeerAuthentication\": \"mesh:PeerAuthentication\",\n    \"Gateway\": \"mesh:Gateway\",\n    \"Sidecar\": \"mesh:Sidecar\",\n    \"ServiceEntry\": \"mesh:ServiceEntry\",\n    \"HTTPRoute\": \"mesh:HTTPRoute\",\n    \"HTTPRouteGroup\": \"smi:HTTPRouteGroup\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"namespace\"\
  : \"k8s:namespace\",\n    \"labels\": \"schema:additionalProperty\",\n    \"annotations\": \"schema:additionalProperty\",\n\n    \"host\": \"mesh:host\",\n    \"port\": \"mesh:port\",\n    \"weight\": \"schema:weight\",\n    \"protocol\": \"schema:protocol\",\n    \"timeout\": \"mesh:timeout\",\n    \"retries\": \"mesh:retries\",\n    \"outlierDetection\": \"mesh:outlierDetection\",\n    \"connectionPool\": \"mesh:connectionPool\",\n    \"loadBalancer\": \"mesh:loadBalancer\",\n\n    \"mode\": \"mesh:mode\",\n    \"action\": \"mesh:action\",\n    \"source\": \"schema:source\",\n    \"destination\": \"schema:target\",\n\n    \"mtls\": \"mesh:mutualTLS\",\n    \"trafficManagement\": \"mesh:trafficManagement\",\n    \"observability\": \"mesh:observability\",\n    \"accessControl\": \"mesh:accessControl\",\n\n    \"backends\": \"mesh:backends\",\n    \"routes\": \"mesh:routes\",\n    \"matches\": \"mesh:matches\",\n    \"headers\": \"mesh:headers\",\n\n    \"created\": {\n      \"@id\": \"\
  schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modified\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/service-mesh/refs/heads/main/json-ld/service-mesh-context.jsonld
tags:
- Service Mesh
- Microservices
- Cloud Native
- Kubernetes
- Networking
- Observability
- Zero Trust
- JSON-LD
- Linked Data
- Semantic Web
---
