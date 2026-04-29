---
class_count: 1
classes:
- BrandVariantsRestriction
context_file: json-ld/adyen-configuration-brand-variants-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-brand-variants-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Configuration Brand Variants from Adyen.
layout: jsonld
name: Adyen Configuration Brand Variants Context
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
  name: operation
  type: string
- container: set
  name: value
  type: string
property_count: 2
provider_name: Adyen
provider_slug: adyen
slug: adyen-configuration-brand-variants-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"BrandVariantsRestriction\": \"adyen:BrandVariantsRestriction\",\n    \"operation\": {\n      \"@id\": \"adyen:operation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"adyen:value\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-brand-variants-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
