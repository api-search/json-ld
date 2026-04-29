---
class_count: 1
classes:
- Localization
context_file: json-ld/adyen-management-localization-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-localization-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Localization from Adyen.
layout: jsonld
name: Adyen Management Localization Context
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
  name: language
  type: string
- container: ''
  name: secondaryLanguage
  type: string
- container: ''
  name: timezone
  type: string
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-localization-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Localization\": \"adyen:Localization\",\n    \"language\": {\n      \"@id\": \"adyen:language\",\n      \"@type\": \"xsd:string\"\n    },\n    \"secondaryLanguage\": {\n      \"@id\": \"adyen:secondaryLanguage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timezone\": {\n      \"@id\": \"adyen:timezone\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-localization-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
