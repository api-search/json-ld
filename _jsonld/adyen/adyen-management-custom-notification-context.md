---
class_count: 1
classes:
- CustomNotification
context_file: json-ld/adyen-management-custom-notification-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-custom-notification-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Custom Notification from Adyen.
layout: jsonld
name: Adyen Management Custom Notification Context
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
  name: amount
  type: string
- container: ''
  name: eventCode
  type: string
- container: ''
  name: eventDate
  type: dateTime
- container: ''
  name: merchantReference
  type: string
- container: ''
  name: paymentMethod
  type: string
- container: ''
  name: reason
  type: string
- container: ''
  name: success
  type: boolean
property_count: 7
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-custom-notification-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CustomNotification\": \"adyen:CustomNotification\",\n    \"amount\": {\n      \"@id\": \"adyen:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventCode\": {\n      \"@id\": \"adyen:eventCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventDate\": {\n      \"@id\": \"adyen:eventDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"merchantReference\": {\n      \"@id\": \"adyen:merchantReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentMethod\": {\n      \"@id\": \"adyen:paymentMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reason\": {\n      \"@id\": \"adyen:reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"success\": {\n      \"@id\": \"adyen:success\",\n      \"@type\": \"\
  xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-custom-notification-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
