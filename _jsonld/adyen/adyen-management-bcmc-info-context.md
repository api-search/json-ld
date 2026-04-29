---
class_count: 1
classes:
- BcmcInfo
context_file: json-ld/adyen-management-bcmc-info-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-bcmc-info-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Bcmc Info from Adyen.
layout: jsonld
name: Adyen Management Bcmc Info Context
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
  name: enableBcmcMobile
  type: boolean
- container: ''
  name: transactionDescription
  type: string
property_count: 2
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-bcmc-info-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"BcmcInfo\": \"adyen:BcmcInfo\",\n    \"enableBcmcMobile\": {\n      \"@id\": \"adyen:enableBcmcMobile\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"transactionDescription\": {\n      \"@id\": \"adyen:transactionDescription\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-bcmc-info-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
