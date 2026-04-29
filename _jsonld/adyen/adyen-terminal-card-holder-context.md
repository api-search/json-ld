---
class_count: 1
classes:
- CardHolderPIN
context_file: json-ld/adyen-terminal-card-holder-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-card-holder-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Card Holder from Adyen.
layout: jsonld
name: Adyen Terminal Card Holder Context
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
  name: EncrPINBlock
  type: string
- container: ''
  name: PINFormat
  type: string
- container: ''
  name: AdditionalInput
  type: string
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-card-holder-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CardHolderPIN\": \"adyen:CardHolderPIN\",\n    \"EncrPINBlock\": {\n      \"@id\": \"adyen:EncrPINBlock\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PINFormat\": {\n      \"@id\": \"adyen:PINFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AdditionalInput\": {\n      \"@id\": \"adyen:AdditionalInput\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-card-holder-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
