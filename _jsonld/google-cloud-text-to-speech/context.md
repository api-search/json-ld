---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google Cloud Text-to-Speech API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-text-to-speech/refs/heads/main/openapi/openapi.yml
class_count: 13
classes:
- SpeechSynthesis
- voice
- languageCode
- ssmlGender
- audioEncoding
- speakingRate
- pitch
- volumeGainDb
- sampleRateHertz
- audioContent
- name
- description
- url
context_file: json-ld/context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-text-to-speech/refs/heads/main/json-ld/context.jsonld
description: JSON-LD context defining the semantic vocabulary for context from Google Cloud Text-To-Speech.
layout: jsonld
name: context Context
namespaces:
- prefix: gcp
  uri: https://cloud.google.com/text-to-speech#
properties: []
property_count: 0
provider_name: Google Cloud Text-To-Speech
provider_slug: google-cloud-text-to-speech
slug: context
source_filename: context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gcp\": \"https://cloud.google.com/text-to-speech#\",\n    \"SpeechSynthesis\": \"gcp:SpeechSynthesis\",\n    \"voice\": \"gcp:voice\",\n    \"languageCode\": \"gcp:languageCode\",\n    \"ssmlGender\": \"gcp:ssmlGender\",\n    \"audioEncoding\": \"gcp:audioEncoding\",\n    \"speakingRate\": \"gcp:speakingRate\",\n    \"pitch\": \"gcp:pitch\",\n    \"volumeGainDb\": \"gcp:volumeGainDb\",\n    \"sampleRateHertz\": \"gcp:sampleRateHertz\",\n    \"audioContent\": \"gcp:audioContent\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-text-to-speech/refs/heads/main/json-ld/context.jsonld
tags:
- Audio
- Google Cloud
- Machine Learning
- Speech Synthesis
- Text-To-Speech
- JSON-LD
- Linked Data
- Semantic Web
---
