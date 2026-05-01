---
api_specs:
- filename: emissary-ingress-openapi.yml
  format: yaml
  label: Emissary-Ingress Configuration API
  slug: emissary-ingress-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/emissary-ingress/refs/heads/main/openapi/emissary-ingress-openapi.yml
class_count: 0
classes: []
context_file: json-ld/emissary-ingress-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/emissary-ingress/refs/heads/main/json-ld/emissary-ingress-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Emissary Ingress from Emissary-Ingress.
layout: jsonld
name: Emissary Ingress Context
namespaces:
- prefix: emissary
  uri: https://www.getambassador.io/vocabulary#
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
  name: Mapping
  type: ''
- container: ''
  name: Host
  type: ''
- container: ''
  name: TLSContext
  type: ''
- container: ''
  name: RateLimitService
  type: ''
- container: ''
  name: AuthService
  type: ''
- container: ''
  name: RetryPolicy
  type: ''
- container: ''
  name: CORSPolicy
  type: ''
- container: ''
  name: LoadBalancer
  type: ''
- container: ''
  name: CircuitBreaker
  type: ''
- container: ''
  name: ACMEProvider
  type: ''
property_count: 10
provider_name: Emissary-Ingress
provider_slug: emissary-ingress
slug: emissary-ingress-context
source_filename: emissary-ingress-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"emissary\": \"https://www.getambassador.io/vocabulary#\",\n    \"k8s\": \"https://kubernetes.io/vocabulary#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"prov\": \"http://www.w3.org/ns/prov#\",\n\n    \"Mapping\": {\n      \"@id\": \"emissary:Mapping\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"namespace\": \"k8s:namespace\",\n        \"prefix\": {\n          \"@id\": \"emissary:urlPrefix\",\n          \"@type\": \"@id\"\n        },\n        \"service\": {\n          \"@id\": \"emissary:upstreamService\",\n          \"@type\": \"@id\"\n        },\n        \"hostname\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"method\": \"emissary:httpMethod\",\n        \"rewrite\": \"emissary:urlRewrite\",\n        \"weight\": \"emissary:trafficWeight\",\n\
  \        \"shadow\": \"emissary:shadowTraffic\",\n        \"timeout_ms\": \"emissary:requestTimeoutMs\",\n        \"labels\": \"k8s:labels\",\n        \"annotations\": \"k8s:annotations\",\n        \"creationTimestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Host\": {\n      \"@id\": \"emissary:Host\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"namespace\": \"k8s:namespace\",\n        \"hostname\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"tlsSecret\": \"emissary:tlsCertificateSecret\",\n        \"acmeProvider\": \"emissary:acmeConfiguration\",\n        \"requestPolicy\": \"emissary:requestPolicy\",\n        \"creationTimestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"TLSContext\": {\n      \"@id\": \"emissary:TLSContext\",\n      \"@context\": {\n   \
  \     \"name\": \"schema:name\",\n        \"namespace\": \"k8s:namespace\",\n        \"secret\": \"emissary:tlsCertificateSecret\",\n        \"min_tls_version\": \"emissary:minimumTLSVersion\",\n        \"max_tls_version\": \"emissary:maximumTLSVersion\",\n        \"cipher_suites\": {\n          \"@id\": \"emissary:cipherSuites\",\n          \"@container\": \"@set\"\n        },\n        \"alpn_protocols\": \"emissary:alpnProtocols\",\n        \"hosts\": {\n          \"@id\": \"emissary:hostnames\",\n          \"@container\": \"@set\"\n        },\n        \"creationTimestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"RateLimitService\": {\n      \"@id\": \"emissary:RateLimitService\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"namespace\": \"k8s:namespace\",\n        \"service\": {\n          \"@id\": \"emissary:rateLimitBackend\",\n          \"@type\": \"@id\"\n        },\n       \
  \ \"protocol_version\": \"emissary:rateLimitProtocolVersion\",\n        \"timeout_ms\": \"emissary:serviceTimeoutMs\",\n        \"creationTimestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"AuthService\": {\n      \"@id\": \"emissary:AuthService\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"namespace\": \"k8s:namespace\",\n        \"auth_service\": {\n          \"@id\": \"emissary:authBackend\",\n          \"@type\": \"@id\"\n        },\n        \"proto\": \"emissary:authProtocol\",\n        \"timeout_ms\": \"emissary:authTimeoutMs\",\n        \"allowed_request_headers\": {\n          \"@id\": \"emissary:allowedRequestHeaders\",\n          \"@container\": \"@set\"\n        },\n        \"allowed_authorization_headers\": {\n          \"@id\": \"emissary:allowedAuthorizationHeaders\",\n          \"@container\": \"@set\"\n        },\n        \"failure_mode_allow\": \"emissary:failOpen\"\
  ,\n        \"creationTimestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"RetryPolicy\": {\n      \"@id\": \"emissary:RetryPolicy\",\n      \"@context\": {\n        \"retry_on\": \"emissary:retryCondition\",\n        \"num_retries\": \"emissary:retryCount\",\n        \"per_try_timeout\": \"emissary:perRetryTimeout\"\n      }\n    },\n\n    \"CORSPolicy\": {\n      \"@id\": \"emissary:CORSPolicy\",\n      \"@context\": {\n        \"origins\": \"emissary:allowedOrigins\",\n        \"methods\": \"emissary:allowedMethods\",\n        \"headers\": \"emissary:allowedHeaders\",\n        \"credentials\": \"emissary:allowCredentials\",\n        \"exposed_headers\": \"emissary:exposedHeaders\",\n        \"max_age\": \"emissary:preflightCacheAge\"\n      }\n    },\n\n    \"LoadBalancer\": {\n      \"@id\": \"emissary:LoadBalancer\",\n      \"@context\": {\n        \"policy\": \"emissary:loadBalancingPolicy\",\n        \"\
  header\": \"emissary:hashHeader\",\n        \"source_ip\": \"emissary:hashSourceIP\"\n      }\n    },\n\n    \"CircuitBreaker\": {\n      \"@id\": \"emissary:CircuitBreaker\",\n      \"@context\": {\n        \"priority\": \"emissary:circuitBreakerPriority\",\n        \"max_connections\": \"emissary:maxConnections\",\n        \"max_pending_requests\": \"emissary:maxPendingRequests\",\n        \"max_requests\": \"emissary:maxRequests\",\n        \"max_retries\": \"emissary:maxRetries\"\n      }\n    },\n\n    \"ACMEProvider\": {\n      \"@id\": \"emissary:ACMEProvider\",\n      \"@context\": {\n        \"authority\": {\n          \"@id\": \"emissary:acmeAuthorityURL\",\n          \"@type\": \"@id\"\n        },\n        \"email\": \"schema:email\",\n        \"privateKeySecret\": \"emissary:acmePrivateKeySecret\",\n        \"registration\": {\n          \"@id\": \"emissary:acmeRegistrationURL\",\n          \"@type\": \"@id\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/emissary-ingress/refs/heads/main/json-ld/emissary-ingress-context.jsonld
tags:
- API Gateway
- Cloud Native
- Envoy
- Incubating
- Ingress
- Kubernetes
- JSON-LD
- Linked Data
- Semantic Web
---
