---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google Cloud Contact Center AI API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-contact-center-ai/refs/heads/main/openapi/openapi.yml
class_count: 2
classes:
- Conversation
- Analysis
context_file: json-ld/context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-contact-center-ai/refs/heads/main/json-ld/context.jsonld
description: JSON-LD context defining the semantic vocabulary for context from Google Cloud Contact Center AI.
layout: jsonld
name: context Context
namespaces:
- prefix: gcloud
  uri: https://cloud.google.com/contact-center/ai/docs/reference/rest/v1/
- prefix: name
  uri: https://schema.org/name
- prefix: description
  uri: https://schema.org/description
- prefix: createTime
  uri: https://schema.org/dateCreated
- prefix: updateTime
  uri: https://schema.org/dateModified
- prefix: startTime
  uri: https://schema.org/startTime
- prefix: duration
  uri: https://schema.org/duration
- prefix: agentId
  uri: https://schema.org/identifier
- prefix: languageCode
  uri: https://schema.org/inLanguage
- prefix: labels
  uri: https://schema.org/keywords
- prefix: turnCount
  uri: https://schema.org/numberOfItems
- prefix: transcript
  uri: https://schema.org/transcript
properties: []
property_count: 0
provider_name: Google Cloud Contact Center AI
provider_slug: google-cloud-contact-center-ai
slug: context
source_filename: context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gcloud\": \"https://cloud.google.com/contact-center/ai/docs/reference/rest/v1/\",\n    \"Conversation\": \"gcloud:projects.locations.conversations\",\n    \"Analysis\": \"gcloud:projects.locations.conversations.analyses\",\n    \"name\": \"https://schema.org/name\",\n    \"description\": \"https://schema.org/description\",\n    \"createTime\": \"https://schema.org/dateCreated\",\n    \"updateTime\": \"https://schema.org/dateModified\",\n    \"startTime\": \"https://schema.org/startTime\",\n    \"duration\": \"https://schema.org/duration\",\n    \"agentId\": \"https://schema.org/identifier\",\n    \"languageCode\": \"https://schema.org/inLanguage\",\n    \"labels\": \"https://schema.org/keywords\",\n    \"turnCount\": \"https://schema.org/numberOfItems\",\n    \"transcript\": \"https://schema.org/transcript\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-contact-center-ai/refs/heads/main/json-ld/context.jsonld
tags:
- AI
- Contact Center
- Conversations
- Customer Service
- Google Cloud
- Virtual Agents
- JSON-LD
- Linked Data
- Semantic Web
---
