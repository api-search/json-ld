---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google Cloud Document AI API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-document-ai/refs/heads/main/openapi/openapi.yml
class_count: 13
classes:
- DocumentProcessing
- processor
- document
- mimeType
- entity
- mentionText
- confidence
- page
- rawDocument
- inlineDocument
- name
- description
- url
context_file: json-ld/context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-document-ai/refs/heads/main/json-ld/context.jsonld
description: JSON-LD context defining the semantic vocabulary for context from Google Cloud Document AI.
layout: jsonld
name: context Context
namespaces:
- prefix: gcp
  uri: https://cloud.google.com/document-ai#
properties: []
property_count: 0
provider_name: Google Cloud Document AI
provider_slug: google-cloud-document-ai
slug: context
source_filename: context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gcp\": \"https://cloud.google.com/document-ai#\",\n    \"DocumentProcessing\": \"gcp:DocumentProcessing\",\n    \"processor\": \"gcp:processor\",\n    \"document\": \"gcp:document\",\n    \"mimeType\": \"gcp:mimeType\",\n    \"entity\": \"gcp:entity\",\n    \"mentionText\": \"gcp:mentionText\",\n    \"confidence\": \"gcp:confidence\",\n    \"page\": \"gcp:page\",\n    \"rawDocument\": \"gcp:rawDocument\",\n    \"inlineDocument\": \"gcp:inlineDocument\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-document-ai/refs/heads/main/json-ld/context.jsonld
tags:
- Data Extraction
- Document Processing
- Forms
- Google Cloud
- Machine Learning
- OCR
- JSON-LD
- Linked Data
- Semantic Web
---
