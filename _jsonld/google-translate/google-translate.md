---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google Cloud Translation API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-translate/refs/heads/main/openapi/openapi.yml
class_count: 2
classes:
- translateRequest
- translateResponse
context_file: json-ld/google-translate.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-translate/refs/heads/main/json-ld/google-translate.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Translate from Google Cloud Translation API.
layout: jsonld
name: Google Translate Context
namespaces:
- prefix: goog
  uri: https://cloud.google.com/translate/docs/reference/rest/v2/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: sourceLanguage
  type: string
- container: ''
  name: targetLanguage
  type: string
- container: ''
  name: translatedText
  type: string
- container: ''
  name: detectedSourceLanguage
  type: string
- container: ''
  name: confidence
  type: float
- container: ''
  name: model
  type: string
- container: ''
  name: inputText
  type: string
- container: ''
  name: format
  type: string
property_count: 8
provider_name: Google Cloud Translation API
provider_slug: google-translate
slug: google-translate
source_filename: google-translate.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"goog\": \"https://cloud.google.com/translate/docs/reference/rest/v2/\",\n    \"translateRequest\": \"goog:TranslateTextRequest\",\n    \"translateResponse\": \"goog:TranslateTextResponse\",\n    \"sourceLanguage\": {\n      \"@id\": \"goog:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetLanguage\": {\n      \"@id\": \"goog:target\",\n      \"@type\": \"xsd:string\"\n    },\n    \"translatedText\": {\n      \"@id\": \"goog:translatedText\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detectedSourceLanguage\": {\n      \"@id\": \"goog:detectedSourceLanguage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"confidence\": {\n      \"@id\": \"goog:confidence\",\n      \"@type\": \"xsd:float\"\n    },\n    \"model\": {\n      \"@id\": \"goog:model\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inputText\": {\n      \"@id\": \"goog:q\",\n      \"@type\": \"xsd:string\"\n    },\n    \"format\"\
  : {\n      \"@id\": \"goog:format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-translate/refs/heads/main/json-ld/google-translate.jsonld
tags:
- Google Cloud
- Internationalization
- Language Detection
- Localization
- Machine Translation
- Natural Language Processing
- Translation
- JSON-LD
- Linked Data
- Semantic Web
---
