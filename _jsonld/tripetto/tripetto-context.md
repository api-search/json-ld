---
api_specs:
- filename: tripetto-form-builder-openapi.yml
  format: yaml
  label: Tripetto FormBuilder SDK
  slug: tripetto-form-builder-sdk
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tripetto/refs/heads/main/openapi/tripetto-form-builder-openapi.yml
class_count: 29
classes:
- Form
- FormDefinition
- FormNode
- FormResponse
- ResponseField
- Webhook
- id
- name
- description
- created
- modified
- definition
- nodes
- sections
- conditions
- formId
- fields
- submittedAt
- fingerprint
- required
- type
- settings
- value
- responseCount
- url
- sendRawData
- enabled
- SurveyAction
- Question
context_file: json-ld/tripetto-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tripetto/refs/heads/main/json-ld/tripetto-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tripetto from Tripetto.
layout: jsonld
name: Tripetto Context
namespaces:
- prefix: tripetto
  uri: https://tripetto.com/sdk/vocab#
properties: []
property_count: 0
provider_name: Tripetto
provider_slug: tripetto
slug: tripetto-context
source_filename: tripetto-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"tripetto\": \"https://tripetto.com/sdk/vocab#\",\n    \"Form\": \"tripetto:Form\",\n    \"FormDefinition\": \"tripetto:FormDefinition\",\n    \"FormNode\": \"tripetto:FormNode\",\n    \"FormResponse\": \"tripetto:FormResponse\",\n    \"ResponseField\": \"tripetto:ResponseField\",\n    \"Webhook\": \"tripetto:Webhook\",\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"created\": \"schema:dateCreated\",\n    \"modified\": \"schema:dateModified\",\n    \"definition\": \"tripetto:definition\",\n    \"nodes\": \"tripetto:nodes\",\n    \"sections\": \"tripetto:sections\",\n    \"conditions\": \"tripetto:conditions\",\n    \"formId\": \"tripetto:formId\",\n    \"fields\": \"tripetto:fields\",\n    \"submittedAt\": \"schema:datePublished\",\n    \"fingerprint\": \"tripetto:fingerprint\",\n    \"required\": \"tripetto:required\",\n    \"type\": \"schema:additionalType\"\
  ,\n    \"settings\": \"tripetto:settings\",\n    \"value\": \"schema:value\",\n    \"responseCount\": \"tripetto:responseCount\",\n    \"url\": \"schema:url\",\n    \"sendRawData\": \"tripetto:sendRawData\",\n    \"enabled\": \"schema:actionStatus\",\n    \"SurveyAction\": \"schema:SurveyAction\",\n    \"Question\": \"schema:Question\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tripetto/refs/heads/main/json-ld/tripetto-context.jsonld
tags:
- Forms
- Surveys
- Form Builder
- No-Code
- SDK
- Webhooks
- JSON-LD
- Linked Data
- Semantic Web
---
