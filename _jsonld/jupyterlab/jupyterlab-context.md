---
api_specs:
- filename: jupyterlab-server-rest-api-openapi.yml
  format: yaml
  label: JupyterLab Server REST API
  slug: jupyterlab-server-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jupyterlab/refs/heads/main/openapi/jupyterlab-server-rest-api-openapi.yml
class_count: 6
classes:
- JupyterLab
- id
- name
- version
- lastModified
- created
context_file: json-ld/jupyterlab-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/jupyterlab/refs/heads/main/json-ld/jupyterlab-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Jupyterlab from JupyterLab.
layout: jsonld
name: Jupyterlab Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: Workspace
  uri: https://jupyterlab.readthedocs.io/vocab#Workspace
- prefix: Setting
  uri: https://jupyterlab.readthedocs.io/vocab#Setting
- prefix: Extension
  uri: https://jupyterlab.readthedocs.io/vocab#Extension
- prefix: Plugin
  uri: https://jupyterlab.readthedocs.io/vocab#Plugin
- prefix: Theme
  uri: https://jupyterlab.readthedocs.io/vocab#Theme
- prefix: data
  uri: https://jupyterlab.readthedocs.io/vocab#data
- prefix: raw
  uri: https://jupyterlab.readthedocs.io/vocab#raw
- prefix: schemaDef
  uri: https://jupyterlab.readthedocs.io/vocab#schema
properties: []
property_count: 0
provider_name: JupyterLab
provider_slug: jupyterlab
slug: jupyterlab-context
source_filename: jupyterlab-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://jupyterlab.readthedocs.io/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"JupyterLab\": \"schema:SoftwareApplication\",\n    \"Workspace\": \"https://jupyterlab.readthedocs.io/vocab#Workspace\",\n    \"Setting\": \"https://jupyterlab.readthedocs.io/vocab#Setting\",\n    \"Extension\": \"https://jupyterlab.readthedocs.io/vocab#Extension\",\n    \"Plugin\": \"https://jupyterlab.readthedocs.io/vocab#Plugin\",\n    \"Theme\": \"https://jupyterlab.readthedocs.io/vocab#Theme\",\n    \"id\": \"schema:identifier\",\n    \"name\": \"schema:name\",\n    \"version\": \"schema:version\",\n    \"data\": \"https://jupyterlab.readthedocs.io/vocab#data\",\n    \"raw\": \"https://jupyterlab.readthedocs.io/vocab#raw\",\n    \"schemaDef\": \"https://jupyterlab.readthedocs.io/vocab#schema\",\n    \"lastModified\": \"schema:dateModified\",\n    \"created\": \"schema:dateCreated\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/jupyterlab/refs/heads/main/json-ld/jupyterlab-context.jsonld
tags:
- Data Science
- Extensions
- IDE
- Interactive Computing
- Notebooks
- Python
- JSON-LD
- Linked Data
- Semantic Web
---
