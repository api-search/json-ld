---
api_specs:
- filename: jupyter-hub-openapi.yml
  format: yaml
  label: JupyterHub REST API
  slug: jupyterhub-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jupyter-hub/refs/heads/main/openapi/jupyter-hub-openapi.yml
class_count: 12
classes:
- name
- description
- url
- User
- Group
- Service
- Server
- Token
- Hub
- username
- admin
- lastActivity
context_file: json-ld/jupyter-hub-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/jupyter-hub/refs/heads/main/json-ld/jupyter-hub-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Jupyter Hub from JupyterHub.
layout: jsonld
name: Jupyter Hub Context
namespaces:
- prefix: jh
  uri: https://raw.githubusercontent.com/api-evangelist/jupyter-hub/main/json-ld/jupyter-hub-context.jsonld#
properties: []
property_count: 0
provider_name: JupyterHub
provider_slug: jupyter-hub
slug: jupyter-hub-context
source_filename: jupyter-hub-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"jh\": \"https://raw.githubusercontent.com/api-evangelist/jupyter-hub/main/json-ld/jupyter-hub-context.jsonld#\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"User\": \"jh:User\",\n    \"Group\": \"jh:Group\",\n    \"Service\": \"jh:Service\",\n    \"Server\": \"jh:Server\",\n    \"Token\": \"jh:Token\",\n    \"Hub\": \"jh:Hub\",\n    \"username\": \"jh:username\",\n    \"admin\": \"jh:admin\",\n    \"lastActivity\": \"jh:lastActivity\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/jupyter-hub/refs/heads/main/json-ld/jupyter-hub-context.jsonld
tags:
- Data Science
- Education
- Jupyter
- Multi-User
- Notebooks
- JSON-LD
- Linked Data
- Semantic Web
---
