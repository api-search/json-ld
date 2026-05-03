---
api_specs:
- filename: telegram-bot-openapi.yml
  format: yaml
  label: Telegram Bot API
  slug: telegram-bot-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telegram/refs/heads/main/openapi/telegram-bot-openapi.yml
class_count: 12
classes:
- Message
- Update
- User
- Chat
- Bot
- ChatMember
- BotCommand
- InlineQuery
- CallbackQuery
- Poll
- Invoice
- StickerSet
context_file: json-ld/telegram-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/telegram/refs/heads/main/json-ld/telegram-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Telegram from Telegram.
layout: jsonld
name: Telegram Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: telegram
  uri: https://core.telegram.org/schema/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: message_id
  type: integer
- container: ''
  name: update_id
  type: integer
- container: ''
  name: chat_id
  type: integer
- container: ''
  name: user_id
  type: integer
- container: ''
  name: from
  type: reference
- container: ''
  name: chat
  type: reference
- container: ''
  name: date
  type: integer
- container: ''
  name: text
  type: string
- container: ''
  name: caption
  type: string
- container: ''
  name: first_name
  type: string
- container: ''
  name: last_name
  type: string
- container: ''
  name: username
  type: string
- container: ''
  name: is_bot
  type: boolean
- container: ''
  name: language_code
  type: string
- container: ''
  name: is_premium
  type: boolean
- container: ''
  name: title
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: invite_link
  type: string
- container: ''
  name: is_anonymous
  type: boolean
- container: ''
  name: command
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: member_count
  type: integer
- container: ''
  name: currency
  type: string
- container: ''
  name: total_amount
  type: integer
- container: ''
  name: file_id
  type: string
- container: ''
  name: file_path
  type: string
- container: ''
  name: file_size
  type: integer
- container: ''
  name: type
  type: string
- container: ''
  name: question
  type: string
- container: ''
  name: options
  type: reference
- container: ''
  name: total_voter_count
  type: integer
property_count: 31
provider_name: Telegram
provider_slug: telegram
slug: telegram-context
source_filename: telegram-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"telegram\": \"https://core.telegram.org/schema/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Message\": \"telegram:Message\",\n    \"Update\": \"telegram:Update\",\n    \"User\": \"telegram:User\",\n    \"Chat\": \"telegram:Chat\",\n    \"Bot\": \"telegram:Bot\",\n    \"ChatMember\": \"telegram:ChatMember\",\n    \"BotCommand\": \"telegram:BotCommand\",\n    \"InlineQuery\": \"telegram:InlineQuery\",\n    \"CallbackQuery\": \"telegram:CallbackQuery\",\n    \"Poll\": \"telegram:Poll\",\n    \"Invoice\": \"telegram:Invoice\",\n    \"StickerSet\": \"telegram:StickerSet\",\n\n    \"message_id\": {\n      \"@id\": \"telegram:messageId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"update_id\": {\n      \"@id\": \"telegram:updateId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"chat_id\": {\n      \"@id\": \"telegram:chatId\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"user_id\": {\n      \"@id\": \"telegram:userId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"from\": {\n      \"@id\": \"telegram:from\",\n      \"@type\": \"@id\"\n    },\n    \"chat\": {\n      \"@id\": \"telegram:chat\",\n      \"@type\": \"@id\"\n    },\n    \"date\": {\n      \"@id\": \"telegram:date\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"text\": {\n      \"@id\": \"telegram:text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"caption\": {\n      \"@id\": \"telegram:caption\",\n      \"@type\": \"xsd:string\"\n    },\n    \"first_name\": {\n      \"@id\": \"schema:givenName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"last_name\": {\n      \"@id\": \"schema:familyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"username\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"is_bot\": {\n      \"@id\": \"telegram:isBot\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"language_code\": {\n    \
  \  \"@id\": \"schema:inLanguage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"is_premium\": {\n      \"@id\": \"telegram:isPremium\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"title\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"invite_link\": {\n      \"@id\": \"telegram:inviteLink\",\n      \"@type\": \"xsd:string\"\n    },\n    \"is_anonymous\": {\n      \"@id\": \"telegram:isAnonymous\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"command\": {\n      \"@id\": \"telegram:command\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"telegram:memberStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"member_count\": {\n      \"@id\": \"schema:numberOfMembers\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"currency\": {\n      \"@id\": \"schema:currency\",\n      \"@type\": \"xsd:string\"\n \
  \   },\n    \"total_amount\": {\n      \"@id\": \"schema:totalPrice\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"file_id\": {\n      \"@id\": \"telegram:fileId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"file_path\": {\n      \"@id\": \"telegram:filePath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"file_size\": {\n      \"@id\": \"telegram:fileSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"type\": {\n      \"@id\": \"telegram:chatType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"question\": {\n      \"@id\": \"schema:question\",\n      \"@type\": \"xsd:string\"\n    },\n    \"options\": {\n      \"@id\": \"telegram:pollOptions\",\n      \"@type\": \"@id\"\n    },\n    \"total_voter_count\": {\n      \"@id\": \"telegram:totalVoterCount\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/telegram/refs/heads/main/json-ld/telegram-context.jsonld
tags:
- Bots
- Chat
- Messaging
- Notifications
- Payments
- Telegram
- JSON-LD
- Linked Data
- Semantic Web
---
