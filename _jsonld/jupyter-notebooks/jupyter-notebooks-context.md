---
api_specs:
- filename: jupyter-notebooks-openapi.yml
  format: yaml
  label: Jupyter Notebook Server REST API
  slug: notebook-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jupyter-notebooks/refs/heads/main/openapi/jupyter-notebooks-openapi.yml
class_count: 13
classes:
- name
- description
- url
- Notebook
- Cell
- Kernel
- KernelSpec
- Session
- Terminal
- cellType
- source
- outputs
- executionCount
context_file: json-ld/jupyter-notebooks-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/jupyter-notebooks/refs/heads/main/json-ld/jupyter-notebooks-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Jupyter Notebooks from Jupyter Notebooks.
layout: jsonld
name: Jupyter Notebooks Context
namespaces:
- prefix: jn
  uri: https://raw.githubusercontent.com/api-evangelist/jupyter-notebooks/main/json-ld/jupyter-notebooks-context.jsonld#
properties: []
property_count: 0
provider_name: Jupyter Notebooks
provider_slug: jupyter-notebooks
slug: jupyter-notebooks-context
source_filename: jupyter-notebooks-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"jn\": \"https://raw.githubusercontent.com/api-evangelist/jupyter-notebooks/main/json-ld/jupyter-notebooks-context.jsonld#\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"Notebook\": \"jn:Notebook\",\n    \"Cell\": \"jn:Cell\",\n    \"Kernel\": \"jn:Kernel\",\n    \"KernelSpec\": \"jn:KernelSpec\",\n    \"Session\": \"jn:Session\",\n    \"Terminal\": \"jn:Terminal\",\n    \"cellType\": \"jn:cellType\",\n    \"source\": \"jn:source\",\n    \"outputs\": \"jn:outputs\",\n    \"executionCount\": \"jn:executionCount\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/jupyter-notebooks/refs/heads/main/json-ld/jupyter-notebooks-context.jsonld
tags:
- Data Science
- Interactive Computing
- Jupyter
- Notebooks
- Python
- JSON-LD
- Linked Data
- Semantic Web
---
