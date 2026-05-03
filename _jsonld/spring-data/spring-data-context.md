---
api_specs:
- filename: spring-data-rest-openapi.yml
  format: yaml
  label: Spring Data REST
  slug: spring-data-rest
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spring-data/refs/heads/main/openapi/spring-data-rest-openapi.yml
class_count: 8
classes:
- name
- description
- url
- SoftwareSourceCode
- SoftwareApplication
- programmingLanguage
- runtimePlatform
- codeRepository
context_file: json-ld/spring-data-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/spring-data/refs/heads/main/json-ld/spring-data-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Spring Data from Spring Data.
layout: jsonld
name: Spring Data Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: spring
  uri: https://spring.io/vocab/
- prefix: springdata
  uri: https://spring.io/projects/spring-data/vocab/
properties:
- container: ''
  name: repository
  type: reference
- container: ''
  name: entity
  type: reference
- container: ''
  name: dataStore
  type: reference
- container: ''
  name: HalResource
  type: reference
- container: ''
  name: PagedResource
  type: reference
- container: ''
  name: Link
  type: reference
- container: ''
  name: href
  type: ''
- container: ''
  name: templated
  type: ''
- container: ''
  name: rel
  type: ''
- container: ''
  name: page
  type: ''
- container: ''
  name: totalElements
  type: ''
- container: ''
  name: totalPages
  type: ''
- container: ''
  name: number
  type: ''
- container: ''
  name: size
  type: ''
- container: ''
  name: sort
  type: ''
- container: ''
  name: projection
  type: ''
property_count: 16
provider_name: Spring Data
provider_slug: spring-data
slug: spring-data-context
source_filename: spring-data-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"spring\": \"https://spring.io/vocab/\",\n    \"springdata\": \"https://spring.io/projects/spring-data/vocab/\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n\n    \"repository\": {\n      \"@id\": \"springdata:repository\",\n      \"@type\": \"@id\"\n    },\n    \"entity\": {\n      \"@id\": \"springdata:entity\",\n      \"@type\": \"@id\"\n    },\n    \"dataStore\": {\n      \"@id\": \"springdata:dataStore\",\n      \"@type\": \"@id\"\n    },\n\n    \"HalResource\": {\n      \"@id\": \"springdata:HalResource\",\n      \"@type\": \"@id\"\n    },\n    \"PagedResource\": {\n      \"@id\": \"springdata:PagedResource\",\n      \"@type\": \"@id\"\n    },\n    \"Link\": {\n      \"@id\": \"springdata:Link\",\n      \"@type\": \"@id\"\n    },\n\n    \"href\": { \"@id\": \"springdata:href\" },\n    \"templated\": { \"@id\":\
  \ \"springdata:templated\" },\n    \"rel\": { \"@id\": \"springdata:rel\" },\n\n    \"page\": { \"@id\": \"springdata:page\" },\n    \"totalElements\": { \"@id\": \"springdata:totalElements\" },\n    \"totalPages\": { \"@id\": \"springdata:totalPages\" },\n    \"number\": { \"@id\": \"springdata:number\" },\n    \"size\": { \"@id\": \"springdata:size\" },\n\n    \"sort\": { \"@id\": \"springdata:sort\" },\n    \"projection\": { \"@id\": \"springdata:projection\" },\n\n    \"SoftwareSourceCode\": \"schema:SoftwareSourceCode\",\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"programmingLanguage\": \"schema:programmingLanguage\",\n    \"runtimePlatform\": \"schema:runtimePlatform\",\n    \"codeRepository\": \"schema:codeRepository\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/spring-data/refs/heads/main/json-ld/spring-data-context.jsonld
tags:
- Data Access
- Database
- Framework
- Java
- JPA
- MongoDB
- ORM
- Redis
- REST
- Spring
- JSON-LD
- Linked Data
- Semantic Web
---
