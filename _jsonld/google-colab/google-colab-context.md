---
api_specs:
- filename: colab-drive-openapi.yml
  format: yaml
  label: Colab API via Google Drive API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-colab/refs/heads/main/openapi/colab-drive-openapi.yml
class_count: 0
classes: []
context_file: json-ld/google-colab-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-colab/refs/heads/main/json-ld/google-colab-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Colab from Google Colab.
layout: jsonld
name: Google Colab Context
namespaces:
- prefix: colab
  uri: https://colab.research.google.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Notebook
  type: ''
- container: ''
  name: Cell
  type: ''
- container: ''
  name: Runtime
  type: ''
- container: ''
  name: Permission
  type: ''
property_count: 4
provider_name: Google Colab
provider_slug: google-colab
slug: google-colab-context
source_filename: google-colab-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"colab\": \"https://colab.research.google.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Notebook\": {\n      \"@id\": \"colab:Notebook\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"fileId\": \"colab:fileId\",\n        \"mimeType\": \"schema:encodingFormat\",\n        \"webViewLink\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"createdTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"owner\": \"schema:author\",\n        \"accelerator\": \"colab:accelerator\"\n      }\n    },\n\n    \"Cell\": {\n      \"@id\"\
  : \"colab:Cell\",\n      \"@context\": {\n        \"cellType\": \"colab:cellType\",\n        \"source\": \"colab:source\",\n        \"executionCount\": \"colab:executionCount\",\n        \"outputs\": \"colab:outputs\"\n      }\n    },\n\n    \"Runtime\": {\n      \"@id\": \"colab:Runtime\",\n      \"@context\": {\n        \"runtimeType\": \"colab:runtimeType\",\n        \"hardwareAccelerator\": \"colab:hardwareAccelerator\",\n        \"state\": \"colab:runtimeState\",\n        \"connectedAt\": {\n          \"@id\": \"colab:connectedAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Permission\": {\n      \"@id\": \"colab:Permission\",\n      \"@context\": {\n        \"role\": \"colab:role\",\n        \"type\": \"colab:permissionType\",\n        \"emailAddress\": \"schema:email\",\n        \"displayName\": \"schema:name\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-colab/refs/heads/main/json-ld/google-colab-context.jsonld
tags:
- Collaboration
- Data Science
- Google Cloud
- Jupyter
- Machine Learning
- Notebooks
- Python
- JSON-LD
- Linked Data
- Semantic Web
---
