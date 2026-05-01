---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google Cloud Translation API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-translation/refs/heads/main/openapi/openapi.yml
class_count: 12
classes:
- Translation
- sourceLanguageCode
- targetLanguageCode
- translatedText
- detectedLanguageCode
- glossary
- mimeType
- contents
- model
- name
- description
- url
context_file: json-ld/context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-translation/refs/heads/main/json-ld/context.jsonld
description: JSON-LD context defining the semantic vocabulary for context from Google Cloud Translation.
layout: jsonld
name: context Context
namespaces:
- prefix: gcp
  uri: https://cloud.google.com/translate#
properties: []
property_count: 0
provider_name: Google Cloud Translation
provider_slug: google-cloud-translation
slug: context
source_filename: context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gcp\": \"https://cloud.google.com/translate#\",\n    \"Translation\": \"gcp:Translation\",\n    \"sourceLanguageCode\": \"gcp:sourceLanguageCode\",\n    \"targetLanguageCode\": \"gcp:targetLanguageCode\",\n    \"translatedText\": \"gcp:translatedText\",\n    \"detectedLanguageCode\": \"gcp:detectedLanguageCode\",\n    \"glossary\": \"gcp:glossary\",\n    \"mimeType\": \"gcp:mimeType\",\n    \"contents\": \"gcp:contents\",\n    \"model\": \"gcp:model\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-translation/refs/heads/main/json-ld/context.jsonld
tags:
- Google Cloud
- Language
- Localization
- Machine Learning
- Translation
- JSON-LD
- Linked Data
- Semantic Web
---
