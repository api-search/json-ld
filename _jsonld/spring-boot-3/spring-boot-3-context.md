---
api_specs:
- filename: spring-boot-3-actuator-openapi.yml
  format: yaml
  label: Spring Boot Actuator API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spring-boot-3/refs/heads/main/openapi/spring-boot-3-actuator-openapi.yml
class_count: 8
classes:
- HealthResponse
- ComponentHealth
- MetricDetail
- Measurement
- EnvironmentResponse
- PropertySource
- LoggerDetail
- ScheduledTask
context_file: json-ld/spring-boot-3-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/spring-boot-3/refs/heads/main/json-ld/spring-boot-3-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Spring Boot 3 from Spring Boot 3.
layout: jsonld
name: Spring Boot 3 Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: boot
  uri: https://spring.io/boot/3/
properties:
- container: ''
  name: status
  type: string
- container: ''
  name: components
  type: reference
- container: ''
  name: details
  type: reference
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: baseUnit
  type: string
- container: list
  name: measurements
  type: reference
- container: ''
  name: statistic
  type: string
- container: ''
  name: value
  type: ''
- container: list
  name: availableTags
  type: reference
- container: ''
  name: tag
  type: string
- container: list
  name: values
  type: ''
- container: list
  name: activeProfiles
  type: ''
- container: list
  name: defaultProfiles
  type: ''
- container: list
  name: propertySources
  type: ''
- container: ''
  name: properties
  type: reference
- container: ''
  name: configuredLevel
  type: string
- container: ''
  name: effectiveLevel
  type: string
- container: ''
  name: threadName
  type: string
- container: ''
  name: threadState
  type: string
- container: ''
  name: daemon
  type: boolean
- container: ''
  name: expression
  type: string
- container: ''
  name: interval
  type: long
- container: ''
  name: initialDelay
  type: long
property_count: 24
provider_name: Spring Boot 3
provider_slug: spring-boot-3
slug: spring-boot-3-context
source_filename: spring-boot-3-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://spring.io/boot/3/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"boot\": \"https://spring.io/boot/3/\",\n\n    \"HealthResponse\": \"boot:HealthResponse\",\n    \"ComponentHealth\": \"boot:ComponentHealth\",\n    \"MetricDetail\": \"boot:MetricDetail\",\n    \"Measurement\": \"boot:Measurement\",\n    \"EnvironmentResponse\": \"boot:EnvironmentResponse\",\n    \"PropertySource\": \"boot:PropertySource\",\n    \"LoggerDetail\": \"boot:LoggerDetail\",\n    \"ScheduledTask\": \"boot:ScheduledTask\",\n\n    \"status\": { \"@id\": \"boot:status\", \"@type\": \"xsd:string\" },\n    \"components\": { \"@id\": \"boot:components\", \"@type\": \"@id\" },\n    \"details\": { \"@id\": \"boot:details\", \"@type\": \"@id\" },\n\n    \"name\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"description\": { \"@id\": \"schema:description\", \"@type\": \"xsd:string\" },\n\
  \    \"baseUnit\": { \"@id\": \"boot:baseUnit\", \"@type\": \"xsd:string\" },\n    \"measurements\": { \"@id\": \"boot:measurements\", \"@type\": \"@id\", \"@container\": \"@list\" },\n    \"statistic\": { \"@id\": \"boot:statistic\", \"@type\": \"xsd:string\" },\n    \"value\": { \"@id\": \"boot:value\" },\n\n    \"availableTags\": { \"@id\": \"boot:availableTags\", \"@type\": \"@id\", \"@container\": \"@list\" },\n    \"tag\": { \"@id\": \"boot:tag\", \"@type\": \"xsd:string\" },\n    \"values\": { \"@id\": \"boot:values\", \"@container\": \"@list\" },\n\n    \"activeProfiles\": { \"@id\": \"boot:activeProfiles\", \"@container\": \"@list\" },\n    \"defaultProfiles\": { \"@id\": \"boot:defaultProfiles\", \"@container\": \"@list\" },\n    \"propertySources\": { \"@id\": \"boot:propertySources\", \"@container\": \"@list\" },\n    \"properties\": { \"@id\": \"boot:properties\", \"@type\": \"@id\" },\n\n    \"configuredLevel\": { \"@id\": \"boot:configuredLevel\", \"@type\": \"xsd:string\"\
  \ },\n    \"effectiveLevel\": { \"@id\": \"boot:effectiveLevel\", \"@type\": \"xsd:string\" },\n\n    \"threadName\": { \"@id\": \"boot:threadName\", \"@type\": \"xsd:string\" },\n    \"threadState\": { \"@id\": \"boot:threadState\", \"@type\": \"xsd:string\" },\n    \"daemon\": { \"@id\": \"boot:daemon\", \"@type\": \"xsd:boolean\" },\n\n    \"expression\": { \"@id\": \"boot:expression\", \"@type\": \"xsd:string\" },\n    \"interval\": { \"@id\": \"boot:interval\", \"@type\": \"xsd:long\" },\n    \"initialDelay\": { \"@id\": \"boot:initialDelay\", \"@type\": \"xsd:long\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/spring-boot-3/refs/heads/main/json-ld/spring-boot-3-context.jsonld
tags:
- Enterprise
- Framework
- Java
- Microservices
- REST API
- Spring Boot
- JSON-LD
- Linked Data
- Semantic Web
---
