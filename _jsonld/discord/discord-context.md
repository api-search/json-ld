---
api_specs:
- filename: discord-api-spec
  format: yaml
  label: Discord REST API
  slug: discord-rest-api
  spec_type: OpenAPI
  url: https://github.com/discord/discord-api-spec
- filename: discord-gateway-api-asyncapi.yml
  format: yaml
  label: Discord Gateway API
  slug: discord-gateway-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/discord/refs/heads/main/asyncapi/discord-gateway-api-asyncapi.yml
- filename: discord-interactions-api-openapi.yml
  format: yaml
  label: Discord Interactions API
  slug: discord-interactions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/discord/refs/heads/main/openapi/discord-interactions-api-openapi.yml
- filename: discord-oauth2-api-openapi.yml
  format: yaml
  label: Discord OAuth2 API
  slug: discord-oauth2-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/discord/refs/heads/main/openapi/discord-oauth2-api-openapi.yml
- filename: discord-webhook-events-api-openapi.yml
  format: yaml
  label: Discord Webhook Events API
  slug: discord-webhook-events-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/discord/refs/heads/main/openapi/discord-webhook-events-api-openapi.yml
- filename: discord-voice-api-asyncapi.yml
  format: yaml
  label: Discord Voice API
  slug: discord-voice-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/discord/refs/heads/main/asyncapi/discord-voice-api-asyncapi.yml
- filename: discord-linked-roles-api-openapi.yml
  format: yaml
  label: Discord Linked Roles API
  slug: discord-linked-roles-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/discord/refs/heads/main/openapi/discord-linked-roles-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/discord-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/discord/refs/heads/main/json-ld/discord-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Discord from Discord.
layout: jsonld
name: Discord Context
namespaces:
- prefix: discord
  uri: https://discord.com/developers/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Guild
  type: ''
- container: ''
  name: Channel
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Message
  type: ''
- container: ''
  name: Role
  type: ''
- container: ''
  name: Emoji
  type: ''
- container: ''
  name: Webhook
  type: ''
- container: ''
  name: GuildMember
  type: ''
- container: ''
  name: Invite
  type: ''
- container: ''
  name: ApplicationCommand
  type: ''
- container: ''
  name: Sticker
  type: ''
- container: ''
  name: GuildScheduledEvent
  type: ''
property_count: 12
provider_name: Discord
provider_slug: discord
slug: discord-context
source_filename: discord-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"discord\": \"https://discord.com/developers/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Guild\": {\n      \"@id\": \"discord:Guild\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"icon\": \"schema:image\",\n        \"ownerId\": \"discord:ownerId\",\n        \"memberCount\": {\n          \"@id\": \"discord:memberCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"premiumTier\": {\n          \"@id\": \"discord:premiumTier\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"verificationLevel\": {\n          \"@id\": \"discord:verificationLevel\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"preferredLocale\": \"discord:preferredLocale\",\n        \"features\": \"discord:features\"\n      }\n\
  \    },\n\n    \"Channel\": {\n      \"@id\": \"discord:Channel\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"topic\": \"schema:description\",\n        \"type\": {\n          \"@id\": \"discord:channelType\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"position\": {\n          \"@id\": \"discord:position\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"nsfw\": {\n          \"@id\": \"discord:nsfw\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"rateLimitPerUser\": {\n          \"@id\": \"discord:rateLimitPerUser\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"parentId\": \"discord:parentId\"\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"discord:User\",\n      \"@context\": {\n        \"username\": \"schema:name\",\n        \"globalName\": \"schema:alternateName\",\n        \"avatar\": \"schema:image\",\n        \"email\": \"schema:email\",\n        \"bot\": {\n          \"@id\": \"discord:bot\"\
  ,\n          \"@type\": \"xsd:boolean\"\n        },\n        \"verified\": {\n          \"@id\": \"discord:verified\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"locale\": \"discord:locale\",\n        \"premiumType\": {\n          \"@id\": \"discord:premiumType\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Message\": {\n      \"@id\": \"discord:Message\",\n      \"@context\": {\n        \"content\": \"schema:text\",\n        \"author\": {\n          \"@id\": \"schema:author\",\n          \"@type\": \"@id\"\n        },\n        \"timestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"editedTimestamp\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"pinned\": {\n          \"@id\": \"discord:pinned\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"tts\": {\n          \"@id\": \"discord:tts\",\n          \"\
  @type\": \"xsd:boolean\"\n        },\n        \"mentionEveryone\": {\n          \"@id\": \"discord:mentionEveryone\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Role\": {\n      \"@id\": \"discord:Role\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"color\": {\n          \"@id\": \"discord:color\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"position\": {\n          \"@id\": \"discord:position\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"permissions\": \"discord:permissions\",\n        \"hoist\": {\n          \"@id\": \"discord:hoist\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"managed\": {\n          \"@id\": \"discord:managed\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"mentionable\": {\n          \"@id\": \"discord:mentionable\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Emoji\": {\n      \"@id\": \"discord:Emoji\",\n   \
  \   \"@context\": {\n        \"name\": \"schema:name\",\n        \"animated\": {\n          \"@id\": \"discord:animated\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"available\": {\n          \"@id\": \"discord:available\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"managed\": {\n          \"@id\": \"discord:managed\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Webhook\": {\n      \"@id\": \"discord:Webhook\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"avatar\": \"schema:image\",\n        \"type\": {\n          \"@id\": \"discord:webhookType\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"token\": \"discord:token\"\n      }\n    },\n\n    \"GuildMember\": {\n      \"@id\": \"discord:GuildMember\",\n      \"@context\": {\n        \"nick\": \"schema:alternateName\",\n        \"joinedAt\"\
  : {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"premiumSince\": {\n          \"@id\": \"discord:premiumSince\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"deaf\": {\n          \"@id\": \"discord:deaf\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"mute\": {\n          \"@id\": \"discord:mute\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"pending\": {\n          \"@id\": \"discord:pending\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Invite\": {\n      \"@id\": \"discord:Invite\",\n      \"@context\": {\n        \"code\": \"discord:inviteCode\",\n        \"maxAge\": {\n          \"@id\": \"discord:maxAge\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"maxUses\": {\n          \"@id\": \"discord:maxUses\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"uses\": {\n          \"@id\": \"discord:uses\",\n          \"@type\"\
  : \"xsd:integer\"\n        },\n        \"temporary\": {\n          \"@id\": \"discord:temporary\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"expiresAt\": {\n          \"@id\": \"schema:expires\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ApplicationCommand\": {\n      \"@id\": \"discord:ApplicationCommand\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"type\": {\n          \"@id\": \"discord:commandType\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"nsfw\": {\n          \"@id\": \"discord:nsfw\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Sticker\": {\n      \"@id\": \"discord:Sticker\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n\
  \        \"type\": {\n          \"@id\": \"discord:stickerType\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"formatType\": {\n          \"@id\": \"discord:formatType\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"available\": {\n          \"@id\": \"discord:available\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"GuildScheduledEvent\": {\n      \"@id\": \"discord:GuildScheduledEvent\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"scheduledStartTime\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"scheduledEndTime\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"status\": {\n          \"@id\": \"discord:eventStatus\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"entityType\": {\n          \"@id\": \"discord:entityType\"\
  ,\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/discord/refs/heads/main/json-ld/discord-context.jsonld
tags:
- Chat
- Communication
- Gaming
- Messaging
- Social
- Video
- Voice
- JSON-LD
- Linked Data
- Semantic Web
---
