---
api_specs:
- filename: aws-app-mesh-openapi.yaml
  format: yaml
  label: AWS App Mesh API
  slug: aws-app-mesh-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/openapi/aws-app-mesh-openapi.yaml
class_count: 16
classes:
- HttpGatewayRoute
- HttpRouteHeader
- HttpRouteMatch
- HttpRoute
- HttpGatewayRouteRewrite
- HttpGatewayRouteMatch
- HttpGatewayRoutePathRewrite
- HttpPathMatch
- HttpTimeout
- HttpGatewayRouteHeader
- HttpRouteAction
- HttpRetryPolicy
- HttpGatewayRoutePrefixRewrite
- HttpGatewayRouteAction
- HttpQueryParameter
- name
context_file: json-ld/aws-app-mesh-http-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-http-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aws App Mesh Http from AWS App Mesh.
layout: jsonld
name: Aws App Mesh Http Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: httpRetryEvents
  type: string
- container: ''
  name: maxRetries
  type: string
- container: ''
  name: perRetryTimeout
  type: string
- container: ''
  name: tcpRetryEvents
  type: string
- container: ''
  name: action
  type: string
- container: ''
  name: match
  type: string
- container: ''
  name: exact
  type: string
- container: ''
  name: headers
  type: string
- container: ''
  name: hostname
  type: string
- container: ''
  name: method
  type: string
- container: ''
  name: path
  type: string
- container: ''
  name: port
  type: string
- container: ''
  name: prefix
  type: string
- container: ''
  name: queryParameters
  type: string
- container: ''
  name: defaultPrefix
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: idle
  type: string
- container: ''
  name: perRequest
  type: string
- container: ''
  name: invert
  type: string
- container: ''
  name: rewrite
  type: string
- container: ''
  name: target
  type: string
- container: ''
  name: scheme
  type: string
- container: ''
  name: retryPolicy
  type: string
- container: ''
  name: timeout
  type: string
- container: ''
  name: regex
  type: string
- container: ''
  name: weightedTargets
  type: string
property_count: 26
provider_name: AWS App Mesh
provider_slug: aws-app-mesh
slug: aws-app-mesh-http-context
source_filename: aws-app-mesh-http-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"HttpGatewayRoute\": \"aws:HttpGatewayRoute\",\n    \"HttpRouteHeader\": \"aws:HttpRouteHeader\",\n    \"HttpRouteMatch\": \"aws:HttpRouteMatch\",\n    \"HttpRoute\": \"aws:HttpRoute\",\n    \"HttpGatewayRouteRewrite\": \"aws:HttpGatewayRouteRewrite\",\n    \"HttpGatewayRouteMatch\": \"aws:HttpGatewayRouteMatch\",\n    \"HttpGatewayRoutePathRewrite\": \"aws:HttpGatewayRoutePathRewrite\",\n    \"HttpPathMatch\": \"aws:HttpPathMatch\",\n    \"HttpTimeout\": \"aws:HttpTimeout\",\n    \"HttpGatewayRouteHeader\": \"aws:HttpGatewayRouteHeader\",\n    \"HttpRouteAction\": \"aws:HttpRouteAction\",\n    \"HttpRetryPolicy\": \"aws:HttpRetryPolicy\",\n    \"HttpGatewayRoutePrefixRewrite\": \"aws:HttpGatewayRoutePrefixRewrite\",\n    \"HttpGatewayRouteAction\"\
  : \"aws:HttpGatewayRouteAction\",\n    \"HttpQueryParameter\": \"aws:HttpQueryParameter\",\n    \"httpRetryEvents\": {\n      \"@id\": \"aws:httpRetryEvents\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxRetries\": {\n      \"@id\": \"aws:maxRetries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"perRetryTimeout\": {\n      \"@id\": \"aws:perRetryTimeout\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tcpRetryEvents\": {\n      \"@id\": \"aws:tcpRetryEvents\",\n      \"@type\": \"xsd:string\"\n    },\n    \"action\": {\n      \"@id\": \"aws:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"match\": {\n      \"@id\": \"aws:match\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exact\": {\n      \"@id\": \"aws:exact\",\n      \"@type\": \"xsd:string\"\n    },\n    \"headers\": {\n      \"@id\": \"aws:headers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hostname\": {\n      \"@id\": \"aws:hostname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"method\": {\n\
  \      \"@id\": \"aws:method\",\n      \"@type\": \"xsd:string\"\n    },\n    \"path\": {\n      \"@id\": \"aws:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"port\": {\n      \"@id\": \"aws:port\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prefix\": {\n      \"@id\": \"aws:prefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queryParameters\": {\n      \"@id\": \"aws:queryParameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultPrefix\": {\n      \"@id\": \"aws:defaultPrefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"aws:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"idle\": {\n      \"@id\": \"aws:idle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"perRequest\": {\n      \"@id\": \"aws:perRequest\",\n      \"@type\": \"xsd:string\"\n    },\n    \"invert\": {\n      \"@id\": \"aws:invert\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rewrite\": {\n      \"@id\": \"aws:rewrite\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"target\": {\n      \"@id\": \"aws:target\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scheme\": {\n      \"@id\": \"aws:scheme\",\n      \"@type\": \"xsd:string\"\n    },\n    \"retryPolicy\": {\n      \"@id\": \"aws:retryPolicy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeout\": {\n      \"@id\": \"aws:timeout\",\n      \"@type\": \"xsd:string\"\n    },\n    \"regex\": {\n      \"@id\": \"aws:regex\",\n      \"@type\": \"xsd:string\"\n    },\n    \"weightedTargets\": {\n      \"@id\": \"aws:weightedTargets\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-http-context.jsonld
tags:
- Deprecated
- Envoy
- Microservices
- Networking
- Service Mesh
- JSON-LD
- Linked Data
- Semantic Web
---
