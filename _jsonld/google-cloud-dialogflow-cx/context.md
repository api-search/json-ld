---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google Cloud Dialogflow CX API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-dialogflow-cx/refs/heads/main/openapi/openapi.yml
class_count: 4
classes:
- Agent
- Flow
- Intent
- Session
context_file: json-ld/context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-dialogflow-cx/refs/heads/main/json-ld/context.jsonld
description: JSON-LD context defining the semantic vocabulary for context from Google Cloud Dialogflow CX.
layout: jsonld
name: context Context
namespaces:
- prefix: gcloud
  uri: https://cloud.google.com/dialogflow/cx/docs/reference/rest/v3/
- prefix: name
  uri: https://schema.org/name
- prefix: displayName
  uri: https://schema.org/name
- prefix: description
  uri: https://schema.org/description
- prefix: defaultLanguageCode
  uri: https://schema.org/inLanguage
- prefix: supportedLanguageCodes
  uri: https://schema.org/availableLanguage
- prefix: timeZone
  uri: https://schema.org/timezone
- prefix: avatarUri
  uri: https://schema.org/image
- prefix: trainingPhrases
  uri: https://schema.org/text
- prefix: transitionRoutes
  uri: https://schema.org/potentialAction
properties:
- container: ''
  name: startFlow
  type: reference
property_count: 1
provider_name: Google Cloud Dialogflow CX
provider_slug: google-cloud-dialogflow-cx
slug: context
source_filename: context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gcloud\": \"https://cloud.google.com/dialogflow/cx/docs/reference/rest/v3/\",\n    \"Agent\": \"gcloud:projects.locations.agents\",\n    \"Flow\": \"gcloud:projects.locations.agents.flows\",\n    \"Intent\": \"gcloud:projects.locations.agents.intents\",\n    \"Session\": \"gcloud:projects.locations.agents.sessions\",\n    \"name\": \"https://schema.org/name\",\n    \"displayName\": \"https://schema.org/name\",\n    \"description\": \"https://schema.org/description\",\n    \"defaultLanguageCode\": \"https://schema.org/inLanguage\",\n    \"supportedLanguageCodes\": \"https://schema.org/availableLanguage\",\n    \"timeZone\": \"https://schema.org/timezone\",\n    \"avatarUri\": \"https://schema.org/image\",\n    \"startFlow\": {\n      \"@id\": \"https://schema.org/hasPart\",\n      \"@type\": \"@id\"\n    },\n    \"trainingPhrases\": \"https://schema.org/text\",\n    \"transitionRoutes\": \"https://schema.org/potentialAction\"\
  \n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-dialogflow-cx/refs/heads/main/json-ld/context.jsonld
tags:
- Chatbots
- Conversational AI
- Dialogflow
- Google Cloud
- NLU
- Virtual Agents
- JSON-LD
- Linked Data
- Semantic Web
---
