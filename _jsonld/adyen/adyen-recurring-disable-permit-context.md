---
class_count: 2
classes:
- DisablePermitRequest
- DisablePermitResult
context_file: json-ld/adyen-recurring-disable-permit-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-recurring-disable-permit-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Recurring Disable Permit from Adyen.
layout: jsonld
name: Adyen Recurring Disable Permit Context
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
  name: merchantAccount
  type: string
- container: ''
  name: token
  type: string
- container: ''
  name: pspReference
  type: string
- container: ''
  name: status
  type: string
property_count: 4
provider_name: Adyen
provider_slug: adyen
slug: adyen-recurring-disable-permit-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DisablePermitRequest\": \"adyen:DisablePermitRequest\",\n    \"DisablePermitResult\": \"adyen:DisablePermitResult\",\n    \"merchantAccount\": {\n      \"@id\": \"adyen:merchantAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"token\": {\n      \"@id\": \"adyen:token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pspReference\": {\n      \"@id\": \"adyen:pspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-recurring-disable-permit-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
