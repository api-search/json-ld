---
api_specs:
- filename: at-and-t-sms-api.yaml
  format: yaml
  label: AT&T SMS API
  slug: att-sms-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/at-and-t/refs/heads/main/openapi/at-and-t-sms-api.yaml
- filename: at-and-t-in-app-messaging-api.yaml
  format: yaml
  label: AT&T In-App Messaging API
  slug: att-in-app-messaging-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/at-and-t/refs/heads/main/openapi/at-and-t-in-app-messaging-api.yaml
- filename: at-and-t-mvnx-api.yaml
  format: yaml
  label: AT&T MVNX API
  slug: att-mvnx-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/at-and-t/refs/heads/main/openapi/at-and-t-mvnx-api.yaml
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
source_filename: at-and-t-in-app-messaging-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://att.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"SendMessageRequest\": \"pan:SendMessageRequest\",\n    \"SendMessageResponse\": \"pan:SendMessageResponse\",\n    \"MessageSummary\": \"pan:MessageSummary\",\n    \"MessageDetail\": \"pan:MessageDetail\",\n    \"MessageListResponse\": \"pan:MessageListResponse\",\n    \"UpdateMessageRequest\": \"pan:UpdateMessageRequest\",\n    \"UpdateMessageResponse\": \"pan:UpdateMessageResponse\",\n    \"MessageIndexResponse\": \"pan:MessageIndexResponse\",\n    \"DeltaResponse\": \"pan:DeltaResponse\",\n    \"messageRequest\": {\n      \"@id\": \"pan:messageRequest\",\n      \"@type\": \"@id\"\n    },\n    \"addresses\": {\n      \"@id\": \"pan:addresses\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"text\": {\n  \
  \    \"@id\": \"pan:text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subject\": {\n      \"@id\": \"pan:subject\",\n      \"@type\": \"xsd:string\"\n    },\n    \"group\": {\n      \"@id\": \"pan:group\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"id\": {\n      \"@id\": \"pan:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceURL\": {\n      \"@id\": \"pan:resourceURL\",\n      \"@type\": \"@id\"\n    },\n    \"messageId\": {\n      \"@id\": \"pan:messageId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"from\": {\n      \"@id\": \"pan:from\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recipients\": {\n      \"@id\": \"pan:recipients\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isUnread\": {\n      \"@id\": \"pan:isUnread\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isIncoming\": {\n      \"@id\": \"pan:isIncoming\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"type\": {\n      \"@id\": \"pan:type\",\n \
  \     \"@type\": \"xsd:string\"\n    },\n    \"typeCode\": {\n      \"@id\": \"pan:typeCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeStamp\": {\n      \"@id\": \"pan:timeStamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"message\": {\n      \"@id\": \"pan:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"messageResultSet\": {\n      \"@id\": \"pan:messageResultSet\",\n      \"@type\": \"@id\"\n    },\n    \"messages\": {\n      \"@id\": \"pan:messages\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"totalCount\": {\n      \"@id\": \"pan:totalCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"offset\": {\n      \"@id\": \"pan:offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"limit\": {\n      \"@id\": \"pan:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"messageIndexInfo\": {\n      \"@id\": \"pan:messageIndexInfo\",\n      \"@type\": \"@id\"\n    },\n    \"state\": {\n      \"@id\": \"pan:state\",\n  \
  \    \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deltaResponse\": {\n      \"@id\": \"pan:deltaResponse\",\n      \"@type\": \"@id\"\n    },\n    \"addedMessages\": {\n      \"@id\": \"pan:addedMessages\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"updatedMessages\": {\n      \"@id\": \"pan:updatedMessages\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"deletedMessages\": {\n      \"@id\": \"pan:deletedMessages\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/at-and-t/refs/heads/main/json-ld/at-and-t-in-app-messaging-api-context.jsonld
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
