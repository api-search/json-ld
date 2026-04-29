---
class_count: 1
classes:
- UpdatePayoutScheduleRequest
context_file: json-ld/adyen-accounts-update-payout-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-update-payout-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Accounts Update Payout from Adyen.
layout: jsonld
name: Adyen Accounts Update Payout Context
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
  name: action
  type: string
- container: ''
  name: reason
  type: string
- container: ''
  name: schedule
  type: string
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-accounts-update-payout-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"UpdatePayoutScheduleRequest\": \"adyen:UpdatePayoutScheduleRequest\",\n    \"action\": {\n      \"@id\": \"adyen:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reason\": {\n      \"@id\": \"adyen:reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"schedule\": {\n      \"@id\": \"adyen:schedule\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-update-payout-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
