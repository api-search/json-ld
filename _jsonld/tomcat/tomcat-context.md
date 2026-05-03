---
api_specs:
- filename: tomcat-manager-openapi.yml
  format: yaml
  label: Apache Tomcat Manager API
  slug: tomcat-manager-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tomcat/refs/heads/main/openapi/tomcat-manager-openapi.yml
class_count: 9
classes:
- WebApplication
- Server
- Session
- path
- status
- sessions
- name
- version
- description
context_file: json-ld/tomcat-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tomcat/refs/heads/main/json-ld/tomcat-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tomcat from Apache Tomcat.
layout: jsonld
name: Tomcat Context
namespaces:
- prefix: tomcat
  uri: https://tomcat.apache.org/tomcat-10.1-doc/#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: url
  type: reference
property_count: 1
provider_name: Apache Tomcat
provider_slug: tomcat
slug: tomcat-context
source_filename: tomcat-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"tomcat\": \"https://tomcat.apache.org/tomcat-10.1-doc/#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"WebApplication\": \"schema:SoftwareApplication\",\n    \"Server\": \"schema:SoftwareApplication\",\n    \"Session\": \"tomcat:Session\",\n    \"path\": \"tomcat:contextPath\",\n    \"status\": \"schema:actionStatus\",\n    \"sessions\": \"tomcat:sessionCount\",\n    \"name\": \"schema:name\",\n    \"version\": \"schema:version\",\n    \"description\": \"schema:description\",\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tomcat/refs/heads/main/json-ld/tomcat-context.jsonld
tags:
- Application Server
- Java
- Servlet Container
- Web Server
- Open Source
- Apache
- JSON-LD
- Linked Data
- Semantic Web
---
