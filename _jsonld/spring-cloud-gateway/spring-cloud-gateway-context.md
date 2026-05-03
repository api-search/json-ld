---
api_specs:
- filename: spring-cloud-gateway-actuator-openapi.yml
  format: yaml
  label: Spring Cloud Gateway Actuator API
  slug: spring-cloud-gateway-actuator
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spring-cloud-gateway/refs/heads/main/openapi/spring-cloud-gateway-actuator-openapi.yml
class_count: 6
classes:
- RouteDefinition
- PredicateDefinition
- FilterDefinition
- APIGateway
- SoftwareApplication
- url
context_file: json-ld/spring-cloud-gateway-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/spring-cloud-gateway/refs/heads/main/json-ld/spring-cloud-gateway-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Spring Cloud Gateway from Spring Cloud Gateway.
layout: jsonld
name: Spring Cloud Gateway Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: spring
  uri: https://spring.io/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: ''
- container: ''
  name: uri
  type: ''
- container: list
  name: predicates
  type: ''
- container: list
  name: filters
  type: ''
- container: ''
  name: order
  type: integer
- container: index
  name: metadata
  type: ''
- container: ''
  name: name
  type: ''
- container: ''
  name: description
  type: ''
- container: index
  name: args
  type: ''
property_count: 9
provider_name: Spring Cloud Gateway
provider_slug: spring-cloud-gateway
slug: spring-cloud-gateway-context
source_filename: spring-cloud-gateway-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"spring\": \"https://spring.io/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"RouteDefinition\": \"spring:RouteDefinition\",\n    \"PredicateDefinition\": \"spring:PredicateDefinition\",\n    \"FilterDefinition\": \"spring:FilterDefinition\",\n    \"APIGateway\": \"spring:APIGateway\",\n\n    \"id\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"uri\": {\n      \"@id\": \"schema:url\"\n    },\n    \"predicates\": {\n      \"@id\": \"spring:predicates\",\n      \"@container\": \"@list\"\n    },\n    \"filters\": {\n      \"@id\": \"spring:filters\",\n      \"@container\": \"@list\"\n    },\n    \"order\": {\n      \"@id\": \"spring:order\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"metadata\": {\n      \"@id\": \"spring:metadata\",\n      \"@container\": \"@index\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"description\"\
  : {\n      \"@id\": \"schema:description\"\n    },\n    \"args\": {\n      \"@id\": \"spring:args\",\n      \"@container\": \"@index\"\n    },\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"url\": \"schema:url\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/spring-cloud-gateway/refs/heads/main/json-ld/spring-cloud-gateway-context.jsonld
tags:
- API Gateway
- Circuit Breaker
- Load Balancing
- Microservices
- Rate Limiting
- Routing
- Spring
- Spring WebFlux
- JSON-LD
- Linked Data
- Semantic Web
---
