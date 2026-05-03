---
api_specs:
- filename: solo-io-gloo-portal-server-api-openapi.yml
  format: yaml
  label: Solo.io Gloo Portal Server API
  slug: gloo-portal-server-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/solo-io/refs/heads/main/openapi/solo-io-gloo-portal-server-api-openapi.yml
- filename: solo-io-gloo-gateway-management-api-openapi.yml
  format: yaml
  label: Solo.io Gloo Gateway Management API
  slug: gloo-gateway-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/solo-io/refs/heads/main/openapi/solo-io-gloo-gateway-management-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/solo-io-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/solo-io/refs/heads/main/json-ld/solo-io-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Solo Io from Solo.io.
layout: jsonld
name: Solo Io Context
namespaces:
- prefix: gloo
  uri: https://docs.solo.io/gloo-edge/latest/reference/api/
- prefix: portal
  uri: https://docs.solo.io/gloo-mesh-gateway/latest/portal/
properties:
- container: ''
  name: User
  type: ''
- container: ''
  name: ApiProduct
  type: ''
- container: ''
  name: ApiVersion
  type: ''
- container: ''
  name: UsagePlan
  type: ''
- container: ''
  name: ApiKey
  type: ''
- container: ''
  name: Upstream
  type: ''
- container: ''
  name: VirtualService
  type: ''
- container: ''
  name: Route
  type: ''
- container: ''
  name: RouteTable
  type: ''
- container: ''
  name: Gateway
  type: ''
- container: ''
  name: Proxy
  type: ''
- container: ''
  name: ResourceMetadata
  type: ''
- container: ''
  name: ResourceStatus
  type: ''
property_count: 13
provider_name: Solo.io
provider_slug: solo-io
slug: solo-io-context
source_filename: solo-io-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gloo\": \"https://docs.solo.io/gloo-edge/latest/reference/api/\",\n    \"portal\": \"https://docs.solo.io/gloo-mesh-gateway/latest/portal/\",\n    \"User\": {\n      \"@id\": \"portal:user\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"email\": \"https://schema.org/email\",\n        \"username\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"groups\": \"https://schema.org/memberOf\"\n      }\n    },\n    \"ApiProduct\": {\n      \"@id\": \"portal:api-product\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"version\": \"https://schema.org/version\",\n        \"contact\": \"https://schema.org/contactPoint\",\n        \"license\": \"https://schema.org/license\",\n        \"\
  termsOfService\": \"https://schema.org/termsOfService\",\n        \"usagePlans\": {\n          \"@id\": \"portal:usage-plan\",\n          \"@type\": \"@id\"\n        },\n        \"apiVersions\": {\n          \"@id\": \"portal:api-version\",\n          \"@type\": \"@id\"\n        },\n        \"visibility\": \"https://schema.org/accessMode\"\n      }\n    },\n    \"ApiVersion\": {\n      \"@id\": \"portal:api-version\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"version\": \"https://schema.org/version\",\n        \"schemaType\": \"https://schema.org/encodingFormat\"\n      }\n    },\n    \"UsagePlan\": {\n      \"@id\": \"portal:usage-plan\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"rateLimitPolicy\": \"https://schema.org/actionOption\",\n        \"apiProducts\": {\n          \"@id\": \"portal:api-product\"\
  ,\n          \"@type\": \"@id\"\n        }\n      }\n    },\n    \"ApiKey\": {\n      \"@id\": \"portal:api-key\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"apiProductId\": {\n          \"@id\": \"portal:api-product\",\n          \"@type\": \"@id\"\n        },\n        \"usagePlanId\": {\n          \"@id\": \"portal:usage-plan\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": \"https://schema.org/dateCreated\",\n        \"metadata\": \"https://schema.org/additionalProperty\"\n      }\n    },\n    \"Upstream\": {\n      \"@id\": \"gloo:upstream\",\n      \"@context\": {\n        \"metadata\": \"https://schema.org/identifier\",\n        \"status\": \"https://schema.org/status\",\n        \"upstreamType\": \"https://schema.org/category\",\n        \"host\": \"https://schema.org/url\",\n        \"port\": \"https://schema.org/identifier\",\n        \"serviceSpec\": \"https://schema.org/serviceType\"\
  ,\n        \"sslConfig\": \"https://schema.org/actionOption\",\n        \"healthChecks\": \"https://schema.org/healthCondition\"\n      }\n    },\n    \"VirtualService\": {\n      \"@id\": \"gloo:virtual-service\",\n      \"@context\": {\n        \"metadata\": \"https://schema.org/identifier\",\n        \"status\": \"https://schema.org/status\",\n        \"displayName\": \"https://schema.org/name\",\n        \"domains\": \"https://schema.org/url\",\n        \"routes\": {\n          \"@id\": \"gloo:route\",\n          \"@type\": \"@id\"\n        },\n        \"sslConfig\": \"https://schema.org/actionOption\",\n        \"virtualHost\": \"https://schema.org/hasPart\"\n      }\n    },\n    \"Route\": {\n      \"@id\": \"gloo:route\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"matchers\": \"https://schema.org/urlTemplate\",\n        \"routeAction\": \"https://schema.org/potentialAction\",\n        \"options\": \"https://schema.org/actionOption\"\n     \
  \ }\n    },\n    \"RouteTable\": {\n      \"@id\": \"gloo:route-table\",\n      \"@context\": {\n        \"metadata\": \"https://schema.org/identifier\",\n        \"status\": \"https://schema.org/status\",\n        \"routes\": {\n          \"@id\": \"gloo:route\",\n          \"@type\": \"@id\"\n        },\n        \"weight\": \"https://schema.org/position\"\n      }\n    },\n    \"Gateway\": {\n      \"@id\": \"gloo:gateway\",\n      \"@context\": {\n        \"metadata\": \"https://schema.org/identifier\",\n        \"status\": \"https://schema.org/status\",\n        \"bindAddress\": \"https://schema.org/url\",\n        \"bindPort\": \"https://schema.org/identifier\",\n        \"ssl\": \"https://schema.org/actionOption\",\n        \"httpGateway\": \"https://schema.org/hasPart\",\n        \"tcpGateway\": \"https://schema.org/hasPart\"\n      }\n    },\n    \"Proxy\": {\n      \"@id\": \"gloo:proxy\",\n      \"@context\": {\n        \"metadata\": \"https://schema.org/identifier\",\n     \
  \   \"status\": \"https://schema.org/status\",\n        \"listeners\": \"https://schema.org/hasPart\",\n        \"compressedSpec\": \"https://schema.org/text\"\n      }\n    },\n    \"ResourceMetadata\": {\n      \"@id\": \"gloo:resource-metadata\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"namespace\": \"https://schema.org/identifier\",\n        \"cluster\": \"https://schema.org/identifier\",\n        \"labels\": \"https://schema.org/keywords\",\n        \"annotations\": \"https://schema.org/additionalProperty\",\n        \"resourceVersion\": \"https://schema.org/version\"\n      }\n    },\n    \"ResourceStatus\": {\n      \"@id\": \"gloo:resource-status\",\n      \"@context\": {\n        \"state\": \"https://schema.org/status\",\n        \"reason\": \"https://schema.org/description\",\n        \"reportedBy\": \"https://schema.org/creator\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/solo-io/refs/heads/main/json-ld/solo-io-context.jsonld
tags:
- AI Gateway
- Analytics
- Automation
- Gateways
- Management
- Monetization
- Observability
- Platform
- Resiliency
- Security
- Service Mesh
- Traffic Control
- JSON-LD
- Linked Data
- Semantic Web
---
