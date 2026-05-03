---
api_specs:
- filename: spring-cloud-gateway-actuator-openapi.yml
  format: yaml
  label: Spring Cloud Gateway
  slug: spring-cloud-gateway
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spring-cloud/refs/heads/main/openapi/spring-cloud-gateway-actuator-openapi.yml
class_count: 8
classes:
- ServiceInstance
- ServiceRegistry
- ConfigServer
- CircuitBreaker
- APIGateway
- LoadBalancer
- SoftwareApplication
- url
context_file: json-ld/spring-cloud-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/spring-cloud/refs/heads/main/json-ld/spring-cloud-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Spring Cloud from Spring Cloud.
layout: jsonld
name: Spring Cloud Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: spring
  uri: https://spring.io/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: serviceId
  type: string
- container: ''
  name: host
  type: ''
- container: ''
  name: port
  type: integer
- container: ''
  name: secure
  type: boolean
- container: ''
  name: uri
  type: ''
- container: ''
  name: instanceId
  type: ''
- container: index
  name: metadata
  type: ''
- container: ''
  name: name
  type: ''
- container: ''
  name: description
  type: ''
property_count: 9
provider_name: Spring Cloud
provider_slug: spring-cloud
slug: spring-cloud-context
source_filename: spring-cloud-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"spring\": \"https://spring.io/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"ServiceInstance\": \"spring:ServiceInstance\",\n    \"ServiceRegistry\": \"spring:ServiceRegistry\",\n    \"ConfigServer\": \"spring:ConfigServer\",\n    \"CircuitBreaker\": \"spring:CircuitBreaker\",\n    \"APIGateway\": \"spring:APIGateway\",\n    \"LoadBalancer\": \"spring:LoadBalancer\",\n\n    \"serviceId\": {\n      \"@id\": \"spring:serviceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"host\": {\n      \"@id\": \"schema:serverAddress\"\n    },\n    \"port\": {\n      \"@id\": \"schema:portNumber\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"secure\": {\n      \"@id\": \"spring:secure\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"uri\": {\n      \"@id\": \"schema:url\"\n    },\n    \"instanceId\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"metadata\"\
  : {\n      \"@id\": \"spring:metadata\",\n      \"@container\": \"@index\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"url\": \"schema:url\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/spring-cloud/refs/heads/main/json-ld/spring-cloud-context.jsonld
tags:
- Circuit Breaker
- Cloud Native
- Distributed Systems
- Java
- Microservices
- Service Discovery
- Spring Framework
- JSON-LD
- Linked Data
- Semantic Web
---
