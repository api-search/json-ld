---
class_count: 1
classes:
- WebhookLinks
context_file: json-ld/adyen-management-webhook-links-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-webhook-links-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Webhook Links from Adyen.
layout: jsonld
name: Adyen Management Webhook Links Context
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
  name: company
  type: string
- container: ''
  name: generateHmac
  type: string
- container: ''
  name: merchant
  type: string
- container: ''
  name: self
  type: string
- container: ''
  name: testWebhook
  type: string
property_count: 5
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-webhook-links-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"WebhookLinks\": \"adyen:WebhookLinks\",\n    \"company\": {\n      \"@id\": \"adyen:company\",\n      \"@type\": \"xsd:string\"\n    },\n    \"generateHmac\": {\n      \"@id\": \"adyen:generateHmac\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchant\": {\n      \"@id\": \"adyen:merchant\",\n      \"@type\": \"xsd:string\"\n    },\n    \"self\": {\n      \"@id\": \"adyen:self\",\n      \"@type\": \"xsd:string\"\n    },\n    \"testWebhook\": {\n      \"@id\": \"adyen:testWebhook\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-webhook-links-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
