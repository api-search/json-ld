---
api_specs:
- filename: spring-boot-actuator-openapi.yml
  format: yaml
  label: Spring Boot Actuator API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spring/refs/heads/main/openapi/spring-boot-actuator-openapi.yml
- filename: spring-initializr-api-openapi.yml
  format: yaml
  label: Spring Initializr API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spring/refs/heads/main/openapi/spring-initializr-api-openapi.yml
class_count: 23
classes:
- SpringApplication
- SpringBootProject
- SpringDependency
- ActuatorEndpoint
- HealthIndicator
- Bean
- Metric
- name
- description
- version
- language
- groupId
- artifactId
- packageName
- bootVersion
- packaging
- javaVersion
- type
- status
- details
- metricName
- statistic
- value
context_file: json-ld/spring-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/spring/refs/heads/main/json-ld/spring-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Spring from Spring Framework.
layout: jsonld
name: Spring Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: spring
  uri: https://spring.io/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: doap
  uri: http://usefulinc.com/ns/doap#
properties:
- container: set
  name: dependencies
  type: ''
- container: index
  name: components
  type: ''
- container: list
  name: measurements
  type: ''
- container: set
  name: tags
  type: ''
- container: ''
  name: url
  type: reference
- container: ''
  name: license
  type: reference
property_count: 6
provider_name: Spring Framework
provider_slug: spring
slug: spring-context
source_filename: spring-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"spring\": \"https://spring.io/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"doap\": \"http://usefulinc.com/ns/doap#\",\n\n    \"SpringApplication\": \"spring:SpringApplication\",\n    \"SpringBootProject\": \"spring:SpringBootProject\",\n    \"SpringDependency\": \"spring:SpringDependency\",\n    \"ActuatorEndpoint\": \"spring:ActuatorEndpoint\",\n    \"HealthIndicator\": \"spring:HealthIndicator\",\n    \"Bean\": \"spring:Bean\",\n    \"Metric\": \"spring:Metric\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"version\": \"schema:version\",\n    \"language\": \"schema:programmingLanguage\",\n    \"groupId\": \"spring:groupId\",\n    \"artifactId\": \"spring:artifactId\",\n    \"packageName\": \"spring:packageName\",\n    \"bootVersion\": \"spring:bootVersion\",\n    \"packaging\": \"spring:packaging\",\n    \"javaVersion\"\
  : \"spring:javaVersion\",\n    \"type\": \"spring:projectType\",\n    \"dependencies\": {\n      \"@id\": \"spring:hasDependency\",\n      \"@container\": \"@set\"\n    },\n    \"status\": \"spring:healthStatus\",\n    \"components\": {\n      \"@id\": \"spring:hasComponent\",\n      \"@container\": \"@index\"\n    },\n    \"details\": \"spring:healthDetails\",\n    \"metricName\": \"spring:metricName\",\n    \"measurements\": {\n      \"@id\": \"spring:hasMeasurement\",\n      \"@container\": \"@list\"\n    },\n    \"statistic\": \"spring:statisticType\",\n    \"value\": \"schema:value\",\n    \"tags\": {\n      \"@id\": \"schema:keywords\",\n      \"@container\": \"@set\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"license\": {\n      \"@id\": \"doap:license\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/spring/refs/heads/main/json-ld/spring-context.jsonld
tags:
- AI
- Cloud Native
- Enterprise
- Framework
- Java
- Microservices
- Open Source
- REST
- Spring Boot
- JSON-LD
- Linked Data
- Semantic Web
---
