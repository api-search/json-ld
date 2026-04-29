---
class_count: 1
classes:
- OfflineProcessing
context_file: json-ld/adyen-management-offline-processing-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-offline-processing-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Offline Processing from Adyen.
layout: jsonld
name: Adyen Management Offline Processing Context
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
  name: chipFloorLimit
  type: integer
- container: set
  name: offlineSwipeLimits
  type: string
property_count: 2
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-offline-processing-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"OfflineProcessing\": \"adyen:OfflineProcessing\",\n    \"chipFloorLimit\": {\n      \"@id\": \"adyen:chipFloorLimit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"offlineSwipeLimits\": {\n      \"@id\": \"adyen:offlineSwipeLimits\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-offline-processing-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
