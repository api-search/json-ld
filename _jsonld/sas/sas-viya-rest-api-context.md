---
api_specs:
- filename: sas-viya-rest-api-openapi.yml
  format: yaml
  label: SAS Viya REST API
  slug: viya-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sas/refs/heads/main/openapi/sas-viya-rest-api-openapi.yml
class_count: 12
classes:
- name
- description
- id
- createdBy
- creationTimeStamp
- modifiedTimeStamp
- Job
- Report
- Decision
- User
- state
- version
context_file: json-ld/sas-viya-rest-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sas/refs/heads/main/json-ld/sas-viya-rest-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sas Viya Rest Api from SAS Institute.
layout: jsonld
name: Sas Viya Rest Api Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: sas
  uri: https://developer.sas.com/vocab/
properties: []
property_count: 0
provider_name: SAS Institute
provider_slug: sas
slug: sas-viya-rest-api-context
source_filename: sas-viya-rest-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://developer.sas.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"sas\": \"https://developer.sas.com/vocab/\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"id\": \"@id\",\n    \"createdBy\": \"schema:creator\",\n    \"creationTimeStamp\": \"schema:dateCreated\",\n    \"modifiedTimeStamp\": \"schema:dateModified\",\n    \"Job\": \"sas:Job\",\n    \"Report\": \"sas:Report\",\n    \"Decision\": \"sas:Decision\",\n    \"User\": \"schema:Person\",\n    \"state\": \"sas:state\",\n    \"version\": \"schema:version\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sas/refs/heads/main/json-ld/sas-viya-rest-api-context.jsonld
tags:
- Analytics
- Data Management
- Artificial Intelligence
- Machine Learning
- Software
- JSON-LD
- Linked Data
- Semantic Web
---
