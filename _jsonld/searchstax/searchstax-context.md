---
api_specs:
- filename: searchstax-provisioning-openapi.yml
  format: yaml
  label: SearchStax Provisioning API
  slug: searchstax-provisioning-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/searchstax/refs/heads/main/openapi/searchstax-provisioning-openapi.yml
class_count: 22
classes:
- Deployment
- Backup
- Node
- Plan
- id
- uid
- name
- status
- application
- application_version
- plan
- plan_type
- cloud_provider_id
- region_id
- termination_lock
- solr_url
- created
- num_nodes
- cpu
- memory_gb
- storage_gb
- healthy
context_file: json-ld/searchstax-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/searchstax/refs/heads/main/json-ld/searchstax-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Searchstax from SearchStax.
layout: jsonld
name: Searchstax Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: searchstax
  uri: https://searchstax.com/vocab/
properties:
- container: set
  name: collections
  type: ''
property_count: 1
provider_name: SearchStax
provider_slug: searchstax
slug: searchstax-context
source_filename: searchstax-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"searchstax\": \"https://searchstax.com/vocab/\",\n    \"Deployment\": \"searchstax:Deployment\",\n    \"Backup\": \"searchstax:Backup\",\n    \"Node\": \"searchstax:Node\",\n    \"Plan\": \"searchstax:Plan\",\n    \"id\": \"@id\",\n    \"uid\": \"searchstax:uid\",\n    \"name\": \"schema:name\",\n    \"status\": \"schema:status\",\n    \"application\": \"searchstax:application\",\n    \"application_version\": \"searchstax:applicationVersion\",\n    \"plan\": \"searchstax:plan\",\n    \"plan_type\": \"searchstax:planType\",\n    \"cloud_provider_id\": \"searchstax:cloudProvider\",\n    \"region_id\": \"searchstax:region\",\n    \"termination_lock\": \"searchstax:terminationLock\",\n    \"solr_url\": \"schema:url\",\n    \"created\": \"schema:dateCreated\",\n    \"num_nodes\": \"searchstax:nodeCount\",\n    \"cpu\": \"searchstax:cpu\"\
  ,\n    \"memory_gb\": \"searchstax:memoryGb\",\n    \"storage_gb\": \"searchstax:storageGb\",\n    \"healthy\": \"schema:healthy\",\n    \"collections\": {\n      \"@id\": \"searchstax:collections\",\n      \"@container\": \"@set\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/searchstax/refs/heads/main/json-ld/searchstax-context.jsonld
tags:
- Search
- Solr
- Managed Search
- Search Infrastructure
- Full-Text Search
- Site Search
- JSON-LD
- Linked Data
- Semantic Web
---
