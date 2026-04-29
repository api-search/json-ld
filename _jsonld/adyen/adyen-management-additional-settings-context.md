---
class_count: 2
classes:
- AdditionalSettingsResponse
- AdditionalSettings
context_file: json-ld/adyen-management-additional-settings-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-additional-settings-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Additional Settings from Adyen.
layout: jsonld
name: Adyen Management Additional Settings Context
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
  name: excludeEventCodes
  type: string
- container: set
  name: includeEventCodes
  type: string
- container: ''
  name: properties
  type: reference
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-additional-settings-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AdditionalSettingsResponse\": \"adyen:AdditionalSettingsResponse\",\n    \"AdditionalSettings\": \"adyen:AdditionalSettings\",\n    \"excludeEventCodes\": {\n      \"@id\": \"adyen:excludeEventCodes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"includeEventCodes\": {\n      \"@id\": \"adyen:includeEventCodes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"properties\": {\n      \"@id\": \"adyen:properties\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-additional-settings-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
