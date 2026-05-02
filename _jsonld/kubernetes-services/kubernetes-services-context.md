---
api_specs:
- filename: kubernetes-services-openapi.yml
  format: yaml
  label: Kubernetes Services
  slug: kubernetes-services
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kubernetes-services/refs/heads/main/openapi/kubernetes-services-openapi.yml
- filename: kubernetes-ingress-openapi.yml
  format: yaml
  label: Kubernetes Ingress
  slug: kubernetes-ingress
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kubernetes-services/refs/heads/main/openapi/kubernetes-ingress-openapi.yml
- filename: kubernetes-gateway-api-openapi.yml
  format: yaml
  label: Kubernetes Gateway API
  slug: kubernetes-gateway-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kubernetes-services/refs/heads/main/openapi/kubernetes-gateway-api-openapi.yml
- filename: kubernetes-endpoint-slices-openapi.yml
  format: yaml
  label: Kubernetes EndpointSlices
  slug: kubernetes-endpoint-slices
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kubernetes-services/refs/heads/main/openapi/kubernetes-endpoint-slices-openapi.yml
- filename: kubernetes-network-policies-openapi.yml
  format: yaml
  label: Kubernetes Network Policies
  slug: kubernetes-network-policies
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kubernetes-services/refs/heads/main/openapi/kubernetes-network-policies-openapi.yml
class_count: 0
classes: []
context_file: json-ld/kubernetes-services-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/kubernetes-services/refs/heads/main/json-ld/kubernetes-services-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Kubernetes Services from Kubernetes Services.
layout: jsonld
name: Kubernetes Services Context
namespaces:
- prefix: k8s
  uri: https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.32/#
- prefix: k8snet
  uri: https://kubernetes.io/docs/concepts/services-networking/
- prefix: gwapi
  uri: https://gateway-api.sigs.k8s.io/reference/spec/#gateway.networking.k8s.io/v1.
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
properties:
- container: ''
  name: Service
  type: ''
- container: ''
  name: Endpoints
  type: ''
- container: ''
  name: EndpointSlice
  type: ''
- container: ''
  name: Ingress
  type: ''
- container: ''
  name: IngressClass
  type: ''
- container: ''
  name: NetworkPolicy
  type: ''
- container: ''
  name: GatewayClass
  type: ''
- container: ''
  name: Gateway
  type: ''
- container: ''
  name: HTTPRoute
  type: ''
- container: ''
  name: GRPCRoute
  type: ''
- container: ''
  name: apiVersion
  type: string
- container: ''
  name: kind
  type: string
- container: ''
  name: metadata
  type: ''
- container: ''
  name: name
  type: string
- container: ''
  name: namespace
  type: string
- container: ''
  name: uid
  type: string
- container: ''
  name: creationTimestamp
  type: dateTime
- container: ''
  name: deletionTimestamp
  type: dateTime
- container: index
  name: labels
  type: ''
- container: index
  name: annotations
  type: ''
- container: ''
  name: resourceVersion
  type: string
- container: ''
  name: generation
  type: integer
- container: ''
  name: spec
  type: ''
- container: ''
  name: status
  type: ''
- container: ''
  name: selector
  type: ''
- container: set
  name: ports
  type: ''
- container: set
  name: rules
  type: ''
- container: set
  name: conditions
  type: ''
property_count: 28
provider_name: Kubernetes Services
provider_slug: kubernetes-services
slug: kubernetes-services-context
source_filename: kubernetes-services-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"k8s\": \"https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.32/#\",\n    \"k8snet\": \"https://kubernetes.io/docs/concepts/services-networking/\",\n    \"gwapi\": \"https://gateway-api.sigs.k8s.io/reference/spec/#gateway.networking.k8s.io/v1.\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n\n    \"Service\": {\n      \"@id\": \"k8s:service-v1-core\",\n      \"@context\": {\n        \"spec\": \"k8s:servicespec-v1-core\",\n        \"status\": \"k8s:servicestatus-v1-core\",\n        \"type\": {\n          \"@id\": \"k8s:servicespec-type-v1-core\",\n          \"@type\": \"xsd:string\"\n        },\n        \"clusterIP\": {\n          \"@id\": \"k8s:servicespec-clusterIP-v1-core\",\n          \"@type\": \"xsd:string\"\n        },\n        \"selector\": \"k8s:servicespec-selector-v1-core\"\
  ,\n        \"ports\": {\n          \"@id\": \"k8s:servicespec-ports-v1-core\",\n          \"@container\": \"@set\"\n        },\n        \"externalName\": {\n          \"@id\": \"k8s:servicespec-externalName-v1-core\",\n          \"@type\": \"xsd:string\"\n        },\n        \"loadBalancerIP\": {\n          \"@id\": \"k8s:servicespec-loadBalancerIP-v1-core\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Endpoints\": {\n      \"@id\": \"k8s:endpoints-v1-core\",\n      \"@context\": {\n        \"subsets\": {\n          \"@id\": \"k8s:endpoints-subsets-v1-core\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"EndpointSlice\": {\n      \"@id\": \"k8s:endpointslice-v1-discovery.k8s.io\",\n      \"@context\": {\n        \"addressType\": {\n          \"@id\": \"k8s:endpointslice-addressType-v1-discovery.k8s.io\",\n          \"@type\": \"xsd:string\"\n        },\n        \"endpoints\": {\n          \"@id\": \"k8s:endpointslice-endpoints-v1-discovery.k8s.io\"\
  ,\n          \"@container\": \"@set\"\n        },\n        \"ports\": {\n          \"@id\": \"k8s:endpointslice-ports-v1-discovery.k8s.io\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Ingress\": {\n      \"@id\": \"k8s:ingress-v1-networking.k8s.io\",\n      \"@context\": {\n        \"spec\": \"k8s:ingressspec-v1-networking.k8s.io\",\n        \"status\": \"k8s:ingressstatus-v1-networking.k8s.io\",\n        \"ingressClassName\": {\n          \"@id\": \"k8s:ingressspec-ingressClassName-v1-networking.k8s.io\",\n          \"@type\": \"xsd:string\"\n        },\n        \"rules\": {\n          \"@id\": \"k8s:ingressspec-rules-v1-networking.k8s.io\",\n          \"@container\": \"@set\"\n        },\n        \"tls\": {\n          \"@id\": \"k8s:ingressspec-tls-v1-networking.k8s.io\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"IngressClass\": {\n      \"@id\": \"k8s:ingressclass-v1-networking.k8s.io\",\n      \"@context\": {\n        \"\
  controller\": {\n          \"@id\": \"k8s:ingressclassspec-controller-v1-networking.k8s.io\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"NetworkPolicy\": {\n      \"@id\": \"k8s:networkpolicy-v1-networking.k8s.io\",\n      \"@context\": {\n        \"spec\": \"k8s:networkpolicyspec-v1-networking.k8s.io\",\n        \"podSelector\": \"k8s:networkpolicyspec-podSelector-v1-networking.k8s.io\",\n        \"policyTypes\": {\n          \"@id\": \"k8s:networkpolicyspec-policyTypes-v1-networking.k8s.io\",\n          \"@container\": \"@set\"\n        },\n        \"ingress\": {\n          \"@id\": \"k8s:networkpolicyspec-ingress-v1-networking.k8s.io\",\n          \"@container\": \"@set\"\n        },\n        \"egress\": {\n          \"@id\": \"k8s:networkpolicyspec-egress-v1-networking.k8s.io\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"GatewayClass\": {\n      \"@id\": \"gwapi:GatewayClass\",\n      \"@context\": {\n        \"controllerName\"\
  : {\n          \"@id\": \"gwapi:GatewayClassSpec.controllerName\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Gateway\": {\n      \"@id\": \"gwapi:Gateway\",\n      \"@context\": {\n        \"gatewayClassName\": {\n          \"@id\": \"gwapi:GatewaySpec.gatewayClassName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"listeners\": {\n          \"@id\": \"gwapi:GatewaySpec.listeners\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"HTTPRoute\": {\n      \"@id\": \"gwapi:HTTPRoute\",\n      \"@context\": {\n        \"parentRefs\": {\n          \"@id\": \"gwapi:HTTPRouteSpec.parentRefs\",\n          \"@container\": \"@set\"\n        },\n        \"hostnames\": {\n          \"@id\": \"gwapi:HTTPRouteSpec.hostnames\",\n          \"@container\": \"@set\"\n        },\n        \"rules\": {\n          \"@id\": \"gwapi:HTTPRouteSpec.rules\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"GRPCRoute\":\
  \ {\n      \"@id\": \"gwapi:GRPCRoute\",\n      \"@context\": {\n        \"parentRefs\": {\n          \"@id\": \"gwapi:GRPCRouteSpec.parentRefs\",\n          \"@container\": \"@set\"\n        },\n        \"rules\": {\n          \"@id\": \"gwapi:GRPCRouteSpec.rules\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"apiVersion\": {\n      \"@id\": \"k8s:apiversion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kind\": {\n      \"@id\": \"k8s:kind\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"k8s:objectmeta-v1-meta\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"namespace\": {\n      \"@id\": \"k8s:namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uid\": {\n      \"@id\": \"dcterms:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationTimestamp\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"deletionTimestamp\"\
  : {\n      \"@id\": \"k8s:deletionTimestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"labels\": {\n      \"@id\": \"k8s:labels\",\n      \"@container\": \"@index\"\n    },\n    \"annotations\": {\n      \"@id\": \"k8s:annotations\",\n      \"@container\": \"@index\"\n    },\n    \"resourceVersion\": {\n      \"@id\": \"k8s:resourceVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"generation\": {\n      \"@id\": \"k8s:generation\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"spec\": {\n      \"@id\": \"k8s:spec\"\n    },\n    \"status\": {\n      \"@id\": \"k8s:status\"\n    },\n    \"selector\": {\n      \"@id\": \"k8s:selector\"\n    },\n    \"ports\": {\n      \"@id\": \"k8s:ports\",\n      \"@container\": \"@set\"\n    },\n    \"rules\": {\n      \"@id\": \"k8s:rules\",\n      \"@container\": \"@set\"\n    },\n    \"conditions\": {\n      \"@id\": \"k8s:conditions\",\n      \"@container\": \"@set\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/kubernetes-services/refs/heads/main/json-ld/kubernetes-services-context.jsonld
tags:
- Container Orchestration
- Kubernetes
- Load Balancing
- Networking
- Service Discovery
- JSON-LD
- Linked Data
- Semantic Web
---
