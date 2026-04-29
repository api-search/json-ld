---
class_count: 7
classes:
- name
- description
- url
- identifier
- dateCreated
- dateModified
- status
context_file: json-ld/amazon-transcribe-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-transcribe/refs/heads/main/json-ld/amazon-transcribe-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Transcribe from Amazon Transcribe.
layout: jsonld
name: Amazon Transcribe Context
namespaces:
- prefix: transcribe
  uri: https://docs.aws.amazon.com/transcribe/latest/APIReference/
- prefix: aws
  uri: https://aws.amazon.com/
properties:
- container: ''
  name: provider
  type: schema:Organization
- container: ''
  name: TranscriptionJob
  type: ''
- container: ''
  name: Vocabulary
  type: ''
- container: ''
  name: VocabularyFilter
  type: ''
- container: ''
  name: Tag
  type: ''
property_count: 5
provider_name: Amazon Transcribe
provider_slug: amazon-transcribe
slug: amazon-transcribe-context
source_filename: amazon-transcribe-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"transcribe\": \"https://docs.aws.amazon.com/transcribe/latest/APIReference/\",\n    \"aws\": \"https://aws.amazon.com/\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"identifier\": \"schema:identifier\",\n    \"dateCreated\": \"schema:dateCreated\",\n    \"dateModified\": \"schema:dateModified\",\n    \"status\": \"schema:status\",\n    \"provider\": {\n      \"@id\": \"schema:provider\",\n      \"@type\": \"schema:Organization\"\n    },\n    \"TranscriptionJob\": {\n      \"@id\": \"transcribe:API_StartTranscriptionJob.html\",\n      \"@context\": {\n        \"TranscriptionJobName\": \"schema:name\",\n        \"TranscriptionJobStatus\": \"schema:status\",\n        \"LanguageCode\": \"schema:inLanguage\",\n        \"Media\": \"transcribe:Media\",\n        \"MediaFileUri\": \"schema:contentUrl\",\n        \"Transcript\": \"transcribe:Transcript\"\
  ,\n        \"TranscriptFileUri\": \"schema:url\",\n        \"CreationTime\": \"schema:dateCreated\",\n        \"StartTime\": \"schema:startDate\",\n        \"CompletionTime\": \"schema:endDate\"\n      }\n    },\n    \"Vocabulary\": {\n      \"@id\": \"transcribe:API_CreateVocabulary.html\",\n      \"@context\": {\n        \"VocabularyName\": \"schema:name\",\n        \"LanguageCode\": \"schema:inLanguage\",\n        \"VocabularyState\": \"schema:status\",\n        \"LastModifiedTime\": \"schema:dateModified\"\n      }\n    },\n    \"VocabularyFilter\": {\n      \"@id\": \"transcribe:API_CreateVocabularyFilter.html\",\n      \"@context\": {\n        \"VocabularyFilterName\": \"schema:name\",\n        \"LanguageCode\": \"schema:inLanguage\",\n        \"LastModifiedTime\": \"schema:dateModified\"\n      }\n    },\n    \"Tag\": {\n      \"@id\": \"transcribe:Tag\",\n      \"@context\": {\n        \"Key\": \"schema:name\",\n        \"Value\": \"schema:value\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-transcribe/refs/heads/main/json-ld/amazon-transcribe-context.jsonld
tags:
- Audio Processing
- AWS
- Machine Learning
- Speech Recognition
- Speech-To-Text
- Transcription
- JSON-LD
- Linked Data
- Semantic Web
---
