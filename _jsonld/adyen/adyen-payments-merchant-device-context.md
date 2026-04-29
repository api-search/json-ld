---
class_count: 1
classes:
- MerchantDevice
context_file: json-ld/adyen-payments-merchant-device-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payments-merchant-device-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Payments Merchant Device from Adyen.
layout: jsonld
name: Adyen Payments Merchant Device Context
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
  name: os
  type: string
- container: ''
  name: osVersion
  type: string
- container: ''
  name: reference
  type: string
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-payments-merchant-device-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"MerchantDevice\": \"adyen:MerchantDevice\",\n    \"os\": {\n      \"@id\": \"adyen:os\",\n      \"@type\": \"xsd:string\"\n    },\n    \"osVersion\": {\n      \"@id\": \"adyen:osVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"adyen:reference\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payments-merchant-device-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
