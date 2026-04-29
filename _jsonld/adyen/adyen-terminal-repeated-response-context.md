---
class_count: 1
classes:
- RepeatedResponseMessageBody
context_file: json-ld/adyen-terminal-repeated-response-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-repeated-response-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Repeated Response from Adyen.
layout: jsonld
name: Adyen Terminal Repeated Response Context
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
  name: LoyaltyResponse
  type: string
- container: ''
  name: PaymentResponse
  type: string
- container: ''
  name: ReversalResponse
  type: string
- container: ''
  name: StoredValueResponse
  type: string
- container: ''
  name: CardAcquisitionResponse
  type: string
- container: ''
  name: CardReaderAPDUResponse
  type: string
property_count: 6
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-repeated-response-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"RepeatedResponseMessageBody\": \"adyen:RepeatedResponseMessageBody\",\n    \"LoyaltyResponse\": {\n      \"@id\": \"adyen:LoyaltyResponse\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PaymentResponse\": {\n      \"@id\": \"adyen:PaymentResponse\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReversalResponse\": {\n      \"@id\": \"adyen:ReversalResponse\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StoredValueResponse\": {\n      \"@id\": \"adyen:StoredValueResponse\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CardAcquisitionResponse\": {\n      \"@id\": \"adyen:CardAcquisitionResponse\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CardReaderAPDUResponse\": {\n      \"@id\": \"adyen:CardReaderAPDUResponse\"\
  ,\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-repeated-response-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
