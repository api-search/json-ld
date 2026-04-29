---
class_count: 1
classes:
- TokenDetails
context_file: json-ld/adyen-recurring-token-details-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-recurring-token-details-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Recurring Token Details from Adyen.
layout: jsonld
name: Adyen Recurring Token Details Context
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
  name: tokenData
  type: reference
- container: ''
  name: tokenDataType
  type: string
property_count: 2
provider_name: Adyen
provider_slug: adyen
slug: adyen-recurring-token-details-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"TokenDetails\": \"adyen:TokenDetails\",\n    \"tokenData\": {\n      \"@id\": \"adyen:tokenData\",\n      \"@type\": \"@id\"\n    },\n    \"tokenDataType\": {\n      \"@id\": \"adyen:tokenDataType\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-recurring-token-details-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
