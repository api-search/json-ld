---
class_count: 8
classes:
- TokenRequest
- TokenResponse
- SendSmsRequest
- SendSmsResponse
- DeliveryInfoResponse
- DeliveryInfo
- InboundSmsResponse
- InboundSmsMessage
context_file: json-ld/at-and-t-sms-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/at-and-t/refs/heads/main/json-ld/at-and-t-sms-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for At And T Sms Api from AT&T.
layout: jsonld
name: At And T Sms Api Context
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
  name: clientId
  type: string
- container: ''
  name: clientSecret
  type: string
- container: ''
  name: grantType
  type: string
- container: ''
  name: scope
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: refreshToken
  type: string
- container: ''
  name: accessToken
  type: string
- container: ''
  name: expiresIn
  type: integer
- container: ''
  name: tokenType
  type: string
- container: ''
  name: outboundSMSRequest
  type: reference
- container: set
  name: address
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: notifyDeliveryStatus
  type: boolean
- container: ''
  name: outboundSMSResponse
  type: reference
- container: ''
  name: messageId
  type: string
- container: ''
  name: resourceReference
  type: reference
- container: ''
  name: resourceURL
  type: reference
- container: ''
  name: deliveryInfoList
  type: reference
- container: set
  name: deliveryInfo
  type: reference
- container: ''
  name: deliveryStatus
  type: string
- container: ''
  name: inboundSMSMessageList
  type: reference
- container: set
  name: inboundSMSMessage
  type: reference
- container: ''
  name: senderAddress
  type: string
- container: ''
  name: destinationAddress
  type: string
- container: ''
  name: dateTime
  type: dateTime
- container: ''
  name: numberOfMessagesInThisBatch
  type: integer
- container: ''
  name: totalNumberOfPendingMessages
  type: integer
property_count: 27
provider_name: AT&T
provider_slug: at-and-t
slug: at-and-t-sms-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://att.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"TokenRequest\": \"pan:TokenRequest\",\n    \"TokenResponse\": \"pan:TokenResponse\",\n    \"SendSmsRequest\": \"pan:SendSmsRequest\",\n    \"SendSmsResponse\": \"pan:SendSmsResponse\",\n    \"DeliveryInfoResponse\": \"pan:DeliveryInfoResponse\",\n    \"DeliveryInfo\": \"pan:DeliveryInfo\",\n    \"InboundSmsResponse\": \"pan:InboundSmsResponse\",\n    \"InboundSmsMessage\": \"pan:InboundSmsMessage\",\n    \"clientId\": {\n      \"@id\": \"pan:client_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientSecret\": {\n      \"@id\": \"pan:client_secret\",\n      \"@type\": \"xsd:string\"\n    },\n    \"grantType\": {\n      \"@id\": \"pan:grant_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scope\": {\n      \"@id\": \"pan:scope\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"pan:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"refreshToken\": {\n      \"@id\": \"pan:refresh_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accessToken\": {\n      \"@id\": \"pan:access_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiresIn\": {\n      \"@id\": \"pan:expires_in\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"tokenType\": {\n      \"@id\": \"pan:token_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outboundSMSRequest\": {\n      \"@id\": \"pan:outboundSMSRequest\",\n      \"@type\": \"@id\"\n    },\n    \"address\": {\n      \"@id\": \"pan:address\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"pan:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notifyDeliveryStatus\": {\n      \"@id\": \"pan:notifyDeliveryStatus\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"outboundSMSResponse\"\
  : {\n      \"@id\": \"pan:outboundSMSResponse\",\n      \"@type\": \"@id\"\n    },\n    \"messageId\": {\n      \"@id\": \"pan:messageId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceReference\": {\n      \"@id\": \"pan:resourceReference\",\n      \"@type\": \"@id\"\n    },\n    \"resourceURL\": {\n      \"@id\": \"pan:resourceURL\",\n      \"@type\": \"@id\"\n    },\n    \"deliveryInfoList\": {\n      \"@id\": \"pan:deliveryInfoList\",\n      \"@type\": \"@id\"\n    },\n    \"deliveryInfo\": {\n      \"@id\": \"pan:deliveryInfo\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"deliveryStatus\": {\n      \"@id\": \"pan:deliveryStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inboundSMSMessageList\": {\n      \"@id\": \"pan:inboundSMSMessageList\",\n      \"@type\": \"@id\"\n    },\n    \"inboundSMSMessage\": {\n      \"@id\": \"pan:inboundSMSMessage\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"senderAddress\"\
  : {\n      \"@id\": \"pan:senderAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destinationAddress\": {\n      \"@id\": \"pan:destinationAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateTime\": {\n      \"@id\": \"pan:dateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"numberOfMessagesInThisBatch\": {\n      \"@id\": \"pan:numberOfMessagesInThisBatch\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalNumberOfPendingMessages\": {\n      \"@id\": \"pan:totalNumberOfPendingMessages\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/at-and-t/refs/heads/main/json-ld/at-and-t-sms-api-context.jsonld
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
