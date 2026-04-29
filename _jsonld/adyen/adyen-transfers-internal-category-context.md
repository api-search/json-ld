---
class_count: 1
classes:
- InternalCategoryData
context_file: json-ld/adyen-transfers-internal-category-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-transfers-internal-category-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Transfers Internal Category from Adyen.
layout: jsonld
name: Adyen Transfers Internal Category Context
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
  name: modificationMerchantReference
  type: string
- container: ''
  name: modificationPspReference
  type: string
- container: ''
  name: type
  type: string
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-transfers-internal-category-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"InternalCategoryData\": \"adyen:InternalCategoryData\",\n    \"modificationMerchantReference\": {\n      \"@id\": \"adyen:modificationMerchantReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modificationPspReference\": {\n      \"@id\": \"adyen:modificationPspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-transfers-internal-category-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
