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
