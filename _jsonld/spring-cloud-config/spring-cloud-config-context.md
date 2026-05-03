---
api_specs:
- filename: spring-cloud-config-server-api.yml
  format: yaml
  label: Spring Cloud Config Server API
  slug: spring-cloud-config-server
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spring-cloud-config/refs/heads/main/openapi/spring-cloud-config-server-api.yml
class_count: 5
classes:
- ConfigEnvironment
- PropertySource
- ConfigServer
- SoftwareSourceCode
- url
context_file: json-ld/spring-cloud-config-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/spring-cloud-config/refs/heads/main/json-ld/spring-cloud-config-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Spring Cloud Config from Spring Cloud Config.
layout: jsonld
name: Spring Cloud Config Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: spring
  uri: https://spring.io/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: name
  type: ''
- container: ''
  name: description
  type: ''
- container: list
  name: profiles
  type: ''
- container: ''
  name: label
  type: string
- container: ''
  name: version
  type: ''
- container: list
  name: propertySources
  type: ''
- container: index
  name: source
  type: ''
- container: ''
  name: application
  type: string
- container: ''
  name: profile
  type: string
property_count: 9
provider_name: Spring Cloud Config
provider_slug: spring-cloud-config
slug: spring-cloud-config-context
source_filename: spring-cloud-config-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"spring\": \"https://spring.io/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"ConfigEnvironment\": \"spring:ConfigEnvironment\",\n    \"PropertySource\": \"spring:PropertySource\",\n    \"ConfigServer\": \"spring:ConfigServer\",\n\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"profiles\": {\n      \"@id\": \"spring:profiles\",\n      \"@container\": \"@list\"\n    },\n    \"label\": {\n      \"@id\": \"spring:label\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\"\n    },\n    \"propertySources\": {\n      \"@id\": \"spring:propertySources\",\n      \"@container\": \"@list\"\n    },\n    \"source\": {\n      \"@id\": \"spring:source\",\n      \"@container\": \"@index\"\n    },\n    \"application\": {\n      \"@id\": \"spring:application\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"profile\": {\n      \"@id\": \"spring:profile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SoftwareSourceCode\": \"schema:SoftwareSourceCode\",\n    \"url\": \"schema:url\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/spring-cloud-config/refs/heads/main/json-ld/spring-cloud-config-context.jsonld
tags:
- Configuration Management
- Distributed Systems
- Externalized Configuration
- Git
- Java
- Microservices
- Spring
- Spring Cloud
- JSON-LD
- Linked Data
- Semantic Web
---
