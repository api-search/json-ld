---
class_count: 1
classes:
- CapabilitySettings
context_file: json-ld/adyen-configuration-capability-settings-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-capability-settings-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Configuration Capability Settings from Adyen.
layout: jsonld
name: Adyen Configuration Capability Settings Context
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
  name: amountPerIndustry
  type: reference
- container: ''
  name: authorizedCardUsers
  type: boolean
- container: set
  name: fundingSource
  type: string
- container: ''
  name: interval
  type: string
- container: ''
  name: maxAmount
  type: string
property_count: 5
provider_name: Adyen
provider_slug: adyen
slug: adyen-configuration-capability-settings-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CapabilitySettings\": \"adyen:CapabilitySettings\",\n    \"amountPerIndustry\": {\n      \"@id\": \"adyen:amountPerIndustry\",\n      \"@type\": \"@id\"\n    },\n    \"authorizedCardUsers\": {\n      \"@id\": \"adyen:authorizedCardUsers\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"fundingSource\": {\n      \"@id\": \"adyen:fundingSource\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"interval\": {\n      \"@id\": \"adyen:interval\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxAmount\": {\n      \"@id\": \"adyen:maxAmount\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-capability-settings-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
