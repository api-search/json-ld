---
class_count: 4
classes:
- Role
- Collection
- name
- description
context_file: json-ld/ansible-roles-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ansible-roles/refs/heads/main/json-ld/ansible-roles-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ansible Roles from Ansible Roles.
layout: jsonld
name: Ansible Roles Context
namespaces:
- prefix: galaxy
  uri: https://api-evangelist.github.io/ansible-roles/schema/
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
  name: namespace
  type: string
- container: ''
  name: githubUser
  type: string
- container: ''
  name: githubRepo
  type: string
- container: ''
  name: downloadCount
  type: integer
- container: ''
  name: stargazersCount
  type: integer
- container: ''
  name: license
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: repository
  type: reference
- container: ''
  name: documentation
  type: reference
- container: ''
  name: certified
  type: boolean
- container: set
  name: tags
  type: string
- container: ''
  name: created
  type: dateTime
- container: ''
  name: modified
  type: dateTime
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
property_count: 16
provider_name: Ansible Roles
provider_slug: ansible-roles
slug: ansible-roles-context
tags:
- Ansible
- Automation
- Collections
- Configuration Management
- DevOps
- Infrastructure As Code
- Roles
- JSON-LD
- Linked Data
- Semantic Web
---
