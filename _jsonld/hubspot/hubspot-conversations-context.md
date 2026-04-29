---
class_count: 0
classes: []
context_file: json-ld/hubspot-conversations-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-conversations-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Conversations from HubSpot.
layout: jsonld
name: Hubspot Conversations Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: Inbox
  type: ''
- container: ''
  name: InboxCollection
  type: ''
- container: ''
  name: Thread
  type: ''
- container: ''
  name: ThreadCollection
  type: ''
- container: ''
  name: Message
  type: ''
- container: ''
  name: MessageStatus
  type: ''
- container: ''
  name: MessageCollection
  type: ''
- container: ''
  name: Actor
  type: ''
- container: ''
  name: ActorCollection
  type: ''
- container: ''
  name: Attachment
  type: ''
- container: ''
  name: Channel
  type: ''
- container: ''
  name: ChannelCollection
  type: ''
- container: ''
  name: SendMessageRequest
  type: ''
- container: ''
  name: MessageRecipient
  type: ''
- container: ''
  name: UpdateThreadRequest
  type: ''
- container: ''
  name: Paging
  type: ''
- container: ''
  name: PagingNext
  type: ''
- container: ''
  name: ErrorDetail
  type: ''
- container: ''
  name: Error
  type: ''
property_count: 19
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-conversations-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"Inbox\": {\n      \"@id\": \"ns:Inbox\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"ns:type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"ns:createdAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"ns:updatedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"archived\": {\n          \"@id\": \"ns:archived\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n    \"InboxCollection\": {\n      \"@id\": \"ns:InboxCollection\",\n      \"@context\": {\n        \"results\": \"ns:results\"\
  ,\n        \"total\": {\n          \"@id\": \"ns:total\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"paging\": {\n          \"@id\": \"ns:paging\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Thread\": {\n      \"@id\": \"ns:Thread\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"inboxId\": {\n          \"@id\": \"ns:inboxId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"spam\": {\n          \"@id\": \"ns:spam\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"associatedContactId\": {\n          \"@id\": \"ns:associatedContactId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"assignedTo\": {\n          \"@id\": \"ns:assignedTo\",\n          \"@type\": \"xsd:string\"\n        },\n        \"originalChannelId\"\
  : {\n          \"@id\": \"ns:originalChannelId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"originalChannelAccountId\": {\n          \"@id\": \"ns:originalChannelAccountId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"latestMessageTimestamp\": {\n          \"@id\": \"ns:latestMessageTimestamp\",\n          \"@type\": \"xsd:string\"\n        },\n        \"latestMessageSentTimestamp\": {\n          \"@id\": \"ns:latestMessageSentTimestamp\",\n          \"@type\": \"xsd:string\"\n        },\n        \"latestMessageReceivedTimestamp\": {\n          \"@id\": \"ns:latestMessageReceivedTimestamp\",\n          \"@type\": \"xsd:string\"\n        },\n        \"closedAt\": {\n          \"@id\": \"ns:closedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"ns:createdAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"archived\": {\n          \"@id\": \"ns:archived\",\n          \"@type\": \"xsd:boolean\"\
  \n        }\n      }\n    },\n    \"ThreadCollection\": {\n      \"@id\": \"ns:ThreadCollection\",\n      \"@context\": {\n        \"results\": \"ns:results\",\n        \"paging\": {\n          \"@id\": \"ns:paging\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Message\": {\n      \"@id\": \"ns:Message\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"ns:type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"text\": {\n          \"@id\": \"ns:text\",\n          \"@type\": \"xsd:string\"\n        },\n        \"richText\": {\n          \"@id\": \"ns:richText\",\n          \"@type\": \"xsd:string\"\n        },\n        \"direction\": {\n          \"@id\": \"ns:direction\",\n          \"@type\": \"xsd:string\"\n        },\n        \"channelId\": {\n          \"@id\": \"ns:channelId\",\n          \"@type\": \"xsd:string\"\n        },\n\
  \        \"channelAccountId\": {\n          \"@id\": \"ns:channelAccountId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"senders\": \"ns:senders\",\n        \"recipients\": \"ns:recipients\",\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"ns:createdAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"truncationStatus\": {\n          \"@id\": \"ns:truncationStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"attachments\": \"ns:attachments\"\n      }\n    },\n    \"MessageStatus\": {\n      \"@id\": \"ns:MessageStatus\",\n      \"@context\": {\n        \"statusType\": {\n          \"@id\": \"ns:statusType\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"MessageCollection\": {\n      \"@id\": \"ns:MessageCollection\",\n      \"@context\": {\n        \"results\": \"ns:results\",\n        \"paging\": {\n      \
  \    \"@id\": \"ns:paging\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Actor\": {\n      \"@id\": \"ns:Actor\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"actorId\": {\n          \"@id\": \"ns:actorId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"email\": {\n          \"@id\": \"ns:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"ns:type\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ActorCollection\": {\n      \"@id\": \"ns:ActorCollection\",\n      \"@context\": {\n        \"results\": \"ns:results\",\n        \"paging\": {\n          \"@id\": \"ns:paging\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Attachment\": {\n      \"@id\": \"ns:Attachment\"\
  ,\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"ns:type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"url\": {\n          \"@id\": \"ns:url\",\n          \"@type\": \"xsd:string\"\n        },\n        \"filename\": {\n          \"@id\": \"ns:filename\",\n          \"@type\": \"xsd:string\"\n        },\n        \"size\": {\n          \"@id\": \"ns:size\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n    \"Channel\": {\n      \"@id\": \"ns:Channel\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"ns:type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"accountId\": {\n          \"@id\": \"ns:accountId\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"ns:createdAt\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ChannelCollection\": {\n      \"@id\": \"ns:ChannelCollection\",\n      \"@context\": {\n        \"results\": \"ns:results\",\n        \"paging\": {\n          \"@id\": \"ns:paging\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"SendMessageRequest\": {\n      \"@id\": \"ns:SendMessageRequest\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"ns:type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"text\": {\n          \"@id\": \"ns:text\",\n          \"@type\": \"xsd:string\"\n        },\n        \"richText\": {\n          \"@id\": \"ns:richText\",\n          \"@type\": \"xsd:string\"\n        },\n        \"senderActorId\": {\n          \"@id\": \"ns:senderActorId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"channelId\": {\n \
  \         \"@id\": \"ns:channelId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"channelAccountId\": {\n          \"@id\": \"ns:channelAccountId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"recipients\": \"ns:recipients\"\n      }\n    },\n    \"MessageRecipient\": {\n      \"@id\": \"ns:MessageRecipient\",\n      \"@context\": {\n        \"actorId\": {\n          \"@id\": \"ns:actorId\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"UpdateThreadRequest\": {\n      \"@id\": \"ns:UpdateThreadRequest\",\n      \"@context\": {\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"assignedTo\": {\n          \"@id\": \"ns:assignedTo\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Paging\": {\n      \"@id\": \"ns:Paging\",\n      \"@context\": {\n        \"next\": {\n          \"@id\": \"ns:next\",\n          \"@type\": \"xsd:string\"\n      \
  \  }\n      }\n    },\n    \"PagingNext\": {\n      \"@id\": \"ns:PagingNext\",\n      \"@context\": {\n        \"after\": {\n          \"@id\": \"ns:after\",\n          \"@type\": \"xsd:string\"\n        },\n        \"link\": {\n          \"@id\": \"ns:link\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ErrorDetail\": {\n      \"@id\": \"ns:ErrorDetail\",\n      \"@context\": {\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"code\": {\n          \"@id\": \"ns:code\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subCategory\": {\n          \"@id\": \"ns:subCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"in\": {\n          \"@id\": \"ns:in\",\n          \"@type\": \"xsd:string\"\n        },\n        \"context\": \"ns:context\"\n      }\n    },\n    \"Error\": {\n      \"@id\": \"ns:Error\",\n      \"@context\": {\n        \"category\": {\n          \"\
  @id\": \"ns:category\",\n          \"@type\": \"xsd:string\"\n        },\n        \"correlationId\": {\n          \"@id\": \"ns:correlationId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subCategory\": {\n          \"@id\": \"ns:subCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"context\": \"ns:context\",\n        \"links\": \"ns:links\",\n        \"errors\": \"ns:errors\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-conversations-context.jsonld
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
