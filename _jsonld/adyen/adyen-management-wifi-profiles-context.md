---
class_count: 1
classes:
- WifiProfiles
context_file: json-ld/adyen-management-wifi-profiles-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-wifi-profiles-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Wifi Profiles from Adyen.
layout: jsonld
name: Adyen Management Wifi Profiles Context
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
  name: profiles
  type: string
- container: ''
  name: settings
  type: string
property_count: 2
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-wifi-profiles-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"WifiProfiles\": \"adyen:WifiProfiles\",\n    \"profiles\": {\n      \"@id\": \"adyen:profiles\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"settings\": {\n      \"@id\": \"adyen:settings\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-wifi-profiles-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
