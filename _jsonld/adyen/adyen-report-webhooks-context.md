---
class_count: 6
classes:
- BalancePlatformNotificationResponse
- ReportNotificationData
- ReportNotificationRequest
- ResourceReference
- Resource
- description
context_file: json-ld/adyen-report-webhooks-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-report-webhooks-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Report Webhooks from Adyen.
layout: jsonld
name: Adyen Report Webhooks Context
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
  name: notificationResponse
  type: string
- container: ''
  name: accountHolder
  type: string
- container: ''
  name: balanceAccount
  type: string
- container: ''
  name: balancePlatform
  type: string
- container: ''
  name: creationDate
  type: dateTime
- container: ''
  name: downloadUrl
  type: string
- container: ''
  name: fileName
  type: string
- container: ''
  name: reportType
  type: string
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
  name: id
  type: string
- container: ''
  name: reference
  type: string
property_count: 13
provider_name: Adyen
provider_slug: adyen
slug: adyen-report-webhooks-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"BalancePlatformNotificationResponse\": \"adyen:BalancePlatformNotificationResponse\",\n    \"ReportNotificationData\": \"adyen:ReportNotificationData\",\n    \"ReportNotificationRequest\": \"adyen:ReportNotificationRequest\",\n    \"ResourceReference\": \"adyen:ResourceReference\",\n    \"Resource\": \"adyen:Resource\",\n    \"notificationResponse\": {\n      \"@id\": \"adyen:notificationResponse\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountHolder\": {\n      \"@id\": \"adyen:accountHolder\",\n      \"@type\": \"xsd:string\"\n    },\n    \"balanceAccount\": {\n      \"@id\": \"adyen:balanceAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"balancePlatform\": {\n      \"@id\": \"adyen:balancePlatform\",\n     \
  \ \"@type\": \"xsd:string\"\n    },\n    \"creationDate\": {\n      \"@id\": \"adyen:creationDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"downloadUrl\": {\n      \"@id\": \"adyen:downloadUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fileName\": {\n      \"@id\": \"adyen:fileName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reportType\": {\n      \"@id\": \"adyen:reportType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"adyen:data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"environment\": {\n      \"@id\": \"adyen:environment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"adyen:reference\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-report-webhooks-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
