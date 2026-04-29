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
context_file: json-ld/amazon-translate-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-translate/refs/heads/main/json-ld/amazon-translate-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Translate from Amazon Translate.
layout: jsonld
name: Amazon Translate Context
namespaces:
- prefix: translate
  uri: https://docs.aws.amazon.com/translate/latest/APIReference/
- prefix: aws
  uri: https://aws.amazon.com/
properties:
- container: ''
  name: provider
  type: schema:Organization
- container: ''
  name: TextTranslationJob
  type: ''
- container: ''
  name: TranslateText
  type: ''
- container: ''
  name: Terminology
  type: ''
- container: ''
  name: Tag
  type: ''
property_count: 5
provider_name: Amazon Translate
provider_slug: amazon-translate
slug: amazon-translate-context
source_filename: amazon-translate-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"translate\": \"https://docs.aws.amazon.com/translate/latest/APIReference/\",\n    \"aws\": \"https://aws.amazon.com/\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"identifier\": \"schema:identifier\",\n    \"dateCreated\": \"schema:dateCreated\",\n    \"dateModified\": \"schema:dateModified\",\n    \"status\": \"schema:status\",\n    \"provider\": {\n      \"@id\": \"schema:provider\",\n      \"@type\": \"schema:Organization\"\n    },\n    \"TextTranslationJob\": {\n      \"@id\": \"translate:API_StartTextTranslationJob.html\",\n      \"@context\": {\n        \"JobId\": \"schema:identifier\",\n        \"JobName\": \"schema:name\",\n        \"JobStatus\": \"schema:status\",\n        \"SourceLanguageCode\": \"schema:inLanguage\",\n        \"TargetLanguageCodes\": \"translate:TargetLanguageCodes\",\n        \"SubmittedTime\": \"schema:dateCreated\"\
  ,\n        \"EndTime\": \"schema:endDate\"\n      }\n    },\n    \"TranslateText\": {\n      \"@id\": \"translate:API_TranslateText.html\",\n      \"@context\": {\n        \"Text\": \"schema:text\",\n        \"TranslatedText\": \"schema:text\",\n        \"SourceLanguageCode\": \"schema:inLanguage\",\n        \"TargetLanguageCode\": \"translate:TargetLanguageCode\"\n      }\n    },\n    \"Terminology\": {\n      \"@id\": \"translate:API_ImportTerminology.html\",\n      \"@context\": {\n        \"Name\": \"schema:name\",\n        \"Description\": \"schema:description\",\n        \"Arn\": \"schema:identifier\",\n        \"SourceLanguageCode\": \"schema:inLanguage\",\n        \"TargetLanguageCodes\": \"translate:TargetLanguageCodes\",\n        \"CreatedAt\": \"schema:dateCreated\",\n        \"LastUpdatedAt\": \"schema:dateModified\"\n      }\n    },\n    \"Tag\": {\n      \"@id\": \"translate:Tag\",\n      \"@context\": {\n        \"Key\": \"schema:name\",\n        \"Value\": \"schema:value\"\
  \n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-translate/refs/heads/main/json-ld/amazon-translate-context.jsonld
tags:
- AWS
- Language Processing
- Localization
- Machine Translation
- NLP
- Translation
- JSON-LD
- Linked Data
- Semantic Web
---
