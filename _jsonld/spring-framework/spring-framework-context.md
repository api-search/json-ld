---
api_specs:
- filename: spring-initializr-openapi.yml
  format: yaml
  label: Spring Initializr API
  slug: spring-initializr
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spring-framework/refs/heads/main/openapi/spring-initializr-openapi.yml
class_count: 10
classes:
- name
- description
- url
- version
- SoftwareSourceCode
- SoftwareApplication
- programmingLanguage
- runtimePlatform
- codeRepository
- license
context_file: json-ld/spring-framework-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/spring-framework/refs/heads/main/json-ld/spring-framework-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Spring Framework from Spring Framework.
layout: jsonld
name: Spring Framework Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: spring
  uri: https://spring.io/vocab/
- prefix: springfw
  uri: https://spring.io/projects/spring-framework/vocab/
properties:
- container: ''
  name: ApplicationContext
  type: reference
- container: ''
  name: BeanDefinition
  type: reference
- container: ''
  name: SpringBootProject
  type: reference
- container: ''
  name: beanName
  type: ''
- container: ''
  name: scope
  type: ''
- container: ''
  name: dependencies
  type: ''
- container: ''
  name: primaryBean
  type: ''
- container: ''
  name: lazyInit
  type: ''
- container: ''
  name: groupId
  type: ''
- container: ''
  name: artifactId
  type: ''
- container: ''
  name: packaging
  type: ''
- container: ''
  name: buildTool
  type: ''
- container: ''
  name: javaVersion
  type: ''
- container: ''
  name: springBootVersion
  type: ''
property_count: 14
provider_name: Spring Framework
provider_slug: spring-framework
slug: spring-framework-context
source_filename: spring-framework-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"spring\": \"https://spring.io/vocab/\",\n    \"springfw\": \"https://spring.io/projects/spring-framework/vocab/\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"version\": \"schema:version\",\n\n    \"ApplicationContext\": {\n      \"@id\": \"springfw:ApplicationContext\",\n      \"@type\": \"@id\"\n    },\n    \"BeanDefinition\": {\n      \"@id\": \"springfw:BeanDefinition\",\n      \"@type\": \"@id\"\n    },\n    \"SpringBootProject\": {\n      \"@id\": \"springfw:SpringBootProject\",\n      \"@type\": \"@id\"\n    },\n\n    \"beanName\": { \"@id\": \"springfw:beanName\" },\n    \"scope\": { \"@id\": \"springfw:scope\" },\n    \"dependencies\": { \"@id\": \"springfw:dependencies\" },\n    \"primaryBean\": { \"@id\": \"springfw:primaryBean\" },\n    \"lazyInit\": { \"@id\": \"springfw:lazyInit\" },\n\n    \"groupId\"\
  : { \"@id\": \"springfw:groupId\" },\n    \"artifactId\": { \"@id\": \"springfw:artifactId\" },\n    \"packaging\": { \"@id\": \"springfw:packaging\" },\n    \"buildTool\": { \"@id\": \"springfw:buildTool\" },\n    \"javaVersion\": { \"@id\": \"springfw:javaVersion\" },\n    \"springBootVersion\": { \"@id\": \"springfw:springBootVersion\" },\n\n    \"SoftwareSourceCode\": \"schema:SoftwareSourceCode\",\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"programmingLanguage\": \"schema:programmingLanguage\",\n    \"runtimePlatform\": \"schema:runtimePlatform\",\n    \"codeRepository\": \"schema:codeRepository\",\n    \"license\": \"schema:license\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/spring-framework/refs/heads/main/json-ld/spring-framework-context.jsonld
tags:
- AOP
- Dependency Injection
- Enterprise
- Framework
- IoC
- Java
- Microservices
- MVC
- Spring Boot
- JSON-LD
- Linked Data
- Semantic Web
---
