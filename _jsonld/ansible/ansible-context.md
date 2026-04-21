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
