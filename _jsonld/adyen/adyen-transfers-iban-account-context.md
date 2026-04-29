---
class_count: 1
classes:
- IbanAccountIdentification
context_file: json-ld/adyen-transfers-iban-account-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-transfers-iban-account-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Transfers Iban Account from Adyen.
layout: jsonld
name: Adyen Transfers Iban Account Context
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
  name: iban
  type: string
- container: ''
  name: type
  type: string
property_count: 2
provider_name: Adyen
provider_slug: adyen
slug: adyen-transfers-iban-account-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"IbanAccountIdentification\": \"adyen:IbanAccountIdentification\",\n    \"iban\": {\n      \"@id\": \"adyen:iban\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-transfers-iban-account-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
