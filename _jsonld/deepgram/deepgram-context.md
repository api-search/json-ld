---
api_specs:
- filename: deepgram-speech-to-text-openapi.yml
  format: yaml
  label: Deepgram Speech-To-Text API
  slug: speech-to-text-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/deepgram/refs/heads/main/openapi/deepgram-speech-to-text-openapi.yml
- filename: deepgram-text-to-speech-openapi.yml
  format: yaml
  label: Deepgram Text-To-Speech API
  slug: text-to-speech-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/deepgram/refs/heads/main/openapi/deepgram-text-to-speech-openapi.yml
- filename: deepgram-voice-agent-asyncapi.yml
  format: yaml
  label: Deepgram Voice Agent API
  slug: voice-agent-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/deepgram/refs/heads/main/asyncapi/deepgram-voice-agent-asyncapi.yml
- filename: deepgram-speech-to-text-openapi.yml
  format: yaml
  label: Deepgram Audio Intelligence API
  slug: audio-intelligence-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/deepgram/refs/heads/main/openapi/deepgram-speech-to-text-openapi.yml
- filename: deepgram-management-openapi.yml
  format: yaml
  label: Deepgram Management API
  slug: management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/deepgram/refs/heads/main/openapi/deepgram-management-openapi.yml
class_count: 0
classes: []
context_file: json-ld/deepgram-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/deepgram/refs/heads/main/json-ld/deepgram-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Deepgram from Deepgram.
layout: jsonld
name: Deepgram Context
namespaces:
- prefix: dg
  uri: https://deepgram.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Transcript
  type: ''
- container: ''
  name: Word
  type: ''
- container: ''
  name: Utterance
  type: ''
- container: ''
  name: SentimentAnalysis
  type: ''
- container: ''
  name: TopicDetection
  type: ''
- container: ''
  name: IntentRecognition
  type: ''
- container: ''
  name: VoiceAgent
  type: ''
- container: ''
  name: Model
  type: ''
- container: ''
  name: Project
  type: ''
- container: ''
  name: ApiKey
  type: ''
- container: ''
  name: SpeechSynthesis
  type: ''
property_count: 11
provider_name: Deepgram
provider_slug: deepgram
slug: deepgram-context
source_filename: deepgram-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"dg\": \"https://deepgram.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Transcript\": {\n      \"@id\": \"dg:Transcript\",\n      \"@context\": {\n        \"requestId\": \"dg:requestId\",\n        \"transactionKey\": \"dg:transactionKey\",\n        \"duration\": {\n          \"@id\": \"schema:duration\",\n          \"@type\": \"xsd:float\"\n        },\n        \"channels\": {\n          \"@id\": \"dg:channels\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"sha256\": \"dg:sha256\",\n        \"model\": \"dg:model\",\n        \"transcript\": \"dg:transcript\",\n        \"confidence\": {\n          \"@id\": \"dg:confidence\",\n          \"@type\": \"xsd:float\"\n        }\n   \
  \   }\n    },\n\n    \"Word\": {\n      \"@id\": \"dg:Word\",\n      \"@context\": {\n        \"word\": \"dg:word\",\n        \"start\": {\n          \"@id\": \"dg:startTime\",\n          \"@type\": \"xsd:float\"\n        },\n        \"end\": {\n          \"@id\": \"dg:endTime\",\n          \"@type\": \"xsd:float\"\n        },\n        \"confidence\": {\n          \"@id\": \"dg:confidence\",\n          \"@type\": \"xsd:float\"\n        },\n        \"speaker\": {\n          \"@id\": \"dg:speaker\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"punctuatedWord\": \"dg:punctuatedWord\"\n      }\n    },\n\n    \"Utterance\": {\n      \"@id\": \"dg:Utterance\",\n      \"@context\": {\n        \"start\": {\n          \"@id\": \"dg:startTime\",\n          \"@type\": \"xsd:float\"\n        },\n        \"end\": {\n          \"@id\": \"dg:endTime\",\n          \"@type\": \"xsd:float\"\n        },\n        \"transcript\": \"dg:transcript\",\n        \"confidence\": {\n          \"@id\"\
  : \"dg:confidence\",\n          \"@type\": \"xsd:float\"\n        },\n        \"speaker\": {\n          \"@id\": \"dg:speaker\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"channel\": {\n          \"@id\": \"dg:channel\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"words\": {\n          \"@id\": \"dg:words\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"SentimentAnalysis\": {\n      \"@id\": \"dg:SentimentAnalysis\",\n      \"@context\": {\n        \"sentiment\": \"dg:sentiment\",\n        \"sentimentScore\": {\n          \"@id\": \"dg:sentimentScore\",\n          \"@type\": \"xsd:float\"\n        },\n        \"text\": \"schema:text\",\n        \"segments\": {\n          \"@id\": \"dg:segments\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"TopicDetection\": {\n      \"@id\": \"dg:TopicDetection\",\n      \"@context\": {\n        \"topic\": \"dg:topic\",\n        \"confidenceScore\": {\n         \
  \ \"@id\": \"dg:confidenceScore\",\n          \"@type\": \"xsd:float\"\n        },\n        \"text\": \"schema:text\",\n        \"segments\": {\n          \"@id\": \"dg:segments\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"IntentRecognition\": {\n      \"@id\": \"dg:IntentRecognition\",\n      \"@context\": {\n        \"intent\": \"dg:intent\",\n        \"confidenceScore\": {\n          \"@id\": \"dg:confidenceScore\",\n          \"@type\": \"xsd:float\"\n        },\n        \"text\": \"schema:text\",\n        \"segments\": {\n          \"@id\": \"dg:segments\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"VoiceAgent\": {\n      \"@id\": \"dg:VoiceAgent\",\n      \"@context\": {\n        \"sessionId\": \"dg:sessionId\",\n        \"instructions\": \"dg:instructions\",\n        \"listenModel\": \"dg:listenModel\",\n        \"thinkModel\": \"dg:thinkModel\",\n        \"speakModel\": \"dg:speakModel\",\n        \"provider\": \"dg:provider\"\
  \n      }\n    },\n\n    \"Model\": {\n      \"@id\": \"dg:Model\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"canonicalName\": \"dg:canonicalName\",\n        \"architecture\": \"dg:architecture\",\n        \"version\": \"schema:version\",\n        \"uuid\": \"dg:uuid\",\n        \"languages\": {\n          \"@id\": \"schema:inLanguage\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Project\": {\n      \"@id\": \"dg:Project\",\n      \"@context\": {\n        \"projectId\": \"dg:projectId\",\n        \"name\": \"schema:name\",\n        \"company\": \"schema:Organization\"\n      }\n    },\n\n    \"ApiKey\": {\n      \"@id\": \"dg:ApiKey\",\n      \"@context\": {\n        \"apiKeyId\": \"dg:apiKeyId\",\n        \"comment\": \"schema:description\",\n        \"scopes\": {\n          \"@id\": \"dg:scopes\",\n          \"@container\": \"@set\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\"\
  : \"xsd:dateTime\"\n        },\n        \"expirationDate\": {\n          \"@id\": \"schema:expires\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"SpeechSynthesis\": {\n      \"@id\": \"dg:SpeechSynthesis\",\n      \"@context\": {\n        \"text\": \"schema:text\",\n        \"model\": \"dg:model\",\n        \"encoding\": \"dg:encoding\",\n        \"sampleRate\": {\n          \"@id\": \"dg:sampleRate\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"container\": \"dg:container\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/deepgram/refs/heads/main/json-ld/deepgram-context.jsonld
tags:
- Artificial Intelligence
- Speech-To-Text
- Text-To-Speech
- Transcription
- Voice AI
- JSON-LD
- Linked Data
- Semantic Web
---
