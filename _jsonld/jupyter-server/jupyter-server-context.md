---
api_specs:
- filename: jupyter-server-rest-api-openapi.yml
  format: yaml
  label: Jupyter Server REST API
  slug: jupyter-server-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jupyter-server/refs/heads/main/openapi/jupyter-server-rest-api-openapi.yml
class_count: 6
classes:
- JupyterServer
- name
- description
- version
- path
- lastActivity
context_file: json-ld/jupyter-server-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/jupyter-server/refs/heads/main/json-ld/jupyter-server-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Jupyter Server from Jupyter Server.
layout: jsonld
name: Jupyter Server Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: Kernel
  uri: https://jupyter-server.readthedocs.io/vocab#Kernel
- prefix: Session
  uri: https://jupyter-server.readthedocs.io/vocab#Session
- prefix: Contents
  uri: https://jupyter-server.readthedocs.io/vocab#Contents
- prefix: Notebook
  uri: https://jupyter-server.readthedocs.io/vocab#Notebook
- prefix: Terminal
  uri: https://jupyter-server.readthedocs.io/vocab#Terminal
- prefix: executionState
  uri: https://jupyter-server.readthedocs.io/vocab#executionState
- prefix: connections
  uri: https://jupyter-server.readthedocs.io/vocab#connections
- prefix: kernel
  uri: https://jupyter-server.readthedocs.io/vocab#kernel
properties: []
property_count: 0
provider_name: Jupyter Server
provider_slug: jupyter-server
slug: jupyter-server-context
source_filename: jupyter-server-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://jupyter-server.readthedocs.io/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"JupyterServer\": \"schema:SoftwareApplication\",\n    \"Kernel\": \"https://jupyter-server.readthedocs.io/vocab#Kernel\",\n    \"Session\": \"https://jupyter-server.readthedocs.io/vocab#Session\",\n    \"Contents\": \"https://jupyter-server.readthedocs.io/vocab#Contents\",\n    \"Notebook\": \"https://jupyter-server.readthedocs.io/vocab#Notebook\",\n    \"Terminal\": \"https://jupyter-server.readthedocs.io/vocab#Terminal\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"version\": \"schema:version\",\n    \"path\": \"schema:contentLocation\",\n    \"lastActivity\": \"schema:dateModified\",\n    \"executionState\": \"https://jupyter-server.readthedocs.io/vocab#executionState\",\n    \"connections\": \"https://jupyter-server.readthedocs.io/vocab#connections\",\n    \"kernel\": \"https://jupyter-server.readthedocs.io/vocab#kernel\"\
  \n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/jupyter-server/refs/heads/main/json-ld/jupyter-server-context.jsonld
tags:
- Compute
- Interactive Computing
- Kernels
- Notebooks
- Portable
- Workbooks
- JSON-LD
- Linked Data
- Semantic Web
---
