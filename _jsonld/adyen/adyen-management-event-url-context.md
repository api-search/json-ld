---
class_count: 1
classes:
- EventUrl
context_file: json-ld/adyen-management-event-url-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-event-url-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Event Url from Adyen.
layout: jsonld
name: Adyen Management Event Url Context
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
  name: eventLocalUrls
  type: string
- container: set
  name: eventPublicUrls
  type: string
property_count: 2
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-event-url-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"EventUrl\": \"adyen:EventUrl\",\n    \"eventLocalUrls\": {\n      \"@id\": \"adyen:eventLocalUrls\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventPublicUrls\": {\n      \"@id\": \"adyen:eventPublicUrls\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-event-url-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
