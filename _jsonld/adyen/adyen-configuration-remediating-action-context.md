---
class_count: 1
classes:
- RemediatingAction
context_file: json-ld/adyen-configuration-remediating-action-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-remediating-action-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Configuration Remediating Action from Adyen.
layout: jsonld
name: Adyen Configuration Remediating Action Context
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
  name: code
  type: string
- container: ''
  name: message
  type: string
property_count: 2
provider_name: Adyen
provider_slug: adyen
slug: adyen-configuration-remediating-action-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"RemediatingAction\": \"adyen:RemediatingAction\",\n    \"code\": {\n      \"@id\": \"adyen:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"adyen:message\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-remediating-action-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
