---
api_specs:
- filename: contour-httpproxy-openapi.yml
  format: yaml
  label: Contour HTTPProxy API
  slug: contour-httpproxy-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/contour/refs/heads/main/openapi/contour-httpproxy-openapi.yml
- filename: contour-gateway-openapi.yml
  format: yaml
  label: Contour Gateway API
  slug: contour-gateway-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/contour/refs/heads/main/openapi/contour-gateway-openapi.yml
class_count: 0
classes: []
context_file: json-ld/contour-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/contour/refs/heads/main/json-ld/contour-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Contour from Contour.
layout: jsonld
name: Contour Context
namespaces:
- prefix: contour
  uri: https://projectcontour.io/vocabulary#
- prefix: k8s
  uri: https://kubernetes.io/vocabulary#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: prov
  uri: http://www.w3.org/ns/prov#
properties:
- container: ''
  name: HTTPProxy
  type: ''
- container: ''
  name: VirtualHost
  type: ''
- container: ''
  name: Route
  type: ''
- container: ''
  name: Service
  type: ''
- container: ''
  name: GatewayClass
  type: ''
- container: ''
  name: Gateway
  type: ''
- container: ''
  name: Listener
  type: ''
- container: ''
  name: HTTPRoute
  type: ''
- container: ''
  name: TLSCertificateDelegation
  type: ''
- container: ''
  name: RateLimitPolicy
  type: ''
- container: ''
  name: RetryPolicy
  type: ''
- container: ''
  name: TimeoutPolicy
  type: ''
property_count: 12
provider_name: Contour
provider_slug: contour
slug: contour-context
source_filename: contour-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"contour\": \"https://projectcontour.io/vocabulary#\",\n    \"k8s\": \"https://kubernetes.io/vocabulary#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"prov\": \"http://www.w3.org/ns/prov#\",\n\n    \"HTTPProxy\": {\n      \"@id\": \"contour:HTTPProxy\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"namespace\": \"k8s:namespace\",\n        \"fqdn\": {\n          \"@id\": \"contour:fullyQualifiedDomainName\",\n          \"@type\": \"@id\"\n        },\n        \"status\": \"contour:proxyStatus\",\n        \"description\": \"schema:description\",\n        \"creationTimestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"labels\": \"k8s:labels\",\n        \"annotations\": \"k8s:annotations\",\n        \"routes\": {\n          \"@id\": \"\
  contour:routes\",\n          \"@container\": \"@set\"\n        },\n        \"includes\": {\n          \"@id\": \"contour:includes\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"VirtualHost\": {\n      \"@id\": \"contour:VirtualHost\",\n      \"@context\": {\n        \"fqdn\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"tls\": \"contour:tlsConfiguration\",\n        \"rateLimitPolicy\": \"contour:rateLimitPolicy\",\n        \"corsPolicy\": \"contour:corsPolicy\"\n      }\n    },\n\n    \"Route\": {\n      \"@id\": \"contour:Route\",\n      \"@context\": {\n        \"conditions\": {\n          \"@id\": \"contour:matchConditions\",\n          \"@container\": \"@set\"\n        },\n        \"services\": {\n          \"@id\": \"contour:backendServices\",\n          \"@container\": \"@set\"\n        },\n        \"timeoutPolicy\": \"contour:timeoutPolicy\",\n        \"retryPolicy\": \"contour:retryPolicy\"\n      }\n  \
  \  },\n\n    \"Service\": {\n      \"@id\": \"contour:BackendService\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"port\": \"schema:portNumber\",\n        \"weight\": \"contour:trafficWeight\",\n        \"protocol\": \"contour:upstreamProtocol\"\n      }\n    },\n\n    \"GatewayClass\": {\n      \"@id\": \"contour:GatewayClass\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"controllerName\": {\n          \"@id\": \"contour:controllerName\",\n          \"@type\": \"@id\"\n        },\n        \"description\": \"schema:description\",\n        \"creationTimestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Gateway\": {\n      \"@id\": \"contour:Gateway\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"namespace\": \"k8s:namespace\",\n        \"gatewayClassName\": {\n          \"@id\": \"contour:gatewayClass\",\n          \"@type\": \"@id\"\
  \n        },\n        \"listeners\": {\n          \"@id\": \"contour:listeners\",\n          \"@container\": \"@set\"\n        },\n        \"addresses\": {\n          \"@id\": \"contour:networkAddresses\",\n          \"@container\": \"@set\"\n        },\n        \"creationTimestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Listener\": {\n      \"@id\": \"contour:Listener\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"hostname\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"port\": \"schema:portNumber\",\n        \"protocol\": \"contour:networkProtocol\"\n      }\n    },\n\n    \"HTTPRoute\": {\n      \"@id\": \"contour:HTTPRoute\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"namespace\": \"k8s:namespace\",\n        \"hostnames\": {\n          \"@id\": \"contour:hostnames\",\n          \"@container\": \"@set\"\n\
  \        },\n        \"rules\": {\n          \"@id\": \"contour:routeRules\",\n          \"@container\": \"@set\"\n        },\n        \"creationTimestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"TLSCertificateDelegation\": {\n      \"@id\": \"contour:TLSCertificateDelegation\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"namespace\": \"k8s:namespace\",\n        \"delegations\": {\n          \"@id\": \"contour:delegations\",\n          \"@container\": \"@set\"\n        },\n        \"secretName\": \"contour:certificateSecretName\",\n        \"targetNamespaces\": {\n          \"@id\": \"contour:targetNamespaces\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"RateLimitPolicy\": {\n      \"@id\": \"contour:RateLimitPolicy\",\n      \"@context\": {\n        \"requests\": \"contour:maxRequests\",\n        \"unit\": \"contour:rateUnit\",\n        \"burst\": \"\
  contour:burstSize\"\n      }\n    },\n\n    \"RetryPolicy\": {\n      \"@id\": \"contour:RetryPolicy\",\n      \"@context\": {\n        \"count\": \"contour:retryCount\",\n        \"perTryTimeout\": \"contour:perTryTimeout\"\n      }\n    },\n\n    \"TimeoutPolicy\": {\n      \"@id\": \"contour:TimeoutPolicy\",\n      \"@context\": {\n        \"response\": \"contour:responseTimeout\",\n        \"idle\": \"contour:idleTimeout\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/contour/refs/heads/main/json-ld/contour-context.jsonld
tags:
- Envoy
- Ingress Controller
- Kubernetes
- Networking
- Proxy
- JSON-LD
- Linked Data
- Semantic Web
---
