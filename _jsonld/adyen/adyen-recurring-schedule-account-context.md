---
class_count: 2
classes:
- ScheduleAccountUpdaterRequest
- ScheduleAccountUpdaterResult
context_file: json-ld/adyen-recurring-schedule-account-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-recurring-schedule-account-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Recurring Schedule Account from Adyen.
layout: jsonld
name: Adyen Recurring Schedule Account Context
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
  name: additionalData
  type: reference
- container: ''
  name: card
  type: string
- container: ''
  name: merchantAccount
  type: string
- container: ''
  name: reference
  type: string
- container: ''
  name: selectedRecurringDetailReference
  type: string
- container: ''
  name: shopperReference
  type: string
- container: ''
  name: pspReference
  type: string
- container: ''
  name: result
  type: string
property_count: 8
provider_name: Adyen
provider_slug: adyen
slug: adyen-recurring-schedule-account-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ScheduleAccountUpdaterRequest\": \"adyen:ScheduleAccountUpdaterRequest\",\n    \"ScheduleAccountUpdaterResult\": \"adyen:ScheduleAccountUpdaterResult\",\n    \"additionalData\": {\n      \"@id\": \"adyen:additionalData\",\n      \"@type\": \"@id\"\n    },\n    \"card\": {\n      \"@id\": \"adyen:card\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantAccount\": {\n      \"@id\": \"adyen:merchantAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"adyen:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"selectedRecurringDetailReference\": {\n      \"@id\": \"adyen:selectedRecurringDetailReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperReference\": {\n     \
  \ \"@id\": \"adyen:shopperReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pspReference\": {\n      \"@id\": \"adyen:pspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"result\": {\n      \"@id\": \"adyen:result\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-recurring-schedule-account-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
