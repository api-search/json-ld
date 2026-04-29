---
class_count: 8
classes:
- Amount
- AuthenticationInfo
- AuthenticationNotificationData
- AuthenticationNotificationRequest
- BalancePlatformNotificationResponse
- ChallengeInfo
- PurchaseInfo
- Resource
context_file: json-ld/adyen-authentication-webhooks-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-authentication-webhooks-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Authentication Webhooks from Adyen.
layout: jsonld
name: Adyen Authentication Webhooks Context
namespaces:
- prefix: adyen
  uri: https://docs.adyen.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: currency
  type: string
- container: ''
  name: value
  type: integer
- container: ''
  name: acsTransId
  type: string
- container: ''
  name: challenge
  type: string
- container: ''
  name: challengeIndicator
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: deviceChannel
  type: string
- container: ''
  name: dsTransID
  type: string
- container: ''
  name: exemptionIndicator
  type: string
- container: ''
  name: inPSD2Scope
  type: boolean
- container: ''
  name: messageCategory
  type: string
- container: ''
  name: messageVersion
  type: string
- container: ''
  name: riskScore
  type: integer
- container: ''
  name: threeDSServerTransID
  type: string
- container: ''
  name: transStatus
  type: string
- container: ''
  name: transStatusReason
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: authentication
  type: string
- container: ''
  name: balancePlatform
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: paymentInstrumentId
  type: string
- container: ''
  name: purchase
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: data
  type: string
- container: ''
  name: environment
  type: string
- container: ''
  name: notificationResponse
  type: string
- container: ''
  name: challengeCancel
  type: string
- container: ''
  name: flow
  type: string
- container: ''
  name: lastInteraction
  type: dateTime
- container: ''
  name: phoneNumber
  type: string
- container: ''
  name: resends
  type: integer
- container: ''
  name: retries
  type: integer
- container: ''
  name: date
  type: string
- container: ''
  name: merchantName
  type: string
- container: ''
  name: originalAmount
  type: string
- container: ''
  name: creationDate
  type: dateTime
property_count: 36
provider_name: Adyen
provider_slug: adyen
slug: adyen-authentication-webhooks-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Amount\": \"adyen:Amount\",\n    \"AuthenticationInfo\": \"adyen:AuthenticationInfo\",\n    \"AuthenticationNotificationData\": \"adyen:AuthenticationNotificationData\",\n    \"AuthenticationNotificationRequest\": \"adyen:AuthenticationNotificationRequest\",\n    \"BalancePlatformNotificationResponse\": \"adyen:BalancePlatformNotificationResponse\",\n    \"ChallengeInfo\": \"adyen:ChallengeInfo\",\n    \"PurchaseInfo\": \"adyen:PurchaseInfo\",\n    \"Resource\": \"adyen:Resource\",\n    \"currency\": {\n      \"@id\": \"adyen:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"adyen:value\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"acsTransId\": {\n      \"@id\": \"adyen:acsTransId\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"challenge\": {\n      \"@id\": \"adyen:challenge\",\n      \"@type\": \"xsd:string\"\n    },\n    \"challengeIndicator\": {\n      \"@id\": \"adyen:challengeIndicator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"adyen:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"deviceChannel\": {\n      \"@id\": \"adyen:deviceChannel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dsTransID\": {\n      \"@id\": \"adyen:dsTransID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exemptionIndicator\": {\n      \"@id\": \"adyen:exemptionIndicator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inPSD2Scope\": {\n      \"@id\": \"adyen:inPSD2Scope\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"messageCategory\": {\n      \"@id\": \"adyen:messageCategory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"messageVersion\": {\n      \"@id\": \"adyen:messageVersion\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"riskScore\": {\n      \"@id\": \"adyen:riskScore\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"threeDSServerTransID\": {\n      \"@id\": \"adyen:threeDSServerTransID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transStatus\": {\n      \"@id\": \"adyen:transStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transStatusReason\": {\n      \"@id\": \"adyen:transStatusReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authentication\": {\n      \"@id\": \"adyen:authentication\",\n      \"@type\": \"xsd:string\"\n    },\n    \"balancePlatform\": {\n      \"@id\": \"adyen:balancePlatform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentInstrumentId\": {\n      \"@id\": \"adyen:paymentInstrumentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"purchase\": {\n      \"\
  @id\": \"adyen:purchase\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"adyen:data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"environment\": {\n      \"@id\": \"adyen:environment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notificationResponse\": {\n      \"@id\": \"adyen:notificationResponse\",\n      \"@type\": \"xsd:string\"\n    },\n    \"challengeCancel\": {\n      \"@id\": \"adyen:challengeCancel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flow\": {\n      \"@id\": \"adyen:flow\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastInteraction\": {\n      \"@id\": \"adyen:lastInteraction\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"phoneNumber\": {\n      \"@id\": \"adyen:phoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resends\": {\n      \"@id\": \"adyen:resends\",\n      \"@type\": \"xsd:integer\"\n    },\n   \
  \ \"retries\": {\n      \"@id\": \"adyen:retries\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"date\": {\n      \"@id\": \"adyen:date\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantName\": {\n      \"@id\": \"adyen:merchantName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"originalAmount\": {\n      \"@id\": \"adyen:originalAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationDate\": {\n      \"@id\": \"adyen:creationDate\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-authentication-webhooks-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
