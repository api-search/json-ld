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
