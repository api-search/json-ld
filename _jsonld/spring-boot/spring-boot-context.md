---
api_specs:
- filename: spring-boot-actuator-openapi.yml
  format: yaml
  label: Spring Boot Actuator API
  slug: spring-boot-actuator
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spring-boot/refs/heads/main/openapi/spring-boot-actuator-openapi.yml
class_count: 12
classes:
- SpringBootActuator
- Health
- Metric
- Logger
- Environment
- PropertySource
- Cache
- SoftwareApplication
- SoftwareSourceCode
- programmingLanguage
- license
- url
context_file: json-ld/spring-boot-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/spring-boot/refs/heads/main/json-ld/spring-boot-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Spring Boot from Spring Boot.
layout: jsonld
name: Spring Boot Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: spring
  uri: https://spring.io/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: status
  type: string
- container: index
  name: components
  type: ''
- container: ''
  name: name
  type: ''
- container: ''
  name: description
  type: ''
- container: list
  name: measurements
  type: ''
- container: ''
  name: statistic
  type: string
- container: ''
  name: value
  type: number
- container: ''
  name: baseUnit
  type: string
- container: list
  name: availableTags
  type: ''
- container: list
  name: activeProfiles
  type: ''
- container: list
  name: propertySources
  type: ''
- container: ''
  name: configuredLevel
  type: string
- container: ''
  name: effectiveLevel
  type: string
property_count: 13
provider_name: Spring Boot
provider_slug: spring-boot
slug: spring-boot-context
source_filename: spring-boot-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"spring\": \"https://spring.io/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"SpringBootActuator\": \"spring:SpringBootActuator\",\n    \"Health\": \"spring:Health\",\n    \"Metric\": \"spring:Metric\",\n    \"Logger\": \"spring:Logger\",\n    \"Environment\": \"spring:Environment\",\n    \"PropertySource\": \"spring:PropertySource\",\n    \"Cache\": \"spring:Cache\",\n\n    \"status\": {\n      \"@id\": \"spring:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"components\": {\n      \"@id\": \"spring:components\",\n      \"@container\": \"@index\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"measurements\": {\n      \"@id\": \"spring:measurements\",\n      \"@container\": \"@list\"\n    },\n    \"statistic\": {\n      \"@id\": \"spring:statistic\",\n \
  \     \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"schema:value\",\n      \"@type\": \"xsd:number\"\n    },\n    \"baseUnit\": {\n      \"@id\": \"spring:baseUnit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"availableTags\": {\n      \"@id\": \"spring:availableTags\",\n      \"@container\": \"@list\"\n    },\n    \"activeProfiles\": {\n      \"@id\": \"spring:activeProfiles\",\n      \"@container\": \"@list\"\n    },\n    \"propertySources\": {\n      \"@id\": \"spring:propertySources\",\n      \"@container\": \"@list\"\n    },\n    \"configuredLevel\": {\n      \"@id\": \"spring:configuredLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"effectiveLevel\": {\n      \"@id\": \"spring:effectiveLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"SoftwareSourceCode\": \"schema:SoftwareSourceCode\",\n    \"programmingLanguage\": \"schema:programmingLanguage\",\n    \"license\": \"schema:license\"\
  ,\n    \"url\": \"schema:url\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/spring-boot/refs/heads/main/json-ld/spring-boot-context.jsonld
tags:
- Auto Configuration
- Embedded Server
- Framework
- Java
- Microservices
- REST API
- Spring
- Web Development
- JSON-LD
- Linked Data
- Semantic Web
---
