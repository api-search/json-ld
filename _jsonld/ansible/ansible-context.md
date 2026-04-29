---
class_count: 4
classes:
- Playbook
- Task
- name
- description
context_file: json-ld/ansible-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ansible/refs/heads/main/json-ld/ansible-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ansible from Ansible.
layout: jsonld
name: Ansible Context
namespaces:
- prefix: ansible
  uri: https://api-evangelist.github.io/ansible/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: hosts
  type: string
- container: ''
  name: become
  type: boolean
- container: ''
  name: becomeUser
  type: string
- container: ''
  name: gatherFacts
  type: boolean
- container: set
  name: roles
  type: string
- container: set
  name: tasks
  type: reference
- container: set
  name: handlers
  type: reference
- container: set
  name: tags
  type: string
- container: ''
  name: when
  type: string
- container: ''
  name: notify
  type: string
property_count: 10
provider_name: Ansible
provider_slug: ansible
slug: ansible-context
source_filename: ansible-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ansible\": \"https://api-evangelist.github.io/ansible/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Playbook\": \"ansible:Playbook\",\n    \"Task\": \"ansible:Task\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"hosts\": {\"@id\": \"ansible:hosts\", \"@type\": \"xsd:string\"},\n    \"become\": {\"@id\": \"ansible:become\", \"@type\": \"xsd:boolean\"},\n    \"becomeUser\": {\"@id\": \"ansible:become_user\", \"@type\": \"xsd:string\"},\n    \"gatherFacts\": {\"@id\": \"ansible:gather_facts\", \"@type\": \"xsd:boolean\"},\n    \"roles\": {\"@id\": \"ansible:roles\", \"@container\": \"@set\", \"@type\": \"xsd:string\"},\n    \"tasks\": {\"@id\": \"ansible:tasks\", \"@container\": \"@set\", \"@type\": \"@id\"},\n    \"handlers\": {\"@id\": \"ansible:handlers\", \"@container\"\
  : \"@set\", \"@type\": \"@id\"},\n    \"tags\": {\"@id\": \"ansible:tags\", \"@container\": \"@set\", \"@type\": \"xsd:string\"},\n    \"when\": {\"@id\": \"ansible:when\", \"@type\": \"xsd:string\"},\n    \"notify\": {\"@id\": \"ansible:notify\", \"@type\": \"xsd:string\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ansible/refs/heads/main/json-ld/ansible-context.jsonld
tags:
- Ansible
- Automation
- Configuration Management
- DevOps
- Infrastructure As Code
- Open Source
- Orchestration
- Red Hat
- JSON-LD
- Linked Data
- Semantic Web
---
