---
class_count: 1
classes:
- MerchantDetails
context_file: json-ld/adyen-binlookup-merchant-details-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-binlookup-merchant-details-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Binlookup Merchant Details from Adyen.
layout: jsonld
name: Adyen Binlookup Merchant Details Context
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
  name: countryCode
  type: string
- container: ''
  name: enrolledIn3DSecure
  type: boolean
- container: ''
  name: mcc
  type: string
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-binlookup-merchant-details-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"MerchantDetails\": \"adyen:MerchantDetails\",\n    \"countryCode\": {\n      \"@id\": \"adyen:countryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enrolledIn3DSecure\": {\n      \"@id\": \"adyen:enrolledIn3DSecure\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"mcc\": {\n      \"@id\": \"adyen:mcc\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-binlookup-merchant-details-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
