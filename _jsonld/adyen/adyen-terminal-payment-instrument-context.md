---
class_count: 2
classes:
- PaymentInstrumentData
- PaymentInstrumentType
context_file: json-ld/adyen-terminal-payment-instrument-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-payment-instrument-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Payment Instrument from Adyen.
layout: jsonld
name: Adyen Terminal Payment Instrument Context
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
  name: ProtectedCardData
  type: string
- container: ''
  name: CardData
  type: string
- container: ''
  name: CheckData
  type: string
- container: ''
  name: MobileData
  type: string
- container: ''
  name: StoredValueAccountID
  type: string
property_count: 5
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-payment-instrument-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PaymentInstrumentData\": \"adyen:PaymentInstrumentData\",\n    \"PaymentInstrumentType\": \"adyen:PaymentInstrumentType\",\n    \"ProtectedCardData\": {\n      \"@id\": \"adyen:ProtectedCardData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CardData\": {\n      \"@id\": \"adyen:CardData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CheckData\": {\n      \"@id\": \"adyen:CheckData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MobileData\": {\n      \"@id\": \"adyen:MobileData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StoredValueAccountID\": {\n      \"@id\": \"adyen:StoredValueAccountID\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-payment-instrument-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
