---
class_count: 3
classes:
- PayoutSettingsRequest
- PayoutSettingsResponse
- PayoutSettings
context_file: json-ld/adyen-management-payout-settings-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-payout-settings-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Payout Settings from Adyen.
layout: jsonld
name: Adyen Management Payout Settings Context
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
  name: enabled
  type: boolean
- container: ''
  name: enabledFromDate
  type: string
- container: ''
  name: transferInstrumentId
  type: string
- container: set
  name: data
  type: string
- container: ''
  name: allowed
  type: boolean
- container: ''
  name: id
  type: string
- container: ''
  name: priority
  type: string
- container: ''
  name: verificationStatus
  type: string
property_count: 8
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-payout-settings-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PayoutSettingsRequest\": \"adyen:PayoutSettingsRequest\",\n    \"PayoutSettingsResponse\": \"adyen:PayoutSettingsResponse\",\n    \"PayoutSettings\": \"adyen:PayoutSettings\",\n    \"enabled\": {\n      \"@id\": \"adyen:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"enabledFromDate\": {\n      \"@id\": \"adyen:enabledFromDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transferInstrumentId\": {\n      \"@id\": \"adyen:transferInstrumentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"adyen:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"allowed\": {\n      \"@id\": \"adyen:allowed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"id\":\
  \ {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"priority\": {\n      \"@id\": \"adyen:priority\",\n      \"@type\": \"xsd:string\"\n    },\n    \"verificationStatus\": {\n      \"@id\": \"adyen:verificationStatus\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-payout-settings-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
