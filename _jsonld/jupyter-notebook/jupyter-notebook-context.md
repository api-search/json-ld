---
api_specs:
- filename: jupyter-notebook-rest-api-openapi.yml
  format: yaml
  label: Jupyter Notebook REST API
  slug: jupyter-notebook-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jupyter-notebook/refs/heads/main/openapi/jupyter-notebook-rest-api-openapi.yml
- filename: jupyter-kernel-gateway-api-openapi.yml
  format: yaml
  label: Jupyter Kernel Gateway API
  slug: jupyter-kernel-gateway-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jupyter-notebook/refs/heads/main/openapi/jupyter-kernel-gateway-api-openapi.yml
- filename: jupyterhub-rest-api-openapi.yml
  format: yaml
  label: JupyterHub REST API
  slug: jupyterhub-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jupyter-notebook/refs/heads/main/openapi/jupyterhub-rest-api-openapi.yml
- filename: jupyter-kernel-messaging-asyncapi.yml
  format: yaml
  label: Jupyter Kernel Messaging Protocol
  slug: jupyter-kernel-messaging
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/jupyter-notebook/refs/heads/main/asyncapi/jupyter-kernel-messaging-asyncapi.yml
class_count: 3
classes:
- name
- description
- version
context_file: json-ld/jupyter-notebook-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/jupyter-notebook/refs/heads/main/json-ld/jupyter-notebook-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Jupyter Notebook from Jupyter Notebook.
layout: jsonld
name: Jupyter Notebook Context
namespaces:
- prefix: jupyter
  uri: https://jupyter.org/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: prov
  uri: http://www.w3.org/ns/prov#
properties:
- container: ''
  name: Notebook
  type: reference
- container: ''
  name: CodeCell
  type: reference
- container: ''
  name: MarkdownCell
  type: reference
- container: ''
  name: RawCell
  type: reference
- container: ''
  name: Kernel
  type: reference
- container: ''
  name: KernelSpec
  type: reference
- container: ''
  name: Session
  type: reference
- container: ''
  name: Terminal
  type: reference
- container: ''
  name: Contents
  type: reference
- container: ''
  name: Output
  type: reference
- container: ''
  name: url
  type: reference
- container: ''
  name: dateCreated
  type: dateTime
- container: ''
  name: dateModified
  type: dateTime
- container: ''
  name: nbformat
  type: integer
- container: ''
  name: nbformat_minor
  type: integer
- container: list
  name: cells
  type: reference
- container: ''
  name: cell_type
  type: string
- container: ''
  name: source
  type: string
- container: list
  name: outputs
  type: reference
- container: ''
  name: execution_count
  type: integer
- container: ''
  name: output_type
  type: string
- container: ''
  name: kernelspec
  type: reference
- container: ''
  name: display_name
  type: string
- container: ''
  name: language
  type: string
- container: list
  name: argv
  type: ''
- container: ''
  name: language_info
  type: reference
- container: ''
  name: mimetype
  type: string
- container: ''
  name: file_extension
  type: string
- container: ''
  name: execution_state
  type: string
- container: ''
  name: connections
  type: integer
- container: ''
  name: last_activity
  type: dateTime
- container: ''
  name: path
  type: string
- container: ''
  name: writable
  type: boolean
- container: ''
  name: format
  type: string
- container: ''
  name: size
  type: integer
- container: ''
  name: content
  type: ''
- container: ''
  name: kernel
  type: reference
- container: set
  name: tags
  type: ''
- container: ''
  name: metadata
  type: ''
- container: ''
  name: wasGeneratedBy
  type: reference
- container: ''
  name: used
  type: reference
- container: ''
  name: author
  type: reference
- container: ''
  name: license
  type: reference
- container: ''
  name: publisher
  type: reference
property_count: 44
provider_name: Jupyter Notebook
provider_slug: jupyter-notebook
slug: jupyter-notebook-context
source_filename: jupyter-notebook-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://jupyter.org/ns/\",\n    \"jupyter\": \"https://jupyter.org/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"prov\": \"http://www.w3.org/ns/prov#\",\n\n    \"Notebook\": {\n      \"@id\": \"jupyter:Notebook\",\n      \"@type\": \"@id\"\n    },\n    \"CodeCell\": {\n      \"@id\": \"jupyter:CodeCell\",\n      \"@type\": \"@id\"\n    },\n    \"MarkdownCell\": {\n      \"@id\": \"jupyter:MarkdownCell\",\n      \"@type\": \"@id\"\n    },\n    \"RawCell\": {\n      \"@id\": \"jupyter:RawCell\",\n      \"@type\": \"@id\"\n    },\n    \"Kernel\": {\n      \"@id\": \"jupyter:Kernel\",\n      \"@type\": \"@id\"\n    },\n    \"KernelSpec\": {\n      \"@id\": \"jupyter:KernelSpec\",\n      \"@type\": \"@id\"\n    },\n    \"Session\": {\n      \"@id\": \"jupyter:Session\",\n      \"@type\": \"@id\"\n    },\n    \"Terminal\": {\n   \
  \   \"@id\": \"jupyter:Terminal\",\n      \"@type\": \"@id\"\n    },\n    \"Contents\": {\n      \"@id\": \"jupyter:Contents\",\n      \"@type\": \"@id\"\n    },\n    \"Output\": {\n      \"@id\": \"jupyter:Output\",\n      \"@type\": \"@id\"\n    },\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"version\": \"schema:version\",\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"dateCreated\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"dateModified\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"nbformat\": {\n      \"@id\": \"jupyter:nbformat\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"nbformat_minor\": {\n      \"@id\": \"jupyter:nbformatMinor\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"cells\": {\n      \"@id\": \"jupyter:hasCell\",\n      \"@type\": \"@id\",\n      \"@container\": \"@list\"\n \
  \   },\n    \"cell_type\": {\n      \"@id\": \"jupyter:cellType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"jupyter:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outputs\": {\n      \"@id\": \"jupyter:hasOutput\",\n      \"@type\": \"@id\",\n      \"@container\": \"@list\"\n    },\n    \"execution_count\": {\n      \"@id\": \"jupyter:executionCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"output_type\": {\n      \"@id\": \"jupyter:outputType\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"kernelspec\": {\n      \"@id\": \"jupyter:hasKernelSpec\",\n      \"@type\": \"@id\"\n    },\n    \"display_name\": {\n      \"@id\": \"jupyter:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"language\": {\n      \"@id\": \"schema:programmingLanguage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"argv\": {\n      \"@id\": \"jupyter:argv\",\n      \"@container\": \"@list\"\n    },\n    \"language_info\": {\n      \"@id\"\
  : \"jupyter:languageInfo\",\n      \"@type\": \"@id\"\n    },\n    \"mimetype\": {\n      \"@id\": \"jupyter:mimeType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"file_extension\": {\n      \"@id\": \"jupyter:fileExtension\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"execution_state\": {\n      \"@id\": \"jupyter:executionState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connections\": {\n      \"@id\": \"jupyter:connectionCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"last_activity\": {\n      \"@id\": \"jupyter:lastActivity\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"path\": {\n      \"@id\": \"jupyter:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"writable\": {\n      \"@id\": \"jupyter:writable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"format\": {\n      \"@id\": \"jupyter:format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"size\": {\n      \"@id\": \"jupyter:fileSize\",\n      \"@type\": \"xsd:integer\"\n    },\n\
  \    \"content\": {\n      \"@id\": \"jupyter:content\"\n    },\n\n    \"kernel\": {\n      \"@id\": \"jupyter:hasKernel\",\n      \"@type\": \"@id\"\n    },\n\n    \"tags\": {\n      \"@id\": \"schema:keywords\",\n      \"@container\": \"@set\"\n    },\n    \"metadata\": {\n      \"@id\": \"jupyter:metadata\"\n    },\n\n    \"wasGeneratedBy\": {\n      \"@id\": \"prov:wasGeneratedBy\",\n      \"@type\": \"@id\"\n    },\n    \"used\": {\n      \"@id\": \"prov:used\",\n      \"@type\": \"@id\"\n    },\n\n    \"author\": {\n      \"@id\": \"schema:author\",\n      \"@type\": \"@id\"\n    },\n    \"license\": {\n      \"@id\": \"schema:license\",\n      \"@type\": \"@id\"\n    },\n    \"publisher\": {\n      \"@id\": \"schema:publisher\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/jupyter-notebook/refs/heads/main/json-ld/jupyter-notebook-context.jsonld
tags:
- Data Science
- Interactive Computing
- Jupyter
- Machine Learning
- Notebooks
- Python
- JSON-LD
- Linked Data
- Semantic Web
---
