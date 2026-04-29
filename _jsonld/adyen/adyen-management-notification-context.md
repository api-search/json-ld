---
class_count: 1
classes:
- Notification
context_file: json-ld/adyen-management-notification-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-notification-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Notification from Adyen.
layout: jsonld
name: Adyen Management Notification Context
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
  name: category
  type: string
- container: ''
  name: details
  type: string
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: showButton
  type: boolean
- container: ''
  name: title
  type: string
property_count: 5
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-notification-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Notification\": \"adyen:Notification\",\n    \"category\": {\n      \"@id\": \"adyen:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"details\": {\n      \"@id\": \"adyen:details\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"adyen:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"showButton\": {\n      \"@id\": \"adyen:showButton\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"title\": {\n      \"@id\": \"adyen:title\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-notification-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
