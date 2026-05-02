---
api_specs:
- filename: jupyterhub-rest-api-openapi.yml
  format: yaml
  label: JupyterHub REST API
  slug: jupyterhub-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jupyterhub/refs/heads/main/openapi/jupyterhub-rest-api-openapi.yml
class_count: 9
classes:
- JupyterHub
- User
- Group
- name
- groups
- users
- created
- lastActivity
- url
context_file: json-ld/jupyterhub-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/jupyterhub/refs/heads/main/json-ld/jupyterhub-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Jupyterhub from JupyterHub.
layout: jsonld
name: Jupyterhub Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: Server
  uri: https://jupyterhub.readthedocs.io/vocab#Server
- prefix: Service
  uri: https://jupyterhub.readthedocs.io/vocab#Service
- prefix: Token
  uri: https://jupyterhub.readthedocs.io/vocab#Token
- prefix: admin
  uri: https://jupyterhub.readthedocs.io/vocab#admin
- prefix: roles
  uri: https://jupyterhub.readthedocs.io/vocab#roles
- prefix: ready
  uri: https://jupyterhub.readthedocs.io/vocab#ready
- prefix: pending
  uri: https://jupyterhub.readthedocs.io/vocab#pending
properties: []
property_count: 0
provider_name: JupyterHub
provider_slug: jupyterhub
slug: jupyterhub-context
source_filename: jupyterhub-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://jupyterhub.readthedocs.io/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"JupyterHub\": \"schema:SoftwareApplication\",\n    \"User\": \"schema:Person\",\n    \"Group\": \"schema:Group\",\n    \"Server\": \"https://jupyterhub.readthedocs.io/vocab#Server\",\n    \"Service\": \"https://jupyterhub.readthedocs.io/vocab#Service\",\n    \"Token\": \"https://jupyterhub.readthedocs.io/vocab#Token\",\n    \"name\": \"schema:name\",\n    \"admin\": \"https://jupyterhub.readthedocs.io/vocab#admin\",\n    \"roles\": \"https://jupyterhub.readthedocs.io/vocab#roles\",\n    \"groups\": \"schema:memberOf\",\n    \"users\": \"schema:member\",\n    \"created\": \"schema:dateCreated\",\n    \"lastActivity\": \"schema:dateModified\",\n    \"url\": \"schema:url\",\n    \"ready\": \"https://jupyterhub.readthedocs.io/vocab#ready\",\n    \"pending\": \"https://jupyterhub.readthedocs.io/vocab#pending\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/jupyterhub/refs/heads/main/json-ld/jupyterhub-context.jsonld
tags:
- Authentication
- Data Science
- Education
- Hub
- Multi-User
- Notebooks
- OAuth2
- Python
- JSON-LD
- Linked Data
- Semantic Web
---
