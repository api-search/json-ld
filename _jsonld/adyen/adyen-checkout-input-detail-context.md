---
class_count: 1
classes:
- InputDetail
context_file: json-ld/adyen-checkout-input-detail-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-input-detail-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Input Detail from Adyen.
layout: jsonld
name: Adyen Checkout Input Detail Context
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
  name: configuration
  type: reference
- container: set
  name: details
  type: string
- container: set
  name: inputDetails
  type: string
- container: ''
  name: itemSearchUrl
  type: string
- container: set
  name: items
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: optional
  type: boolean
- container: ''
  name: type
  type: string
- container: ''
  name: value
  type: string
property_count: 9
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-input-detail-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"InputDetail\": \"adyen:InputDetail\",\n    \"configuration\": {\n      \"@id\": \"adyen:configuration\",\n      \"@type\": \"@id\"\n    },\n    \"details\": {\n      \"@id\": \"adyen:details\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inputDetails\": {\n      \"@id\": \"adyen:inputDetails\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"itemSearchUrl\": {\n      \"@id\": \"adyen:itemSearchUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"items\": {\n      \"@id\": \"adyen:items\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"key\": {\n      \"@id\": \"adyen:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"optional\"\
  : {\n      \"@id\": \"adyen:optional\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"adyen:value\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-input-detail-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
