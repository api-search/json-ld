---
class_count: 3
classes:
- GetNotificationConfigurationListResponse
- GetNotificationConfigurationRequest
- GetNotificationConfigurationResponse
context_file: json-ld/adyen-notification-configurations-get-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-notification-configurations-get-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Notification Configurations Get from Adyen.
layout: jsonld
name: Adyen Notification Configurations Get Context
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
- container: set
  name: configurations
  type: string
- container: set
  name: invalidFields
  type: string
- container: ''
  name: pspReference
  type: string
- container: ''
  name: resultCode
  type: string
- container: ''
  name: notificationId
  type: integer
- container: ''
  name: configurationDetails
  type: string
property_count: 6
provider_name: Adyen
provider_slug: adyen
slug: adyen-notification-configurations-get-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"GetNotificationConfigurationListResponse\": \"adyen:GetNotificationConfigurationListResponse\",\n    \"GetNotificationConfigurationRequest\": \"adyen:GetNotificationConfigurationRequest\",\n    \"GetNotificationConfigurationResponse\": \"adyen:GetNotificationConfigurationResponse\",\n    \"configurations\": {\n      \"@id\": \"adyen:configurations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"invalidFields\": {\n      \"@id\": \"adyen:invalidFields\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pspReference\": {\n      \"@id\": \"adyen:pspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resultCode\": {\n      \"@id\": \"adyen:resultCode\",\n   \
  \   \"@type\": \"xsd:string\"\n    },\n    \"notificationId\": {\n      \"@id\": \"adyen:notificationId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"configurationDetails\": {\n      \"@id\": \"adyen:configurationDetails\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-notification-configurations-get-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
