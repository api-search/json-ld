---
api_specs:
- filename: messagebird-sms-messaging-openapi.yml
  format: yaml
  label: MessageBird SMS Messaging API
  slug: sms-messaging-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/messagebird/refs/heads/main/openapi/messagebird-sms-messaging-openapi.yml
- filename: messagebird-voice-calling-openapi.yml
  format: yaml
  label: MessageBird Voice Calling API
  slug: voice-calling-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/messagebird/refs/heads/main/openapi/messagebird-voice-calling-openapi.yml
- filename: messagebird-voice-messaging-openapi.yml
  format: yaml
  label: MessageBird Voice Messaging API
  slug: voice-messaging-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/messagebird/refs/heads/main/openapi/messagebird-voice-messaging-openapi.yml
- filename: messagebird-conversations-openapi.yml
  format: yaml
  label: MessageBird Conversations API
  slug: conversations-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/messagebird/refs/heads/main/openapi/messagebird-conversations-openapi.yml
- filename: messagebird-whatsapp-openapi.yml
  format: yaml
  label: MessageBird WhatsApp API
  slug: whatsapp-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/messagebird/refs/heads/main/openapi/messagebird-whatsapp-openapi.yml
- filename: messagebird-verify-openapi.yml
  format: yaml
  label: MessageBird Verify API
  slug: verify-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/messagebird/refs/heads/main/openapi/messagebird-verify-openapi.yml
- filename: messagebird-lookup-openapi.yml
  format: yaml
  label: MessageBird Lookup API
  slug: lookup-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/messagebird/refs/heads/main/openapi/messagebird-lookup-openapi.yml
- filename: messagebird-hlr-openapi.yml
  format: yaml
  label: MessageBird HLR API
  slug: hlr-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/messagebird/refs/heads/main/openapi/messagebird-hlr-openapi.yml
- filename: messagebird-contacts-openapi.yml
  format: yaml
  label: MessageBird Contacts API
  slug: contacts-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/messagebird/refs/heads/main/openapi/messagebird-contacts-openapi.yml
- filename: messagebird-numbers-openapi.yml
  format: yaml
  label: MessageBird Numbers API
  slug: numbers-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/messagebird/refs/heads/main/openapi/messagebird-numbers-openapi.yml
- filename: messagebird-balance-openapi.yml
  format: yaml
  label: MessageBird Balance API
  slug: balance-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/messagebird/refs/heads/main/openapi/messagebird-balance-openapi.yml
- filename: messagebird-integrations-openapi.yml
  format: yaml
  label: MessageBird Integrations API
  slug: integrations-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/messagebird/refs/heads/main/openapi/messagebird-integrations-openapi.yml
class_count: 0
classes: []
context_file: json-ld/messagebird-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/messagebird/refs/heads/main/json-ld/messagebird-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Messagebird from messagebird.
layout: jsonld
name: Messagebird Context
namespaces:
- prefix: mb
  uri: https://developers.messagebird.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Message
  type: ''
- container: ''
  name: Conversation
  type: ''
- container: ''
  name: Contact
  type: ''
- container: ''
  name: Channel
  type: ''
- container: ''
  name: VoiceCall
  type: ''
- container: ''
  name: PhoneNumber
  type: ''
- container: ''
  name: Verification
  type: ''
- container: ''
  name: Template
  type: ''
property_count: 8
provider_name: messagebird
provider_slug: messagebird
slug: messagebird-context
source_filename: messagebird-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"mb\": \"https://developers.messagebird.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Message\": {\n      \"@id\": \"mb:Message\",\n      \"@context\": {\n        \"id\": \"mb:messageId\",\n        \"href\": {\n          \"@id\": \"mb:href\",\n          \"@type\": \"@id\"\n        },\n        \"direction\": \"mb:direction\",\n        \"type\": \"mb:messageType\",\n        \"originator\": \"mb:originator\",\n        \"body\": \"schema:text\",\n        \"reference\": \"mb:reference\",\n        \"reportUrl\": {\n          \"@id\": \"mb:reportUrl\",\n          \"@type\": \"@id\"\n        },\n        \"validity\": \"mb:validity\",\n        \"gateway\": \"mb:gateway\",\n        \"datacoding\": \"mb:datacoding\",\n        \"scheduledDatetime\": {\n          \"@id\": \"mb:scheduledDatetime\",\n          \"@type\": \"\
  xsd:dateTime\"\n        },\n        \"createdDatetime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"recipients\": {\n          \"@id\": \"mb:recipients\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Conversation\": {\n      \"@id\": \"mb:Conversation\",\n      \"@context\": {\n        \"id\": \"mb:conversationId\",\n        \"contactId\": \"mb:contactId\",\n        \"status\": \"mb:status\",\n        \"lastUsedChannelId\": \"mb:lastUsedChannelId\",\n        \"createdDatetime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedDatetime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastReceivedDatetime\": {\n          \"@id\": \"mb:lastReceivedDatetime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Contact\": {\n      \"@id\": \"mb:Contact\",\n\
  \      \"@context\": {\n        \"id\": \"mb:contactId\",\n        \"href\": {\n          \"@id\": \"mb:href\",\n          \"@type\": \"@id\"\n        },\n        \"msisdn\": \"schema:telephone\",\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"displayName\": \"schema:name\",\n        \"createdDatetime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedDatetime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Channel\": {\n      \"@id\": \"mb:Channel\",\n      \"@context\": {\n        \"id\": \"mb:channelId\",\n        \"name\": \"schema:name\",\n        \"platformId\": \"mb:platformId\",\n        \"status\": \"mb:status\",\n        \"createdDatetime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedDatetime\": {\n          \"@id\"\
  : \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"VoiceCall\": {\n      \"@id\": \"mb:VoiceCall\",\n      \"@context\": {\n        \"id\": \"mb:callId\",\n        \"status\": \"mb:status\",\n        \"source\": \"mb:source\",\n        \"destination\": \"mb:destination\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endedAt\": {\n          \"@id\": \"mb:endedAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"PhoneNumber\": {\n      \"@id\": \"mb:PhoneNumber\",\n      \"@context\": {\n        \"number\": \"schema:telephone\",\n        \"country\": \"schema:addressCountry\",\n        \"region\": \"schema:addressRegion\",\n        \"locality\": \"schema:addressLocality\",\n        \"type\": \"mb:numberType\",\n\
  \        \"features\": {\n          \"@id\": \"mb:features\",\n          \"@container\": \"@set\"\n        },\n        \"status\": \"mb:status\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Verification\": {\n      \"@id\": \"mb:Verification\",\n      \"@context\": {\n        \"id\": \"mb:verificationId\",\n        \"recipient\": \"schema:telephone\",\n        \"status\": \"mb:status\",\n        \"createdDatetime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"validUntilDatetime\": {\n          \"@id\": \"mb:validUntilDatetime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Template\": {\n      \"@id\": \"mb:Template\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"language\": \"schema:inLanguage\",\n        \"category\": \"mb:category\",\n        \"status\": \"mb:status\",\n\
  \        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/messagebird/refs/heads/main/json-ld/messagebird-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
