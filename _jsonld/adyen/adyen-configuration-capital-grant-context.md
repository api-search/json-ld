---
class_count: 1
classes:
- CapitalGrantAccount
context_file: json-ld/adyen-configuration-capital-grant-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-capital-grant-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Configuration Capital Grant from Adyen.
layout: jsonld
name: Adyen Configuration Capital Grant Context
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
- container: set
  name: balances
  type: string
- container: ''
  name: fundingBalanceAccountId
  type: string
- container: ''
  name: id
  type: string
- container: set
  name: limits
  type: string
property_count: 4
provider_name: Adyen
provider_slug: adyen
slug: adyen-configuration-capital-grant-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CapitalGrantAccount\": \"adyen:CapitalGrantAccount\",\n    \"balances\": {\n      \"@id\": \"adyen:balances\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fundingBalanceAccountId\": {\n      \"@id\": \"adyen:fundingBalanceAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"limits\": {\n      \"@id\": \"adyen:limits\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-capital-grant-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
