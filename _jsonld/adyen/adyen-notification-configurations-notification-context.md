---
class_count: 3
classes:
- NotificationConfigurationDetails
- NotificationEventConfiguration
- description
context_file: json-ld/adyen-notification-configurations-notification-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-notification-configurations-notification-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Notification Configurations Notification from Adyen.
layout: jsonld
name: Adyen Notification Configurations Notification Context
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
  name: active
  type: boolean
- container: ''
  name: apiVersion
  type: integer
- container: set
  name: eventConfigs
  type: string
- container: ''
  name: hmacSignatureKey
  type: string
- container: ''
  name: notificationId
  type: integer
- container: ''
  name: notifyPassword
  type: string
- container: ''
  name: notifyURL
  type: string
- container: ''
  name: notifyUsername
  type: string
- container: ''
  name: sslProtocol
  type: string
- container: ''
  name: eventType
  type: string
- container: ''
  name: includeMode
  type: string
property_count: 11
provider_name: Adyen
provider_slug: adyen
slug: adyen-notification-configurations-notification-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"NotificationConfigurationDetails\": \"adyen:NotificationConfigurationDetails\",\n    \"NotificationEventConfiguration\": \"adyen:NotificationEventConfiguration\",\n    \"active\": {\n      \"@id\": \"adyen:active\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"apiVersion\": {\n      \"@id\": \"adyen:apiVersion\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"description\": \"schema:description\",\n    \"eventConfigs\": {\n      \"@id\": \"adyen:eventConfigs\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hmacSignatureKey\": {\n      \"@id\": \"adyen:hmacSignatureKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notificationId\": {\n      \"@id\": \"adyen:notificationId\",\n      \"@type\"\
  : \"xsd:integer\"\n    },\n    \"notifyPassword\": {\n      \"@id\": \"adyen:notifyPassword\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notifyURL\": {\n      \"@id\": \"adyen:notifyURL\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notifyUsername\": {\n      \"@id\": \"adyen:notifyUsername\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sslProtocol\": {\n      \"@id\": \"adyen:sslProtocol\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventType\": {\n      \"@id\": \"adyen:eventType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"includeMode\": {\n      \"@id\": \"adyen:includeMode\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-notification-configurations-notification-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
