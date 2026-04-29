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
source_filename: ansible-roles-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"galaxy\": \"https://api-evangelist.github.io/ansible-roles/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Role\": \"galaxy:Role\",\n    \"Collection\": \"galaxy:Collection\",\n    \"id\": {\"@id\": \"dcterms:identifier\", \"@type\": \"xsd:integer\"},\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"namespace\": {\"@id\": \"galaxy:namespace\", \"@type\": \"xsd:string\"},\n    \"githubUser\": {\"@id\": \"galaxy:github_user\", \"@type\": \"xsd:string\"},\n    \"githubRepo\": {\"@id\": \"galaxy:github_repo\", \"@type\": \"xsd:string\"},\n    \"downloadCount\": {\"@id\": \"galaxy:download_count\", \"@type\": \"xsd:integer\"},\n    \"stargazersCount\": {\"@id\": \"galaxy:stargazers_count\", \"@type\": \"xsd:integer\"},\n    \"license\": {\"@id\": \"dcterms:license\", \"@type\": \"\
  xsd:string\"},\n    \"version\": {\"@id\": \"schema:version\", \"@type\": \"xsd:string\"},\n    \"repository\": {\"@id\": \"schema:codeRepository\", \"@type\": \"@id\"},\n    \"documentation\": {\"@id\": \"schema:url\", \"@type\": \"@id\"},\n    \"certified\": {\"@id\": \"galaxy:certified\", \"@type\": \"xsd:boolean\"},\n    \"tags\": {\"@id\": \"galaxy:tags\", \"@container\": \"@set\", \"@type\": \"xsd:string\"},\n    \"created\": {\"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\"},\n    \"modified\": {\"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\"},\n    \"createdAt\": {\"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\"},\n    \"updatedAt\": {\"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ansible-roles/refs/heads/main/json-ld/ansible-roles-context.jsonld
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
