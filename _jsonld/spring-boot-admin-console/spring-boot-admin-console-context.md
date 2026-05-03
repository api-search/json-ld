---
api_specs:
- filename: spring-boot-admin-console-openapi.yml
  format: yaml
  label: Spring Boot Admin Server API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spring-boot-admin-console/refs/heads/main/openapi/spring-boot-admin-console-openapi.yml
class_count: 6
classes:
- Application
- Instance
- Registration
- StatusInfo
- InstanceEvent
- Endpoint
context_file: json-ld/spring-boot-admin-console-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/spring-boot-admin-console/refs/heads/main/json-ld/spring-boot-admin-console-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Spring Boot Admin Console from Spring Boot Admin Console.
layout: jsonld
name: Spring Boot Admin Console Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: sba
  uri: https://codecentric.github.io/spring-boot-admin/schema/
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: version
  type: integer
- container: ''
  name: registered
  type: boolean
- container: ''
  name: registration
  type: reference
- container: ''
  name: statusInfo
  type: reference
- container: ''
  name: statusTimestamp
  type: dateTime
- container: ''
  name: info
  type: reference
- container: list
  name: endpoints
  type: reference
- container: ''
  name: buildVersion
  type: string
- container: ''
  name: tags
  type: reference
- container: list
  name: instances
  type: reference
- container: ''
  name: status
  type: string
- container: ''
  name: details
  type: reference
- container: ''
  name: managementUrl
  type: anyURI
- container: ''
  name: healthUrl
  type: anyURI
- container: ''
  name: serviceUrl
  type: anyURI
- container: ''
  name: metadata
  type: reference
- container: ''
  name: instance
  type: string
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: type
  type: string
- container: ''
  name: url
  type: anyURI
property_count: 22
provider_name: Spring Boot Admin Console
provider_slug: spring-boot-admin-console
slug: spring-boot-admin-console-context
source_filename: spring-boot-admin-console-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://codecentric.github.io/spring-boot-admin/schema/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"sba\": \"https://codecentric.github.io/spring-boot-admin/schema/\",\n\n    \"Application\": \"sba:Application\",\n    \"Instance\": \"sba:Instance\",\n    \"Registration\": \"sba:Registration\",\n    \"StatusInfo\": \"sba:StatusInfo\",\n    \"InstanceEvent\": \"sba:InstanceEvent\",\n    \"Endpoint\": \"sba:Endpoint\",\n\n    \"id\": { \"@id\": \"schema:identifier\", \"@type\": \"xsd:string\" },\n    \"name\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"version\": { \"@id\": \"sba:version\", \"@type\": \"xsd:integer\" },\n\n    \"registered\": { \"@id\": \"sba:registered\", \"@type\": \"xsd:boolean\" },\n    \"registration\": { \"@id\": \"sba:registration\", \"@type\": \"@id\" },\n    \"statusInfo\": { \"@id\": \"sba:statusInfo\", \"@type\": \"@id\" },\n   \
  \ \"statusTimestamp\": { \"@id\": \"sba:statusTimestamp\", \"@type\": \"xsd:dateTime\" },\n    \"info\": { \"@id\": \"sba:info\", \"@type\": \"@id\" },\n    \"endpoints\": { \"@id\": \"sba:endpoints\", \"@type\": \"@id\", \"@container\": \"@list\" },\n    \"buildVersion\": { \"@id\": \"sba:buildVersion\", \"@type\": \"xsd:string\" },\n    \"tags\": { \"@id\": \"sba:tags\", \"@type\": \"@id\" },\n    \"instances\": { \"@id\": \"sba:instances\", \"@type\": \"@id\", \"@container\": \"@list\" },\n    \"status\": { \"@id\": \"sba:status\", \"@type\": \"xsd:string\" },\n    \"details\": { \"@id\": \"sba:details\", \"@type\": \"@id\" },\n\n    \"managementUrl\": { \"@id\": \"sba:managementUrl\", \"@type\": \"xsd:anyURI\" },\n    \"healthUrl\": { \"@id\": \"sba:healthUrl\", \"@type\": \"xsd:anyURI\" },\n    \"serviceUrl\": { \"@id\": \"sba:serviceUrl\", \"@type\": \"xsd:anyURI\" },\n    \"metadata\": { \"@id\": \"sba:metadata\", \"@type\": \"@id\" },\n\n    \"instance\": { \"@id\": \"sba:instance\"\
  , \"@type\": \"xsd:string\" },\n    \"timestamp\": { \"@id\": \"sba:timestamp\", \"@type\": \"xsd:dateTime\" },\n    \"type\": { \"@id\": \"sba:eventType\", \"@type\": \"xsd:string\" },\n\n    \"url\": { \"@id\": \"schema:url\", \"@type\": \"xsd:anyURI\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/spring-boot-admin-console/refs/heads/main/json-ld/spring-boot-admin-console-context.jsonld
tags:
- Actuator
- Administration
- Java
- Microservices
- Monitoring
- Spring Boot
- JSON-LD
- Linked Data
- Semantic Web
---
