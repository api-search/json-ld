---
class_count: 8
classes:
- Amount
- BalancePlatformNotificationResponse
- ResourceReference
- Resource
- TransactionNotificationRequestV4
- Transaction
- TransferData
- description
context_file: json-ld/adyen-transaction-webhooks-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-transaction-webhooks-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Transaction Webhooks from Adyen.
layout: jsonld
name: Adyen Transaction Webhooks Context
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
  name: notificationResponse
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: reference
  type: string
- container: ''
  name: balancePlatform
  type: string
- container: ''
  name: creationDate
  type: dateTime
- container: ''
  name: data
  type: string
- container: ''
  name: environment
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: accountHolder
  type: string
- container: ''
  name: amount
  type: string
- container: ''
  name: balanceAccount
  type: string
- container: ''
  name: bookingDate
  type: dateTime
- container: ''
  name: status
  type: string
- container: ''
  name: transfer
  type: string
- container: ''
  name: valueDate
  type: dateTime
property_count: 17
provider_name: Adyen
provider_slug: adyen
slug: adyen-transaction-webhooks-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Amount\": \"adyen:Amount\",\n    \"BalancePlatformNotificationResponse\": \"adyen:BalancePlatformNotificationResponse\",\n    \"ResourceReference\": \"adyen:ResourceReference\",\n    \"Resource\": \"adyen:Resource\",\n    \"TransactionNotificationRequestV4\": \"adyen:TransactionNotificationRequestV4\",\n    \"Transaction\": \"adyen:Transaction\",\n    \"TransferData\": \"adyen:TransferData\",\n    \"currency\": {\n      \"@id\": \"adyen:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"adyen:value\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"notificationResponse\": {\n      \"@id\": \"adyen:notificationResponse\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\"\
  ,\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"adyen:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"balancePlatform\": {\n      \"@id\": \"adyen:balancePlatform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationDate\": {\n      \"@id\": \"adyen:creationDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"data\": {\n      \"@id\": \"adyen:data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"environment\": {\n      \"@id\": \"adyen:environment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountHolder\": {\n      \"@id\": \"adyen:accountHolder\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"adyen:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"balanceAccount\": {\n      \"@id\": \"adyen:balanceAccount\",\n      \"@type\": \"xsd:string\"\n  \
  \  },\n    \"bookingDate\": {\n      \"@id\": \"adyen:bookingDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transfer\": {\n      \"@id\": \"adyen:transfer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"valueDate\": {\n      \"@id\": \"adyen:valueDate\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-transaction-webhooks-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
