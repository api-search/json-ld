---
api_specs:
- filename: dreamfactory-system-api-openapi.yml
  format: yaml
  label: DreamFactory System API
  slug: system-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dreamfactory/refs/heads/main/openapi/dreamfactory-system-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/dreamfactory-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dreamfactory/refs/heads/main/json-ld/dreamfactory-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dreamfactory from DreamFactory.
layout: jsonld
name: Dreamfactory Context
namespaces:
- prefix: dreamfactory
  uri: https://www.dreamfactory.com/ns/
properties:
- container: ''
  name: Admin
  type: ''
- container: ''
  name: App
  type: ''
- container: ''
  name: Role
  type: ''
- container: ''
  name: Service
  type: ''
- container: ''
  name: User
  type: ''
property_count: 5
provider_name: DreamFactory
provider_slug: dreamfactory
slug: dreamfactory-context
source_filename: dreamfactory-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"dreamfactory\": \"https://www.dreamfactory.com/ns/\",\n    \"Admin\": {\n      \"@id\": \"dreamfactory:Admin\",\n      \"@context\": {\n        \"id\": \"dreamfactory:adminId\",\n        \"name\": \"schema:name\",\n        \"first_name\": \"schema:givenName\",\n        \"last_name\": \"schema:familyName\",\n        \"email\": \"schema:email\",\n        \"is_active\": \"dreamfactory:isActive\",\n        \"created_date\": \"schema:dateCreated\",\n        \"last_modified_date\": \"schema:dateModified\"\n      }\n    },\n    \"App\": {\n      \"@id\": \"dreamfactory:App\",\n      \"@context\": {\n        \"id\": \"dreamfactory:appId\",\n        \"name\": \"schema:name\",\n        \"api_key\": \"dreamfactory:apiKey\",\n        \"description\": \"schema:description\",\n        \"is_active\": \"dreamfactory:isActive\",\n        \"type\": \"dreamfactory:appType\",\n        \"role_id\": \"dreamfactory:roleId\",\n\
  \        \"created_date\": \"schema:dateCreated\",\n        \"last_modified_date\": \"schema:dateModified\"\n      }\n    },\n    \"Role\": {\n      \"@id\": \"dreamfactory:Role\",\n      \"@context\": {\n        \"id\": \"dreamfactory:roleId\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"is_active\": \"dreamfactory:isActive\",\n        \"role_service_access_by_role_id\": \"dreamfactory:serviceAccess\",\n        \"created_date\": \"schema:dateCreated\",\n        \"last_modified_date\": \"schema:dateModified\"\n      }\n    },\n    \"Service\": {\n      \"@id\": \"dreamfactory:Service\",\n      \"@context\": {\n        \"id\": \"dreamfactory:serviceId\",\n        \"name\": \"schema:name\",\n        \"label\": \"schema:alternateName\",\n        \"description\": \"schema:description\",\n        \"type\": \"dreamfactory:serviceType\",\n        \"is_active\": \"dreamfactory:isActive\",\n        \"config\": \"dreamfactory:serviceConfig\",\n\
  \        \"created_date\": \"schema:dateCreated\",\n        \"last_modified_date\": \"schema:dateModified\"\n      }\n    },\n    \"User\": {\n      \"@id\": \"dreamfactory:User\",\n      \"@context\": {\n        \"id\": \"dreamfactory:userId\",\n        \"name\": \"schema:name\",\n        \"first_name\": \"schema:givenName\",\n        \"last_name\": \"schema:familyName\",\n        \"email\": \"schema:email\",\n        \"is_active\": \"dreamfactory:isActive\",\n        \"phone\": \"schema:telephone\",\n        \"created_date\": \"schema:dateCreated\",\n        \"last_modified_date\": \"schema:dateModified\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dreamfactory/refs/heads/main/json-ld/dreamfactory-context.jsonld
tags:
- Automation
- Deployment
- Documentation
- Generation
- Security
- JSON-LD
- Linked Data
- Semantic Web
---
