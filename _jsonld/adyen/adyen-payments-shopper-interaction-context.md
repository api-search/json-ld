---
class_count: 1
classes:
- ShopperInteractionDevice
context_file: json-ld/adyen-payments-shopper-interaction-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payments-shopper-interaction-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Payments Shopper Interaction from Adyen.
layout: jsonld
name: Adyen Payments Shopper Interaction Context
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
  name: locale
  type: string
- container: ''
  name: os
  type: string
- container: ''
  name: osVersion
  type: string
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-payments-shopper-interaction-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ShopperInteractionDevice\": \"adyen:ShopperInteractionDevice\",\n    \"locale\": {\n      \"@id\": \"adyen:locale\",\n      \"@type\": \"xsd:string\"\n    },\n    \"os\": {\n      \"@id\": \"adyen:os\",\n      \"@type\": \"xsd:string\"\n    },\n    \"osVersion\": {\n      \"@id\": \"adyen:osVersion\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payments-shopper-interaction-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
