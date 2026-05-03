---
api_specs:
- filename: streamlit-cloud-openapi.yml
  format: yaml
  label: Streamlit Community Cloud API
  slug: streamlit-cloud-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/streamlit/refs/heads/main/openapi/streamlit-cloud-openapi.yml
class_count: 0
classes: []
context_file: json-ld/streamlit-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/streamlit/refs/heads/main/json-ld/streamlit-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Streamlit from Streamlit.
layout: jsonld
name: Streamlit Context
namespaces:
- prefix: streamlit
  uri: https://streamlit.io/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: doap
  uri: http://usefulinc.com/ns/doap#
properties:
- container: ''
  name: App
  type: ''
- container: ''
  name: Workspace
  type: ''
property_count: 2
provider_name: Streamlit
provider_slug: streamlit
slug: streamlit-context
source_filename: streamlit-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"streamlit\": \"https://streamlit.io/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"doap\": \"http://usefulinc.com/ns/doap#\",\n\n    \"App\": {\n      \"@id\": \"streamlit:App\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"status\": {\n          \"@id\": \"streamlit:deploymentStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"repo\": {\n          \"@id\": \"doap:repository\",\n          \"@type\": \"xsd:string\"\n        },\n        \"branch\": {\n          \"@id\": \"doap:branch\",\n          \"@type\": \"xsd:string\"\n        },\n        \"mainFile\": {\n          \"@id\": \"streamlit:mainFile\",\n          \"@type\": \"xsd:string\"\n        },\n\
  \        \"owner\": {\n          \"@id\": \"schema:author\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Workspace\": {\n      \"@id\": \"streamlit:Workspace\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"owner\": \"schema:author\",\n        \"plan\": \"schema:offers\",\n        \"appCount\": {\n          \"@id\": \"streamlit:appCount\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/streamlit/refs/heads/main/json-ld/streamlit-context.jsonld
tags:
- Data Science
- Machine Learning
- Open Source
- Python
- Web Applications
- JSON-LD
- Linked Data
- Semantic Web
---
