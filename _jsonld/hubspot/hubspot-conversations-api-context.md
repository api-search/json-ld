---
class_count: 17
classes:
- Inbox
- InboxCollection
- Thread
- ThreadCollection
- Message
- MessageStatus
- MessageCollection
- Actor
- ActorCollection
- Attachment
- Channel
- ChannelCollection
- SendMessageRequest
- MessageRecipient
- UpdateThreadRequest
- Paging
- PagingNext
context_file: json-ld/hubspot-conversations-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-conversations-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Conversations Api from HubSpot.
layout: jsonld
name: Hubspot Conversations Api Context
namespaces:
- prefix: hubspot
  uri: https://developers.hubspot.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: name
  type: ''
- container: ''
  name: type
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: archived
  type: boolean
- container: set
  name: results
  type: reference
- container: ''
  name: total
  type: integer
- container: ''
  name: paging
  type: reference
- container: ''
  name: inboxId
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: spam
  type: boolean
- container: ''
  name: associatedContactId
  type: string
- container: ''
  name: assignedTo
  type: string
- container: ''
  name: originalChannelId
  type: string
- container: ''
  name: originalChannelAccountId
  type: string
- container: ''
  name: latestMessageTimestamp
  type: dateTime
- container: ''
  name: latestMessageSentTimestamp
  type: dateTime
- container: ''
  name: latestMessageReceivedTimestamp
  type: dateTime
- container: ''
  name: closedAt
  type: dateTime
- container: ''
  name: text
  type: string
- container: ''
  name: richText
  type: string
- container: ''
  name: direction
  type: string
- container: ''
  name: channelId
  type: string
- container: ''
  name: channelAccountId
  type: string
- container: set
  name: senders
  type: reference
- container: set
  name: recipients
  type: reference
- container: ''
  name: truncationStatus
  type: string
- container: set
  name: attachments
  type: reference
- container: ''
  name: statusType
  type: string
- container: ''
  name: actorId
  type: string
- container: ''
  name: email
  type: ''
- container: ''
  name: url
  type: ''
- container: ''
  name: filename
  type: string
- container: ''
  name: size
  type: integer
- container: ''
  name: accountId
  type: string
- container: ''
  name: senderActorId
  type: string
- container: ''
  name: next
  type: reference
- container: ''
  name: after
  type: string
- container: ''
  name: link
  type: string
property_count: 40
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-conversations-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"hubspot\": \"https://developers.hubspot.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Inbox\": \"hubspot:Inbox\",\n    \"id\": {\n      \"@id\": \"hubspot:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"type\": {\n      \"@id\": \"hubspot:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"hubspot:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"hubspot:updatedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"archived\": {\n      \"@id\": \"hubspot:archived\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"InboxCollection\": \"hubspot:InboxCollection\",\n    \"results\": {\n      \"@id\": \"hubspot:results\",\n      \"@container\": \"@set\",\n      \"@type\"\
  : \"@id\"\n    },\n    \"total\": {\n      \"@id\": \"hubspot:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"paging\": {\n      \"@id\": \"hubspot:paging\",\n      \"@type\": \"@id\"\n    },\n    \"Thread\": \"hubspot:Thread\",\n    \"inboxId\": {\n      \"@id\": \"hubspot:inboxId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"hubspot:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"spam\": {\n      \"@id\": \"hubspot:spam\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"associatedContactId\": {\n      \"@id\": \"hubspot:associatedContactId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assignedTo\": {\n      \"@id\": \"hubspot:assignedTo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"originalChannelId\": {\n      \"@id\": \"hubspot:originalChannelId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"originalChannelAccountId\": {\n      \"@id\": \"hubspot:originalChannelAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"latestMessageTimestamp\": {\n      \"@id\": \"hubspot:latestMessageTimestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"latestMessageSentTimestamp\": {\n      \"@id\": \"hubspot:latestMessageSentTimestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"latestMessageReceivedTimestamp\": {\n      \"@id\": \"hubspot:latestMessageReceivedTimestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"closedAt\": {\n      \"@id\": \"hubspot:closedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"ThreadCollection\": \"hubspot:ThreadCollection\",\n    \"Message\": \"hubspot:Message\",\n    \"text\": {\n      \"@id\": \"hubspot:text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"richText\": {\n      \"@id\": \"hubspot:richText\",\n      \"@type\": \"xsd:string\"\n    },\n    \"direction\": {\n      \"@id\": \"hubspot:direction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"channelId\": {\n      \"@id\": \"hubspot:channelId\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"channelAccountId\": {\n      \"@id\": \"hubspot:channelAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"senders\": {\n      \"@id\": \"hubspot:senders\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"recipients\": {\n      \"@id\": \"hubspot:recipients\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"truncationStatus\": {\n      \"@id\": \"hubspot:truncationStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attachments\": {\n      \"@id\": \"hubspot:attachments\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"MessageStatus\": \"hubspot:MessageStatus\",\n    \"statusType\": {\n      \"@id\": \"hubspot:statusType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MessageCollection\": \"hubspot:MessageCollection\",\n    \"Actor\": \"hubspot:Actor\",\n    \"actorId\": {\n      \"@id\": \"hubspot:actorId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": {\n      \"\
  @id\": \"schema:email\"\n    },\n    \"ActorCollection\": \"hubspot:ActorCollection\",\n    \"Attachment\": \"hubspot:Attachment\",\n    \"url\": {\n      \"@id\": \"schema:url\"\n    },\n    \"filename\": {\n      \"@id\": \"hubspot:filename\",\n      \"@type\": \"xsd:string\"\n    },\n    \"size\": {\n      \"@id\": \"hubspot:size\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Channel\": \"hubspot:Channel\",\n    \"accountId\": {\n      \"@id\": \"hubspot:accountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ChannelCollection\": \"hubspot:ChannelCollection\",\n    \"SendMessageRequest\": \"hubspot:SendMessageRequest\",\n    \"senderActorId\": {\n      \"@id\": \"hubspot:senderActorId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MessageRecipient\": \"hubspot:MessageRecipient\",\n    \"UpdateThreadRequest\": \"hubspot:UpdateThreadRequest\",\n    \"Paging\": \"hubspot:Paging\",\n    \"next\": {\n      \"@id\": \"hubspot:next\",\n      \"@type\": \"@id\"\n    },\n    \"\
  PagingNext\": \"hubspot:PagingNext\",\n    \"after\": {\n      \"@id\": \"hubspot:after\",\n      \"@type\": \"xsd:string\"\n    },\n    \"link\": {\n      \"@id\": \"hubspot:link\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-conversations-api-context.jsonld
tags:
- Analytics
- Commerce
- Content
- CRM
- Customer Service
- Email Marketing
- Marketing
- Marketing Automation
- Operations
- Sales
- JSON-LD
- Linked Data
- Semantic Web
---
