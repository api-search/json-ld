---
class_count: 2
classes:
- RefundNotPaidOutTransfersRequest
- RefundNotPaidOutTransfersResponse
context_file: json-ld/adyen-funds-refund-not-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-funds-refund-not-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Funds Refund Not from Adyen.
layout: jsonld
name: Adyen Funds Refund Not Context
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
  name: accountCode
  type: string
- container: ''
  name: accountHolderCode
  type: string
- container: set
  name: invalidFields
  type: string
- container: ''
  name: pspReference
  type: string
- container: ''
  name: resultCode
  type: string
property_count: 5
provider_name: Adyen
provider_slug: adyen
slug: adyen-funds-refund-not-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"RefundNotPaidOutTransfersRequest\": \"adyen:RefundNotPaidOutTransfersRequest\",\n    \"RefundNotPaidOutTransfersResponse\": \"adyen:RefundNotPaidOutTransfersResponse\",\n    \"accountCode\": {\n      \"@id\": \"adyen:accountCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountHolderCode\": {\n      \"@id\": \"adyen:accountHolderCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"invalidFields\": {\n      \"@id\": \"adyen:invalidFields\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pspReference\": {\n      \"@id\": \"adyen:pspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resultCode\": {\n      \"@id\": \"adyen:resultCode\",\n      \"@type\": \"xsd:string\"\n    }\n \
  \ }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-funds-refund-not-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
