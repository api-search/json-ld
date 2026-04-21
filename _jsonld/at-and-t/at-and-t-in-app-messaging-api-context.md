---
class_count: 9
classes:
- SendMessageRequest
- SendMessageResponse
- MessageSummary
- MessageDetail
- MessageListResponse
- UpdateMessageRequest
- UpdateMessageResponse
- MessageIndexResponse
- DeltaResponse
context_file: json-ld/at-and-t-in-app-messaging-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/at-and-t/refs/heads/main/json-ld/at-and-t-in-app-messaging-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for At And T In App Messaging Api from AT&T.
layout: jsonld
name: At And T In App Messaging Api Context
namespaces:
- prefix: pan
  uri: https://att.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: messageRequest
  type: reference
- container: set
  name: addresses
  type: string
- container: ''
  name: text
  type: string
- container: ''
  name: subject
  type: string
- container: ''
  name: group
  type: boolean
- container: ''
  name: id
  type: string
- container: ''
  name: resourceURL
  type: reference
- container: ''
  name: messageId
  type: string
- container: ''
  name: from
  type: string
- container: set
  name: recipients
  type: string
- container: ''
  name: isUnread
  type: boolean
- container: ''
  name: isIncoming
  type: boolean
- container: ''
  name: type
  type: string
- container: ''
  name: typeCode
  type: string
- container: ''
  name: timeStamp
  type: dateTime
- container: ''
  name: message
  type: string
- container: ''
  name: messageResultSet
  type: reference
- container: set
  name: messages
  type: reference
- container: ''
  name: totalCount
  type: integer
- container: ''
  name: offset
  type: integer
- container: ''
  name: limit
  type: integer
- container: ''
  name: messageIndexInfo
  type: reference
- container: ''
  name: state
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: deltaResponse
  type: reference
- container: set
  name: addedMessages
  type: reference
- container: set
  name: updatedMessages
  type: reference
- container: set
  name: deletedMessages
  type: string
property_count: 28
provider_name: AT&T
provider_slug: at-and-t
slug: at-and-t-in-app-messaging-api-context
tags:
- Telecommunications
- Wireless
- Wireline
- Messaging
- Speech
- Mobile
- Broadband
- Enterprise
- JSON-LD
- Linked Data
- Semantic Web
---
