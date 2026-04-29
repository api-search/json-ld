---
class_count: 1
classes:
- Configuration
context_file: json-ld/adyen-management-configuration-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-configuration-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Configuration from Adyen.
layout: jsonld
name: Adyen Management Configuration Context
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
  name: brand
  type: string
- container: set
  name: country
  type: string
- container: set
  name: currencies
  type: string
- container: set
  name: sources
  type: string
property_count: 4
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-configuration-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Configuration\": \"adyen:Configuration\",\n    \"brand\": {\n      \"@id\": \"adyen:brand\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"adyen:country\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencies\": {\n      \"@id\": \"adyen:currencies\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sources\": {\n      \"@id\": \"adyen:sources\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-configuration-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
