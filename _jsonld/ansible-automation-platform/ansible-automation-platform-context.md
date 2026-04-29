---
class_count: 3
classes:
- JobTemplate
- Job
- Inventory
context_file: json-ld/ansible-automation-platform-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ansible-automation-platform/refs/heads/main/json-ld/ansible-automation-platform-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ansible Automation Platform from Ansible Automation Platform.
layout: jsonld
name: Ansible Automation Platform Context
namespaces:
- prefix: ansible
  uri: https://ansible.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: integer
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: jobType
  type: string
- container: ''
  name: playbook
  type: string
- container: ''
  name: hostCount
  type: integer
- container: ''
  name: scmType
  type: string
- container: ''
  name: scmUrl
  type: reference
property_count: 9
provider_name: Ansible Automation Platform
provider_slug: ansible-automation-platform
slug: ansible-automation-platform-context
source_filename: ansible-automation-platform-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ansible\": \"https://ansible.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"JobTemplate\": \"ansible:JobTemplate\",\n    \"Job\": \"ansible:Job\",\n    \"Inventory\": \"ansible:Inventory\",\n    \"id\": { \"@id\": \"ansible:id\", \"@type\": \"xsd:integer\" },\n    \"name\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"description\": { \"@id\": \"schema:description\", \"@type\": \"xsd:string\" },\n    \"status\": { \"@id\": \"ansible:status\", \"@type\": \"xsd:string\" },\n    \"jobType\": { \"@id\": \"ansible:job_type\", \"@type\": \"xsd:string\" },\n    \"playbook\": { \"@id\": \"ansible:playbook\", \"@type\": \"xsd:string\" },\n    \"hostCount\": { \"@id\": \"ansible:host_count\", \"@type\": \"xsd:integer\" },\n    \"scmType\": { \"@id\": \"ansible:scm_type\", \"@type\": \"xsd:string\" },\n    \"scmUrl\": { \"@id\": \"ansible:scm_url\"\
  , \"@type\": \"@id\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ansible-automation-platform/refs/heads/main/json-ld/ansible-automation-platform-context.jsonld
tags:
- Automation
- Configuration Management
- DevOps
- Infrastructure as Code
- Orchestration
- JSON-LD
- Linked Data
- Semantic Web
---
