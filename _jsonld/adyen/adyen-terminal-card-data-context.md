---
class_count: 1
classes:
- CardData
context_file: json-ld/adyen-terminal-card-data-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-card-data-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Card Data from Adyen.
layout: jsonld
name: Adyen Terminal Card Data Context
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
  name: PaymentBrand
  type: string
- container: ''
  name: MaskedPan
  type: string
- container: ''
  name: PaymentAccountRef
  type: string
- container: ''
  name: EntryMode
  type: string
- container: ''
  name: CardCountryCode
  type: integer
- container: ''
  name: ProtectedCardData
  type: string
- container: ''
  name: SensitiveCardData
  type: string
- container: set
  name: AllowedProductCode
  type: integer
- container: set
  name: AllowedProduct
  type: string
- container: ''
  name: PaymentToken
  type: string
- container: set
  name: CustomerOrder
  type: string
property_count: 11
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-card-data-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CardData\": \"adyen:CardData\",\n    \"PaymentBrand\": {\n      \"@id\": \"adyen:PaymentBrand\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaskedPan\": {\n      \"@id\": \"adyen:MaskedPan\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PaymentAccountRef\": {\n      \"@id\": \"adyen:PaymentAccountRef\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EntryMode\": {\n      \"@id\": \"adyen:EntryMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CardCountryCode\": {\n      \"@id\": \"adyen:CardCountryCode\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ProtectedCardData\": {\n      \"@id\": \"adyen:ProtectedCardData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SensitiveCardData\": {\n      \"@id\": \"adyen:SensitiveCardData\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"AllowedProductCode\": {\n      \"@id\": \"adyen:AllowedProductCode\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"AllowedProduct\": {\n      \"@id\": \"adyen:AllowedProduct\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PaymentToken\": {\n      \"@id\": \"adyen:PaymentToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CustomerOrder\": {\n      \"@id\": \"adyen:CustomerOrder\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-card-data-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
