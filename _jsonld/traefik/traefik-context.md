---
api_specs:
- filename: traefik-api-openapi.yml
  format: yaml
  label: Traefik REST API
  slug: traefik-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/traefik/refs/heads/main/openapi/traefik-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/traefik-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/traefik/refs/heads/main/json-ld/traefik-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Traefik from Traefik.
layout: jsonld
name: Traefik Context
namespaces:
- prefix: traefik
  uri: https://traefik.io/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Router
  type: ''
- container: ''
  name: Service
  type: ''
- container: ''
  name: Middleware
  type: ''
- container: ''
  name: EntryPoint
  type: ''
- container: ''
  name: LoadBalancer
  type: ''
- container: ''
  name: Server
  type: ''
- container: ''
  name: TLSConfig
  type: ''
- container: ''
  name: Version
  type: ''
- container: ''
  name: Overview
  type: ''
property_count: 9
provider_name: Traefik
provider_slug: traefik
slug: traefik-context
source_filename: traefik-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"traefik\": \"https://traefik.io/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Router\": {\n      \"@id\": \"traefik:Router\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"entryPoints\": {\n          \"@id\": \"traefik:entryPoints\",\n          \"@container\": \"@set\"\n        },\n        \"rule\": \"traefik:rule\",\n        \"ruleSyntax\": \"traefik:ruleSyntax\",\n        \"priority\": \"traefik:priority\",\n        \"service\": \"traefik:service\",\n        \"middlewares\": {\n          \"@id\": \"traefik:middlewares\",\n          \"@container\": \"@list\"\n        },\n        \"status\": \"traefik:status\",\n        \"provider\": \"traefik:provider\",\n        \"tls\": \"traefik:tls\"\n      }\n    },\n\n    \"Service\": {\n      \"@id\": \"traefik:Service\",\n      \"@context\": {\n\
  \        \"name\": \"schema:name\",\n        \"type\": \"traefik:serviceType\",\n        \"status\": \"traefik:status\",\n        \"provider\": \"traefik:provider\",\n        \"loadBalancer\": \"traefik:loadBalancer\",\n        \"serverStatus\": \"traefik:serverStatus\"\n      }\n    },\n\n    \"Middleware\": {\n      \"@id\": \"traefik:Middleware\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"traefik:middlewareType\",\n        \"status\": \"traefik:status\",\n        \"provider\": \"traefik:provider\",\n        \"usedBy\": {\n          \"@id\": \"traefik:usedBy\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"EntryPoint\": {\n      \"@id\": \"traefik:EntryPoint\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"address\": \"traefik:address\",\n        \"transport\": \"traefik:transport\"\n      }\n    },\n\n    \"LoadBalancer\": {\n      \"@id\": \"traefik:LoadBalancer\",\n      \"@context\": {\n    \
  \    \"servers\": {\n          \"@id\": \"traefik:servers\",\n          \"@container\": \"@set\"\n        },\n        \"passHostHeader\": \"traefik:passHostHeader\",\n        \"healthCheck\": \"traefik:healthCheck\"\n      }\n    },\n\n    \"Server\": {\n      \"@id\": \"traefik:Server\",\n      \"@context\": {\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"address\": \"traefik:address\"\n      }\n    },\n\n    \"TLSConfig\": {\n      \"@id\": \"traefik:TLSConfig\",\n      \"@context\": {\n        \"passthrough\": \"traefik:passthrough\",\n        \"options\": \"traefik:tlsOptions\",\n        \"certResolver\": \"traefik:certResolver\",\n        \"domains\": {\n          \"@id\": \"traefik:domains\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Version\": {\n      \"@id\": \"traefik:Version\",\n      \"@context\": {\n        \"version\": \"schema:softwareVersion\",\n        \"codename\": \"traefik:codename\"\
  ,\n        \"startDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Overview\": {\n      \"@id\": \"traefik:Overview\",\n      \"@context\": {\n        \"http\": \"traefik:httpOverview\",\n        \"tcp\": \"traefik:tcpOverview\",\n        \"udp\": \"traefik:udpOverview\",\n        \"features\": \"traefik:features\",\n        \"providers\": {\n          \"@id\": \"traefik:providers\",\n          \"@container\": \"@set\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/traefik/refs/heads/main/json-ld/traefik-context.jsonld
tags:
- API Gateway
- Kubernetes
- Load Balancer
- Open Source
- Reverse Proxy
- JSON-LD
- Linked Data
- Semantic Web
---
