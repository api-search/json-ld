---
class_count: 1
classes:
- RiskData
context_file: json-ld/adyen-checkout-risk-data-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-risk-data-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Risk Data from Adyen.
layout: jsonld
name: Adyen Checkout Risk Data Context
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
  name: clientData
  type: string
- container: ''
  name: customFields
  type: reference
- container: ''
  name: fraudOffset
  type: integer
- container: ''
  name: profileReference
  type: string
property_count: 4
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-risk-data-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"RiskData\": \"adyen:RiskData\",\n    \"clientData\": {\n      \"@id\": \"adyen:clientData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customFields\": {\n      \"@id\": \"adyen:customFields\",\n      \"@type\": \"@id\"\n    },\n    \"fraudOffset\": {\n      \"@id\": \"adyen:fraudOffset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"profileReference\": {\n      \"@id\": \"adyen:profileReference\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-risk-data-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
