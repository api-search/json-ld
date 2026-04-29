---
class_count: 1
classes:
- NotificationUrl
context_file: json-ld/adyen-management-notification-url-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-notification-url-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Notification Url from Adyen.
layout: jsonld
name: Adyen Management Notification Url Context
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
  name: localUrls
  type: string
- container: set
  name: publicUrls
  type: string
property_count: 2
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-notification-url-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"NotificationUrl\": \"adyen:NotificationUrl\",\n    \"localUrls\": {\n      \"@id\": \"adyen:localUrls\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publicUrls\": {\n      \"@id\": \"adyen:publicUrls\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-notification-url-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
