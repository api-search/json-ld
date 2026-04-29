---
class_count: 4
classes:
- PlaybookJob
- Inventory
- name
- description
context_file: json-ld/ansible-playbooks-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ansible-playbooks/refs/heads/main/json-ld/ansible-playbooks-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ansible Playbooks from Ansible Playbooks.
layout: jsonld
name: Ansible Playbooks Context
namespaces:
- prefix: ansible
  uri: https://api-evangelist.github.io/ansible-playbooks/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: integer
- container: ''
  name: status
  type: string
- container: ''
  name: playbook
  type: string
- container: ''
  name: started
  type: dateTime
- container: ''
  name: finished
  type: dateTime
- container: ''
  name: elapsed
  type: decimal
- container: ''
  name: jobType
  type: string
- container: ''
  name: launchType
  type: string
- container: ''
  name: verbosity
  type: integer
- container: ''
  name: limit
  type: string
- container: ''
  name: extraVars
  type: string
- container: ''
  name: inventory
  type: integer
- container: ''
  name: project
  type: integer
- container: ''
  name: organization
  type: integer
- container: ''
  name: kind
  type: string
- container: ''
  name: variables
  type: string
- container: ''
  name: totalHosts
  type: integer
- container: ''
  name: totalGroups
  type: integer
- container: ''
  name: created
  type: dateTime
- container: ''
  name: modified
  type: dateTime
property_count: 20
provider_name: Ansible Playbooks
provider_slug: ansible-playbooks
slug: ansible-playbooks-context
source_filename: ansible-playbooks-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ansible\": \"https://api-evangelist.github.io/ansible-playbooks/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"PlaybookJob\": \"ansible:PlaybookJob\",\n    \"Inventory\": \"ansible:Inventory\",\n\n    \"id\": {\"@id\": \"dcterms:identifier\", \"@type\": \"xsd:integer\"},\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"status\": {\"@id\": \"ansible:status\", \"@type\": \"xsd:string\"},\n    \"playbook\": {\"@id\": \"ansible:playbook\", \"@type\": \"xsd:string\"},\n    \"started\": {\"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\"},\n    \"finished\": {\"@id\": \"ansible:finished\", \"@type\": \"xsd:dateTime\"},\n    \"elapsed\": {\"@id\": \"ansible:elapsed\", \"@type\": \"xsd:decimal\"},\n    \"jobType\": {\"@id\": \"ansible:job_type\", \"@type\": \"xsd:string\"\
  },\n    \"launchType\": {\"@id\": \"ansible:launch_type\", \"@type\": \"xsd:string\"},\n    \"verbosity\": {\"@id\": \"ansible:verbosity\", \"@type\": \"xsd:integer\"},\n    \"limit\": {\"@id\": \"ansible:limit\", \"@type\": \"xsd:string\"},\n    \"extraVars\": {\"@id\": \"ansible:extra_vars\", \"@type\": \"xsd:string\"},\n    \"inventory\": {\"@id\": \"ansible:inventory\", \"@type\": \"xsd:integer\"},\n    \"project\": {\"@id\": \"ansible:project\", \"@type\": \"xsd:integer\"},\n    \"organization\": {\"@id\": \"ansible:organization\", \"@type\": \"xsd:integer\"},\n    \"kind\": {\"@id\": \"ansible:kind\", \"@type\": \"xsd:string\"},\n    \"variables\": {\"@id\": \"ansible:variables\", \"@type\": \"xsd:string\"},\n    \"totalHosts\": {\"@id\": \"ansible:total_hosts\", \"@type\": \"xsd:integer\"},\n    \"totalGroups\": {\"@id\": \"ansible:total_groups\", \"@type\": \"xsd:integer\"},\n    \"created\": {\"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\"},\n    \"modified\": {\"\
  @id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ansible-playbooks/refs/heads/main/json-ld/ansible-playbooks-context.jsonld
tags:
- Ansible
- Automation
- Configuration Management
- DevOps
- Infrastructure As Code
- Orchestration
- Playbooks
- JSON-LD
- Linked Data
- Semantic Web
---
