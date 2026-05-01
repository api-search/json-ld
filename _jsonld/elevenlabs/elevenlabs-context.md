---
api_specs:
- filename: elevenlabs-text-to-speech-openapi.yml
  format: yaml
  label: ElevenLabs Text to Speech API
  slug: text-to-speech
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/elevenlabs/refs/heads/main/openapi/elevenlabs-text-to-speech-openapi.yml
- filename: elevenlabs-speech-to-text-openapi.yml
  format: yaml
  label: ElevenLabs Speech to Text API
  slug: speech-to-text
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/elevenlabs/refs/heads/main/openapi/elevenlabs-speech-to-text-openapi.yml
- filename: elevenlabs-voice-cloning-openapi.yml
  format: yaml
  label: ElevenLabs Voice Cloning API
  slug: voice-cloning
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/elevenlabs/refs/heads/main/openapi/elevenlabs-voice-cloning-openapi.yml
- filename: elevenlabs-voices-openapi.yml
  format: yaml
  label: ElevenLabs Voices API
  slug: voices
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/elevenlabs/refs/heads/main/openapi/elevenlabs-voices-openapi.yml
- filename: elevenlabs-sound-effects-openapi.yml
  format: yaml
  label: ElevenLabs Sound Effects API
  slug: sound-effects
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/elevenlabs/refs/heads/main/openapi/elevenlabs-sound-effects-openapi.yml
- filename: elevenlabs-audio-isolation-openapi.yml
  format: yaml
  label: ElevenLabs Audio Isolation API
  slug: audio-isolation
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/elevenlabs/refs/heads/main/openapi/elevenlabs-audio-isolation-openapi.yml
- filename: elevenlabs-dubbing-openapi.yml
  format: yaml
  label: ElevenLabs Dubbing API
  slug: dubbing
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/elevenlabs/refs/heads/main/openapi/elevenlabs-dubbing-openapi.yml
- filename: elevenlabs-voice-changer-openapi.yml
  format: yaml
  label: ElevenLabs Voice Changer API
  slug: voice-changer
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/elevenlabs/refs/heads/main/openapi/elevenlabs-voice-changer-openapi.yml
- filename: elevenlabs-music-openapi.yml
  format: yaml
  label: ElevenLabs Music Generation API
  slug: music
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/elevenlabs/refs/heads/main/openapi/elevenlabs-music-openapi.yml
- filename: elevenlabs-conversational-ai-openapi.yml
  format: yaml
  label: ElevenLabs Conversational AI API
  slug: conversational-ai
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/elevenlabs/refs/heads/main/openapi/elevenlabs-conversational-ai-openapi.yml
- filename: elevenlabs-studio-openapi.yml
  format: yaml
  label: ElevenLabs Studio API
  slug: studio
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/elevenlabs/refs/heads/main/openapi/elevenlabs-studio-openapi.yml
class_count: 0
classes: []
context_file: json-ld/elevenlabs-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/elevenlabs/refs/heads/main/json-ld/elevenlabs-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Elevenlabs from elevenlabs.
layout: jsonld
name: Elevenlabs Context
namespaces:
- prefix: elevenlabs
  uri: https://elevenlabs.io/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Voice
  type: ''
- container: ''
  name: VoiceSettings
  type: ''
- container: ''
  name: Agent
  type: ''
- container: ''
  name: Conversation
  type: ''
- container: ''
  name: DubbingProject
  type: ''
- container: ''
  name: StudioProject
  type: ''
- container: ''
  name: Chapter
  type: ''
- container: ''
  name: KnowledgeBaseDocument
  type: ''
- container: ''
  name: Tool
  type: ''
- container: ''
  name: Model
  type: ''
- container: ''
  name: PronunciationDictionary
  type: ''
property_count: 11
provider_name: elevenlabs
provider_slug: elevenlabs
slug: elevenlabs-context
source_filename: elevenlabs-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"elevenlabs\": \"https://elevenlabs.io/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Voice\": {\n      \"@id\": \"elevenlabs:Voice\",\n      \"@context\": {\n        \"voice_id\": \"elevenlabs:voiceId\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"category\": \"elevenlabs:voiceCategory\",\n        \"preview_url\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"@id\"\n        },\n        \"labels\": \"elevenlabs:voiceLabels\",\n        \"settings\": \"elevenlabs:voiceSettings\",\n        \"samples\": \"elevenlabs:voiceSamples\",\n        \"high_quality_base_model_ids\": \"elevenlabs:compatibleModels\"\n      }\n    },\n\n    \"VoiceSettings\": {\n      \"@id\": \"elevenlabs:VoiceSettings\",\n      \"@context\": {\n        \"stability\": \"\
  elevenlabs:stability\",\n        \"similarity_boost\": \"elevenlabs:similarityBoost\",\n        \"style\": \"elevenlabs:style\",\n        \"use_speaker_boost\": \"elevenlabs:useSpeakerBoost\"\n      }\n    },\n\n    \"Agent\": {\n      \"@id\": \"elevenlabs:Agent\",\n      \"@context\": {\n        \"agent_id\": \"elevenlabs:agentId\",\n        \"name\": \"schema:name\",\n        \"conversation_config\": \"elevenlabs:conversationConfig\",\n        \"tools\": {\n          \"@id\": \"elevenlabs:agentTools\",\n          \"@container\": \"@set\"\n        },\n        \"knowledge_base\": {\n          \"@id\": \"elevenlabs:knowledgeBase\",\n          \"@container\": \"@set\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Conversation\": {\n      \"@id\": \"elevenlabs:Conversation\",\n      \"@context\": {\n        \"conversation_id\": \"elevenlabs:conversationId\",\n        \"agent_id\"\
  : \"elevenlabs:agentId\",\n        \"status\": \"elevenlabs:conversationStatus\",\n        \"transcript\": {\n          \"@id\": \"elevenlabs:transcript\",\n          \"@container\": \"@list\"\n        },\n        \"started_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"duration_seconds\": \"elevenlabs:durationSeconds\"\n      }\n    },\n\n    \"DubbingProject\": {\n      \"@id\": \"elevenlabs:DubbingProject\",\n      \"@context\": {\n        \"dubbing_id\": \"elevenlabs:dubbingId\",\n        \"name\": \"schema:name\",\n        \"status\": \"elevenlabs:dubbingStatus\",\n        \"source_language\": {\n          \"@id\": \"schema:inLanguage\"\n        },\n        \"target_languages\": {\n          \"@id\": \"elevenlabs:targetLanguages\",\n          \"@container\": \"@set\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n  \
  \  \"StudioProject\": {\n      \"@id\": \"elevenlabs:StudioProject\",\n      \"@context\": {\n        \"project_id\": \"elevenlabs:projectId\",\n        \"name\": \"schema:name\",\n        \"state\": \"elevenlabs:projectState\",\n        \"default_voice_id\": \"elevenlabs:defaultVoiceId\",\n        \"chapters\": {\n          \"@id\": \"elevenlabs:chapters\",\n          \"@container\": \"@list\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Chapter\": {\n      \"@id\": \"elevenlabs:Chapter\",\n      \"@context\": {\n        \"chapter_id\": \"elevenlabs:chapterId\",\n        \"name\": \"schema:name\",\n        \"content\": \"schema:text\",\n        \"voice_id\": \"elevenlabs:voiceId\",\n        \"state\": \"elevenlabs:chapterState\"\n      }\n    },\n\n    \"KnowledgeBaseDocument\": {\n      \"@id\": \"elevenlabs:KnowledgeBaseDocument\",\n      \"@context\": {\n        \"document_id\"\
  : \"elevenlabs:documentId\",\n        \"name\": \"schema:name\",\n        \"type\": \"elevenlabs:documentType\",\n        \"source_url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Tool\": {\n      \"@id\": \"elevenlabs:Tool\",\n      \"@context\": {\n        \"tool_id\": \"elevenlabs:toolId\",\n        \"name\": \"schema:name\",\n        \"type\": \"elevenlabs:toolType\",\n        \"description\": \"schema:description\",\n        \"webhook_url\": {\n          \"@id\": \"elevenlabs:webhookUrl\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Model\": {\n      \"@id\": \"elevenlabs:Model\",\n      \"@context\": {\n        \"model_id\": \"elevenlabs:modelId\",\n        \"name\"\
  : \"schema:name\",\n        \"description\": \"schema:description\",\n        \"can_do_text_to_speech\": \"elevenlabs:canDoTextToSpeech\",\n        \"can_do_voice_conversion\": \"elevenlabs:canDoVoiceConversion\",\n        \"languages\": {\n          \"@id\": \"schema:availableLanguage\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"PronunciationDictionary\": {\n      \"@id\": \"elevenlabs:PronunciationDictionary\",\n      \"@context\": {\n        \"pronunciation_dictionary_id\": \"elevenlabs:dictionaryId\",\n        \"version_id\": \"elevenlabs:dictionaryVersionId\",\n        \"name\": \"schema:name\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/elevenlabs/refs/heads/main/json-ld/elevenlabs-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
