---
api_specs:
- filename: deepl-translation-api-openapi.yml
  format: yaml
  label: DeepL Translation API
  slug: deepl-translation-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/deepl/refs/heads/main/openapi/deepl-translation-api-openapi.yml
class_count: 3
classes:
- Translation
- Glossary
- Document
context_file: json-ld/deepl-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/deepl/refs/heads/main/json-ld/deepl-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Deepl from DeepL.
layout: jsonld
name: Deepl Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: deepl
  uri: https://schema.deepl.com/
properties:
- container: ''
  name: translations
  type: ''
- container: ''
  name: text
  type: schema:Text
- container: ''
  name: detected_source_language
  type: schema:Text
- container: ''
  name: source_lang
  type: schema:Text
- container: ''
  name: target_lang
  type: schema:Text
- container: ''
  name: glossary_id
  type: ''
- container: ''
  name: name
  type: schema:Text
- container: ''
  name: creation_time
  type: schema:DateTime
- container: ''
  name: entry_count
  type: schema:Integer
property_count: 9
provider_name: DeepL
provider_slug: deepl
slug: deepl-context
source_filename: deepl-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.deepl.com/\",\n    \"schema\": \"https://schema.org/\",\n    \"deepl\": \"https://schema.deepl.com/\",\n    \"Translation\": \"deepl:Translation\",\n    \"Glossary\": \"deepl:Glossary\",\n    \"Document\": \"schema:DigitalDocument\",\n    \"translations\": {\"@id\": \"deepl:translations\"},\n    \"text\": {\"@id\": \"schema:text\", \"@type\": \"schema:Text\"},\n    \"detected_source_language\": {\"@id\": \"deepl:detectedSourceLanguage\", \"@type\": \"schema:Text\"},\n    \"source_lang\": {\"@id\": \"deepl:sourceLanguage\", \"@type\": \"schema:Text\"},\n    \"target_lang\": {\"@id\": \"deepl:targetLanguage\", \"@type\": \"schema:Text\"},\n    \"glossary_id\": {\"@id\": \"schema:identifier\"},\n    \"name\": {\"@id\": \"schema:name\", \"@type\": \"schema:Text\"},\n    \"creation_time\": {\"@id\": \"schema:dateCreated\", \"@type\": \"schema:DateTime\"},\n    \"entry_count\": {\"@id\": \"deepl:entryCount\"\
  , \"@type\": \"schema:Integer\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/deepl/refs/heads/main/json-ld/deepl-context.jsonld
tags:
- Artificial Intelligence
- Deep Learning
- Glossaries
- Localization
- Machine Learning
- Machine Translation
- Translation
- JSON-LD
- Linked Data
- Semantic Web
---
